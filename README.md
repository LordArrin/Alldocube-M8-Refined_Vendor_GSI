# Alldocube M8 Refined Vendor GSI

# Device was sold, work was stopped. Goodbye)

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

He is also in /vendor/data as camerafix.sh

For better batterysaving turn on wq_power_saving throw the any kernel manager app. I recommend EX Kernel Manager.
    
Works on stock ROM, but I recommend GSI A11, especially this one by eremitein.
https://sourceforge.net/projects/treblerom/files/crDRom11/

The Alldocube M8 (codenamed _"M8"_) this is a budget-class tablet from Alldocube.
It was released in December 2019. His SoC is MediaTek Helio X27 (MT6797X), which provides three processor clusters, each designed to more efficiently handle different types of workloads. The premium MediaTek Helio X27 features a maximized clock frequency across all three clusters, with an unequaled maximum of 2.6GHz on the powerful ARM Cortex-A72 cluster.


| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Deca-core                                                                                                                      |
| Chipset                 | Mediatek Helio X27 (MT6797X)                                                                                                   |
| GPU                     | Mali-T880 MP4                                                                                                                  |
| Memory                  | 3 GB LPDDR3 RAM Dual-channel                                                                                                   |
| Shipped Android Version | 8.0 x64                                                                                                                        |
| Storage                 | 32 GB EMMC5.1                                                                                                                  |
| Battery                 | Non-removable 5500 mAh battery                                                                                                 |
| Display                 | 8" IPS LCD 1200 x 1920 pixels                                                                                                  |
| Camera                  | 5MP + 2MP withot LED and legacy Camera2Api support                                                                             | 

## Device picture
<img src="https://github.com/LordArrin/different_trash/blob/fc37bd7d1ec60dcd12391efbf78bfbe168598464/alldocube-m8-fill.jpg"/>

#Benchmarks   

Geekbench 5.44  

<img src="https://github.com/LordArrin/different_trash/blob/main/viber_2022-02-22_09-02-03-278-lines-scale-0_50x-gigapixel.jpg"/>    
https://browser.geekbench.com/v5/cpu/12931261

vs stock: https://browser.geekbench.com/search?k=v5_cpu&q=ALLDOCUBE+M8 

345/1074   
187/1146   
171/1131   
...  
- from +7% to +121% better in single-core and from -4% to +25% in multi-core!

3DMark for Android 2.2.4801  

<img src="https://github.com/LordArrin/different_trash/blob/main/2022-02-22_09-56-15-002-gigapixel-lines-scale-0_50x%20(1).jpg"/>   
<img src="https://github.com/LordArrin/different_trash/blob/main/2022-02-22_09-56-15-002-gigapixel-lines-scale-0_50x%20(2).jpg"/>    
<img src="https://github.com/LordArrin/different_trash/blob/main/2022-02-22_09-56-15-002-gigapixel-lines-scale-0_50x%20(3).jpg"/>    

vs stock: https://benchmarks.ul.com/hardware/tablet/Alldocube+M8+review

- from -1% to +40% difference!

Credits and links: 

https://github.com/Iscle/OrangePi_4G-IOT_Android_8.1_BSP

https://dumps.tadiphone.dev/dumps/meizu/pro7plus

https://dumps.tadiphone.dev/dumps/shift/shift6m
         
https://elementalx.org/devices/pixel/

https://github.com/SHIFTPHONES/android_device_shift_mt6797-common
