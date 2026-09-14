<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.96″ AMOLED 410×502 (CO5300 · QSPI)</h1>

<p align="center"><b>AMOLED module · QSPI · CO5300 · capacitive touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 1.96 inch" src="https://img.shields.io/badge/Size-1.96%22-3498DB?style=flat-square" />
  <img alt="Resolution: 410x502" src="https://img.shields.io/badge/Resolution-410%C3%97502-8E44AD?style=flat-square" />
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: CO5300" src="https://img.shields.io/badge/Driver-CO5300-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.96 inch 410×502 AMOLED QSPI module (CO5300) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **1.96″ 410×502 AMOLED** is a **QSPI** color display module driven by **CO5300**, with capacitive touch (**CST820**). Suited to handheld devices, wearables, and compact portrait HMI.

Spec ID (repository name): `amoled-1.96-410x502-qspi-co5300`

Current module version: **AM196Q410502LK**. Electrical and mechanical details follow [`docs/AM_196_Q410502_LK_0710e73b4c.pdf`](./docs/AM_196_Q410502_LK_0710e73b4c.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.96 inch |
| Type | AMOLED (color) |
| Resolution | 410×502 |
| Interface | QSPI |
| Driver IC | CO5300 |
| Touch driver | CST820 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-S3 · CO5300 QSPI + esp-lvgl-adapter / LVGL8 | [`examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/`](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/) |
| ESP32-S3 · CO5300 QSPI + esp-lvgl-adapter / LVGL9 | [`examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/`](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/) |
| ESP32-S3 · LVGL8 + TE | [`examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/`](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/) |
| ESP32-S3 · LVGL9 + TE | [`examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/`](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/) |
| ESP32-S3 · LVGL8 + TE + software rotate 90° | [`examples/with-te-sw-rotate-90/esp32s3-idf5_co5300-qspi_lvgl8_amoled-with-te/`](./examples/with-te-sw-rotate-90/esp32s3-idf5_co5300-qspi_lvgl8_amoled-with-te/) |

## Repository layout

```text
amoled-1.96-410x502-qspi-co5300/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── AM196Q410502LK/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (AM196Q410502LK) | [`docs/AM_196_Q410502_LK_0710e73b4c.pdf`](./docs/AM_196_Q410502_LK_0710e73b4c.pdf) |
| Driver IC datasheet (CO5300) | [`docs/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf`](./docs/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf) |
| Touch IC datasheet (CST820) | [`docs/DS_CST_820_V1_2_e0543732ca.pdf`](./docs/DS_CST_820_V1_2_e0543732ca.pdf) |
| Init sequence (text) | [`docs/Truly1.952_CO5300_BV6802_QSPI_简码_20240314.txt`](./docs/Truly1.952_CO5300_BV6802_QSPI_%E7%AE%80%E7%A0%81_20240314.txt) |
| 1.96″ AMOLED adapter schematic | [`docs/1.96寸AMOLED转接板原理图.png`](./docs/1.96%E5%AF%B8AMOLED%E8%BD%AC%E6%8E%A5%E6%9D%BF%E5%8E%9F%E7%90%86%E5%9B%BE.png) |
| 1.96 / 2.13 AMOLED adapter board | [`docs/PCB-1.96&2.13AMOLED转接板.pdf`](./docs/PCB-1.96%262.13AMOLED%E8%BD%AC%E6%8E%A5%E6%9D%BF.pdf) |
| Connector datasheet (OK-23GF024-04) | [`docs/OK-23GF024-04.pdf`](./docs/OK-23GF024-04.pdf) |

### Samples

- [ESP32-S3 CO5300 QSPI + LVGL8](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/)
- [ESP32-S3 CO5300 QSPI + LVGL9](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/)
- [ESP32-S3 LVGL8 + TE](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/)
- [ESP32-S3 LVGL9 + TE](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/)
- [ESP32-S3 LVGL8 + TE + software rotate 90°](./examples/with-te-sw-rotate-90/esp32s3-idf5_co5300-qspi_lvgl8_amoled-with-te/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository if you have any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
