# See /LICENSE for more information.
# This is free software, licensed under the GNU General Public License v2.

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-gpon
PKG_VERSION:=1.0
PKG_RELEASE:=1

PKG_LICENSE:=GPL-2.0
PKG_LICENSE_FILES:=LICENSE
PKG_MAINTAINER:=Your Name <your.email@example.com>

LUCI_TITLE:=LuCI GPON app for js-based luci
LUCI_DEPENDS:=+luci-base
LUCI_PKGARCH:=all

LUCI_CATEGORY:=LuCI
LUCI_SUBMENU:=3. Applications

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
$(eval $(call BuildPackage,$(PKG_NAME)))
