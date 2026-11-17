# CANmeleon — USB-CAN / CAN FD 硬件、固件与解决方案

[English](https://github.com/CANmeleon/.github/blob/main/profile/README.md) · [官网](https://canmeleon.com/) · [开源硬件](https://github.com/CANmeleon/canmeleon-hardware/blob/main/README.zh-CN.md) · [固件下载](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装) · [联系 CANmeleon](mailto:len2slaw@foxmail.com)

## CANmeleon 提供什么

**一个入口，连接你需要的 USB-CAN / CAN FD 硬件、固件与方案。**

无论你在寻找现成硬件、开源设计、可用固件，还是需要 OEM 集成、芯片平台移植和定制开发，都可以从 CANmeleon 找到对应的项目、技术资源与合作入口。我们的目标是满足一切有关 USB-CAN/CAN FD 的需求，服务汽车、工业、机器人、船舶与自动化等领域。

| 你需要什么 | CANmeleon 提供什么 |
| --- | --- |
| **硬件** | 开源硬件项目、设计协作，以及已适配设备的选型与兼容资料。 |
| **固件** | 多种软件生态的固件选择、下载、安装与设备管理，以及新板卡和芯片平台的固件适配。 |
| **方案** | 面向制造商和应用团队的软件/固件方案、OEM 集成、平台移植维护与定制开发。 |

CANmeleon 是面向不同硬件厂商、芯片厂商和开发者的生态平台。你可以选用已有方案，也可以带着自己的硬件、芯片或应用需求加入。

## 按你的需求找方案

| 如果你是…… | 你想解决的问题 | 从这里开始 / 联系我们 |
| --- | --- | --- |
| **寻找高质量开源 USB-CAN FD 方案的开发者** | 获取可复用的硬件设计、了解适用固件、参与设计改进。 | [开源硬件项目](https://github.com/CANmeleon/canmeleon-hardware/blob/main/README.zh-CN.md) · [贡献与项目提案](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) |
| **USB-CAN / CAN FD 制造商** | 为自有产品接入固件、电脑端软件和设备管理，减少从零开发。 | [固件目录](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md) · [产品集成咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| **极客 / DIY 爱好者** | 自制适配器、改进开源板卡，了解板卡适配和固件安装。 | [硬件项目](https://github.com/CANmeleon/canmeleon-hardware/blob/main/README.zh-CN.md) · [开源板卡适配申请](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md) |
| **方案集成商 / OEM 团队** | 将 USB-CAN FD 集成进设备或系统，匹配接口、API 与产品功能。 | [设备兼容目录](https://canmeleon.com/zh/firmware/devices/) · [OEM 与方案集成咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20OEM%20integration) |
| **机器人开发团队** | 将 CAN/CAN FD 设备接入 Linux SocketCAN 或自有控制软件，选择适合通道和通信需求的方案。 | [GS USB](https://canmeleon.com/zh/firmware/gs-usb/) · [KCAN](https://canmeleon.com/zh/firmware/kcan/) · [机器人项目咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20robotics%20integration) |
| **汽车研发工程师** | 接入总线分析、标定和研发软件，匹配现有驱动与 API。 | [按软件选择固件](#按软件选择固件) · [汽车研发应用咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20automotive%20workflow) |
| **考虑 USB-CAN FD 应用的芯片产品经理** | 评估目标芯片的平台适配与产品化路径，建立固件和软件生态。 | [平台移植与维护服务](#商业技术服务) · [芯片方案咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| **工业、船舶或自动化设备团队** | 根据通道、电气接口、操作系统和应用软件，选择硬件与固件组合。 | [设备选型](https://canmeleon.com/zh/firmware/devices/) · [应用方案咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20application%20solution) |
| **已有设备、需要安装或升级的用户** | 找到对应型号的固件包，完成安装、切换、恢复或问题反馈。 | [固件下载与安装](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md#下载与安装) · [设备管理器](https://github.com/CANmeleon/canmeleon-device-manager/blob/main/README.zh-CN.md) · [固件支持](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues) |

还有其他 USB-CAN/CAN FD 需求？[告诉我们你的应用场景](mailto:len2slaw@foxmail.com?subject=CANmeleon%20solution%20inquiry)，一起确定合适的硬件、固件与合作方式。

### 按软件选择固件

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

## CANmeleon 主要做什么

**为每个细分应用选择合适的芯片方案，开发和适配完善的 USB-CAN/CAN FD 固件生态。**

我们以应用需求为起点，以适配程度和性价比为芯片选型目标，将芯片、硬件、固件与电脑端软件连接起来：

1. **选对平台。** 根据通道数量、USB 与 CAN 外设、处理能力、存储资源和成本，为不同细分需求选择芯片方案。
2. **建设固件生态。** 开发、移植和维护固件，适配驱动、API、应用软件及设备管理，让硬件能够服务不同开发工作流。
3. **复用并持续改进。** 复用已有固件和集成经验，减少重复开发，将工程投入用于性能、稳定性与产品质量。

我们的目标是以更合适的成本提供优秀的 USB-CAN/CAN FD 方案，让硬件厂商、芯片厂商与应用团队更专注于自己的产品。

## 开源与商业业务

### 开源建设与免费固件适配

- **开源硬件建设：** 在 [canmeleon-hardware](https://github.com/CANmeleon/canmeleon-hardware/blob/main/README.zh-CN.md) 汇集 USB-CAN/CAN FD 硬件设计与板卡资料。具体硬件资料正在整理，欢迎[贡献设计和文档](https://github.com/CANmeleon/canmeleon-hardware/blob/main/CONTRIBUTING.md#中文)或[提出板卡方案](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md)。
- **部分免费固件适配：** 为部分开源 USB-CAN/CAN FD 硬件提供固件适配。通过[适配申请](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md)提交项目链接、板卡修订、MCU、USB/CAN 外设及目标固件/API，确认适用组合与获取条件。

硬件设计与固件分别采用对应许可证；免费提供的固件包按其实际许可使用。已发布固件包用于指定板卡和硬件修订，其他板卡或 MCU 可申请移植。

### 商业技术服务

| 业务 | 面向的需求 | 联系入口 |
| --- | --- | --- |
| **硬件厂商软件与固件方案** | 自有 USB-CAN/CAN FD 产品的软件接入、固件集成与设备管理。 | [产品方案咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| **芯片平台固件移植与维护** | 将 CANmeleon 系列固件移植到目标芯片，并提供约定范围的版本维护。 | [芯片平台合作](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| **定制固件开发** | 按特定接口、软件工作流及设备功能开发固件，支持 OEM 与系统集成需求。 | [定制开发咨询](mailto:len2slaw@foxmail.com?subject=CANmeleon%20custom%20firmware) |

**商业适配案例：** 鲲弘 KHCM 系列芯片及其衍生 USB-CAN/CAN FD 硬件是 CANmeleon 商业固件适配的案例。可查看 [KHCM 芯片资料](https://docs.kunhong-elec.com/zh/products/can-communication/CANmeleon-controller-ic.html)和[已适配设备目录](https://canmeleon.com/zh/firmware/devices/)；其他厂商可围绕自有芯片与硬件开展合作。

### 联系与参与

- **方案与商业合作：** [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com)。来信请说明应用场景、目标 MCU/板卡、CAN/CAN FD 通道、USB 接口、操作系统/API、所需功能及计划时间。
- **开源硬件贡献：** [硬件项目 Issues](https://github.com/CANmeleon/canmeleon-hardware/issues)。
- **固件适配与使用问题：** [固件 Issues](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues)，附板卡、固件、驱动与软件版本及问题描述。
- **设备管理器使用问题：** [客户端 Issues](https://github.com/CANmeleon/canmeleon-device-manager/issues)。

## 关于我们

CANmeleon 成员来自资深的 USB-CAN/CAN FD 产品开发团队。核心成员拥有超过 10 年的相关行业经验，专业背景涵盖嵌入式与芯片开发验证、医疗自动化、机器人，以及芯片虚拟仿真工具开发。

我们将跨行业的产品研发经验用于芯片选型、固件生态建设和方案集成，与开源贡献者、硬件厂商、芯片厂商及应用团队共同完善 USB-CAN/CAN FD 生态。
