saa7231_core-objs		:= saa7231_pci.o	\
				   saa7231_cgu.o	\
				   saa7231_i2c.o	\
				   saa7231_if.o		\
				   saa7231_msi.o	\
				   saa7231_dmabuf.o	\
				   saa7231_gpio.o	\
				   saa7231_ring.o	\
				   saa7231_ts2dtl.o	\
				   saa7231_stream.o	\
				   saa7231_dvb.o


obj-$(CONFIG_SAA7231_CORE)	+= saa7231_core.o
obj-$(CONFIG_SAA7231_DRV)	+= saa7231_drv.o

ccflags-y += -Idrivers/media/dvb-core/
ccflags-y += -Idrivers/media/dvb-frontends/
ccflags-y += -Idrivers/media/tuners/
