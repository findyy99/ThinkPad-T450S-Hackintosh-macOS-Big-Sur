# Thanks to [simprecicchiani](https://github.com/simprecicchiani), had move to T460s branch to add support for YogaSMC!
# English(current)
# OpenCore Version: 0.6.9
![About this Mac](./Pic/ScreenShoot.jpg)
![TouchPad](./Pic/trackpad.png)
![Battery](./Pic/battery.png)
![YogaSMC](./Pic/pane.png)
![YogaSMCNC](./Pic/pane.png)
 
### This is the configuration of the computer

- **Intel 5th Generation Architecture (Broadwell)**
- **Intel HD Graphics 5500**
- **Intel Series 9 Chipset Family**
- **macOS Big Sur**
- **Broadcom DW1560**


### Recommended **BIOS** settings
- `Security -> Security Chip`: **Disabled**;
- `Virtualization -> Intel Virtualization Technology`: **Enabled**;
- `Internal Device Access -> Bottom Cover Tamper Detection`:**Disabled**;
- `Anti-Theft -> Current Setting`: **Disabled**;
- `Anti-Theft -> Computrace -> Current Setting`: **Disabled**;
- `Secure Boot -> Secure Boot`: **Disabled**;
- `UEFI/Legacy Boot`: **UEFI Only**;
- `CSM Support`: **Yes**.


###  Works well

- CPU: Good frequency conversion.
- Graphics card: HD5500, good drive, acceleration available, mini DP external display, HDMI display with Dock.
- Sound card: use layout-id 32, if not suitable, you can replace it by yourself.
- Touchpad: powered by `VoodooSMBus` and `VoodooRMI`, silky and smooth, can be temporarily disabled by `PrtSc`.
- USB: works good.
- Little red dot and threes key(I don't know how to call them): works good.

### Places not working
- VGA

### Another things for dock-users
- HDMI: works fine.
- USB: works fine.
- Audio: works only when `layout-id` is 55.
