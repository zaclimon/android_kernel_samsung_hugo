#
# OTG infrastructure and transceiver drivers
#

# infrastructure
obj-$(CONFIG_USB_OTG_UTILS)	+= otg.o

obj-$(CONFIG_MICROUSBIC_INTR)	+= microusbic/
obj-$(CONFIG_FSA9480_MICROUSB)	+= fsa9480_i2c.o
obj-$(CONFIG_MAX14577_MICROUSB)	+= MD_MAX14577.o battery_monitor.o charger_max14577.o fuelgauge_adc_emul.o sleep_i2c1.o sleep_i2c2.o sleep_madc.o Bq27425_fuelguage_kernel.o

# transceiver drivers
obj-$(CONFIG_USB_GPIO_VBUS)	+= gpio_vbus.o
obj-$(CONFIG_ISP1301_OMAP)	+= isp1301_omap.o
obj-$(CONFIG_TWL6030_USB)	+= twl6030-usb.o
obj-$(CONFIG_TWL4030_USB)	+= twl4030-usb.o
obj-$(CONFIG_NOP_USB_XCEIV)	+= nop-usb-xceiv.o
obj-$(CONFIG_USB_ULPI)		+= ulpi.o

ccflags-$(CONFIG_USB_DEBUG)	+= -DDEBUG
ccflags-$(CONFIG_USB_GADGET_DEBUG) += -DDEBUG

