# Qt6 packaging for SFOS: aarch64

This repository is used to build Qt6 packages for aarch64. As Sailfish SDK has bugs,
To build, clone this repository and build with tbuilder. 

See TBuider repository for docs: https://github.com/rinigus/tbuilder


## Building

Current builds are performed on Oracle Cloud instance. While some packages can be built
on OBS, it is difficult to make builds that are split between tbuilder and OBS if the packages
depend on each other. So, all Qt6 and KF6 packages are packaged here and later uploaded as a part
of prebuilt package.

Build node configuration: 
- Shape: VM.Standard.A2.Flex
- OCPU count: 4
- Memory (GB): 24
- Boot volume: 75 GB

