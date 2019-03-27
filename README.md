# hackintosh

I was initially having problems with the disk, it was saying that it couldn't be formatted to APFS... Solved with this combination of drivers + formatting to APFS in Disk Utility (pre install).
Also, I'm trying to dual boot with Win10 on a separate disk.
I followed the guide at hackintosh.gitbook.io, so vanilla method. The config.plist isn't updated, I'll have to figure out what I need to censor before I upload it again xD.

### hardware:
- Core i9 9900K
- MSI Vega 56 Airboost
- EVGA CLC 280
- Crucial Ballistix 32GB 3000Mhz
- MSI Z390 MEG Tomahawk
- Samsung 960 PRO 512GB
- TP-Link Archer T6E
- EVGA G3 650
- NZXT H500

### kexts
- AppleALC
- IntelMausiEthernet
- Lilu
- SMCLightSensor
- SMCProcessor
- SMCSuperIO
- VegaTab_56
- VirtualSMC
- WhateverGreen

### drivers64UEFI
- VBoxHfs
- ApfsDriverLoader
- EmuVariableUefi
- NvmExpressDxe
- OsxAptioFixDrv
