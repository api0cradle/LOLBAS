## Url.dll

* Functions: Execute

```
rundll32.exe url.dll,OpenURL "C:\test\calc.hta"    

rundll32.exe url.dll,OpenURL "C:\test\calc.url"     

rundll32.exe url.dll, FileProtocolHandler calc.exe     
```

Acknowledgements:
* Jimmy - @bohops

Code sample:
* 

Resources:
* https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for-pass-thru-command-execution-and-lateral-movement/    

Full path:
```
c:\windows\system32\url.dll
c:\windows\sysWOW64\url.dll
```

Notes:



Detection:
MITRE ATT&CK:
* [Regsvr32](https://attack.mitre.org/wiki/Technique/T1117)
* [Rundll32](https://attack.mitre.org/wiki/Technique/T1085)
* [Gatekeeper Bypass](https://attack.mitre.org/wiki/Technique/T1144)
