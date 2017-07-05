# ip命令

ip命令是linux下使用最频繁的网络命令，ip命令的子命令大约有十几个，我目前了解的，也仅仅是其中两三个子命令，不要紧，我们会一步一步通过实验，把ip命令的子命令都掌握清楚

## ip address
这个命令大家应该很熟悉了,通常用来查看ip的配置`ip address`或者使用简写`ip a`,大部分ip命令都支持简写，后续使用简写模式不再做特殊说明。


	[root@localhost ~]# ip address
	1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host
       valid_lft forever preferred_lft forever
	2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP qlen 1000
    link/ether 08:00:27:6c:2f:c5 brd ff:ff:ff:ff:ff:ff
    inet 192.168.0.152/24 brd 192.168.0.255 scope global enp0s3
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:27ff:fe6c:2fc5/64 scope link
       valid_lft forever preferred_lft forever

