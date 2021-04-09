# FTK-Imager-Triage-Note

[FTK Imager User Guide](./Files/FTKImager_UserGuide.pdf)

## Things to collect from a windows machine when grabbing a custom triage imaage

* **$MFT** - The master file table, which is the index of every file and folder on the system.
* **Pageflle.sys** - The windows pagefile (an extension of RAM).
* **Hiberfile.sys:** - The hibernation file is a compressed image of RAM the last time the system was placed
into hibernation
* **$Logfile**
* **$USN**
* **$Journal):** The file recording file activity (file open, close, creation, deletion
* **All registry hives and perhaps backup registry hives:**
  * SAM
  * SYSTEM
  * SOFTWARE
  * DEFAULT
  * NTUSER.DAT
  * USRCLASS.DAT
  * *.evtx
  * setupapi.dev.log (plug and play logfiles
  * firewall logs
  * IIS Logs
  * [root]\Windows\System32/logFiles
  * [root]\inetpub\logs\logFiles
  * *.Ink files: These are all link files by extension .Ink.
  * *.pf: These are all prefetch files by extension .pf
