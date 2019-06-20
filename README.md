netkeeper的账号拦截+多拨+SSR  

账号拦截采用的是LittleWhite-Carry大佬的软件（本人纯粹搬运 手动滑稽）  
https://github.com/LittleWhite-Carry/NetKeeper-Connect  

因为觉得这位大佬提供的斐讯K2的固件可是实现账号拦截和多拨，但由于此固件功能太少。所以就自己更换了新的固件,并且新的固件有以下功能：  

![image](https://github.com/yuyangyangyu/netkeeper/blob/master/test/test.png)  

注意：
------  
因为自带的固件不带有rp-pppoe-server和rp-pppoe-common而这两软件需要libssp这个依赖软件；使用winscp 将三个所需的软件上传到路由器的/tmp目录下，然后使用ssh 进行安装命令格式为：  
opkg install xxx.ipk  
安装顺序为： 

1.libssp  
2.rp-pppoe-common  
3.rp-pppoe-server 

固件和三个需要的软件我已经打包上传。如需其他软件可自行在：https://downloads.pangubox.com/pandorabox/ 进行下载
经过测试其中的SSR是能够正常使用的，最后推荐一个免费的SSR网站： 

~~https://dukou.org/auth/register?code=invited_by_15526330414F通过此链接进行注册可以获得50G流量，每天可签到领流量  
并且可以用此网站配合路由器的SSR使用，具体的使用教程可自行百度 之前的链接挂掉的，这里推荐一个新的连接:https:jiji.ws/signup?aff=VUim 通过此链接可以获得23G流量。每天可以通过签到获得流量，可流畅看4K  

新的免费机场：suannai.tk每天签到可得1Gb流量
