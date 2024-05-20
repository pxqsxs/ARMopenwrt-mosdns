下载相关文件
luci-app-mosdns_1.5.16_all.ipk
luci-i18n-mosdns-zh-cn_git-23.309.43711-74d15c2_all.ipk
mosdns_5.3.1-1_aarch64_generic.ipk 这个需要根据自己的CPU架构进行下载
v2dat_2022-12-15-47b8ee51-1_aarch64_generic.ipk 这个需要根据自己的CPU架构进行下载
v2ray-geoip_2023-11-06_all.ipk
v2ray-geosite_2023-11-06_all.ipk
上传下载好的文件

可以通过winscp上传，默认是root文件夹下，直接opkg install *.ipk安装所有ipk

或者通过openwrt系统——文件传输——选择文件——点击上传（把六个文件都上传）

安装
# 进入安装包所在目录
cd /tmp/upload
# 查看目录下所有文件
ls
# 安装所有软件包
opkg install *.ipk --force-reinstall
