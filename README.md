# BLE_data_transfer

- Establish a connection using "bluetoothctl"
- "bluetoothctl" will display available attribuites and services from the remote BLE
- use "select-attribute" to select one attribute
- use "read" or "write 33 44" to read/write values to the devivce
- more details (https://docs.ubuntu.com/core/en/stacks/bluetooth/bluez/docs/reference/gatt-services)

BLE with AFH channel map
-----
- AFH channel map seems to be not implemented yet in BLE. You can use some app to update AFH channel map.. 
- See details (https://e2e.ti.com/support/wireless_connectivity/bluetooth_low_energy/f/538/p/450836/1621568)

General lib for CC2540
---
- https://github.com/Harper04/Python-for-TI-CC2540
- https://e2e.ti.com/support/wireless_connectivity/bluetooth_low_energy/f/538/t/117829
- https://e2e.ti.com/support/wireless_connectivity/bluetooth_low_energy/f/538/p/594081/2183929
- https://e2e.ti.com/support/wireless_connectivity/bluetooth_low_energy/f/538/p/450836/1621568

BLE btmgmt
-----
- https://github.com/chrippa/ds4drv/issues/123

Install Bluez
---
- https://urbanjack.wordpress.com/2014/06/05/how-to-set-bluez-into-ble-or-le-only-mode-ibeacon/
