# Supported devices

> [!IMPORTANT]  
> Tuya devices share model names.  
> **Identify your device by Zigbee Manufacturer.** *Do not install if it does not match!*  

To support a new device, read [contribute/porting.md](/docs/contribute/porting.md) and ask for help.  
**Also read:** [recommended.md](./recommended.md) & [not_recommended.md](./not_recommended.md)  

### Legend

| Symbol | Meaning  |                    |                      |                    |                |           |
| :----: | ---------| ------------------ | -------------------- | ------------------ | -------------- | ----------|
|   🚧   | Status   | 🟩 Fully supported | 🟨 Mostly supported  | 🟧 In progress     | 🟥 Unsupported |           |
|   📦   | Build    | ✔️ Available       | ❌ Unavailable       |                    |                |           |
|   💡   | Category | 🇲 Module          | 🇸 Switch            | 🇴  Outlet         | 🇷 Remote      | 🇧  Board |
|   ⚡   | Power    | 🔌 Mains           | 🔋 Battery           | 🔱 USB             |                |           |
|   📲   | Install  | 🛜 Wireless        | ➿ By wire           |                    |                |           |
|   🏭   | MCU      | `TL` Telink        | `SL` Silicon Labs    |                    |                |           |

> [!NOTE]  
> Z2M pages are sometimes generic.  
> ***Look up devices in the linked threads and store listings!***

<!-------------------------------------------------------------------
  This page (`supported.md`) is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make update_supported_devices`
-------------------------------------------------------------------->

### Device list

| 🚧 | 📦 | 💡 | ⚡ | 📲 | 🏭 | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | -- | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_hyziup76` <br> `TS0001` | [GoSmart IP-2101SZ <br> EMOS H5101](https://www.zigbee2mqtt.io/devices/TS0001.html) | [`Store`](https://www.emosgosmart.eu/en/products/gosmart-switch-module-ip-2101sz-zigbee-1-channel/) [`amzn`](https://www.amazon.de/dp/B0DDCJ53Y4) | [`#199`](https://github.com/romasku/tuya-zigbee-switch/issues/199) | Supported | 

Data from [`device_db.yaml`](/device_db.yaml)
