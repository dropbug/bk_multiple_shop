# 业务机和UKey使用

这一章讲具体用法,如何登录店铺.

先看流程图,下面有针对每一个流程的详细解释.
![防关联登录流程图](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/%E9%98%B2%E5%85%B3%E8%81%94%E7%99%BB%E5%BD%95%E6%B5%81%E7%A8%8B%E5%9B%BE.jpeg)


#### 1. 在内网

内网指深圳公司4楼机房的局域网.三台物理服务器和连接ADSL宽带的PC,部署在这里.  
在深圳公司4楼的网络环境中,就叫"在内网".  
如果在内网,可以不用跳板,直接连业务机,速度更快.

如果是分公司同事,或者深圳同事回家/出差等不在内网的情况下,必须先连接跳板机.  
天津专用跳板机地址:lmtj.zapto.org:8001  
深圳专用跳板机地址:lmsz.zapto.org  
这两个跳板机,都是用虚拟机做的.

天津同事的跳板机账号,都开设在天津跳板机上  
深圳同事的跳板机账号,都开设在深圳跳板机上

天津,深圳各自一台跳板机,是从人员负载方面考虑,与连接人所在的地域无关.  
天津同事来深圳出差.在深圳,但不在内网时,仍然用天津跳板机.在内网,可以直连业务机.  
同样,深圳同事去天津出差,仍然用深圳跳板机.

#### 2. 连跳板机
连接方法非常简单,使用Windows系统自带的远程桌面服务,输入一个地址和账号密码即可.
这个操作可以分为三步
+ 呼出 远程桌面连接
+ 输入地址和账号密码,勾选本地资源


##### 2.1 呼出远程桌面连接
"远程桌面服务"有两种打开方式
**命令呼出**
Win7,Win8,Win10都能用
   按Windows键+R,呼出运行窗口
   ![win+r](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/win%2Br.jpg)
   
   运行窗口输入 mstsc ,确定
   ![mstsc](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/mstsc.jpg)
**附件点击打开**
仅推荐Win7使用.
(Win8,Win10的附件不好找,但是搜索很好用,直接搜 远程桌面连接 就出来了)

Win7系统下,点左下角"开始"->"所有程序"->"附件"->鼠标点击"附件",展开菜单
   ![附件远程桌面](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/%E9%99%84%E4%BB%B6mstsc.png)

#### 2.2 输入地址和账号密码,勾选本地资源
这里假设 王小明 是天津公司同事,他的跳板机账号是:wangxiaoming 
界面应该是这个样子的
![wangxiaoming](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/wangxiaoming.png)

点击"显示选项",展开隐藏菜单.
![展开1](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E5%B1%95%E5%BC%801.jpg)

按下图操作

![驱动器](http://lemai.oss-cn-shenzhen.aliyuncs.com/gitbook_netlogin/%E8%BF%9C%E7%A8%8B%E5%8B%BE%E9%80%89%E9%A9%B1%E5%8A%A8%E5%99%A8.jpg)
这个是保证我们能和远程的目标进行相互文件复制,粘贴的基础.


第一次连接时可能会问"要不要相信什么什么的","要不要保存什么什么的",全部都给勾上,能保存的凭据全保存,下次连接时就不会再跳询问窗口了.


