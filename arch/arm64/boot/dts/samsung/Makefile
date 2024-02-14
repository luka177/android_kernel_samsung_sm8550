# SPDX-License-Identifier: GPL-2.0

ifeq ($(CONFIG_SEC_PLATFORM),"dm1q")
dts-dirs += diamond/dm1q
else ifeq ($(CONFIG_SEC_PLATFORM),"dm3q")
dts-dirs += diamond/dm3q
else ifeq ($(CONFIG_SEC_PLATFORM),"q5q")
dts-dirs += foldable/q5q
endif

always          := $(dtb-y)
subdir-y        := $(dts-dirs)

clean-files := *.dtb *.reverse.dts *.dtbo
