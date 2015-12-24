# Minolta-PagePro-1100-printserver-mac
Using old Minolta PagePro 1100 printer connected to Mac via network print server (SMC7004ABR). (Always forget how it's done, so let's save it to github)


1. Connect printer to print server
2. Connect mac to print server with ethernet cable (I'm using Mac OS X El Capitan (10.11))
3. Install [Gutenprint package](http://gimp-print.sourceforge.net/index.php)
4. System Preferences -> Printers & Scanners -> + -> IP
5. Address: print server IP
6. Protocol: LPD
7. Queue: lpt1 (have a look at your printeserver documentation)
8. Name and location - doesn't care
9. Use -> Select Software 
10. Find your printer model (Minolta PagePro 1100 - CUPS+Gutenprint ...)
11. Add
12. Done
