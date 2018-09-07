## regedit.exe

* Functions: Write ADS, Read ADS, Import registry

```
regedit /E c:\ads\file.txt:regfile.reg HKEY_CURRENT_USER\MyCustomRegKey
    
regedit c:\ads\file.txt:regfile.reg   
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
* 

Resources:
* https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f

Full path:
```
c:\windows\system32\regedit.exe
c:\windows\sysWOW64\regedit.exe
```

Notes:



 
MITRE ATT&CK:
* [SIP and Trust Provider Hijacking](https://attack.mitre.org/wiki/Technique/T1198)
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
