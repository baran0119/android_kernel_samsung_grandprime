ifeq ($(CONFIG_MACH_FORTUNA_EUR_OPEN),y)
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/sensor
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/codecs
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/isps
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/pproc
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2_eur/jpeg_10

obj-$(CONFIG_MSMB_CAMERA) += msm.o
obj-$(CONFIG_MSMB_CAMERA) += cam_dummy.o
obj-$(CONFIG_MSMB_CAMERA) += camera/
obj-$(CONFIG_MSMB_CAMERA) += msm_vb2/
obj-$(CONFIG_MSMB_CAMERA) += sensor/
obj-$(CONFIG_MSMB_CAMERA) += pproc/
obj-$(CONFIG_MSMB_CAMERA) += isp/
obj-$(CONFIG_MSMB_CAMERA) += ispif/
obj-$(CONFIG_MSMB_JPEG) += jpeg_10/
obj-$(CONFIG_MSMB_CAMERA) += msm_buf_mgr/
endif
