#
# Copyright (C) 2011, Marvell International Ltd.
#
# This software file (the "File") is distributed by Marvell International
# Ltd. under the terms of the GNU General Public License Version 2, June 1991
# (the "License").  You may use, redistribute and/or modify this File in
# accordance with the terms and conditions of the License, a copy of which
# is available by writing to the Free Software Foundation, Inc.,
# 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA or on the
# worldwide web at http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt.
#
# THE FILE IS DISTRIBUTED AS-IS, WITHOUT WARRANTY OF ANY KIND, AND THE
# IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE
# ARE EXPRESSLY DISCLAIMED.  The License provides additional details about
# this warranty disclaimer.
EXTRA_CFLAGS += -DANDROID_KERNEL
EXTRA_CFLAGS += -DSTA_CFG80211
	EXTRA_CFLAGS += -DPROC_DEBUG
	export CONFIG_PROC_DEBUG
	EXTRA_CFLAGS += -DSTA_SUPPORT
	EXTRA_CFLAGS += -DREASSOCIATION
	EXTRA_CFLAGS += -DUAP_SUPPORT
	EXTRA_CFLAGS += -DWIFI_DIRECT_SUPPORT
	EXTRA_CFLAGS += -DWIFI_DISPLAY_SUPPORT
	EXTRA_CFLAGS += -DMFG_CMD_SUPPORT
	EXTRA_CFLAGS += -DSDIO_MULTI_PORT_TX_AGGR
	EXTRA_CFLAGS += -DSDIO_MULTI_PORT_RX_AGGR
	EXTRA_CFLAGS += -DSDIO_SUSPEND_RESUME
	EXTRA_CFLAGS += -DDFS_TESTING_SUPPORT
	EXTRA_CFLAGS += -DSTA_WEXT
	EXTRA_CFLAGS += -DUAP_WEXT
	EXTRA_CFLAGS += -DUAP_CFG80211







mwifiex-y += main.o
mwifiex-y += init.o
mwifiex-y += cfp.o
mwifiex-y += cmdevt.o
mwifiex-y += util.o
mwifiex-y += txrx.o
mwifiex-y += wmm.o
mwifiex-y += 11n.o
mwifiex-y += 11n_aggr.o
mwifiex-y += 11n_rxreorder.o
mwifiex-y += scan.o
mwifiex-y += join.o
mwifiex-y += sta_ioctl.o
mwifiex-y += sta_cmd.o
mwifiex-y += sta_cmdresp.o
mwifiex-y += sta_event.o
mwifiex-y += sta_tx.o
mwifiex-y += sta_rx.o
mwifiex-y += cfg80211.o
mwifiex-$(CONFIG_DEBUG_FS) += debugfs.o
obj-$(CONFIG_MWIFIEX) += mwifiex.o

mwifiex_sdio-y += sdio.o
obj-$(CONFIG_MWIFIEX_SDIO) += mwifiex_sdio.o

mwifiex_pcie-y += pcie.o
obj-$(CONFIG_MWIFIEX_PCIE) += mwifiex_pcie.o
