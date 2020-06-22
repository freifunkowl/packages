include $(TOPDIR)/rules.mk

PKG_NAME:=fflip-activate-mesh
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/fflip-activate-mesh
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Activates mesh on all devices
endef

define Package/fflip-activate-mesh/description
	Activates mesh on all devices
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/fflip-activate-mesh/install
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,fflip-activate-mesh))
