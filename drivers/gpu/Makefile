obj-y			+= drm/ vga/ ion/

obj-$(CONFIG_TEGRA_HOST1X)	+= host1x/

ifeq ($(CONFIG_MALI400),y)
ifeq ($(CONFIG_MALI_VER_R3P2),y)
obj-y           += mali400/r3p2/mali/
obj-y           += mali400/r3p2/ump/
endif
endif
