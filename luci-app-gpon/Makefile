# See /LICENSE for more information.
# This is free software, licensed under the GNU General Public License v2.

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-gpon
PKG_VERSION:=1.0
PKG_RELEASE:=1

LUCI_TITLE:=LuCI GPON app for js-based luci
LUCI_DEPENDS:=+luci-base
LUCI_PKGARCH:=all

LUCI_CATEGORY:=LuCI
LUCI_SUBMENU:=3. Applications

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
$(eval $(call BuildPackage,$(PKG_NAME)))
