# SPDX-License-Identifier: GPL-2.0
KALAMA_BASE_DTB += ../../../vendor/qcom/kalama.dtb ../../../vendor/qcom/kalama-v2.dtb
KALAMA_APQ_BASE_DTB += ../../../vendor/qcom/kalamap.dtb ../../../vendor/qcom/kalamap-v2.dtb

SAMSUNG_GALAXYTAB_KALAMA_BOARDS += \
	01_dtbdump_Samsung_GTS9WIFI_PROJECT_board-id00.dtbo \
	02_dtbdump_Samsung_GTS9WIFI_PROJECT_board-id01.dtbo \
	03_dtbdump_Samsung_GTS9WIFI_PROJECT_board-id02.dtbo \
	04_dtbdump_Samsung_GTS9WIFI_PROJECT_board-id04.dtbo

kalama-overlays-dtb-y += $(SAMSUNG_GALAXYTAB_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_GALAXYTAB_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
