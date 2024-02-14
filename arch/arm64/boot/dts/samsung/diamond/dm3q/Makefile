# SPDX-License-Identifier: GPL-2.0
KALAMA_BASE_DTB += ../../../vendor/qcom/kalama.dtb ../../../vendor/qcom/kalama-v2.dtb
KALAMA_APQ_BASE_DTB += ../../../vendor/qcom/kalamap.dtb ../../../vendor/qcom/kalamap-v2.dtb

SAMSUNG_DIAOMOND_KALAMA_BOARDS += \
	01_dtbdump_Samsung_DM3Q_PROJECT_board-id01.dtbo \
	02_dtbdump_Samsung_DM3Q_PROJECT_board-id02.dtbo \
	03_dtbdump_Samsung_DM3Q_PROJECT_board-id03.dtbo \
	04_dtbdump_Samsung_DM3Q_PROJECT_board-id03.dtbo \
	05_dtbdump_Samsung_DM3Q_PROJECT_board-id05.dtbo \
	06_dtbdump_Samsung_DM3Q_PROJECT_board-id06.dtbo \
	07_dtbdump_Samsung_DM3Q_PROJECT_board-id08.dtbo \
	08_dtbdump_Samsung_DM3Q_PROJECT_board-id09.dtbo \
	09_dtbdump_Samsung_DM3Q_PROJECT_board-id11.dtbo \
	10_dtbdump_Samsung_DM3Q_PROJECT_board-id13.dtbo

kalama-overlays-dtb-y += $(SAMSUNG_DIAOMOND_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_DIAOMOND_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
