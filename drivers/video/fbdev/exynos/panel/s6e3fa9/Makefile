# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Linux kernel panel device drivers.
#

mcd-panel-s6e3fa9-y := s6e3fa9.o
mcd-panel-s6e3fa9-$(CONFIG_EXTEND_LIVE_CLOCK) += s6e3fa9_aod.o
mcd-panel-s6e3fa9-$(CONFIG_SUPPORT_DISPLAY_PROFILER) += s6e3fa9_profiler.o

obj-$(CONFIG_EXYNOS_DECON_LCD_S6E3FA9) += mcd-panel-s6e3fa9.o
