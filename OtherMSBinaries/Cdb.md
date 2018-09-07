## Cdb.exe

* Functions: Execute

```
cdb.exe -cf x64_calc.wds -o notepad.exe
```

Acknowledgements:
* Matt Graeber - @mattifestation

Code sample:
* [Cdb_calc.wds](Payload/Cdb_calc.wds)

Resources:
* http://www.exploit-monday.com/2016/08/windbg-cdb-shellcode-runner.html
* https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/cdb-command-line-options
* https://gist.github.com/mattifestation/94e2b0a9e3fe1ac0a433b5c3e6bd0bda

Full path:
```
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\cdb.exe
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe
```

Notes:
Part of the Debugging tools for Windows


Detection:
? 
 
MITRE ATT&CK:
* [Trusted Developer Utilities](https://attack.mitre.org/wiki/Technique/T1127)
