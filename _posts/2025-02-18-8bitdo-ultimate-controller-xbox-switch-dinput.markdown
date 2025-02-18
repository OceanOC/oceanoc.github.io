---
layout: sans
title:  "How to change controller modes of your 8BitDo Ultimate Controller"
date:   2025-02-18
categories: jekyll update
---
(Last Updated: 02/18/2025) \
\
Since there were no guides on how to change the mode on the 8BitDo Ultimate Controller, I decided to make one
### **FOLLOW AT YOUR OWN RISK**
Updating the firmware may **corrupt** or render the controller **completely unusable**. By following these instructions, you acknowledge that any issues arising from the firmware update are **at your own risk.**
## Instructions
The firmware upgrader is Windows 10/11 only. *(Linux might work, but I won't reccomend using it)*
1. Download the firmware from [8BitDo's Fileserver](https://tempfiles.8bitdo.com/SPSP/UltimateBLRR103m.zip), This is not the same as the one as their Firmware Updater
2. Extract the ZIP file
3. Plug in the 2.4G receiver
4. Open `Updater.exe`
5. follow its instructions and choose `BETAFW103.dat`
6. Wait patiently while the update is done

WARNING: **DO NOT UNPLUG THE RECEIVER WHILE IT IS UPDATING**
## How to change modes after the update
```
Hold 5sec swap mode

Switch mode:   SELECT+Y

X-Input mode:   SELECT+X

D-Input mode:   SELECT+B

Default mode:   SELECT+START

Default modes:
Win10/11             X-Input
Linux/Android/Others D-Input
Switch               Switch

MINUS(-) = SELECT
```
Features:
<table style="text-align: center">
    <tr>
        <td>Mode</td>
        <td>Gyro</td>
        <td>Vibration</td>
        <td>Triggers</td>
        <td>Back Pedals</td>
    </tr>
    <tr>
        <td>D-Input</td>
        <td style="background-color:darkred">No</td>
        <td style="background-color:darkred">No</td>
        <td style="background-color:green">Analog</td>
        <td style="background-color:darkred">No</td>
    </tr>
    <tr>
        <td>X-Input</td>
        <td style="background-color:darkred">No</td>
        <td style="background-color:green">Yes</td>
        <td style="background-color:green">Analog</td>
        <td style="background-color:darkred">No</td>
    </tr>
    <tr>
        <td>Switch</td>
        <td style="background-color:green">Yes</td>
        <td style="background-color:green">Yes</td>
        <td style="background-color:darkblue">Digital</td>
        <td style="background-color:darkred">No</td>
    </tr>
</table>