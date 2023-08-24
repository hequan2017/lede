include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-myplugin
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

include $(TOPDIR)/feeds/luci/luci.mk

# Package description
PKG_LICENSE:=GPL-3.0-or-later
PKG_MAINTAINER:=Your Name <your.email@example.com>

define Package/luci-app-myplugin
  SECTION:=luci
  CATEGORY:=LuCI
  SUBMENU:=3. Applications
  TITLE:=My LuCI Plugin
  DEPENDS:=+dep1 +dep2
endef

define Package/luci-app-myplugin/description
  A custom LuCI plugin for OpenWrt.
endef

$(eval $(call BuildPackage,luci-app-myplugin))
