# SPDX-License-Identifier: GPL-2.0

dtb-$(CONFIG_MACH_EXYNOS7885_JACKPOTLTE_EUR_OPEN) += \
	exynos/exynos7885-jackpotlte_eur_open_03.dtb \
	exynos/exynos7885-jackpotlte_eur_open_04.dtb \
	exynos/exynos7885-jackpotlte_eur_open_05.dtb \
	exynos/exynos7885-jackpotlte_eur_open_06.dtb \
	exynos/exynos7885-jackpotlte_eur_open_07.dtb

dtb-$(CONFIG_MACH_EXYNOS7885_JACKPOTLTE_JPN_DCM) += \
	exynos/exynos7885-jackpotlte_jpn_dcm_00.dtb \
	exynos/exynos7885-jackpotlte_jpn_dcm_03.dtb

dtb-$(CONFIG_MACH_EXYNOS7885_JACKPOT2LTE_EUR_OPEN) += \
	exynos/exynos7885-jackpot2lte_eur_open_03.dtb \
	exynos/exynos7885-jackpot2lte_eur_open_04.dtb \
	exynos/exynos7885-jackpot2lte_eur_open_05.dtb \
	exynos/exynos7885-jackpot2lte_eur_open_06.dtb \
	exynos/exynos7885-jackpot2lte_eur_open_07.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
