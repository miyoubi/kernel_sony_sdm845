zram-y	:=	zcomp.o zram_drv.o

ccflags-y += -mllvm -inline-threshold=15000
ccflags-y += -mllvm -inlinehint-threshold=10000

obj-$(CONFIG_ZRAM)	+=	zram.o
