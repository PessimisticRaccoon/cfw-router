########################################
Router: Linksys WRT3200ACM
Custom Firmware
########################################
Firmware 1:
DD-WRT (https://dd-wrt.com/)

Guide Used:
https://forum.dd-wrt.com/phpBB2/viewtopic.php?t=311117

Link to the DD-WRT firmware for Linksys WRT3200ACM:
https://dd-wrt.com/support/router-database/?model=WRT3200ACM_-
    Includes two bin files:
    The factory to dd-wrt is for installing DD-WRT from the Linksys GUI. This file will be used under two circumstances.
    1. You are installing DD-WRT for the first time.
    2. You have switched back to opposite partition and you have the Linksys Stock Firmware on that partition.

    The dd-wrt webflash is for upgrading a current DD-WRT installation. This file will result in the following circumstances.
    1. A new version of DD-WRT will be installed on the opposite & inactive partition.
    2. The previous DD-WRT version will be left on what is now the inactive partition (after reboot).
    3. All settings and configuration will be kept and applied to new version (unless a reset is selected in Firmware Upgrade Sub-Tab).

    Note: It’s only one file per Install / Upgrade. If you use the ‘factory to dd-wrt’ file followed by the ‘dd-wrt webflash’ file you will have installed the same version of DD-WRT on BOTH partitions and overwritten the Linksys OEM Firmware.

DD-WRT Firmware File:
https://dd-wrt.com/support/other-downloads/
https://dd-wrt.com/support/other-downloads/?path=betas%2F2020%2F04-20-2020-r42954%2Flinksys-wrt3200acm%2F

Instructions for upgrading Firmware from Linksys GUI can be found here:
https://www.linksys.com/us/support-article?articleNum=140365

Location for Linksys OEM Firmware:
https://www.linksys.com/us/support-article?articleNum=135206

Default Login Creds for DD-WRT:
The default username / password combination is “root” / “admin”
