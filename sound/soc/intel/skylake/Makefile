# SPDX-License-Identifier: GPL-2.0-only
snd-soc-skl-y := skl.o skl-pcm.o skl-nhlt.o skl-messages.o skl-topology.o \
		skl-sst-ipc.o skl-sst-dsp.o cnl-sst-dsp.o skl-sst-cldma.o \
		skl-sst.o bxt-sst.o cnl-sst.o skl-sst-utils.o

ifdef CONFIG_DEBUG_FS
  snd-soc-skl-y += skl-debug.o
endif

obj-$(CONFIG_SND_SOC_INTEL_SKYLAKE_COMMON) += snd-soc-skl.o

#Skylake Clock device support
snd-soc-skl-ssp-clk-y := skl-ssp-clk.o

obj-$(CONFIG_SND_SOC_INTEL_SKYLAKE_SSP_CLK) += snd-soc-skl-ssp-clk.o
