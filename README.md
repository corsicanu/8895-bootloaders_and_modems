# Modem and bootloader repository 
**for Samsung Galaxy S8(+)/Note8 Exynos variants (including korean)**

### Do note this is not a way to downgrade revision of modem and bootloader.

```
Copyright 2019-2020 © corsicanu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
### Disclaimer
```
I am not responsable for anything you do with your device, don't blame me or anyone else 
involved in this for your failures, you are the only one choosing to mess up with your device. 
All the files here are pulled from official firmwares of the devices mentioned.
```

## Latest releases:
```
G950FXXS8DTC6
G955FXXS8DTC6
N950FXXSADTC4
G950NKSU4DTD1
G955NKSU4DTD1
N950NKSU5DTD2
```

## Instructions:
**1. Update via TWRP:**
   - Download **\*\_twrp\_flashable\.zip** from [releases](https://github.com/corsicanu/8895-bootloaders_and_modems/releases)
   - Boot phone in TWRP
   - Flash the downloaded zip as any other

**2. Update via Odin:**
   - Download Odin v3.13.1
   - Download and install Samsung Drivers (if you have them installed you can skip this step)
   - Download **\*\_odin\_flashable\.zip** from [releases](https://github.com/corsicanu/8895-bootloaders_and_modems/releases) and unpack it
   - Switch off the phone
   - Use Volume Down+Bixby+Power to enter Download Mode
   - Open Odin and make sure that your device is detected
   - Put **BL\*.tar** file into BL tab and **CP\*.tar** file into CP tab
   - Click Start and wait for the device to reboot
