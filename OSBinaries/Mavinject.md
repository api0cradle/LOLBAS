## Mavinject.exe

* Functions: Execute, Read ADS

```
MavInject.exe <PID> /INJECTRUNNING <PATH DLL>

MavInject.exe 3110 /INJECTRUNNING c:\folder\evil.dll     
   
mavinject.exe 4172 /INJECTRUNNING "c:\ads\file.txt:file.dll"
```

Acknowledgements:
* Giuseppe N3mes1s - @gN3mes1s
* Adam - @hexacorn
* Oddvar Moe - @oddvarmoe
   
Code sample:
* 

Resources:
* https://twitter.com/gN3mes1s/status/941315826107510784     
* https://twitter.com/Hexcorn/status/776122138063409152     
* https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it/


Full path:
```
C:\Windows\System32\mavinject.exe
C:\Windows\SysWOW64\mavinject.exe
```

Notes:



 
MITRE ATT&CK:
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [Signed Binary Proxy Execution](https://attack.mitre.org/wiki/Technique/T1218)
