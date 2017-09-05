# OneOaaS-Monitor Community Edition （社区版）
最新版下载，请到官方网站下载 http://www.oneoaas.com/download    
功能:故障展示大屏,替换Zabbix的Dashboard，适合在大屏上面展示故障   
本项目版权归OneOaaS所有，不遵循开源协议，但可以让所有企业免费使用，无需担心版权问题，如有更复杂需求，可以联系使用企业版  

- [在线体验demo](http://monitor.community.oneoaas.com)

### 功能概要
- 数据采集速率
- 当前故障数量
- 当前有故障的设备数量
- 当前故障按不同级别分布图
- 故障列表,可按最低故障级别过滤
- 故障数量趋势图,可按时间过滤
- 所有模块都支持定时刷新,可选择刷新周期
- 新版本消息提示
- 后续版本会逐步发布graphtree等功能

### 使用说明
- zabbix版本 >= 3.0.0 (2.X未经过测试，不保证能够使用)
- 支持的平台
    + windows/amd64
    + linux/amd64
    + darwin/amd64
- 注意:账号体系和Zabbix原来一致
### 安装说明
- Linux 系统的安装
```
wget https://raw.githubusercontent.com/OneOaaS/monitor_ce/master/v0.1_beta/rpm/oneoaas-monitor-ce-linux-amd64-0.1-1.x86_64.rpm
rpm -ivh oneoaas-monitor-ce-linux-amd64-0.1-1.x86_64.rpm
修改配置文件/usr/share/oneoaas-monitor-ce/conf/app.conf
/etc/init.d/oneoaas-monitor-ce start
```
访问 http://IP或域名:4005端口
账号体系和Zabbix原来一致 如Admin/zabbix
- 其他平台分别执行二进制文件即可

- 配置文件说明 conf/app.conf
```
httpport 项目运行端口
dbtype 数据库
dbuser 用户名
dbpass 密码
dbhost 主机
dbport 数据库端口
dbname 数据库名称
```

### 界面截图
![dashboard](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/dashboard.png?raw=true)
![part1](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/part1.png?raw=true)
![part2](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/part2.png?raw=true)
![part3](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/problem1.png?raw=true)
![part4](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/problem2.png?raw=true)
![part5](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/problemPriority.png?raw=true)
![part6](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/trends1.png?raw=true)
![part7](https://github.com/OneOaaS/monitor_ce/blob/master/shortcut/trends2.png?raw=true)


### 项目合作

- 请联系 support#oneoaas.com(#替换成@)
- 公司官网[www.oneoaas.com](http://www.oneoaas.com)
