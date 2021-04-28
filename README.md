# macOS on Thinkpad T480s

## My hardware configuration
| Name                | Specifications | Funtional or not |
| ------------------- | -----------------------------------------|---------------|
| Processor           | Intel Core i7-8560U Processor            |Fully|
| Memory              | 16GB-> 8GB on Bourd and 8GB on the slot  |Fully|
| Storage             | samsung evo 970 256GB  |Fully|
| Graphics            | Intel UHD Graphics 620                   |Fully with WhateverGreen.kext and properties inject|
| Display             | 14.0" FHD 1920x1080 LED IPS              |Fully|
| Audio               | Realtek Audio ALC257 codec               |Fully with AppleALC.kext and layout-id 11|
| Ethernet            | Intel(R) Ethernet Connection (4) I219-V  |Fully with IntelMausi.kext|
| WLAN & Bluetooth    | bcr cs2 .so if you dont use this card wifi, you can find this kext in other pp and copy it to here
| MicroSD Card Reader | Generic-SD/MMC CRW USB Device            |not tested|
| Keyboard & Trackpad | LED backlight, TrackPoint and multi-touch touchpad |Almost fully with VoodooPS2Controller.kext, VodooSMBUS.kext and SSDT-KBRB patch| 
| Fingerprint         | On chip fingerprint reader               |Non-funtional|
| Camera         | built in camera               |Working with USBInjectAll.kext|



## Other Reasources

- https://github.com/EETagent/T480-OpenCore-Hackintosh/
- https://github.com/tylernguyen/x1c6-hackintosh

  
