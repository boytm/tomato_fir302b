# tomato
tomato 固件，目的是在 4M rom 中提供完整的 VPN 或者 代理方案。
主要改进在 pptp 服务端、客户端性能上；增加 minivtun 包；提供完整的策略路由方案；编译器升级到 GCC 4.4 以便更好优化二进制大小。

测试路由器为廉价的 斐讯 Fir302B 。


# Installation #
基于 tomato-shibby-RT-AC 分支，补丁可以直接打在 20150601 之前的版本上。如果嫌补丁麻烦，可以直接浏览 bitbucket，上面有完整的源码。

#TODO
minivtun 的web界面还需要完善 


