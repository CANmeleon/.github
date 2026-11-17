# CANmeleon — USB-CAN / CAN FD 方案平台

**让每一种 USB-CAN / CAN FD 需求，都有解决方案的起点。**

CANmeleon 汇集 USB 转 CAN 硬件、固件、软件兼容指南和集成资源。我们的目标是满足一切有关 USB-CAN/CAN FD 的需求：从选择一款适配器，到 OEM 集成、定制固件开发，以及向自有硬件移植。

无论是**汽车、工业、机器人、船舶还是自动化**，都欢迎从实际应用出发，在这里寻找已有方案，或提出下一步需要解决的问题。

[English](https://github.com/CANmeleon/.github/blob/main/profile/README.md) · [官网](https://canmeleon.com/) · [支持硬件](https://canmeleon.com/zh/firmware/devices/) · [固件下载](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装) · [设备管理器](https://github.com/CANmeleon/canmeleon-device-manager/blob/main/README.zh-CN.md)

## 从你的需求开始

| 你需要什么 | 从这里开始 |
| --- | --- |
| USB-CAN / USB-CAN FD 硬件 | 在[设备目录](https://canmeleon.com/zh/firmware/devices/)选择适配器、模块或控制器芯片，查看对应型号的规格与接线资料。 |
| OEM 产品集成方案 | 查看[鲲弘硬件与集成资源](https://www.kunhong-elec.com/)，并[沟通 OEM 项目需求](https://www.kunhong-elec.com/contact)。 |
| 接入现有 CAN 软件 | 按操作系统、驱动与 API，在[固件目录](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md)选择固件。 |
| 下载、安装或切换固件 | 获取[固件包与安装说明](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装)，使用 [CANmeleon 设备管理器](https://github.com/CANmeleon/canmeleon-device-manager/blob/main/README.zh-CN.md)。 |
| 固件开发或移植到新硬件 | [提交固件开发或移植需求](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues)，说明目标 MCU/开发板、USB 接口、CAN 通道、电脑端系统及软件/API。 |

## 按软件选择固件

CANmeleon 固件运行于支持的 CANmeleon 硬件。所选固件决定电脑端驱动与软件接口，硬件决定物理通道及电气能力。选型时核对完整设备型号，以及固件模式、版本和授权要求。

| 软件或开发接口 | 固件与使用资料 |
| --- | --- |
| Linux SocketCAN；Windows WinUSB、EcuBus-Pro | [GS USB](https://canmeleon.com/zh/firmware/gs-usb/) |
| Windows KCANBasic / kcan-bus；Linux kcan 驱动 / SocketCAN | [KCAN](https://canmeleon.com/zh/firmware/kcan/) |
| PCAN-View、PCAN-Basic | [PCAN FD 固件](https://github.com/CANmeleon/canmeleon-pcanfd-firmware/blob/main/README.zh-CN.md) · [PCAN-USB 经典 CAN](https://canmeleon.com/zh/firmware/pcan-usb/) |
| CANoe、CANalyzer、CANape、Vector XL Driver Library | [VN16xx 兼容固件](https://github.com/CANmeleon/canmeleon-VN16xx-firmware/blob/main/README.zh-CN.md) |
| ETAS INCA、BOA；XCP/CCP 标定 | [ES582 兼容固件](https://github.com/CANmeleon/canmeleon-es582-firmware/blob/main/README.zh-CN.md) |
| ZCANPRO、ZXDoc、CANtest、ZLG API | [ZLG USBCANFD 兼容固件](https://github.com/CANmeleon/canmeleon-zlg-usbcanfd-firmware/blob/main/README.zh-CN.md) |
| Kvaser CANlib、CanKing | [Kvaser FD](https://canmeleon.com/zh/firmware/kvaser-fd/) · [Kvaser Leaf 经典 CAN](https://canmeleon.com/zh/firmware/kvaser-leaf/) |

[浏览全部固件系列与参数对照](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#按软件需求选择固件)。

## 从一款适配器，到你自己的产品

从需要连接的 CAN 或 CAN FD 网络开始：汽车 ECU、工业控制器、机器人、船舶设备或自动化系统。先明确通道数、总线速率、电气接口、操作系统和软件/API，再搭配硬件与固件。

对于 **OEM 集成**，可向[鲲弘硬件团队](https://www.kunhong-elec.com/contact)说明尺寸、供电与隔离、连接器及预计用量。对于**固件开发和移植**，可在[固件需求入口](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues)说明目标开发板或 MCU、USB 与 CAN 外设、电脑端接口，以及更新和恢复要求。

## 常见问题

**CANmeleon 是什么？** CANmeleon 是 USB-CAN/CAN FD 方案平台，连接硬件选型、固件下载、设备管理、软件集成与定制开发需求。

**只面向汽车行业吗？** CANmeleon 面向汽车、工业、机器人、船舶和自动化等领域的 USB-CAN/CAN FD 项目。按安装环境的电气与环境要求选择硬件，并为目标网络选择电脑端软件。

**一款适配器可以接入多种软件生态吗？** 支持设备可通过管理器切换适用的固件系列，每次运行一种。可用模式及可保存固件数量取决于硬件、存储空间和授权。

**自有硬件可以使用这些固件吗？** 已发布固件包面向设备目录中的型号。其他开发板或 MCU 可提交移植需求，并提供硬件及电脑端接口要求。

**源码与许可证在哪里？** 各组件或发布包分别说明可获取的文件及许可。固件总览和专题仓库提供使用文档、参数数据及二进制下载入口。

## 开始使用与获取支持

- [选择硬件](https://canmeleon.com/zh/firmware/devices/)，[下载固件](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装)。
- [反馈固件问题或提出功能需求](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues)，附上型号、固件、驱动、软件/API 与复现步骤。
- [设备管理器问题](https://github.com/CANmeleon/canmeleon-device-manager/issues)：安装、识别、更新与恢复。
- [联系鲲弘，沟通硬件采购与 OEM 集成](https://www.kunhong-elec.com/contact)。
