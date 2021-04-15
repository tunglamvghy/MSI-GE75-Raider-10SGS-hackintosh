# INSTALLATION GUIDE

1. Make a recovery USB using [**gibMacOS**](https://github.com/corpnewt/gibMacOS) or **Olarila image** (recommended)
2. Copy **OC** folder and **Boot** folder to EFI partition of your USB.
3. Change all Debug options for OC including

| Property | Value |
| - | - |
| ScanPolicy | 0 |        
| ApplePanic | True |
| AppleDebug | True |
| Display Level | 2147483650 |
| Target | 0x43 |

Add '-v' to boot-args

4. Boot to Mac Recovery using usb you have just made
5. Turn on Wifi and install macOS on your SSD.
6. Boot to macOS you've installed
7. Using [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) or **OpenCore Configurator** to generate new SMBIOS
8. Copy **OC** folder and **Boot** folder from EFI partition of your USB to EFI partition of your SSD.
9. Go to Post-installation folder, and install AsusSMCDaemon and ComboJack.
10. Restart and Enjoy your new hackintosh


- If your pc has different specs, try to read [**OpenCore guide**](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) or [**Dortania guide**](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) for more details

## Need help. Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/tunglamvghy)
***If you want me to create your own EFI with a little payment, contact me via Telegram.***

## [Donate me](https://paypal.me/vtlam98)
If you want to donate, send me via [**PayPal**](https://paypal.me/vtlam98)
