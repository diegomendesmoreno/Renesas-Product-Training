---
title: "Introdução ao Bluetooth Low Energy (BLE) Renesas"
date: "2022-04-01"
draft: false
---

[Link de download da apresentação](../assets/material/DA14531_BLE_Introduction.pdf)

Seguindo a aquisição da Dialog Semi em 2021, a Renesas ganhou um novo portifólio de comunicação sem fio ([Wireless Connectivity](https://www.renesas.com/us/en/products/wireless-connectivity)). Veja abaixo, mais especificamente, as soluções de [Bluetooth Low Energy (BLE)](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy):

- [DA14531MOD](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy/da14531mod-smartbond-tiny-bluetooth-low-energy-module) - Módulo Bluetooth® Low Energy
  - DA14531MOD-00F0100 - módulo com PCB antena e **_certificação ANATEL_** (baixe os certificados na [página do produto](https://www.renesas.com/us/en/document/cer/smartbond-tiny-certification-brazil-canada?r=1601921))

    ![DA14531MOD](../assets/img/da14531mod.png "DA14531MOD")

- [DA14531](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy/da14531-smartbond-ultra-low-power-bluetooth-51-system-chip) - System on a Chip (SoC) Bluetooth® Low Energy. Packages FCGQFN24 (2.2×3mm) ou WLCSP17 (2x1.7mm)
- Kits de desenvolvimento:
  - [US159-DA14531EVZ](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy/us159-da14531evz-low-power-bluetooth-pmod-board-renesas-quick-connect-iot): Pmod™ Board (Renesas Quick-Connect IoT Platform)

    ![DA14531MOD Kit](../assets/img/da14531evz-pmod-board.png "DA14531MOD Kit")

  - [DA14531MOD-00DEVKT-P](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy/da14531mod-00devkt-p-smartbond-tiny-da14531-bluetooth-low-energy-51-system-chip-module-development-kit-pro): Bluetooth® Low Energy Module Development Kit Pro
  - [DA14531-00FXDEVKT-P](https://www.renesas.com/us/en/products/wireless-connectivity/bluetooth-low-energy/da14531-00fxdevkt-p-smartbond-tiny-da14531-bluetooth-low-energy-51-system-chip-development-kit-pro): Bluetooth® Low Energy SoC Development Kit Pro
- Programa de longevidade (PLP) com produção garantida de 10 anos (módulo) e 15 anos (SoC) a partir da data de lançamento. [Consulte aqui as datas de cada produto](https://www.renesas.com/us/en/product-longevity-program-plp-former-dialog-products).

- Modos de operação:
  - Modem (outro MCU como host da aplicação): [CodeLess™ AT Commands](https://www.renesas.com/us/en/software-tool/smartbond-codeless-commands) - interface com um MCU host via UART
    - [CodeLess User Manual](https://lpccs-docs.renesas.com/UM-140-DA145x-CodeLess/index.html)
    - [Lista de Comandos AT](https://lpccs-docs.renesas.com/UM-140-DA145x-CodeLess/atcommands.html)
    - [Renesas SmartConsole App](https://www.renesas.com/us/en/software-tool/smartbond-codeless-commands?downloads-title-filter=smartconsole#downloads) (Android / iOS)

  - Host (código de aplicação rodando no BLE): [Tutorial SDK6 Getting Started](https://lpccs-docs.renesas.com/Tutorial_SDK6/index.html) - stack BLE + código de aplicação no DA14531
    - [BLE_SDK6_examples (GitHub)](https://github.com/dialog-semiconductor/BLE_SDK6_examples)
    - [Renesas SmartBond App](https://play.google.com/store/apps/details?id=com.renesas.smartbond)

  - [Serial Port Service (SPS)](https://www.renesas.com/us/en/software-tool/serial-port-service-sps) – emulação de uma comunicação a cabo via BLE
    - [Tutorial Getting Started](https://lpccs-docs.renesas.com/Tutorial_DA145xx_DSPS_Getting_Started/introduction.html)
- Links relevantes:
  - [DA14531 TINY™ Module Getting Started](https://lpccs-docs.renesas.com/UM-B-139-Getting-Started-with-DA14531-TINY-Module/index.html)
  - [AN-B-075: DA14530/531 Hardware Guidelines](https://www.renesas.com/us/en/document/apn/b-075-da14530531-hardware-guidelines?r=1564826)
  - [AN-B-072: DA14531 Booting from OTP and Serial Interfaces](https://www.renesas.com/us/en/document/apn/b-072-da14531-booting-otp-and-serial-interfaces?r=1564826)
  - [SmartBond™ Development Tools](https://www.renesas.com/us/en/software-tool/smartbond-development-tools)
    - SmartSnippets™ Toolbox
    - SmartBond™ Flash Programmer

Vale a pena também darem uma olhada nos recursos abaixo:
- [Renesas Quick-Connect IoT Platform](https://www.renesas.com/us/en/software-tool/quick-connect-iot-platform): fast prototyping by providing compatible hardware and software building blocks
