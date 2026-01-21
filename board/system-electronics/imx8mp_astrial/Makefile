#
# Copyright 2019 NXP
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx8mp_astrial.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX8MP_ASTRIAL_RAM_2G) += lpddr4_timing_2gb.o
obj-$(CONFIG_IMX8MP_ASTRIAL_RAM_4G) += lpddr4_timing_4gb.o
obj-$(CONFIG_IMX8MP_ASTRIAL_RAM_8G) += lpddr4_timing_8gb.o
endif
