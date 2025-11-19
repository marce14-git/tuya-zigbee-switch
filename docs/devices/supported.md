# Supported devices

**Z2M device name** usually represents a collection of devices.  
Even if they work the same, rebranded versions have different internals and different pinouts (and therefore require custom builds).  

**Zigbee Manufacturer** is the most reliable unique device identifier. If the TZ3000 id of your device is not on this list, it requires porting. 

For devices that contain a **supported Tuya Zigbee module** (ZTU, ZT2S, ZT3L), porting is relatively simple.  
It consists of tracing (or guessing) the **board pinout**, adding an entry in the `device_db.yaml` file and running the build action. 

Also read:  
- [contribute/porting_to_new_device.md](/docs/contribute/porting_to_new_device.md)
- [recommended.md](./recommended.md)
- [not_recommended.md](./not_recommended.md)

| Z2M device name | Vendor name | Zigbee Manufacturer | Type | Status | Issue |
| --- | --- | --- | --- | --- | --- |
| [TS0001_switch_module](https://www.zigbee2mqtt.io/devices/TS0001_switch_module.html) | Tuya 1-gang  | _TZ3000_hyziup76 | router | in_progress |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/)  | 
| [TS0002_switch_module](https://www.zigbee2mqtt.io/devices/TS0002_switch_module.html) | Tuya 2-gang  | _TZ3000_wxtmgjbd | router | in_progress |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/)  | 

