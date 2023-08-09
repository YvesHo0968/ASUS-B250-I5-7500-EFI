# ASUS-B250-i5-7500-OC-EFI
OC 0.9.4
支持的系统 BigSur、Monterey和Ventura
[BIOS 设置](https://zhuanlan.zhihu.com/p/65124550) 低版本系统自行测试

## 硬件参数

- CPU：i5-7500
- 显卡：HD630
- 蓝牙：无
- 以太网：RealtekRTL8111
- 声卡：Realtek ALC887
- USB：usb 3.0

## 正常工作

1. 显卡：核显加速
2. 声卡
3. 以太网
4. USB

## 需要修改
文件地址 OC/config.plist

参考[GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

1. PlatformInfo->Generic->MLB：需要修改；
2. PlatformInfo->Generic->SystemProductName：需要修改；
3. PlatformInfo->Generic->SystemSerialNumber：需要修改；
4. PlatformInfo->Generic->SystemUUID：需要修改。
