## 检查网络

大部分业务机都做了网络限制,不拨号或者不拨VPN就上不了网(为了防关联).  
连到业务机第一件事情是检查网络连接.

点右下角小电脑,呼出网络状态栏.如果未连接,点连接即可.

业务机的网络连接有两种
1. VPN(连接名是一个外网IP)
2. ADSL宽带(连接名就叫"宽带连接")
***
#### VPN连接
![vpn连接](http://img.qingyunkj.com/gitbook_netlogin/VPN%E6%8B%A8%E5%8F%B7.jpg)

连接成功之后,我们可以访问IP查询网站 [ip138.com](http://ip138.com) 查询当前业务机的外网IP,是否与VPN连接的名称一致.
这一步是管理员手动配置的,有可能配置错误.如果有错,请立即联系管理员.
![vpn-internet](http://img.qingyunkj.com/gitbook_netlogin/vpn_inetnet.jpg)

***
#### ADSL宽带

![kuandai](http://img.qingyunkj.com/gitbook_netlogin/kuandai.jpg)

这种业务机使用ADSL动态拨号网络,每次拨号分配的IP地址都会变.无需指定VPN.
目前只有亚马逊的一部分店铺在使用这种业务机.