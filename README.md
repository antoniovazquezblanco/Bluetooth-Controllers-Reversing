# Bluetooth Controllers Reversing

Reverse engineering Bluetooth controllers to get more out of them!

This repository serves two main purposes:

- Map Bluetooth dongles to Bluetooth chip controllers to facilitate purchase decissions.
- Map vendor commands available for each chip, to get advanced functionalities.

## Dongles

| Device                                                       | VID    | PID    | Chip                                             |
| ------------------------------------------------------------ | ------ | ------ | ------------------------------------------------ |
| [Cypress CYW920819EVB-02](Dongle_Cypress_CYW920819EVB-02.md) | ?      | ?      | [Cypress CYW20819](Chip_Cypress_CYW20819.md)     |
| [EDUP EP-B3536](Dongle_EDUP_EP-B3536.md)                     | ?      | ?      | [Realtek RTL8761BUV](Chip_Realtek_RTL8761BUV.md) |
| [EDUP EP-B3553Plus](Dongle_EDUP_EP-B3553Plus.md)             | 0x0bda | 0xa728 | [Realtek RTL8761BUV](Chip_Realtek_RTL8761BUV.md) |
| [TP-Link UB4A](Dongle_TPLink_UB4A.md)                        | 0x0a12 | 0x0001 | [Qualcomm CSR8150](Chip_Qualcomm_CSR8150.md)     |
| [UGREEN CM591](Dongle_UGREEN_CM591.md)                       | 0x10d7 | 0xb012 | [Actions ATS2851](Chip_Actions_ATS2851.md)       |
| [UGREEN CM748](Dongle_UGREEN_CM748.md)                       | 0x33fa | 0x0012 | [Barrot Unk](Chip_Barrot_Unk.md)                 |
| [UGREEN CM749](Dongle_UGREEN_CM749.md)                       | 0x33fa | 0x0010 | [Barrot BR8554](Chip_Barrot_BR8554.md)           |

## Chips

| Chip                                             |
| ------------------------------------------------ |
| [Actions ATS2851](Chip_Actions_ATS2851.md)       |
| [Barrot BR8554](Chip_Barrot_BR8554.md)           |
| [Barrot Unk](Chip_Barrot_Unk.md)                 |
| [Espressif ESP32](Chip_Espressif_ESP32.md)       |
| [Qualcomm CSR8150](Chip_Qualcomm_CSR8150.md)     |
| [Realtek RTL8761BUV](Chip_Realtek_RTL8761BUV.md) |

## Tools

- [Vendor Command Enumerator](https://github.com/TarlogicSecurity/BluetoothExamplesAndDemos/tree/main/VendorCommandEnumerator)
