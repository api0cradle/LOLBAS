## Diskshadow.exe

* Functions: Execute, Dump NTDS.dit

```
diskshadow.exe /s c:\test\diskshadow.txt   

diskshadow> exec calc.exe    
```

Acknowledgements:
* Jimmy - @bohops

Code sample:
*

Resources:
* https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active-directory-database-extraction/

Full path:
```
c:\windows\system32\diskshadow.exe
c:\windows\sysWOW64\diskshadow.exe
```

Notes:
Only present on Windows Server OS 2008 and newer


 
MITRE ATT&CK:
* [Credential Dumping](https://attack.mitre.org/wiki/Technique/T1003)
