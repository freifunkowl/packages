include $(TOPDIR)/rules.mk

PKG_NAME:=fflip-unifi-gain-adjustor
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/fflip-unifi-gain-adjustor
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Adjusts antenna gain values on UniFi devices
endef

define Package/fflip-unfi-gain-adjustor/description
	Adjusts antenna gain values on UniFi devices
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/fflip-unifi-gain-adjustor/install
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,fflip-unifi-gain-adjustor))
