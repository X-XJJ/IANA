# 协议管理机制
---
* IANA是用于许多网络协议名称和编号登记的中央存储库，IANA的三大职能之一，是与各标准化组织一同进行协议分配、管理协议编号系统。
[1]

	![](http://i.imgur.com/hsyow96.jpg)[2]

## IANA协议分配
* IANA管理多种IETF网络协议参数，其中包括名称使用的统一资源标识符（Uniform Resource Identifier，URI）方案、建议在互联网上使用的字符编码等。
* 目前，IANA的网络协议参数已超过2800。

[2][3]


### 1、协议注册登记
* IANA负责维持众多的号码中包含多种网络协议，并且和互联网工程任务组（the Internet Engineering Task Force，IETF）[4]共同协调合作服务。
* 协议参数包括：
 * 互联网协议参数：IP数据报首部标志，端口号，服务类型值等；
 * 电话路由参数：地址族，应用协议，属性等；
 * 多用途互联网邮件扩展类型MIME(Multipurpose Internet Mail Extensions)和媒体类型：访问类型，事件代码，媒体类别等；
 * 传输控制协议：首部标志，加密算法等。
- IANA在IETF撰写的互联网草案作为正式RFC发布之前，就需要执行草案中所定义/完善的内容。这些内容包含着建立唯一协议参数注册表的说明和登记策略，以及初始注册表和保留值，成为IANA部门日后审核申请的依据；
* 创建注册表时，IANA需要完成信息和内容的记录——共分四种类型：私人使用，供实验使用，闲置未标明，保留用于特殊情况。其中实验使用的不被IANA记录。
- IANA在协议参数注册表中的作用：
 - 在正式批准RFC前，IANA对其进行预评审、最终评审和评估；
 - 在RFC批准发布后，对其进行实施和维护；
- IANA提供各种协议参数注册表的查看，支持申请/修改注册表，准遵循注册资格标准，一般没有特殊要求，有特殊要求的将在[Protocol Registration Forms（协议登记表）](http://www.iana.org/protocols/apply)中列出。有关协议参数的监督协调方面的内容，则由IETF协议登记监督委员会负责。

[2][5][6][7]

-  [协议参数注册表Comprehensive index of protocol parameter registries）](https://www.iana.org/protocols)
* IANA处理协议参数请求——
 * 查看请求，确认申请的协议参数类型；
 * 查看已注册的注册表，确定请求的协议参数需遵循的策略，定义其RFC；
 * 依据策略通过适当的程序处理请求，其间视情况咨询专家和向申请者进一步确认信息；
 * 更新注册表，通知申请者申请成功。
 * 具体过程图示：

	![](http://i.imgur.com/ZySpIkT.jpg)[2]




### 2、时区数据库
- IANA的时区数据库（Time Zone Database，通常称为TZ数据库或中经银讯）中，包含代码、表示本地时间对应世界各地的许多代表性的地点时间的数据。
- TZ数据库是一个关于世界时区信息协同编制，它定期更新以反映政治机构的时区界限、UTC偏移量的变化、夏令时规则，主要用于计算机程序和操作系统，其管理程序是维修时间带数据库的程序。
IANA提供从不同时间段时区数据库的下载——[Time Zone Database](http://www.iana.org/time-zones)。

[8][9]

### 3、统计事项
- 统计IANA凭证系统处理队列的日常日志，同时按月统计队列，记录到月日志中并展示出来。
 - 日志包含每个队列的历史处理动作。
 - 根据资料的记录，可以通过凭证显示事件从开始到结束的过程和月底还未完成的凭证。
- 公开的数据——
 - 凭证的数量
 - 已完成的凭证
 - 对相关方面资料收集处理的总时长
 - 申请者提交的可用数据情况
 - 每个凭证从开始到结束的总时长，或从开始到当前进度为止的总时长
 - 平均处理时间
 - 中值处理结果
 - 平均处理时间相对于标准的偏差
- 各类定义（如协议、草案）参照[Definitions](http://www.iana.org/performance/ietf-statistics)。
- 同时，IANA记录IETF草案状态以便更新协议参数。

[10] 


###参考文献和资料 
[1] [IANA官方网站](http://www.iana.org/)

[2] [icann - Protocol Parameters - 《iana101-protocol-parameters》](https://icann.adobeconnect.com/p25olhfoar5/?launcher=false&fcsContent=true&pbMode=normal)

[3] [RFC2860 - 《 Memorandum of Understanding Concerning the Technical Work of the Internet Assigned Numbers Authority》](http://tools.ietf.org/html/rfc2860)

[4] [iana - 《Glossary of terms》（术语汇编）](http://www.iana.org/glossary)

[5] [iana - 《Introducing IANA》](http://www.iana.org/about)

[6] [RFC5226 - 《Guidelines for Writing an IANA Considerations Section in RFCs》](http://tools.ietf.org/html/rfc5226)

[7] [iana - 《Protocol Registries》Comprehensive index of protocol parameter registries（协议参数注册表的综合指数）](https://www.iana.org/protocols)

[8] [RFC6557 - 《Procedures for Maintaining the Time Zone Database》](http://tools.ietf.org/html/rfc6557)

[9] [iana - 《Time Zone Database》](http://www.iana.org/time-zones)

[10] [iana - 《IANA Statistics for IETF-related Requests》](http://www.iana.org/performance/ietf-statistics)



