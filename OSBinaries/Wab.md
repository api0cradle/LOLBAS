## Wab.exe

* Functions: Execute

```
Wab.exe (requires registry changes)
```

Acknowledgements:
* Adam - @Hexacorn

Code sample:
* 

Resources:
* http://www.hexacorn.com/blog/2018/05/01/wab-exe-as-a-lolbin/
* https://twitter.com/Hexacorn/status/991447379864932352

Full path:
```
C:\Program Files\Windows Mail\wab.exe    
C:\Program Files (x86)\Windows Mail\wab.exe    
```

Notes:
Searches for wab.dll. Can be manipulated with the following registry key:
```
HKLM\Software\Microsoft\WAB\DLLPath
```

Binary is used to manage Windows contacts/wab files. (Legacy)


Detection:
Look for registry changes to HKLM\Software\Microsoft\WAB\DLLPath


 
