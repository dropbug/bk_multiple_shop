## 连跳板机
使用Windows系统自带的远程桌面服务   
1. [呼出 远程桌面连接](chapter3-2.md#1-呼出远程桌面连接)
2. [输入地址和账号密码,勾选本地资源](chapter3-2.md#2-输入地址和账号密码勾选本地资源)

如果您30分钟内将不再使用跳板机,请注销您的会话.(主动及时释放资源,尽量不影响别人)

***
### 1-呼出远程桌面连接

"远程桌面服务"打开方式  
+ [敲命令](chapter3-2.md#1.1-打开远程桌面-敲命令)


按Windows键+R,呼出运行窗口  
![win+r](http://img.qingyunkj.com/gitbook_netlogin/win%2Br.jpg)
   
运行窗口 输入 `mstsc` 确定  
![mstsc](http://img.qingyunkj.com/gitbook_netlogin/mstsc.jpg)



   ***


### 2-输入地址和账号密码,勾选本地资源

每个人都有自己的跳板机账号,账号一般是中文名姓名的字母拼写.  
跳板机账号不可混用.  

![远程桌面界面展示](http://img.qingyunkj.com/gitbook_netlogin/yczmlj.jpg)



点击"显示选项",展开隐藏菜单.  
![展开1](http://img.qingyunkj.com/gitbook_netlogin/%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E5%B1%95%E5%BC%801.jpg)

按下图操作,这个是保证我们能和远程的目标进行相互文件复制,粘贴的基础.
![驱动器](http://img.qingyunkj.com/gitbook_netlogin/%E8%BF%9C%E7%A8%8B%E5%8B%BE%E9%80%89%E9%A9%B1%E5%8A%A8%E5%99%A8.jpg)

第一次连接时可能会问"要不要相信,要不要保存什么什么的",全部给勾上,能保存的凭据全保存,下次连接时就不会再跳询问窗口了



***




登录成功后,可以把这个远程桌面连接另存为RDP文件,下次直接双击RDP文件,即可快速连接
![另存为rdp](http://img.qingyunkj.com/gitbook_netlogin/%E5%8F%A6%E5%AD%98%E4%B8%BArdp.jpg)

如下
![rdp_file.jpg](http://img.qingyunkj.com/gitbook_netlogin/rdp_file.jpg)




