[![](https://img.shields.io/badge/Gitter%20HL%20Community-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/Hackintosh-Life-IT/community)
[![](https://img.shields.io/badge/Reposity-Baio77-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/Baio1977?tab=repositories)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)

# HP16 Pavilion Gaming

![descrizione](./ScreenShot/1.png)

## Computer Spec:

| Component          | Brank                               |
| ------------------ | ----------------------------------  |
| CPU                | Intel® i7-10750H (CometLake)        |
| IGPU               | Intel® UHD Graphics 630             |
| dGPU               | Nvidia 1060 GTX (disabled on macOs) |
| Display            | 1920x1080                           |
| Audio              | Realtek ALC 245 |
| Ram                | 16GB                                |
| SSD                | Kingstone A400 128gb                |
| SmBios             | MacbookPro 16,4                     |
| BootLoader         | OpenCore                            |

### Trackpad

# Patch ACPI 

```swift
Scope (I2C1)
{
    If (_OSI ("Darwin"))
    {
        Name (USTP, One)
    }
    
    Scope (TPD0)
    {
        If (_OSI ("Darwin"))
        {
             Name (OSYS, 0x07DC)
        }        
    }
}     
```               
![descrizione](./ScreenShot/4.png)

# If you need help please contact us on [Telegram](https://t.me/HackintoshLife_it) or [Web](https://www.hackintoshlife.it/)
