KBUILD_CFLAGS += -Wno-unused-variable -Wno-return-type -Wno-unused-function -O3
subdir-ccflags-y += -Werror
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include
# In case the platform does NOT support this type of sensors
obj-y   +=  mtk_tpd.o
obj-y   +=  tpd_button.o
obj-y   +=  tpd_calibrate.o
obj-y   +=  tpd_default.o
obj-y   +=  tpd_misc.o
obj-y   +=  tpd_setting.o
obj-$(CONFIG_TOUCHSCREEN_COMMON)       += lct_tp_info.o
obj-$(CONFIG_TOUCHSCREEN_COMMON)       += lct_tp_selftest.o
obj-$(CONFIG_TOUCHSCREEN_COMMON)       += lct_tp_gesture.o
obj-$(CONFIG_TOUCHSCREEN_COMMON)       += lct_tp_grip_area.o
obj-$(CONFIG_TOUCHSCREEN_COMMON)       += lct_tp_work.o
obj-$(CONFIG_TOUCHSCREEN_MTK_FOCALTECH_TS)	+=  focaltech_touch/
obj-$(CONFIG_TOUCHSCREEN_HIMAX_CHIPSET)		+=  hxchipset/
obj-$(CONFIG_TOUCHSCREEN_FTS)		+=  ft8006s_spi/
obj-$(CONFIG_TOUCHSCREEN_NT36XXX_HOSTDL_SPI)	+=  nt36xxx_spi/
obj-$(CONFIG_TOUCHSCREEN_CHIPONE)	+= chipone/

