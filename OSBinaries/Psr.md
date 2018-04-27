## Psr.exe

* Functions: Surveillance

```
psr.exe /start /gui 0 /output c:\users\user\out.zip    

psr.exe /start /maxsc 100 /gui 0 /output c:\users\user\out.zip    

psr.exe /stop    
```

Acknowledgements:
* 

Code sample:
* 

Resources:
* https://www.sans.org/summit-archives/file/summit-archive-1493861893.pdf

Full path:
```
C:\Windows\System32\Psr.exe
C:\Windows\SysWOW64\Psr.exe
```

Notes:
It does not log keystrokes. Only screenshots when something is clicked.

psr.exe [/start |/stop][/output <fullfilepath>] [/sc (0|1)] [/maxsc <value>]
    [/sketch (0|1)] [/slides (0|1)] [/gui (o|1)]
    [/arcetl (0|1)] [/arcxml (0|1)] [/arcmht (0|1)]
    [/stopevent <eventname>] [/maxlogsize <value>] [/recordpid <pid>]

/start            :Start Recording. (Outputpath flag SHOULD be specified)
/stop            :Stop Recording.
/sc            :Capture screenshots for recorded steps.
/maxsc            :Maximum number of recent screen captures.
/maxlogsize        :Maximum log file size (in MB) before wrapping occurs.
/gui            :Display control GUI.
/arcetl            :Include raw ETW file in archive output.
/arcxml            :Include MHT file in archive output.
/recordpid        :Record all actions associated with given PID.
/sketch            :Sketch UI if no screenshot was saved.
/slides            :Create slide show HTML pages.
/output            :Store output of record session in given path.
/stopevent        :Event to signal after output files are generated.

 