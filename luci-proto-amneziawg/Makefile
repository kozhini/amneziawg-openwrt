include $(TOPDIR)/rules.mk

LUCI_TITLE:=Support for AmneziaWG VPN
LUCI_DESCRIPTION:=Provides support and Web UI for AmneziaWG VPN
PKG_VERSION:=2.0.6
LUCI_DEPENDS:=+amneziawg-tools +ucode +luci-lib-uqr +resolveip \
	+kmod-amneziawg \
	+@BUSYBOX_CONFIG_IP \
	+@BUSYBOX_CONFIG_FEATURE_IP_LINK
LUCI_PKGARCH:=all

PKG_LICENSE:=Apache-2.0

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
