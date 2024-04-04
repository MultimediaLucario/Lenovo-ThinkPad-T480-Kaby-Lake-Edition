# Lenovo ThinkPad T480 (Kaby Lake Edition)

![repository-t480-template](https://github.com/MultimediaLucario/Lenovo-ThinkPad-T480/assets/72415505/0307c12a-d992-4c37-8835-3b888c9e772e)


[![macOS](https://img.shields.io/badge/macOS-Ventura-orange.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.8-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)

<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>Version: </strong>1.5.0
   <br />
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T480-Kaby-Lake-Edition/releases"><strong>Download now »</strong></a>
   <br />
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T480"><strong>Lenovo ThinkPad T480 OG EFI »</strong></a>
   <br />
   <a href="https://github.com/MultimediaLucario/Lenovo-ThinkPad-T480/issues">Report Bug</a>
   <a href="https://github.com/valnoxy/t480-oc/blob/main/CHANGELOG.md">View Changelog</a>
  </p>
</p>
</br>



### The ideal hardware: 

CPU: ```Intel Core i5-7300U```

RAM: ```8GB DDR4 RAM```

Storage Type: ```Solid State Drive```

Wifi: ```Intel 8265 Wireless Card```


This is a fork of Valnoxy's ThinkPad T480 OpenCore Configuration that has been modified to be optimized for the Kaby Lake (Intel Core i5-7300U 7th Gen) configuration.

## Disclaimer: 

The original developer of this fork had to install Monterey first using the EFI found at https://github.com/Comet1903/t480-monterey-opencore. From there, they moved their SMBIOS information to the "EFI" config found at https://github.com/valnoxy/t480-oc. They also installed CPUFriend to deal with thermals and power management. For some reason, this caused their system to speed up considerably whilst being cooler and having a much longer battery life. The current hypothesis is that the CPU was drawing too much power, overheating, then thermal throttling whilst continuing to overheat, necessitating more use of the fans, which caused the CPU to heat up more, and so on. By installing CPUFriend, they interruped this feedback loop at its origin, thereby eliminating all of these problems at once. 
