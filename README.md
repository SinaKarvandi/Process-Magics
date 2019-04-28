# Process-Magics
This is a collection of interesting codes about Windows Process creation. Please contribute if you know one.


## CriticalProcess
This program enables SeDebugPrivilege and then sets its own process as Windows Critical Process, if by any reason the process is killed or closed then as it's a critical process, a blue screen appears.

## EnumAllHandles
This program enumerates all the handles from all the processes using a call to the native API NtQuerySystemInformation.
