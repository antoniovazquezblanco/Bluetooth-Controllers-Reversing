# Guide

## Dongle identification

There are many products that do not have a clear manufacturer name or model.

You may start by trying to locate a web with the manufacturer name and search there for possible model numbers.

Also, wireless devices should undergo a certification process to be legal to sell in certain countries. Particularly, for the US market, FCC performs this certification. Try to locate the "FCC ID" of your device and try to look up for the certification documents in webs such as <https://device.report/> or <https://fcc.report/>.

1. Create a document in the `Dongle` folder by copying the format of other existing examples.
2. Add an image of the device, if possible directly from the manufacturer webpage.
3. Fill in the information you have found. Do not forget to add the links to the FCC reports or de manufacturer web.
4. Add teardown images if you have opened your device.
5. Identify the VID and PID of the USB. In Linux and MacOS you may use the `lsusb` command for this. In Windows, the `Device Manager` allows you to browse device `Properties`. In the `Details` tab you may locate the `Hardware ID` property.
6. Add the device to the readme table.

## Dongle chip identification

This is not always an easy task.

From the previous section, having a VID and PID for the USB device may give you hints of the manufacturer and sometimes the chip model.

You may also recover the chip `Local Version Information` using the `hciconfig -a` command in Linux or using the [Vendor Command Enumerator](https://github.com/TarlogicSecurity/BluetoothExamplesAndDemos/tree/main/VendorCommandEnumerator) python script in any OS. Local version information contains a `Vendor` field that is useful.

Other sources of information to achieve this would be the FCC report internal photos. Try to locate the Bluetooth chip in FCC internal photos and search the markings.

Sometimes there is no other option than to tear down the dongle and identify the chips.

## Vendor command enumeration

For vendor command enumeration you may use the [Vendor Command Enumerator](https://github.com/TarlogicSecurity/BluetoothExamplesAndDemos/tree/main/VendorCommandEnumerator) python script.
