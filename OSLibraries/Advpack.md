# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## Advpack.dll

* Functions: Execute

```
rundll32.exe advpack.dll,LaunchINFSection c:\test.inf,DefaultInstall_SingleUser,1,     
rundll32.exe advpack.dll,RegisterOCX calc.exe
```

Acknowledgements:
* Jimmy - @bohops

Code sample:
* [Advpack.inf](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack.inf)    
* [Advpack_calc.sct](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSLibraries/Payload/Advpack_calc.sct)

Resources:
* https://bohops.com/2018/02/26/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence/
* https://twitter.com/ItsReallyNick/status/967859147977850880
* https://twitter.com/bohops/status/974497123101179904

Full path:
```
c:\windows\system32\advpack.dll
c:\windows\sysWOW64\advpack.dll
```

Notes:



Detection:


 
