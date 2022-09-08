# BrainStorm
在线答题系统

开发环境：Linux Ubuntu、QT、G++、Makefile、Mysql
实现功能：注册、登录、个人训练、在线对战、段位记录、段位匹配、超级用户(查看在线用户、上传广告)
项目描述：
1.	采用C/S架构，采用libevent+线程池实现服务器与多个客户端之间的通信。
2.	服务器与客户端采用 json 数据格式进行数据交换。客户端及服务端对 json 字符串进行解析并进行相关 操作。
3.	采用 Mysql 数据库在服务器端进行记录用户信息以及游戏题目。
4.	采用 spdlog 在服务器端记录日志信息。
5.	客户端基于 QT 实现与服务器通信，并进行了简单的界面搭建，界面跳转，以实现游戏的相关操作。
