# Lenovo ThinkPad T480 (Kaby Lake Edition)

### The ideal hardware: 

CPU: ```Intel Core i5-7300U```

RAM: ```8GB DDR4 RAM```

Storage Type: ```Solid State Drive```

Wifi: ```Intel 8265 Wireless Card```


I forked Valnoxy's ThinkPad T480 OpenCore Configuration and modified some specifics to optimize it for the Kaby Lake (Intel Core i5-7300U 7th Gen) configuration.

Disclaimer: 

The original developer of this fork had to install Monterey first using the EFI found at https://github.com/Comet1903/t480-monterey-opencore. From there, I moved my SMBIOS information to the "EFI" config found at https://github.com/valnoxy/t480-oc. I also installed CPUFriend to deal with thermals and power management. For some reason, this caused my system to speed up considerably whilst being cooler and having a much longer battery life. My current hypothesis is that the CPU was drawing too much power, overheating, then thermal throttling whilst continuing to overheat, necessitating more use of the fans, which caused the CPU to heat up more, and so on. By installing CPUFriend, I think I interruped this feedback loop at its origin, thereby eliminating all of these problems at once. 
