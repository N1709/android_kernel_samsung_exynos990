# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Linux kernel panel device drivers.
#

mcd-panel-s6e3hac-y := s6e3hac.o
mcd-panel-s6e3hac-$(CONFIG_EXTEND_LIVE_CLOCK) += s6e3hac_aod.o
mcd-panel-s6e3hac-$(CONFIG_SUPPORT_DISPLAY_PROFILER) += s6e3hac_profiler.o

obj-$(CONFIG_EXYNOS_DECON_LCD_S6E3HAC) += mcd-panel-s6e3hac.o
