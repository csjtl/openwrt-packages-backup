include $(TOPDIR)/rules.mk

PKG_NAME:=default-settings
PKG_VERSION:=0.1
PKG_RELEASE:=$(COMMITCOUNT)

PKG_LICENSE:=GPL-3.0

include $(INCLUDE_DIR)/package.mk

define Package/default-settings
  SECTION:=luci
  CATEGORY:=LuCI
  TITLE:=LuCI support for Default Settings
  PKGARCH:=all
  DEPENDS:=+luci-lib-base
endef
