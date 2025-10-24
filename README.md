# Bluetooth Controllers Reversing

Reverse engineering Bluetooth controllers to get more out of them!

This repository serves two main purposes:

- Map Bluetooth dongles to Bluetooth chip controllers to facilitate purchase decissions.
- Map vendor commands available for each chip, to get advanced functionalities.

If you want to contribute to this documentation and do not know how to, checkout the [Guide](Guide/README.md)

## Dongles

| Device                                                       | VID&PID              | Transp | Ant | Con | Chip                                             |
| ------------------------------------------------------------ | -------------------- | ------ | --- | --- | ------------------------------------------------ |
| [Cypress CYW920819EVB-02](Dongle/Cypress_CYW920819EVB-02.md) | 04b4:009b            | UART   | 1   | UFL | [Cypress CYW20819](Chip/Cypress_CYW20819.md)     |
| [EDUP EP-B3536](Dongle/EDUP_EP-B3536.md)                     | 0bda:a728, 2550:8761 | USB    | 1   | SMA | [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) |
| [Nebra CSR8510](Dongle/Nebra_CSR8510.md)                     | 0a12:0001            | USB    | 0   | No  | [Qualcomm CSR8150](Chip/Qualcomm_CSR8150.md)     |
| [TP-Link UB4A](Dongle/TPLink_UB4A.md)                        | 0a12:0001            | USB    | 0   | No  | [Qualcomm CSR8150](Chip/Qualcomm_CSR8150.md)     |
| [TP-Link UB500 Plus](Dongle/TPLink_UB500Plus.md)             | 2357:0604            | USB    | 0   | No  | [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) |
| [TP-Link UB500](Dongle/TPLink_UB500.md)                      | 2357:0604            | USB    | 1   | No  | [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) |
| [UGREEN CM591](Dongle/UGREEN_CM591.md)                       | 10d7:b012            | USB    | 0   | No  | [Actions ATS2851](Chip/Actions_ATS2851.md)       |
| [UGREEN CM748](Dongle/UGREEN_CM748.md)                       | 33fa:0012            | USB    | 0   | No  | [Barrot Unk](Chip/Barrot_Unk.md)                 |
| [UGREEN CM749](Dongle/UGREEN_CM749.md)                       | 33fa:0010            | USB    | 1   | No  | [Barrot BR8554](Chip/Barrot_BR8554.md)           |
| [ZEXMTE Unk1](Dongle/ZEXMTE_Unk1.md)                         | 0bda:a728            | USB    | 1   | SMA | [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) |
| [ZEXMTE Z01](Dongle/ZEXMTE_Z01.md)                           | 0bda:a729            | USB    | 2   | No  | [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) |
| [ZEXMTE Z03](Dongle/ZEXMTE_Z03.md)                           | ?                    | USB    | 0   | No  | ?                                                |

## Chips

| Chip                                             | WOOTB[^1] | Modes     | BT Ver |
| ------------------------------------------------ | --------- | --------- | ------ |
| [Actions ATS2851](Chip/Actions_ATS2851.md)       | Yes       |           | 5.3    |
| [Barrot BR8554](Chip/Barrot_BR8554.md)           | Yes       |           | 5.4    |
| [Barrot Unk](Chip/Barrot_Unk.md)                 | Yes       |           |        |
| [Cypress CYW20819](Chip/Cypress_CYW20819.md)     | Yes       |           |        |
| [Espressif ESP32](Chip/Espressif_ESP32.md)       | Yes       | BR/EDR/LE | 4.2    |
| [Qualcomm CSR8150](Chip/Qualcomm_CSR8150.md)     | Yes       |           | 4.0    |
| [Realtek RTL8761BUV](Chip/Realtek_RTL8761BUV.md) | No        | BR/EDR/LE | 5.1    |

[^1]: Works out of the box.
