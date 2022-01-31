# File management tools for Windows OS

## mklink [- Link](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/mklink) `#f03c15`
- Creates a directory link/junction
- Useful for moving to and from network locations rather than mapping a network drive

## robocopy [- Link](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/robocopy)
- Copies, logs, .. , compares directories
- Can be automated using batch files with task scheduler

## chkdsk [- Link](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk)
- Checks the file system and file system metadata of a volume for logical and physical errors

## DISM [- Link](https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/what-is-dism?view=windows-11)
- Service and prepare Windows images
- DISM can be used to mount and service a Windows image from a .wim file, .ffu file, .vhd file, or a .vhdx file and also to update a running operating system

## sfc [- Link](https://support.microsoft.com/en-us/topic/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system-files-79aa86cb-ca52-166a-92a3-966e85d4094e)
- Scan Windows and restore your files
- sfc /scannow is the most useful/common commandlet to run

## Custom Powershell Script [- Link](https://www.davor.josipovic.be/blog/2013/06/02/ignoring-device-io-errors-during-copy-with-powershell/)
- Useful for copying when you know there are bad sectors on a disk
- Efficient and effective compared to other tools
