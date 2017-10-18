# MacBook-Issues-WorkArounds

## Boot Camp issues
### Internet too slow
Diagnostics:  the Storage Service is hanging or having issues, which results in a
crash and ends up taking the WLAN with it.
Work around: start cmd as administrator, run the command **sc config storsvc type= own** and restart the computer.
Referenced source: https://answers.microsoft.com/en-us/windows/forum/windows_10-networking/november-update-1511-wifi-issue-wifi-keeps/999a92ab-fa69-4f8a-a9dc-27dfa7385a5e
