dtbo-y += samsung/a33x/a33x_eur_open_w00_r04.dtbo
dtb-y += exynos/s5e8825.dtb
dtbo-y += exynos/board/erd/s5e8825-erd8825_r11.dtbo
dtbo-y += exynos/board/erd/s5e8825-erd8825_r10.dtbo
dtbo-y += exynos/board/erd/s5e8825-erd8825.dtbo
dtbo-y += exynos/board/univ/s5e8825-universal8825_r00.dtbo
dtbo-y += samsung/a33x/a33x_eur_open_w00_r02.dtbo
dtbo-y += samsung/a33x/a33x_eur_open_w00_r03.dtbo
dtbo-y += samsung/a33x/a33x_eur_open_w00_r01.dtbo
dtbo-y += samsung/a33x/a33x_eur_open_w00_r00.dtbo
dtbo-y += exynos/board/univ/s5e8825-universal8825_r00.dtbo
dtbo-y += exynos/board/univ/s5e9925-universal9925_rev1b.dtbo
dtbo-y += exynos/board/univ/s5e9925-universal9925_rev00.dtbo
dtbo-y += exynos/board/univ/s5e9925_evt0-universal9925_rev00.dtbo
dtbo-y += exynos/board/univ/s5e9925-universal9925_rev17.dtbo
dtbo-y += exynos/board/erd/s5e9925_evt0_s5300-erd9925.dtbo
dtbo-y += exynos/board/erd/s5e8825-erd8825.dtbo
dtbo-y += exynos/board/erd/s5e9925-erd9925_r13.dtbo
dtbo-y += exynos/board/erd/s5e8825-erd8825_r10.dtbo
dtbo-y += exynos/board/erd/s5e9925_evt0_s5300-erd9925_r11.dtbo
dtbo-y += exynos/board/erd/s5e9925-erd9925.dtbo
dtbo-y += exynos/board/erd/s5e9925_evt0-erd9925.dtbo
dtbo-y += exynos/board/erd/s5e8825-erd8825_r11.dtbo
dtbo-y += exynos/board/erd/s5e9925_evt0-erd9925_r11.dtbo
dtb-y += exynos/s5e9925_evt0.dtb
dtb-y += exynos/exynos5433-tm2e.dtb
dtb-y += exynos/exynos5433-tm2.dtb
dtb-y += exynos/exynos7-espresso.dtb
dtb-y += exynos/s5e8825.dtb
dtb-y += exynos/s5e9925.dtb
dtb-y += exynos/exynos2100.dtb
dtb-y += sprd/sc9836-openphone.dtb
dtb-y += sprd/sp9863a-1h10.dtb
dtb-y += sprd/sp9860g-1h10.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always-y  := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
