# MacBook-Issues-WorkArounds

## Boot Camp issues
### Internet too slow
Diagnostics:  the Storage Service is hanging or having issues, which results in a
crash and ends up taking the WLAN with it.
Work around: start cmd as administrator, run the command **sc config storsvc type= own** and restart the computer.
