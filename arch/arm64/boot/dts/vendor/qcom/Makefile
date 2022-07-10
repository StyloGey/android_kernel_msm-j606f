ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-y += \
	j606f-overlay.dtbo

j606f-overlay.dtbo-base := bengalp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
