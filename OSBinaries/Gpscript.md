## Gpscript.exe

* Functions: Execute

```
Gpscript /logon    

Gpscript /startup    
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
*

Resources:
* https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/


Full path:
```
c:\windows\system32\gpscript.exe
c:\windows\sysWOW64\gpscript.exe
```

Notes:
You need to add Scripts.ini file under C:\Windows\System32\GroupPolicy\User\Scripts that contains the following:
[Logon]
0CmdLine=C:\data\dummy.bat
0Parameters=

If you want ps1 scripts you need to name the file PSscripts.ini instead.

You also need to add CSE guid to gpt.ini file and also increase version number. This is located under C:\Windows\System32\GroupPolicy\.

Before running gpscript.exe /logon you need to run gpupdate with the mentioned files in place first.


Detection:
Changes to or new scripts.ini or psscripts.ini
 
