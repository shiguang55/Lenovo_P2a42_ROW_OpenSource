GCC_VERSION      := $(shell $(CONFIG_SHELL) $(srctree)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
ccflags-y += -Idrivers/media/video/msm
ccflags-y += -I../vendor/lenovo/camera/camera-driver/common

obj-$(CONFIG_MSM_FD) += msm_fd_dev.o msm_fd_hw.o
