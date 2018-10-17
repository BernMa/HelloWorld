# HelloWorld
This is my first repository
////////////////////////////////

配置完毕后，可能需要重启 Shadowsocks 服务，启动脚本后面的参数含义，从左至右依次为：启动，停止，重启，查看状态。

Shadowsocks-Python 版：
/etc/init.d/shadowsocks-python start | stop | restart | status

举个例子，你安装的是 Shadowsocks-Python 版，需要重启 Shadowsocks 服务，则使用 SSH 工具登录服务器后，输入命令：/etc/init.d/shadowsocks-python restart
