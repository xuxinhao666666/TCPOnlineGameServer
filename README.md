# UNITYSERVER2
WINDOWS IOCP多线程unity联机服务端（完成度30%）
===========================================================================

采用是UNITYSERVER1 的改进版  增加了iocp改善了一连接一线程的情况，从而可以大大提高并发量

对应unity相关工程文件 https://plastichub.unity.cn/future_xxh/ONLINEGAME
============================================================================

当前完成：

服务器基础框架（多线程，IOCP模型）

数据处理与转发

简单功能实现：聊天，客户端心跳包检测，玩家退出，最简单的位置同步
==========================================================================

未来更新：

帧同步（真正的同步实现）
 
安全码：验证是否是客户端发出来的合法数据

数据传输加密

更好的代码风格：更易维护与扩展

MYSQL支持：数据库支持，从而扩展更多功能（登录，数据储存等等）

简单防作弊系统：进行MD5数据验证
