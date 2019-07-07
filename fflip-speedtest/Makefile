include $(TOPDIR)/rules.mk

PKG_NAME:=fflip-speedtest
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/fflip-speedtest
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Downloads files > /dev/zero via http for speed testing + /usr/sbin/speedtest
endef

define Package/fflip-speedtest/description
	Downloads files > /dev/zero via http for speed testing + /usr/sbin/speedtest
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/fflip-speedtest/install
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,fflip-speedtest))
