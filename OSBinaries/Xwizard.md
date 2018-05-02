## Xwizard.exe

* Functions: DLL hijack, Execute

```
xwizard.exe     

xwizard RunWizard {00000001-0000-0000-0000-0000FEEDACDC}    
```

Acknowledgements:
* Adam - @Hexacorn
* Nick Tyrer - @nicktyrer

Code sample:
* https://gist.github.com/NickTyrer/0598b60112eaafe6d07789f7964290d5

Resources:
* http://www.hexacorn.com/blog/2017/07/31/the-wizard-of-x-oppa-plugx-style/
* https://www.youtube.com/watch?v=LwDHX7DVHWU
* https://gist.github.com/NickTyrer/0598b60112eaafe6d07789f7964290d5

Full path:
```
c:\windows\system32\xwizard.exe
c:\windows\sysWOW32\xwizard.exe
```

Notes:
DLL hijack/Sideloading needs to copy out xwizard.exe to a user controlled folder. 
If you add your own version of xwizard.dll it will execute when you start xwizard.exe.

Xwizard RunWizard requires you to import registry keys that points to external SCT file.





 
