# SPDX-License-Identifier: GPL-2.0
KALAMA_BASE_DTB += ../../../vendor/qcom/kalama.dtb ../../../vendor/qcom/kalama-v2.dtb
KALAMA_APQ_BASE_DTB += ../../../vendor/qcom/kalamap.dtb ../../../vendor/qcom/kalamap-v2.dtb

SAMSUNG_KALAMA_BOARDS += \
		q5q_eur_openx_w00_r04.dtbo \
		q5q_eur_openx_w00_r06.dtbo \
		q5q_eur_openx_w00_r09.dtbo

kalama-overlays-dtb-y += $(SAMSUNG_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
