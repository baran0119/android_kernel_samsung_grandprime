#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/

ifeq ($(CONFIG_MACH_FORTUNA_EUR_OPEN),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_eur/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif

obj-$(CONFIG_MSM_VPU) += vpu/
