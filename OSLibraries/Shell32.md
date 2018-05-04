## Shell32.dll

* Functions: Execute

```
rundll32.exe shell32.dll,Control_RunDLL payload.dll    

rundll32.exe shell32.dll,ShellExec_RunDLL beacon.exe    
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken (ShellExec_RunDLL)

Code sample:
* 

Resources:
* https://twitter.com/pabraeken/status/991768766898941953

Full path:
```
c:\windows\system32\shell32.dll
c:\windows\sysWOW64\shell32.dll
```

Notes:



Detection:
