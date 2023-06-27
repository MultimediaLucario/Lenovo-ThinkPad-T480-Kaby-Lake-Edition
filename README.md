### Lenovo ThinkPad T480 (Kaby Lake Edition)

My hardware: 

Intel Core i5-7300U

16GB DDR4 RAM

Samsung 850 EVO SSD (500GB)

Intel 8265 Wireless Card


I've created this project based on Valnoxy's project, and modified some specifics to fit my individual needs and to resolve some of the minor issues that come with using Valnoxy's version with the 7th generation processor rather than the 8th generation processor. 

Disclaimer: 

I had to install Monterey first using the EFI found at https://github.com/Comet1903/t480-monterey-opencore. From there, I moved my SMBIOS information to the "EFI" config found at https://github.com/valnoxy/t480-oc. I also installed CPUFriend to deal with thermals and power management. For some reason, this caused my system to speed up considerably whilst being cooler and having a much longer battery life. My current hypothesis is that the CPU was drawing too much power, overheating, then thermal throttling whilst continuing to overheat, necessitating more use of the fans, which caused the CPU to heat up more, and so on. By installing CPUFriend, I think I interruped this feedback loop at its origin, thereby eliminating all of these problems at once. 
