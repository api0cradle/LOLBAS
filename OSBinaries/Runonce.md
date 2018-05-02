## Runonce.exe

* Functions: Execute

```
Runonce.exe /AlternateShellStartup   
 
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken


Resources:
* https://twitter.com/pabraeken/status/990717080805789697

Full path:
```
c:\windows\system32\runonce.exe
c:\windows\sysWOW64\runonce.exe
```

Notes:
* Prerequisites

1) Create HKLM\SOFTWARE\Microsoft\Active Setup\Installed Components\[YOURKEY]
2) Create two Strings : 
a) @ : Hi from Active Setup
b) StubPath : calc.exe


 
