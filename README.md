# mercury_D26g_Pro
mercury_D26g_Pro adapting for OpenWrt 

How to Use

Step1: mv dts file to target/linux/ramips/dts/

Step2: mv corresponding patch and .config file to the root directory of lede or openwrt

Step3: execute "git apply xxx.patch" to apply the patch

Step4: execute "cp D26G_xm.config .config & make defconfig" to use default config
