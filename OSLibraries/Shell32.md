## Shell32.dll

* Functions: Execute

```
rundll32.exe shell32.dll,Control_RunDLL payload.dll    

rundll32.exe shell32.dll,ShellExec_RunDLL beacon.exe    

rundll32.exe shell32.dll,OpenAs_RunDLL c:\temp\calc.hta   

rundll32.exe shell32.dll,ShellExec_RunDLLA beacon.exe   
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken (ShellExec_RunDLL)   
* Vincent Yiu - @vysecurity (ShellExec_RunDLLA)   

Code sample:
* 

Resources:
* https://twitter.com/pabraeken/status/991768766898941953
* https://twitter.com/pabraeken/status/998625299976867840

Full path:
```
c:\windows\system32\shell32.dll
c:\windows\sysWOW64\shell32.dll
```

Notes:



Detection:
MITRE ATT&CK:
* [Control Panel Items](https://attack.mitre.org/wiki/Technique/T1196)
* [Rundll32](https://attack.mitre.org/wiki/Technique/T1085)
