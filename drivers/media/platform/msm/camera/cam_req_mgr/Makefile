ccflags-y += -Idrivers/media/platform/msm/camera/cam_core/
ccflags-y += -Idrivers/media/platform/msm/camera/cam_smmu/
ccflags-y += -Idrivers/media/platform/msm/camera/cam_utils
ccflags-y += -Idrivers/media/platform/msm/camera/cam_req_mgr

obj-$(CONFIG_SPECTRA_CAMERA) += cam_req_mgr_core.o\
				cam_req_mgr_dev.o \
				cam_req_mgr_util.o \
				cam_req_mgr_workq.o \
				cam_mem_mgr.o \
				cam_req_mgr_timer.o

ifdef CONFIG_DEBUG_KERNEL
obj-$(CONFIG_SPECTRA_CAMERA) += cam_req_mgr_debug.o
endif
