    # Alarm-Zabbix-for-Windows-login
    目的：zabbix监控报警Windows用户登陆
    环境：
    zabbix Server：（可proxy代理）
    Windows：（pc或者Server版本）
    步骤可参考博主博客：
    1、http://renzhiyuan.blog.51cto.com/10433137/1892355
    2、代码模块：
    git@github.com:renzhiyuan6666666/Alarm-Zabbix-for-Windows-login.git
    3、效果展示：
	![image](https://s4.51cto.com/wyfs02/M01/92/59/wKiom1j-wzrxNikIAAC1_oVSFrg715.png)
    告警主机:pc-renzhiyuan
    告警时间:2017.04.19 08:39:30
    告警等级:Disaster
    告警信息: Windows账户登录成功 on pc-renzhiyuan
    告警项目:eventlog[Security,,"Success Audit",,^4624$,,skip]
    问题详情:账户登录成功:已成功登录帐户。
    
    使用者:
    安全 ID:	S-1-5-18
    帐户名:	PC-RENZHIYUAN$
    帐户域:	WORKGROUP
    登录 ID:	0x3E7
    
    登录类型:	7
    
    模拟级别:	模拟
    
    新登录:
    安全 ID:	S-1-5-21-1483994392-2153443528-2842395118-1017
    帐户名:	renzhiyuan
    帐户域:	PC-RENZHIYUAN
    登录 ID:	0x6FB1580
    登录 GUID:	{00000000-0000-0000-0000-000000000000}
    
    进程信息:
    进程 ID:	0x270
    进程名:	C:\Windows\System32\winlogon.exe
    
    网络信息:
    工作站名:	PC-RENZHIYUAN
    源网络地址:	127.0.0.1
    源端口:	0
    
    当前状态:OK:已成功登录帐户。
    
    使用者:
    安全 ID:	S-1-5-18
    帐户名:	PC-RENZHIYUAN$
    帐户域:	WORKGROUP
    登录 ID:	0x3E7
    
    登录类型:	7
    
    模拟级别:	模拟
    
    新登录:
    安全 ID:	S-1-5-21-1483994392-2153443528-2842395118-1017
    帐户名:	renzhiyuan
    帐户域:	PC-RENZHIYUAN
    登录 ID:	0x6FB1580
    登录 GUID:	{00000000-0000-0000-0000-000000000000}
    
    进程信息:
    进程 ID:	0x270
    进程名:	C:\Windows\System32\winlogon.exe
    
    网络信息:
    工作站名:	PC-RENZHIYUAN
    源网络地址:	127.0.0.1
    源端口:	0
    
    事件ID:890
