TARGET := iphone:clang
ARCHS = armv7 arm64
THEOS_BUILD_DIR = Packages

include @@THEOS@@/makefiles/common.mk

TWEAK_NAME = @@PROJECTNAME@@
@@PROJECTNAME@@_FILES = Tweak.xm

include $(THEOS_MAKE_PATH)/tweak.mk

@@KILL_RULE@@
