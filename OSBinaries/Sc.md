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



 
