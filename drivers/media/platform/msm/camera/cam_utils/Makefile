ccflags-y += -Idrivers/media/platform/msm/camera/cam_core/
ccflags-y += -Idrivers/media/platform/msm/camera/cam_req_mgr/
ccflags-y += -Idrivers/media/platform/msm/camera/cam_smmu/

obj-$(CONFIG_SPECTRA_CAMERA) += cam_soc_util.o cam_io_util.o cam_packet_util.o cam_trace.o cam_common_util.o

ifdef CONFIG_DEBUG_KERNEL
obj-$(CONFIG_SPECTRA_CAMERA) += cam_debug_util.o
endif

obj-$(CONFIG_SPECTRA_CAMERA) += cam_cx_ipeak.o
