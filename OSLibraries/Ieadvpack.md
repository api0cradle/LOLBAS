## Ieadvpack.dll

* Functions: Execute

```
rundll32.exe ieadvpack.dll,LaunchINFSection test.inf,,1,   

rundll32.exe IEAdvpack.dll,RegisterOCX calc.exe   
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken (RegisterOCX)
* Jimmy - @bohops

Code sample:
* [Ieadvpack.inf](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Ieadvpack.inf)    
* [Ieadvpack_calc.sct](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Ieadvpack_calc.sct)

Resources:
* https://twitter.com/pabraeken/status/991695411902599168
* https://bohops.com/2018/03/10/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence-part-2/

Full path:
```
c:\windows\system32\ieadvpack.dll
c:\windows\sysWOW64\ieadvpack.dll
```

Notes:



Detection:


 
