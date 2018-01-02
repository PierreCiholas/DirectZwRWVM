# DirectZwRWVM

2 functions to read or write another process' memory from user-mode without calling ReadProcessMemory, WriteProcessMemory, NtReadVirtualMemory, or NtWriteVirtualMemory.
Useful to increase slightly performance (the operations of the basic user-mode functions are skipped) and avoid detection based on user-mode hooks.
