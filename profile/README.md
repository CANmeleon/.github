# CANmeleon — USB-CAN & CAN FD Ecosystem

**One ecosystem for your USB-CAN and USB-CAN FD needs.**

CANmeleon connects hardware makers, chip vendors and developers through USB-CAN/CAN FD hardware, firmware and software. Our goal is to meet every USB-CAN/CAN FD need across **automotive, industrial systems, robotics, marine electronics and automation**.

The ecosystem is open to hardware from different manufacturers. Participate in open-source hardware development, request a free firmware adaptation for an open-source board, or work with us on a commercial firmware solution for your product or chip platform.

[简体中文](https://github.com/CANmeleon/.github/blob/main/profile/README.zh-CN.md) · [Website](https://canmeleon.com/) · [Firmware downloads](https://github.com/CANmeleon/canmeleon-usb-can-firmware#download-and-install) · [Device Manager](https://github.com/CANmeleon/canmeleon-device-manager) · [Business contact](mailto:len2slaw@foxmail.com)

## Open-source development and free firmware adaptations

[CANmeleon Hardware](https://github.com/CANmeleon/canmeleon-hardware) is the GitHub home for open-source USB-CAN/CAN FD hardware designs and board documentation. Hardware materials are being organized there, with project discussions and contributions open to developers and manufacturers.

| What you need | Where to go |
| --- | --- |
| Hardware designs and board documentation | [canmeleon-hardware](https://github.com/CANmeleon/canmeleon-hardware) |
| Contribute a design or propose a board | [Contribution guide](https://github.com/CANmeleon/canmeleon-hardware/blob/main/CONTRIBUTING.md) · [Hardware project proposals](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) |
| Free firmware adaptation for an open-source board | [Submit an adaptation request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md) with the project URL, board revision, MCU, USB/CAN peripherals and desired firmware/API. |

The free adaptation program applies to selected board and firmware combinations. Hardware design files and firmware carry their respective licenses; follow the instructions for the specific project and package.

## Commercial services

| Who we work with | What we provide | Contact |
| --- | --- | --- |
| USB-CAN/CAN FD hardware manufacturers | Software and firmware solutions for product integration, host-software connectivity and device management. | [Hardware integration inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20hardware%20integration) |
| Chip vendors serving USB-CAN/CAN FD applications | CANmeleon firmware-family porting and maintenance for target chip platforms. | [Chip platform porting and maintenance](mailto:len2slaw@foxmail.com?subject=CANmeleon%20chip%20platform%20porting) |
| Teams with specific product requirements | Custom firmware development for required interfaces, software workflows and device behavior. | [Custom firmware inquiry](mailto:len2slaw@foxmail.com?subject=CANmeleon%20custom%20firmware) |

Include your company/project, target MCU or board, CAN/CAN FD channels, USB interface, host OS and API, required features and schedule. For ongoing maintenance, describe the releases and support scope you need. Send project documents and commercial details by email.

## Commercial adaptation example: Kunhong KHCM and derived hardware

Kunhong's **KHCM-series chips and derived USB-CAN/CAN FD hardware** are examples of commercial CANmeleon firmware adaptation. The [device compatibility catalog](https://canmeleon.com/en/firmware/devices/) lists model-specific firmware choices, including KHCM102 and KH-UCANFD devices. Use each model's documentation for its electrical interfaces, channels and installation requirements.

[KHCM chip documentation](https://docs.kunhong-elec.com/en/products/can-communication/CANmeleon-controller-ic.html) · [Adapted device models](https://canmeleon.com/en/firmware/devices/) · [Discuss your own platform](mailto:len2slaw@foxmail.com?subject=CANmeleon%20platform%20adaptation)

## Find the firmware for your software

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

## Frequently asked questions

**Is CANmeleon tied to one hardware manufacturer?** CANmeleon is a USB-CAN/CAN FD ecosystem for multiple hardware and chip vendors. Existing adaptations are examples; manufacturers can bring their own products and platforms for integration.

**Where can I find hardware projects and contribute?** Start with the CANmeleon Hardware repository on GitHub. Its README links project documentation, contribution instructions and hardware proposals. Board-specific files and revisions are organized in that repository.

**Which firmware adaptations are free?** The program covers selected open-source hardware and firmware combinations. Submit your board's project URL, revision and desired firmware through the adaptation request form to establish the applicable package and access terms.

**Can I install an existing firmware package on my own board?** Use a published package only for the board and hardware revision it targets. For another board or MCU, request a port and provide its hardware and host-interface requirements.

**Can one adapter use different software ecosystems?** Supported devices can switch between applicable firmware families. One firmware runs at a time; available modes and stored images depend on hardware, storage and licensing.

## Contact and participate

- **Commercial solutions, chip porting/maintenance and custom firmware:** [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com).
- **Open-source hardware and free adaptation:** [contribute to CANmeleon Hardware](https://github.com/CANmeleon/canmeleon-hardware) or [submit an adaptation request](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md).
- **Firmware support and feature requests:** [firmware issue tracker](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues). Include the board, firmware, driver, software/API and reproduction steps.
- **Device Manager support:** [client issue tracker](https://github.com/CANmeleon/canmeleon-device-manager/issues) for installation, detection, updates or recovery.
