GCC_VERSION      := $(shell $(CONFIG_SHELL) $(srctree)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)

GCOV_PROFILE := y

ccflags-y += -Idrivers/media/platform/msm/camera_v2_2016/jpeg_10
ccflags-y += -Idrivers/media/platform/msm/camera_v2_2016/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2_2016/smmu

obj-$(CONFIG_MSMB_JPEG) += msm_jpeg_dev.o msm_jpeg_sync.o msm_jpeg_core.o msm_jpeg_hw.o msm_jpeg_platform.o
