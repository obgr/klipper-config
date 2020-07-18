# BLV-ender-3-duet2
This repository contains my Reprapfirmware configuration for my BLV modded Ender 3 Pro.
Please not that this configuration is not "final, there is still issues to resolve and settings to optimise.

## Why?
I did not have many refferences for my configuration, so i decided to upload my own configuration if someone else would like to look at it.

# Hardware
- Ender 3 Pro
- Duet 2 Wifi
- BLV Ender 3 Pro upgrade aluminum Kit
- Bondtech BMG Extruder (direct drive)
- Extruder stepper: NEMA 17, 0.9°, 18 N/cm, Stepper length: 26 mm.
- Dual Z steppers (stock creality steppers)
- E3d V6 (generic heater cartridge)

# FAQ
Q: How did you connect your duet 2 wifi to a hidden wifi?
A: First i entered the wifi password via console.
   ```
   M587 S"MyHiddenSSID" P"MySecretWifiPassword!"
   ```
   Second, i added a line in config.g in order to connect to the hidden wifi on boot
   ```
   M552 S1 P"MyHiddenSSID" ;Connect to hidden wifi
   ```

# Links 
- BLV Projects
https://www.blvprojects.com/blv-ender-3-pro

- Extruder stepper
Nema 17 Motor Slim Power 0.9
https://www.bondtech.se/en/product/nema-17-motor-slim-power-ldo-42sth25-1404mac-0-9-degree/

- Duet3d Documentation
https://duet3d.dozuki.com/
