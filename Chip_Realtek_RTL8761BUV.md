# Realtek RTL8761BUV Chip

## Vendor commands

| Command | Purpose                                                                                                                                    |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 0xfc10  | Unknown, resets the device and shows with different VID & PID                                                                              |
| 0xfc11  | Unknown, resets the device and shows with different VID & PID                                                                              |
| 0xfc12  | Unknown                                                                                                                                    |
| 0xfc13  | Unknown                                                                                                                                    |
| 0xfc14  | Unknown                                                                                                                                    |
| 0xfc16  | Unknown                                                                                                                                    |
| 0xfc17  | Unknown                                                                                                                                    |
| 0xfc1a  | Unknown                                                                                                                                    |
| 0xfc1f  | Unknown                                                                                                                                    |
| 0xfc20  | [HCI_VSC_DOWNLOAD_PATCH](https://github.com/torvalds/linux/blob/ee94b00c1a648530333d9734200be7a45e6e00cd/drivers/bluetooth/btrtl.c#L846)   |
| 0xfc21  | Unknown                                                                                                                                    |
| 0xfc22  | Unknown                                                                                                                                    |
| 0xfc27  | Unknown                                                                                                                                    |
| 0xfc28  | Unknown                                                                                                                                    |
| 0xfc35  | Unknown                                                                                                                                    |
| 0xfc37  | Unknown                                                                                                                                    |
| 0xfc39  | Unknown                                                                                                                                    |
| 0xfc46  | Unknown                                                                                                                                    |
| 0xfc50  | Unknown                                                                                                                                    |
| 0xfc55  | Unknown                                                                                                                                    |
| 0xfc56  | Unknown                                                                                                                                    |
| 0xfc61  | HCI_VSC_READ_MEMORY?                                                                                                                       |
| 0xfc62  | HCI_VSC_WRITE_MEMORY?                                                                                                                      |
| 0xfc64  | Unknown                                                                                                                                    |
| 0xfc65  | Unknown                                                                                                                                    |
| 0xfc66  | Unknown                                                                                                                                    |
| 0xfc67  | Unknown                                                                                                                                    |
| 0xfc68  | Unknown                                                                                                                                    |
| 0xfc69  | Unknown                                                                                                                                    |
| 0xfc6a  | Unknown                                                                                                                                    |
| 0xfc6b  | Unknown                                                                                                                                    |
| 0xfc6c  | Unknown                                                                                                                                    |
| 0xfc6d  | [HCI_VSC_READ_ROM_VERSION](https://github.com/torvalds/linux/blob/ee94b00c1a648530333d9734200be7a45e6e00cd/drivers/bluetooth/btrtl.c#L391) |
| 0xfc6e  | Unknown                                                                                                                                    |
| 0xfc73  | Unknown                                                                                                                                    |
| 0xfc79  | Unknown                                                                                                                                    |
| 0xfc7a  | Unknown                                                                                                                                    |
| 0xfc80  | Unknown                                                                                                                                    |
| 0xfc81  | Unknown                                                                                                                                    |
| 0xfc83  | Unknown                                                                                                                                    |
| 0xfc8a  | Unknown                                                                                                                                    |
| 0xfc8b  | Unknown                                                                                                                                    |
| 0xfc93  | Unknown                                                                                                                                    |
| 0xfc97  | Unknown                                                                                                                                    |
| 0xfc98  | Unknown                                                                                                                                    |
| 0xfc99  | Unknown                                                                                                                                    |
| 0xfca1  | Unknown                                                                                                                                    |
| 0xfca2  | Unknown                                                                                                                                    |
| 0xfcc0  | Unknown                                                                                                                                    |
| 0xfcc1  | Unknown                                                                                                                                    |
| 0xfcc2  | Unknown                                                                                                                                    |
| 0xfcc4  | Unknown                                                                                                                                    |
| 0xfcc5  | Unknown                                                                                                                                    |
| 0xfcc7  | Unknown                                                                                                                                    |
| 0xfcc8  | Unknown                                                                                                                                    |
| 0xfcc9  | Unknown                                                                                                                                    |
| 0xfcca  | Unknown                                                                                                                                    |
| 0xfccb  | Unknown                                                                                                                                    |
| 0xfccd  | Unknown                                                                                                                                    |
| 0xfcce  | Unknown                                                                                                                                    |
| 0xfccf  | Unknown                                                                                                                                    |
| 0xfcd0  | Unknown                                                                                                                                    |
| 0xfcd4  | Unknown                                                                                                                                    |
| 0xfcd9  | Unknown                                                                                                                                    |
| 0xfcda  | Unknown                                                                                                                                    |
| 0xfcdb  | Unknown                                                                                                                                    |
| 0xfcdc  | Unknown                                                                                                                                    |
| 0xfcf0  | Unknown                                                                                                                                    |
| 0xfd40  | Unknown                                                                                                                                    |
| 0xfd41  | Unknown                                                                                                                                    |
| 0xfd42  | Unknown                                                                                                                                    |
| 0xfd43  | Unknown                                                                                                                                    |
| 0xfd47  | Unknown                                                                                                                                    |
| 0xfd49  | Unknown                                                                                                                                    |
| 0xfd4a  | Unknown                                                                                                                                    |
| 0xfd4b  | Unknown                                                                                                                                    |
| 0xfd4c  | Unknown                                                                                                                                    |
| 0xfd4d  | Unknown                                                                                                                                    |

## Firmware

Latest patches:

- <https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/tree/rtl_bt/rtl8761bu_fw.bin>
- <https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/tree/rtl_bt/rtl8761bu_config.bin>

Patches history:

- <https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/log/rtl_bt/rtl8761bu_fw.bin>

## Links and documentation

- <https://kaimte.com/upload/attach/20240109/cf0bd5cb45bd513b56f9f7f76cfce266.pdf>
- <https://gist.github.com/peteristhegreat/b48da772167f86f43decbd34edbd0849>
