## Clevo_N960Sx_Hackintosh

## OpenCore版本：0.8.8

## 系统版本：Sonoma_14.0

#### 适用型号

1. 战神TX8-CU5DA（N960SD）

2. 战神TX8-CU5DK（N960SD）

3. 战神TX8-CU5DS（N9x0sD2/N960SD2-HA）

![战神TX8-CU5DS 2024/1/19](https://foruda.gitee.com/images/1705725216625195312/520965f7_10135614.jpeg "sonoma.jpg")

#### 硬件参数
| 硬件  | 名称       | 备注            |
|-----|----------|---------------|
| CPU | i5-10400 | 支持22档变频和睿频 |
| GPU | UHD630   | RTX2060已屏蔽    |
| 内存 | Crucial 8G*2   | 原厂16G内存   |
| 硬盘 | Phiso SATA SSD | 原厂512G硬盘    |
| 网卡  | AX201    | 不支持隔空投送       |
| 声卡  | ALC293   | 不支持Win热重启至Mac |
| 触控板 | I2C      | 支持多指触控 |
| 摄像头 | Chicony USB2.0 Camera | 原厂摄像头 |

#### 已知问题

1. 电池的读取和显示×
2. 个人热点和USB共享网络×
3. 自动调节亮度×
4. Windows系统热重启至MacOS时，内建扬声器将无法使用。

#### 注意事项

1.  安装系统请使用鼠标，触控板仅能滑动光标。
2.  进入系统后，请打开设置-触控板-轻点来点按。
3.  请不要将亮度调至最小值，否则显示器将黑屏。
4.  若您的电脑有异常发热的情况请按Fn+1键强冷。

#### BIOS说明

1.  确保为原厂BIOS。
2.  设置Advanced-SATA Mode-AHCI Mode.
3.  开启Advanced-Advanced Chipset Control-UEFI OS Fast Boot.
4.  关闭Advanced-Advanced Chipset Control-Software Guard Extensions（SGX）.

#### 早期版本
MacOS_Monterey_12.x版本：[N960SD_Monterey_OpenCore0.7.8_220701](https://www.lanzoux.com/i1AF81lnrhkf)
