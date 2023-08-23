## -图吧工具箱

测试机器工具

实用功能：

- 烤鸡
- windows数字激活

链接:http://www.tbtool.cn/download/202201-2.html

------

## -Listary

一个真正令人惊叹且精致的搜索实用程序

链接:https://www.listary.com

------

## -Snipaste

一个简单但强大的截图工具，支持将截图贴到屏幕上

链接:https://zh.snipaste.com

------

## -K-Lite Codec Pack

一个编解码器	包含播放所有常见音频和视频文件格式

链接:https://www.codecguide.com/download_kl.htm

------

## -TranslucentTB

使 Windows 任务栏半透明/透明的轻量级实用程序

链接:https://translucenttb.github.io

------

# win + r
cmd					 --打开命令指示符

control				--打开控制面板

regedit				--打开注册表

services.msc	  --打开windows服务

calc					  --打开计算器

osk					  --打开屏幕键盘

msconfig			--系统配置实用程序

netstat -ano | findstr 端口号	--查看端口占用

taskmgr			 --打开任务管理器

explorer			--打开资源管理器

devmgmt.msc 	--打开设备管理器



----



Shutdown -s -t 600：表示600秒后自动关机

shutdown -a ：可取消定时关机

Shutdown -r -t 600：表示600秒后自动重启



----



**查看端口占用情况**

win+r — cmd — netstat -ano（查看所有端口占用情况）

win+r — cmd — netstat -ano 端口号/netstat -aon|findstr "端口号"（查看指定端口占用情况）

记住PID数字

tasklist|findstr PID (查看对应的程序名)

taskkill /f /t /im 进程名 (结束对应进程)