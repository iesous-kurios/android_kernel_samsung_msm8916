obj-$(CONFIG_BATTERY_SAMSUNG)		+= sec_battery.o
ifeq ($(CONFIG_OF),y)
obj-$(CONFIG_BATTERY_SAMSUNG)		+= sec_board-battery.o
endif

# Fuel Gauge
obj-$(CONFIG_FUELGAUGE_DUMMY)		+= sec_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_MAX77849)	+= max77849_fuelgauge.o

# Charger
obj-$(CONFIG_CHARGER_DUMMY)		+= sec_charger.o
obj-$(CONFIG_CHARGER_MAX77849)		+= max77849_charger.o
