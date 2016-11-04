ss-bash
=======

Shadowsocks流量管理脚本

* 目前只支持python版Shadowsocks
* 目前只支持统计ipv4流量

[英文版](https://github.com/hellofwy/ss-bash/tree/en)请见`en`分支，感谢[@Yaoshicn](https://github.com/Yaoshicn)的贡献。


[使用说明][User Manual]


[User Manual]:    https://github.com/hellofwy/ss-bash/wiki

[Modify]

*  帮助信息修改以下部分：
    修改用户流量限制(如果该端口之前已经用完流量被限制，需重启服务)：
        ssadmin.sh clim port limit
    修改所有用户流量限制(如果该之前有端口已经用完流量被限制，需重启服务)：
        ssadmin.sh change_all_limit limit
    用户流量使用量置零(如果该端口之前已经用完流量被限制，需重启服务)：
        ssadmin.sh rused port
    所有用户流量使用量置零(如果该之前有端口已经用完流量被限制，需重启服务)：
        ssadmin.sh reset_all_used

