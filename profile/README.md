# CANmeleon — USB-CAN & CAN FD Solutions

**One place for your USB-CAN and USB-CAN FD needs.**

CANmeleon brings together USB-to-CAN hardware, firmware, software compatibility guides and integration resources. Our goal is to meet every USB-CAN/CAN FD need: from choosing an adapter to OEM integration, custom firmware development and porting to your own hardware.

We welcome projects across **automotive, industrial systems, robotics, marine electronics and automation**. Start with your application, find an existing solution, or bring us the requirements for what comes next.

[简体中文](https://github.com/CANmeleon/.github/blob/main/profile/README.zh-CN.md) · [Website](https://canmeleon.com/) · [Supported hardware](https://canmeleon.com/en/firmware/devices/) · [Firmware downloads](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install) · [Device Manager](https://github.com/CANmeleon/canmeleon-device-manager)

## What do you need?

| Your goal | Start here |
| --- | --- |
| Choose USB-CAN or USB-CAN FD hardware | Compare adapters, modules and controller ICs in the [device catalog](https://canmeleon.com/en/firmware/devices/); follow each model's hardware specifications and wiring guide. |
| Integrate CAN connectivity into an OEM product | Explore [Kunhong hardware and integration resources](https://www.kunhong-elec.com/en/), then [discuss your OEM requirements](https://www.kunhong-elec.com/en/contact). |
| Connect an adapter to your CAN software | Use the [firmware catalog](https://github.com/CANmeleon/canmeleon-usb-can-firmware) to choose a firmware for your operating system, driver and API. |
| Download, install or switch firmware | Get [firmware packages and installation instructions](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install) and [CANmeleon Device Manager](https://github.com/CANmeleon/canmeleon-device-manager). |
| Develop custom firmware or port it to a new board | [Describe your firmware development or porting request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues): target MCU/board, USB interface, CAN channels, host OS and software/API. |

## Find the firmware for your software

CANmeleon firmware runs on supported CANmeleon hardware. The selected firmware determines the host driver and software interface; the hardware determines physical channels and electrical capabilities. Choose the complete device model and check the firmware's mode, version and license requirements.

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

## From an adapter to your own product

Start with the CAN or CAN FD network you need to connect: an automotive ECU, industrial controller, robot, marine device or automated system. Define the channel count, bus rates, electrical interface, operating system and software/API, then choose hardware and firmware together.

For **OEM integration**, share your form factor, power and isolation requirements, connectors and expected production volume with [Kunhong's hardware team](https://www.kunhong-elec.com/en/contact). For **firmware development and porting**, describe the target board or MCU, USB and CAN peripherals, required host interface and update/recovery needs in a [firmware request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues).

## Frequently asked questions

**What is CANmeleon?** A USB-CAN/CAN FD solution platform connecting hardware selection, firmware downloads, device management, software integration and custom development needs.

**Is CANmeleon only for automotive applications?** CANmeleon welcomes USB-CAN/CAN FD projects across automotive, industrial, robotics, marine and automation applications. Select hardware for your installation's electrical and environmental requirements, and choose the host software for your network.

**Can I use several software ecosystems with one adapter?** Supported devices can switch between applicable firmware families using Device Manager. One firmware runs at a time; available modes and stored images depend on hardware, storage and licensing.

**Can I use the firmware on my own hardware?** Published packages target the models in the device catalog. For another board or MCU, start a porting request with its hardware and host-interface requirements.

**Where are source code and licenses?** Each component or release states its available files and license. The firmware catalog and topic repositories provide documentation, parameter data and binary-download routes.

## Get started or ask for help

- [Choose hardware](https://canmeleon.com/en/firmware/devices/) and [download firmware](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install).
- [Report a firmware issue or request a feature](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues); include the model, firmware, driver, software/API and reproduction steps.
- [Get help with Device Manager](https://github.com/CANmeleon/canmeleon-device-manager/issues) for installation, detection, updates or recovery.
- [Discuss hardware procurement and OEM integration with Kunhong](https://www.kunhong-elec.com/en/contact).
