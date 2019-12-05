Linux系统管理员/DevOps面试问题
====================================================

Linux系统管理员/DevOps面试问题。随时通过拉取请求，问题或电子邮件做出贡献。


## <a name='toc'>目录</a>


  1. [贡献者](#contributors)
  1. [一般问题](#general)
  1. [简单级linux问题](#simple)
  1. [中级级linux问题](#medium)
  1. [高级级linux问题](#hard)
  1. [专家级linux问题](#expert)
  1. [网络问题](#network)
  1. [Mysql数据库问题](#mysql)
  1. [DevOps问题](#devop)
  1. [有趣的问题](#fun)
  1. [演示时间](#demo)
  1. [其他重要参考](#references)


#### [[⬆]](#toc) <a name='contributors'>贡献者:</a>


* [moregeek](https://github.com/moregeek)
* [typhonius](https://github.com/typhonius)
* [schumar](https://github.com/schumar)
* [negesti](https://github.com/negesti)
* peter
* [andreashappe](https://github.com/andreashappe)
* [quatrix](https://github.com/quatrix)
* [biyanisuraj](https://github.com/biyanisuraj)
* [pedroguima](https://github.com/pedroguima)
* Ben
* [bharatnc](https://github.com/bharatnc)


#### [[⬆]](#toc) <a name='general'>一般问题:</a>


* 您昨天/本周学到了什么？
* 讨论您首选的开发/管理环境。 （操作系统，编辑器，浏览器，工具等）
* 告诉我您完成的最后一个大型Linux项目。
* 告诉我您在[最近一段时间]犯的最大错误，以及今天您将如何做不同的事情。 您从这次经历中学到了什么？
* 为什么我们必须选择您？
* DNS在网络上发挥什么功能？
* 什么是HTTP？
* 什么是HTTP代理，它如何工作？
* 简要描述HTTPS的工作方式。
* 什么是SMTP？ 给出如何通过SMTP传递邮件的基本方案。
* 什么是RAID？ 什么是RAID0，RAID1，RAID5，RAID10？
* 什么是0级备份？ 什么是增量备份？
* 描述Linux系统的一般文件系统层次结构。
* 公共和私有SSH密钥之间有哪些区别？


#### [[⬆]](#toc) <a name='simple'>简单的linux问题:</a>


* 管理员用户的名称和UID是什么？
* 如何列出目录中的所有文件，包括隐藏文件？
* 用于删除目录及其内容的Unix/Linux命令是什么？
* 哪个命令将显示您的可用内存？Linux上是否存在可用内存？
* 如何在目录文件中递归搜索字符串“my konfu is best”？
* 如何连接到远程服务器或什么是SSH？
* 如何获取所有环境变量以及如何使用它们？
* 当我运行`ifconfig -a`时，我得到“找不到命令”。有什么事吗
* 如果键入TAB-TAB，会发生什么？
* 什么命令将显示Unix/Linux系统上的可用磁盘空间？
* 您知道哪些可用于检查DNS记录的命令？
* 哪些Unix/Linux命令会更改文件所有权，文件权限？
* ```chmod + x FILENAME```是做什么的？
* 文件上的0750权限是什么意思？
* 目录上的0750权限是什么意思？
* 如何添加没有登录权限的新系统用户？
* 如何从用户添加/删除组？
* 什么是bash别名？
* 如何设置root/a用户的邮件地址？
* CTRL-c是做什么的？
* CTRL-d是做什么的？
* CTRL-z是做什么的？
* /etc/services中有什么？
* 如何在bash中重定向STDOUT和STDERR？ （> /dev/ null 2>＆1）
* UNIX和Linux有什么区别。
* Telnet和SSH有什么区别？
* 解释三个平均负载及其含义。可以使用什么命令查看平均负载？
* 您能为GNU```ls```命名一个无效的小写字母吗？
* 什么是Linux内核模块？
* 引导我完成引导进入单用户模式的步骤以解决问题。
* 引导我逐步完成对所管理的Web应用程序中的404错误进行故障排除的步骤。
* 什么是ICMP协议？为什么需要使用？


#### [[⬆]](#toc) <a name='medium'>中级的linux问题:</a>


* 以下命令是做什么的，您将如何使用它们？
* ```tee```
* ```awk```
* ```tr```
* ```cut```
* ```tac```
* ```curl```
* ```wget```
* ```watch```
* ```head```
* ```tail```
* ```less```
* ```cat```
* ```touch```
* ```sar```
* ```netstat```
* ```tcpdump```
* ```lsof```
* 命令后的```＆```是做什么的？
* 命令后的```＆ disown```是做什么的？
* 什么是数据包过滤器，它如何工作？
* 什么是虚拟内存？
* 什么是交换及其用途？
* 什么是A记录，NS记录，PTR记录，CNAME记录，MX记录？
* 还有其他的RR吗？它们有什么用？
* 什么是水平分割DNS？
* 粘性位是什么？
* 不变位对文件有什么作用？
* 硬链接和符号链接有什么区别？将源删除到符号链接/硬链接时会发生什么？
* 什么是索引节点，索引节点中存储哪些字段？
* 如何在下次重新引导时强制/触发文件系统检查？
* 什么是SNMP？SNMP的用途是什么？
* 什么是运行级别以及如何获取当前运行级别？
* 什么是SSH端口转发？
* 本地和远程端口转发有什么区别？
* 不使用useradd/adduser将用户添加到系统的步骤是什么？
* 特殊文件的主要和次要数量是多少？
* 描述mknod命令以及何时使用它。
* 描述当您遇到“文件系统已满”错误，但“df”显示有可用空间时的情况。
* 描述删除文件时的情况，但“df”未显示正在释放的空间。
* 描述“ps”的工作原理。
* 死亡的子进程没有父进程等待它会怎样，这有什么不好呢？
* 简要说明每个过程状态。
* 如何知道哪个进程在特定端口上侦听？
* 什么是僵尸进程，可能是什么原因？
* 您运行一个bash脚本，并且想要在终端上查看其输出并将其保存到文件中。你怎么能做到
* 解释echo “1”> /proc/sys/net/ipv4/ip_forward 的作用。
* 简要描述为网站https://foo.example.com创建和安装有效证书所需采取的步骤。
* 您可以拥有共享相同IP的多个HTTPS虚拟主机吗？
* 什么是通配符证书？
* 您知道哪些Linux文件类型？
* 进程和线程之间有什么区别？以及fork系统调用后的父子进程？
*  exec和fork有什么区别？
* “nohup”的作用是什么？
* 这两个命令有什么区别？
* ```myvar = hello```
* ```export myvar = hello```
* 您将在本地ntp.conf中配置多少个NTP服务器？
* “ntpq -p”输出中的“ reach”列是什么意思？
* 您需要在100-1000台服务器上升级内核，该怎么做？
* 如何获取SCSI磁盘的Host，Channel，ID，LUN？
* 如何限制进程的内存使用量？
* 什么是bash快速替换/插入符替换（^x^y）？
* 您知道其他替代shell吗？如果是这样，您有使用过吗？
* 什么是tarpipe（或者，如何将所有内容（包括硬链接和特殊文件）从一台服务器复制到另一台服务器？
* 如何确定httpd软件包是否已安装？
* 如何列出包装内容？
* 如何确定哪个软件包更好：openssh-server-5.3p1-118.1.el6_8.x86_64或openssh-server-6.6p1-1.el6.x86_64？
* 您能告诉我基于块的存储和基于对象的存储之间的区别吗？


#### [[⬆]](#toc) <a name='hard'>高级的linux问题:</a>


* 什么是隧道？如何绕过http代理？
* IDS和IPS有什么区别？
* 您定期使用哪些快捷方式？
* 什么是Linux标准库？
* 什么是原子操作？
* 重新启动后，新配置的http服务器未运行，该怎么办？
* 〜/.ssh/authorized_keys中有什么样的密钥，该文件是用来做什么的？
* 我已将我的公共ssh密钥添加到authorized_keys中，但仍收到密码提示，这可能是什么问题？
* 您是否曾经创建过RPM，DEB或solaris pkg？
* ```:(){ :|:& };:```在您的系统上做什么？
* 如何在脚本上捕获Linux信号？
* 您能抓到SIGKILL吗？
* 当Linux内核启动OOM Killer时发生了什么，它如何选择首先杀死哪个进程？
* 尽可能详细地描述linux引导过程，从系统启动时开始，到出现提示时结束。
* 什么是chroot监狱？
* 当尝试卸载目录时，它说它很忙，如何找出哪个PID保存该目录？
* 什么是LD_PRELOAD？何时使用？
* 您运行了二进制文件，但没有任何反应。您将如何调试呢？
* 什么是cgroup？您可以指定可以使用它们的方案吗？
* 如何删除/删除文件名仅包含不可打印/不可键入字符的文件？
* 如何增加或减少Linux中进程的优先级？


#### [[⬆]](#toc) <a name='expert'>专家级的linux问题:</a>


* 正在运行的进程在读取套接字时会得到```EAGAIN: Resource temporarily unavailable```。 如何在不终止进程的情况下关闭此错误的套接字/文件描述符？
* 您如何控制互换性？
* 如何更改TCP堆栈缓冲区？您如何计算？
* 什么是大桌子？为什么默认情况下不启用它？为什么以及何时使用它？
* 什么是LUKS？如何使用它？


#### [[⬆]](#toc) <a name='network'>网络问题:</a>


* 什么是localhost，为什么```ping localhost```会失败？
* “ping”和“ traceroute”之间的相似之处是什么？traceroute如何能够找到跃点。
* 用于显示机器上所有打开的端口和/或套接字连接的命令是什么？
* 300.168.0.123是有效的IPv4地址吗？
* 哪些IP范围/子网是“专用”或“不可路由的”（RFC 1918）？
* 什么是VLAN？
* 什么是ARP？ARP的用途是什么？
* TCP和UDP有什么区别？
* 默认网关的用途是什么？
* 在Linux机器上用于显示路由表的命令是什么？
* 网络上的TCP连接可以由4种事物唯一定义。那是什么东西
* 当运行Web浏览器的客户端连接到Web服务器时，连接的源端口是什么，目标端口是什么？
* 如何将IPv6地址添加到特定接口？
* 您已经为接口eth0添加了IPv4和IPv6地址。对v4地址执行ping操作，但对v6地址进行ping操作会给您响应“ sendmsg：不允许操作”。有什么事吗
* 什么是SNAT？何时使用？
* 说明您如何ssh登录到使用SSH隧道DROP丢弃所有新传入数据包的Linux系统。
* 您如何阻止DDoS攻击？
* 如何查看IP数据包的内容？
* 什么是IPoAC（RFC 1149）？
* 绑定端口0会发生什么？


#### [[⬆]](#toc) <a name='mysql'>Mysql数据库问题:</a>


* 如何创建用户？
* 您如何为用户提供特权？
* “左”联接和“右”联接有什么区别？
* 简要说明InnoDB和MyISAM之间的区别。
* 简要描述创建简单的主/从集群所需遵循的步骤。
* 为什么在安装MySQL之后为什么要运行“ mysql_secure_installation”？
* 如何检查正在运行的作业？
* 您将如何备份MySQL数据库？


#### [[⬆]](#toc) <a name='devop'>DevOps问题:</a>


* 创建脚本时可以描述您的工作流程吗？
* 什么是GIT？
* 什么是动态/静态链接文件？
* “./configure && make && make install”是做什么的？
* puppet/chef/ansible的是什么？
* Nagios/Zenoss/NewRelic的用途是什么？
* Jenkins/TeamCity/GoCI的用途是什么？
* 容器和虚拟机之间有什么区别？
* 如何创建新的postgres用户？
* 什么是虚拟IP地址？什么是集群？
* 如何打印文件中存在的所有可打印字符字符串？
* 如何找到共享库的依赖关系？
* 什么是Automake和Autoconf？
* ./configure显示一个错误，提示您的系统缺少libfoobar，如何解决此问题，这可能是什么问题？
* 脚本与编译程序的优缺点是什么？
* 持续交付与DevOps之间有什么关系？
* 持续集成和部署系统的重要方面是什么？
* 您如何在AWS内启用网络文件共享，以允许多个可用性区域中的EC2实例共享数据？


#### [[⬆]](#toc) <a name='fun'>有趣的问题:</a>


* 粗心的系统管理员执行以下命令：```chmod 444 / bin / chmod```-您如何解决此问题？
* 我忘记了root密码，该怎么办？
* 我已经重新启动了远程服务器，但是10分钟后我仍然无法进入SSH服务器，这可能是什么问题？
* 如果您被困在只有5个命令行实用程序的荒岛上，您会选择哪个？
* 您遇到一台随机计算机，它似乎是Universe的命令控制台。 您输入的第一件事是什么？
* 告诉我您使用SSH的创新方式吗？
* 您已错误地删除了正在运行的脚本，该如何恢复？
* 2038年1月19日会发生什么？
* 当重启命令没有响应时，如何重启服务器？


#### [[⬆]](#toc) <a name='demo'>演示时间:</a>


* 无需手册或Google即可解压缩test.tar.gz。
* 递归地从testdir中删除所有“*.pyc”文件？
* 在所有*.py文件中搜索“my konfu is the best”。
* 在所有*.txt文件中，用“I'm a linux jedi master”代替“my konfu is the best”。
* 测试IP地址为X.X.X.X的计算机上的端口443是否可访问。
* 通过telnet获取http：//myinternal.webserver.local/test.html。
* 如何仅在命令行上不使用邮件客户端发送电子邮件？
* 在python/perl/bash/pseudo中编写一个```get_prim```方法。
* 查找最近30天内访问过的所有文件。
* 解释以下命令```（date; ps -ef | awk'{print $ 1}'| sort | uniq | wc -l）>> Activity.log`''
* 编写脚本以列出两个目录之间的所有差异。
* 在内容为```<TIME>：[MESSAGE]：[ERROR_NO]-Human readable text```的日志文件中，显示每小时或每小时发生的特定错误编号的摘要/计数。


#### [[⬆]](#toc) <a name='references'>其他重要参考:</a>


有些问题是从其他出色的参考文献中“借来的”，例如：

* https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
* https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
* http://slideshare.net/kavyasri790693/linux-admin-interview-questions
