# 这是迅雷云监工docker版
***
## 版本说明
***
- :sj，为随机分钟数的每小时重启一次云监工  
- :txcq，为每小时的0分重启一次云监工  
- :tixian，为没有重启计划的云监工  
***
## 2016.03.04 15:20更新
***
- 更新计划任务时间分钟数为随机0-59，每小时启动一次
***
## 2016.03.03 19:00更新
- 更新标签为txcq为最新版，以免daocloud版本识别混乱！	
***
## 2016.03.02 17:20更新
***
- 增加了计划任务，每1小时自动重启云监工
***
## 2016.03.02 9:50更新
***
- 源代码降为提现版本  
- 查询数据改为15秒刷新  
***
## 2016.03.01 17:30更新
***
- 源代码更新为免费开宝箱版本  
- 自动收水晶改为6个小时收取一次  
***
## 2016.03.01 15:00更新
*********
- 更新时区设置，设置为北京时间  
***
## 2016.02.29 17:00更新
***

### 源代码是搬运的，我只是做了docker镜像和启动脚本    

此版本增加了自动提现功能  

云监工程序docker版，以`tutum/ubuntu:trusty`为母镜像  

适用于所有docker平台  

外接卷路径`/var/lib/redis`，就是redis数据库存放目录  

容器端口云监工端口4000 ssh端口22，可以ssh到容器，root密码在日志查找  

此云监工源代码提取自 `https://gitbhub.com/sanzuwu/crysadm.git`  

也是我fork自别人，如果有更新，我会更新的  

不足之处：服务器时区不是北京时区，不能定时重启云监工，这些都需要ssh或控制台自己实现  
***
# 联系方式
***
Email：(sanzuwu@gmail.com)
***

