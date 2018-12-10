# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
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
