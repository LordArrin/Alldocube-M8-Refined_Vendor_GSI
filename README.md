# Alldocube-M8-Refined_Vendor_GSI
Modded and tweaked vendor for GSI ROMs.

*Disabled useless mediatek's trash
*Disabled camera's fps drop
*Disabled encryption by default
*Disabled many perf daemons
*Added optimised settings from the other devices. 
*So much else that I've forgot)

To fix camera add script to autorun: 


#!/system/bin/sh

sleep 60

killall camerahalserver

killall cameraserver

done


Works on stock ROM, but I recommend GSI A11, especially this one by eremitein.
https://sourceforge.net/projects/treblerom/files/crDRom11/

The UMIDIGI A5 Pro (codenamed _"M8"_) this is a budget-class tablet from Alldocube.
It was released in December 2019. His SoC is MediaTek Helio X27 (MT6797X), which provides three processor clusters, each designed to more efficiently handle different types of workloads. The premium MediaTek Helio X27 features a maximized clock frequency across all three clusters, with an unequaled maximum of 2.6GHz on the powerful ARM Cortex-A72 cluster.


| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Deca-core                                                                                                                      |
| Chipset                 | Mediatek Helio X27 (MT6797X)                                                                                                   |
| GPU                     | Mali-T880 MP4                                                                                                                  |
| Memory                  | 3 GB RAM                                                                                                                       |
| Shipped Android Version | 8.0                                                                                                                            |
| Storage                 | 32 GB                                                                                                                          |
| Battery                 | Non-removable 5500 mAh battery                                                                                                 |
| Display                 | 1200 x 1920 pixels, 5:8 ratio (~283 ppi density)                                                                               |
| Camera                  | 5MP + 2MP withot LED and legacy Camera2Api support                                                                             | 

## Device picture
<img src="https://github.com/LordArrin/different_trash/blob/fc37bd7d1ec60dcd12391efbf78bfbe168598464/alldocube-m8-fill.jpg"/>

Credits: 

https://github.com/Iscle/OrangePi_4G-IOT_Android_8.1_BSP

https://dumps.tadiphone.dev/dumps/meizu/pro7plus
         
https://elementalx.org/devices/pixel/

https://github.com/SHIFTPHONES/android_device_shift_mt6797-common
