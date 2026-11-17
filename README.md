# CANmeleon — USB-CAN & CAN FD Hardware, Firmware and Solutions

[简体中文](https://github.com/CANmeleon/.github/blob/main/profile/README.zh-CN.md) · [Website](https://canmeleon.com/) · [Open hardware](https://github.com/CANmeleon/canmeleon-hardware) · [Firmware downloads](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install) · [Contact CANmeleon](mailto:len2slaw@foxmail.com)

## What CANmeleon provides

**One place to find the USB-CAN / CAN FD hardware, firmware and solutions you need.**

Whether you need an existing device, an open hardware design, ready-to-use firmware, OEM integration, a chip platform port or custom development, CANmeleon connects you with relevant projects, technical resources and engineering services. Our goal is to meet every USB-CAN/CAN FD need across automotive, industrial systems, robotics, marine electronics and automation.

| What you need | What you can find here |
| --- | --- |
| **Hardware** | Open hardware projects, design collaboration and selection and compatibility information for adapted devices. |
| **Firmware** | Firmware choices for different software ecosystems, downloads, installation and device management, plus ports for new boards and chip platforms. |
| **Solutions** | Software/firmware solutions for manufacturers and application teams, OEM integration, platform porting and maintenance, and custom development. |

CANmeleon is an ecosystem for multiple hardware manufacturers, chip vendors and developers. Start with an existing solution or bring your own hardware, chip platform or application requirements.

## Find a solution for your needs

| If you are… | What you want to achieve | Start here / get in touch |
| --- | --- | --- |
| **A developer seeking a high-quality open USB-CAN FD design** | Find reusable hardware designs, explore applicable firmware and contribute improvements. | [Open hardware project](https://github.com/CANmeleon/canmeleon-hardware) · [Contributions and project proposals](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) |
| **A USB-CAN / CAN FD manufacturer** | Add firmware, host-software connectivity and device management to your own products with less development from scratch. | [Firmware catalog](https://github.com/CANmeleon/canmeleon-usb-can-firmware) · [Product integration inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| **A maker / DIY enthusiast** | Build an adapter, improve an open board and find a path to firmware adaptation and installation. | [Hardware project](https://github.com/CANmeleon/canmeleon-hardware) · [Open-board adaptation request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md) |
| **A solution integrator / OEM team** | Integrate USB-CAN FD into a device or system with the required interfaces, APIs and product behavior. | [Device compatibility catalog](https://canmeleon.com/en/firmware/devices/) · [OEM integration inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20OEM%20integration) |
| **A robotics development team** | Connect CAN/CAN FD devices to Linux SocketCAN or your control software, with suitable channel and communication capabilities. | [GS USB](https://canmeleon.com/en/firmware/gs-usb/) · [KCAN](https://canmeleon.com/en/firmware/kcan/) · [Discuss a robotics project](mailto:len2slaw@foxmail.com?subject=CANmeleon%20robotics%20integration) |
| **An automotive R&D engineer** | Connect to bus analysis, calibration and development software using the required drivers and APIs. | [Choose by software](#find-the-firmware-for-your-software) · [Automotive workflow inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20automotive%20workflow) |
| **A chip product manager exploring USB-CAN FD applications** | Assess platform adaptation and a path to products supported by a firmware and software ecosystem. | [Porting and maintenance services](#commercial-services) · [Discuss your chip platform](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| **An industrial, marine or automation team** | Match hardware and firmware to channel counts, electrical interfaces, operating systems and application software. | [Device selection](https://canmeleon.com/en/firmware/devices/) · [Application solution inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20application%20solution) |
| **An existing device user** | Find the right firmware package, install, switch or recover firmware, and get support. | [Downloads and installation](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install) · [Device Manager](https://github.com/CANmeleon/canmeleon-device-manager) · [Firmware support](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues) |

Have another USB-CAN/CAN FD requirement? [Tell us about your application](mailto:len2slaw@foxmail.com?subject=CANmeleon%20solution%20inquiry) so we can identify suitable hardware, firmware and a way to work together.

### Find the firmware for your software

CANmeleon firmware runs on hardware with a matching CANmeleon firmware port. The selected firmware determines the host driver and software interface; the hardware determines physical channels and electrical capabilities. Choose the complete device model and check the firmware's mode, version and license requirements.

| Software or development interface | Firmware and documentation |
| --- | --- |
| Linux SocketCAN; Windows WinUSB and EcuBus-Pro | [GS USB](https://canmeleon.com/en/firmware/gs-usb/) |
| Windows KCANBasic / kcan-bus; Linux kcan driver / SocketCAN | [KCAN](https://canmeleon.com/en/firmware/kcan/) |
| PCAN-View and PCAN-Basic | [PCAN FD firmware](https://github.com/CANmeleon/canmeleon-pcanfd-firmware) · [PCAN-USB Classic CAN](https://canmeleon.com/en/firmware/pcan-usb/) |
| CANoe, CANalyzer, CANape and Vector XL Driver Library | [VN16xx-compatible firmware](https://github.com/CANmeleon/canmeleon-VN16xx-firmware) |
| ETAS INCA and BOA; XCP/CCP calibration | [ES582-compatible firmware](https://github.com/CANmeleon/canmeleon-es582-firmware) |
| ZCANPRO, ZXDoc, CANtest and ZLG API | [ZLG USBCANFD-compatible firmware](https://github.com/CANmeleon/canmeleon-zlg-usbcanfd-firmware) |
| Kvaser CANlib and CanKing | [Kvaser FD](https://canmeleon.com/en/firmware/kvaser-fd/) · [Kvaser Leaf Classic CAN](https://canmeleon.com/en/firmware/kvaser-leaf/) |

[Browse all firmware families and compare parameters](https://github.com/CANmeleon/canmeleon-usb-can-firmware#choose-your-firmware).

## What we focus on

**Selecting suitable chips for each application segment and building a comprehensive USB-CAN/CAN FD firmware ecosystem around them.**

We start with application requirements and select chip platforms for their fit and value, connecting the chip, hardware, firmware and host software:

1. **Choose the right platform.** Evaluate channel counts, USB and CAN peripherals, processing capacity, memory and cost for each use case.
2. **Build the firmware ecosystem.** Develop, port and maintain firmware, connecting drivers, APIs, application software and device management to support different development workflows.
3. **Reuse and improve.** Build on existing firmware and integration experience to reduce duplicated development and focus engineering effort on performance, reliability and product quality.

Our goal is to deliver excellent USB-CAN/CAN FD solutions at an appropriate cost, helping hardware makers, chip vendors and application teams focus on their own products.

## Open-source and commercial work

### Open-source development and free firmware adaptations

- **Open hardware development:** [canmeleon-hardware](https://github.com/CANmeleon/canmeleon-hardware) brings together USB-CAN/CAN FD designs and board documentation. Board materials are being organized; [contribute designs and documentation](https://github.com/CANmeleon/canmeleon-hardware/blob/main/CONTRIBUTING.md) or [propose a board](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md).
- **Selected free firmware adaptations:** We provide firmware adaptations for selected open-source USB-CAN/CAN FD hardware. [Submit a request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md) with the project URL, board revision, MCU, USB/CAN peripherals and desired firmware/API to establish the applicable combination and access terms.

Hardware designs and firmware have their respective licenses; use free firmware packages according to their package terms. Published packages target specific boards and revisions. Request a port for a different board or MCU.

### Commercial services

| Service | What it addresses | Contact |
| --- | --- | --- |
| **Software and firmware solutions for hardware manufacturers** | Host-software connectivity, firmware integration and device management for your USB-CAN/CAN FD products. | [Product solution inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| **Chip platform porting and maintenance** | Ports of CANmeleon firmware families to your target chip, with version maintenance within an agreed scope. | [Chip platform cooperation](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| **Custom firmware development** | Firmware for required interfaces, software workflows and device behavior, including OEM and system integration needs. | [Custom development inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20custom%20firmware) |

**Commercial adaptation example:** Kunhong's KHCM-series chips and derived USB-CAN/CAN FD hardware are examples of commercial CANmeleon firmware adaptation. See the [KHCM chip documentation](https://docs.kunhong-elec.com/en/products/can-communication/CANmeleon-controller-ic.html) and [adapted device catalog](https://canmeleon.com/en/firmware/devices/). Other vendors can work with us on their own chips and hardware.

### Contact and participate

- **Solutions and commercial cooperation:** [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com). Include your application, target MCU/board, CAN/CAN FD channels, USB interface, host OS/API, required features and schedule.
- **Open hardware contributions:** [hardware project Issues](https://github.com/CANmeleon/canmeleon-hardware/issues).
- **Firmware adaptation and support:** [firmware Issues](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues). Include the board, firmware, driver and software versions and a description of the issue.
- **Device Manager support:** [client Issues](https://github.com/CANmeleon/canmeleon-device-manager/issues).

## About us

CANmeleon members come from experienced USB-CAN/CAN FD product development teams. Our core members have more than 10 years of relevant industry experience, with backgrounds spanning embedded systems and chip development and validation, medical automation, robotics, and chip virtual simulation tool development.

We bring that product engineering experience to chip selection, firmware ecosystems and solution integration, working with open-source contributors, hardware manufacturers, chip vendors and application teams to advance the USB-CAN/CAN FD ecosystem.
