include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-nightboot
PKG_VERSION:=1
PKG_RELEASE:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/gluon-nightboot
  SECTION:=daemon
  CATEGORY:=Freifunk Lippe
  TITLE:=Reboots node at 4 am 
endef

define Package/gluon-nightboot/description
	Reboots node at 4 am
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-nightboot/install
	$(INSTALL_DIR) $(1)/usr/lib/micron.d/
	$(INSTALL_DATA) files/usr/lib/micron.d/nightboot $(1)/usr/lib/micron.d/nightboot
endef

$(eval $(call BuildPackage,gluon-nightboot))
