# Alarm-Zabbix-for-Windows-login
目的：zabbix监控报警Windows用户登陆
环境：
zabbix Server：（可proxy代理）
Windows：（个人pc或者Server版本）

步骤可参考博客：
1、http://renzhiyuan.blog.51cto.com/10433137/1892355
2、代码模块：
git@github.com:renzhiyuan6666666/Alarm-Zabbix-for-Windows-login.git
3、效果展示：
告警主机:pc-renzhiyuan
告警时间:2017.04.19 08:38:14
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

详细身份验证信息:
登录进程:	User32 
身份验证数据包:	Negotiate
传递的服务:	-
数据包名(仅限 NTLM):	-
密钥长度:	0

创建登录会话后，在被访问的计算机上生成此事件。

“使用者”字段指明本地系统上请求登录的帐户。这通常是一个服务(例如 Server 服务)或本地进程(例如 Winlogon.exe 或 Services.exe)。

“登录类型”字段指明发生的登录种类。最常见的类型是 2 (交互式)和 3 (网络)。

“新登录”字段指明新登录是为哪个帐户创建的，即登录的帐户。

“网络”字段指明远程登录请求来自哪里。“工作站名”并非总是可用，而且在某些情况下可能会留为空白。

模拟级别字段指明登录会话中的进程可以模拟的程度。

“身份验证信息”字段提供关于此特定登录请求的详细信息。
-“登录 GUID”是可用于将此事件与 KDC 事件关联起来的唯一标识符。
-“传递的服务”指明哪些中间服务参与了此登录请求。
- “数据包名”指明在 NTLM 协议之间使用了哪些子协议。
-“密钥长度”指明生成的会话密钥的长度。如果没有请求会话密钥，则此字段为 0。
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

详细身份验证信息:
登录进程:	User32 
身份验证数据包:	Negotiate
传递的服务:	-
数据包名(仅限 NTLM):	-
密钥长度:	0

事件ID:889
