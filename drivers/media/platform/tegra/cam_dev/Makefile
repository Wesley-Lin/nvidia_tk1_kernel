GCOV_PROFILE := y

subdir-ccflags-y := -Werror
#
# Makefile for the camera devices spec.
#

ccflags-y	+= -Idrivers/video/tegra/host
obj-$(CONFIG_VIDEO_CAMERA)		+= dev_access.o
obj-$(CONFIG_VIDEO_CAMERA)		+= debugfs.o
obj-$(CONFIG_VIDEO_CAMERA)		+= virtual.o
obj-$(CONFIG_VIDEO_CAMERA)		+= edp.o
obj-$(CONFIG_VIDEO_CAMERA)		+= of_camera.o
obj-$(CONFIG_CAMERA_DEV_AS364X)		+= as364x.o
obj-$(CONFIG_CAMERA_DEV_IMX135)		+= imx135.o
