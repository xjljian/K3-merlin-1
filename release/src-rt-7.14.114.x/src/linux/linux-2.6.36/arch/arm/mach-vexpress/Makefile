#
# Makefile for the linux kernel.
#

obj-y					:= v2m.o
obj-$(CONFIG_ARCH_VEXPRESS_CA9X4)	+= ct-ca9x4.o
obj-$(CONFIG_SMP)			+= platsmp.o headsmp.o
obj-$(CONFIG_LOCAL_TIMERS)		+= localtimer.o
