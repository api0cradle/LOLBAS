## reg.exe

* Functions: Export Reg, Add ADS, Import Reg

```
reg export HKLM\SOFTWARE\Microsoft\Evilreg c:\ads\file.txt:evilreg.reg
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
* 

Resources:
* https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f

Full path:
```
c:\windows\system32\reg.exe
c:\windows\sysWOW64\reg.exe
```

Notes:



 
MITRE ATT&CK:
* [Credential Dumping](https://attack.mitre.org/wiki/Technique/T1003)
* [Credentials in Registry](https://attack.mitre.org/wiki/Technique/T1214)
* [Winlogon Helper DLL](https://attack.mitre.org/wiki/Technique/T1004)
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [Security Software Discovery](https://attack.mitre.org/wiki/Technique/T1063)
* [Modify Registry](https://attack.mitre.org/wiki/Technique/T1112)
* [Query Registry](https://attack.mitre.org/wiki/Technique/T1012)
