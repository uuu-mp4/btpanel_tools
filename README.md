
###### 简单介绍
宝塔linux工具箱是一个主要面向Linux Centos系统的脚本管理工具，支持Centos7。
它包含了一键修改宝塔面板模板、去除强制登陆、一键修复面板、一键更换yum源、清除系统垃圾缓存、系统优化等一系列常见的Linux运维需求。
###### 作品截图
 ![btpanel_tools](https://z3.ax1x.com/2021/09/06/h45UBV.jpg) 
###### 官方网站
 [https://www.btpanel.cm/home/tools/index.html](https://www.btpanel.cm/home/tools/index.html) 
###### github命令
```shell-session
wget -O btpanel_tools.sh https://raw.githubusercontent.com/gacjie/btpanel_tools/main/btpanel_tools.sh && bash btpanel_tools.sh
``` 
###### 原版命令
```shell-session
wget -O btpanel_tools.sh https://download.btpanel.cm/tools/btpanel_tools.sh && bash btpanel_tools.sh
``` 
###### 功能说明
()清理垃圾[清理系统面板网站产生的缓存日志文件慎用]   
()系统优化[优化系统部分设置暂时只支持centos7.X]  
()登陆限制[去除宝塔linux面板强制登陆的限制]  
()停止服务[停止面板LNMP,Redis,Memcached服务]  
()修复面板[清理破解版修复面板环境并更新到官方最新]  
()修复环境[安装升级宝塔lnmp的环境只支持centos7]  
()挂载磁盘[官方的一键自动挂载工具]  
()自动换源[目前只支持更换centos7的yum源]  
()面板美化[此功能可将面板首页显示为永久企业版]  
()面板降级[支持历史版本降级操作]  
()插件优化[暂时支持所有安全插件木马查杀库的升级]  
()面板离线[用来屏蔽宝塔的通讯接口，会影响安装升级面板插件功能]  
()卸载面板[替换为官方的卸载脚本，支持只删面板不删环境，删除环境注意 ]  
()版本检测[可检测您安装的面板是否为盗版 ]  
###### 更新日志：
2021年9月3日  
()面板降级[修复无法使用报404错误]  
2021年8月29日  
()面板离线[增加api.bt.cn以及破解版域名的离线]  
()系统优化[新功能上线 暂时只支持centos7]  
()版本检测[新功能上线 可检测您安装的面板是否为盗版 ]    
()脚本更新[更改脚本升级为手动触发检测升级]    
()面板美化[删除该系列功能]  
()插件优化[查杀库升级改为一键智能升级]  
()合作宝塔[删除该系列功能]  
###### 免责条款
一、承诺不牺牲用户任何利益，无木马后门；  
二、免费开源脚本，用户可随意审查脚本内容；  
三、做好数据备份，因环境不同可能会出问题，如有问题可联系我处理，但不保证能够解决！  
