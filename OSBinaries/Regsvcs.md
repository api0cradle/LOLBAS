## Regsvcs.exe

* Functions: Execute

```
regsvcs.exe AllTheThingsx64.dll
```

Acknowledgements:
* Casey Smith - @subtee

Code sample:
* [AllTheThingsx64.dll](https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/AllTheThings/AllTheThingsx64.dll)[1]     
* [AllTheThingsx86.dll](https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/AllTheThings/AllTheThingsx86.dll)[1]     

Resources:
* https://pentestlab.blog/2017/05/19/applocker-bypass-regasm-and-regsvcs/
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Payloads/RegSvcsRegAsmBypass.cs
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Execution/RegsvcsRegasm.md
* https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/

Full path:
```
C:\Windows\Microsoft.NET\Framework\v2.0.50727\regsvcs.exe
C:\Windows\Microsoft.NET\Framework64\v2.0.50727\regsvcs.exe
C:\Windows\Microsoft.NET\Framework\v4.0.30319\regsvcs.exe
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\regsvcs.exe
```

Notes:
[1]Code sample linked to Red Canary - Atomic Red TeamMITRE ATT&CK:
* [Regsvcs/Regasm](https://attack.mitre.org/wiki/Technique/T1121)
