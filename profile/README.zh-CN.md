# CANmeleon — USB-CAN / CAN FD 生态平台

**连接硬件、芯片、固件与软件，让每一种 USB-CAN / CAN FD 需求都有解决方案的起点。**

CANmeleon 面向硬件厂商、芯片厂商和开发者，致力于满足**汽车、工业、机器人、船舶和自动化**等行业的 USB-CAN/CAN FD 需求。

生态面向不同厂商的硬件开放。你可以参与开源硬件建设、为开源板卡申请免费固件适配，也可以围绕自己的产品或芯片平台，与我们开展商业固件方案合作。

[English](https://github.com/CANmeleon/.github/blob/main/profile/README.md) · [官网](https://canmeleon.com/) · [固件下载](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装) · [设备管理器](https://github.com/CANmeleon/canmeleon-device-manager/blob/main/README.zh-CN.md) · [商业联系](mailto:len2slaw@foxmail.com)

## 开源建设与免费固件适配

[CANmeleon Hardware](https://github.com/CANmeleon/canmeleon-hardware) 是 GitHub 上的 USB-CAN/CAN FD 开源硬件项目入口，用于汇集设计文件与板卡资料。硬件内容正在仓库中整理，欢迎开发者和制造商参与项目讨论与贡献。

| 你的需求 | 入口 |
| --- | --- |
| 硬件设计与板卡资料 | [canmeleon-hardware](https://github.com/CANmeleon/canmeleon-hardware/blob/main/README.zh-CN.md) |
| 贡献设计或提出板卡方案 | [贡献指南](https://github.com/CANmeleon/canmeleon-hardware/blob/main/CONTRIBUTING.md#中文) · [硬件项目提案](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) |
| 为开源板卡申请免费固件适配 | [提交适配申请](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md)，提供项目链接、板卡修订、MCU、USB/CAN 外设及目标固件/API。 |

免费适配计划面向部分板卡与固件组合。硬件设计文件与固件分别采用对应的许可，使用时查看具体项目和固件包说明。

## 商业技术服务

| 服务对象 | 服务内容 | 联系入口 |
| --- | --- | --- |
| USB-CAN/CAN FD 硬件厂商 | 提供用于产品集成、电脑端软件接入和设备管理的软件与固件解决方案。 | [硬件产品集成咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| 涉及 USB-CAN/CAN FD 应用的芯片厂商 | 为目标芯片平台提供 CANmeleon 系列固件移植与维护服务。 | [芯片平台移植与维护](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| 有特定产品需求的团队 | 针对接口、软件工作流及设备功能开发定制固件。 | [定制固件开发咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20custom%20firmware) |

来信请说明公司/项目、目标 MCU 或板卡、CAN/CAN FD 通道、USB 接口、电脑端系统及 API、所需功能和计划时间。需要持续维护时，请说明版本维护与支持范围。项目文档和商务资料可通过邮件沟通。

## 商业适配案例：鲲弘 KHCM 芯片及衍生硬件

鲲弘 **KHCM 系列芯片及衍生 USB-CAN/CAN FD 硬件**是 CANmeleon 商业固件适配案例。[设备兼容目录](https://canmeleon.com/zh/firmware/devices/)列出 KHCM102、KH-UCANFD 等型号的可选固件；电气接口、通道及安装要求请查阅对应型号资料。

[KHCM 芯片资料](https://docs.kunhong-elec.com/zh/products/can-communication/CANmeleon-controller-ic.html) · [已适配设备型号](https://canmeleon.com/zh/firmware/devices/) · [咨询你的平台适配](mailto:len2slaw@foxmail.com?subject=CANmeleon%20platform%20adaptation)

## 按软件选择固件

CANmeleon 固件运行于已完成 CANmeleon 固件适配的硬件。所选固件决定电脑端驱动与软件接口，硬件决定物理通道及电气能力。选型时核对完整设备型号，以及固件模式、版本和授权要求。

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

## 常见问题

**CANmeleon 绑定某一家硬件厂商吗？** CANmeleon 是面向多家硬件与芯片厂商的 USB-CAN/CAN FD 生态平台。现有适配产品作为案例展示，厂商可携自有产品与平台参与集成。

**在哪里查看硬件项目并参与贡献？** 从 GitHub 上的 CANmeleon Hardware 仓库开始，README 提供项目资料、贡献说明和硬件提案入口，各板卡文件及修订在该仓库中整理。

**哪些固件适配免费？** 免费适配计划覆盖部分开源硬件与固件组合。可通过适配申请表提交板卡项目链接、修订版本及所需固件，确认适用包和获取条件。

**已有固件可以直接安装到自有板卡吗？** 已发布包用于其指定的板卡和硬件修订。其他开发板或 MCU 可申请移植，并提供硬件及电脑端接口需求。

**一款适配器可以接入多种软件生态吗？** 支持设备可切换适用的固件系列，每次运行一种。可用模式及可保存固件数量取决于硬件、存储空间和授权。

## 联系与参与

- **商业方案、芯片移植维护、定制固件：** [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com)。
- **开源硬件与免费适配：** [参与 CANmeleon Hardware](https://github.com/CANmeleon/canmeleon-hardware)，或[提交适配申请](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md)。
- **固件支持与功能建议：** [固件问题入口](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues)，附板卡、固件、驱动、软件/API 和复现步骤。
- **设备管理器支持：** [客户端问题入口](https://github.com/CANmeleon/canmeleon-device-manager/issues)，用于安装、识别、更新与恢复问题。
