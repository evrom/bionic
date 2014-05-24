#	$NetBSD: Makefile,v 1.165 2014/03/04 14:58:14 joerg Exp $
#	@(#)Makefile	8.2 (Berkeley) 2/3/94
#
#	FORMAT
#	all lines of code of Android.mk commented, followed by BSD style make syntax
#LOCAL_PATH := $(call my-dir)
LOCAL_PATH := (.CURDIR)

# Make everything depend on any changes to included makefiles.
#libc_common_additional_dependencies := $(LOCAL_PATH)/Android.mk

# Load config for TARGET_ARCH
#my_2nd_arch_prefix :=

#include $(LOCAL_PATH)/arch-$(TARGET_ARCH)/$(TARGET_ARCH).mk
include $(LOCAL_PATH)/arch-$(TARGET_ARCH)/Makefile.inc

#libc_common_additional_dependencies += \
#    $(LOCAL_PATH)/arch-$(TARGET_ARCH)/$(TARGET_ARCH).mk
libc_common_additional_dependencies += \
    $(LOCAL_PATH)/arch-$(TARGET_ARCH)/Makefile.inc

#ifdef TARGET_2ND_ARCH
# Load config for TARGET_2ND_ARCH
#my_2nd_arch_prefix := $(TARGET_2ND_ARCH_VAR_PREFIX)
#include $(LOCAL_PATH)/arch-$(TARGET_2ND_ARCH)/$(TARGET_2ND_ARCH).mk
#my_2nd_arch_prefix :=
#libc_common_additional_dependencies += \
#    $(LOCAL_PATH)/arch-$(TARGET_2ND_ARCH)/$(TARGET_2ND_ARCH).mk
#endif
#
# crt obj files
# ========================================================
# crtbrand.c needs <stdint.h> and a #define for the platform SDK version.




#end my additions


