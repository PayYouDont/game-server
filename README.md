[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/jzyong/game-server/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jzyong/game-server?style=social)](https://github.com/jzyong/game-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/jzyong/game-server?style=social)](https://github.com/jzyong/game-server/network)

简介
====
一个基于棋牌、MMORPG游戏的分布式java游戏服务器，理论上可以无限水平扩展网关服，大厅服、游戏服达到人数承载。实现了集群注册中心，网关、登陆、后台服务器监控等通用服务器;封装了redis集群、mongodb等数据库处理；封装了消息队列、线程模型、及导表等常用工具类。网关服务器使用mina封装了TCP、UDP、WebSocket、HTTP通信，使该框架能同时支持多种协议的客户端进行游戏。每个以scripts名字结尾的目录都为相应项目的脚本文件。

![项目架构图](https://raw.githubusercontent.com/jzyong/game-server/master/game-config/src/main/resources/image/server-architecture.jpg)

文档
---------

详细请查看[wiki](https://github.com/jzyong/game-server/wiki)  
项目已无新功能开发，只维护：
* 新版本服务器 可参考 [GameServer4j](https://github.com/jzyong/GameServer4j)  
* game-ai 移动到[GameAi4j](https://github.com/jzyong/GameAi4j)  

TODO
---------
* 更新JDK到17


交流
---------

* QQ群:144709243(已满)	 143469012


感谢
---------
<img src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png" width = "150" height = "150" div align=left />

[![contributors](https://contributors-img.web.app/image?repo=jzyong/game-server)](https://github.com/jzyong/game-server/graphs/contributors)









