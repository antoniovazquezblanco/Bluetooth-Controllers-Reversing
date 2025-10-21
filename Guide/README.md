# Guide

## Dongle identification

There are many products that do not have a clear manufacturer name or model.

You may start by trying to locate a web with the manufacturer name and search there for possible model numbers.

Also, wireless devices should undergo a certification process to be legal to sell in certain countries. Particularly, for the US market, FCC performs this certification. Try to locate the "FCC ID" of your device and try to look up for the certification documents in webs such as <https://device.report/> or <https://fcc.report/>.

1. Create a document in the `Dongle` folder by copying the format of other existing examples.
2. Add an image of the device, if possible directly from the manufacturer webpage.
3. Fill in the information you have found. Do not forget to add the links to the FCC reports or de manufacturer web.
4. Add the device to the readme table.

## Dongle chip identification

Try to locate the Bluetooth chip in FCC internal photos.
Identify the VID and PID of the USB.
See vendor in the local version information HCI packet.
Tear down the dongle and identify the chips.

## Vendor command enumeration

[Vendor Command Enumerator](https://github.com/TarlogicSecurity/BluetoothExamplesAndDemos/tree/main/VendorCommandEnumerator)
