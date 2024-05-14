Proof of concept for Process Hollowing in Windows Operating Systems, performed on Windows 10 64 Bit 22H2. Hollowing the process "Notepad++.exe" and executing a reverse TCP shellcode.

Sources:

https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessa

https://learn.microsoft.com/en-us/windows/win32/procthread/process-creation-flags

https://learn.microsoft.com/en-us/windows/win32/procthread/zwqueryinformationprocess

https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-readprocessmemory

https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-writeprocessmemory

https://www.geoffchappell.com/studies/windows/km/ntoskrnl/inc/api/pebteb/peb/index.htm

https://crypt0ace.github.io/posts/Shellcode-Injection-Techniques-Part-2/

https://0xrick.github.io/win-internals/pe3/

http://www.pinvoke.net/index.aspx
