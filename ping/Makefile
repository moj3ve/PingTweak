include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = Ping

Ping_FILES = JBPRootListController.m
Ping_INSTALL_PATH = /Library/PreferenceBundles
Ping_FRAMEWORKS = UIKit
Ping_PRIVATE_FRAMEWORKS = Preferences
Ping_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/Pingpref.plist$(ECHO_END)
