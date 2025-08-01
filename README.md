# 系统支持 Debian 9+/Ubuntu 20.04+/Centos 7+
sockes5 一键搭建脚本 
使用方法  2选1

 bash <(curl -sL https://my.oofeye.com/nsock.sh)

wget https://my.oofeye.com/work/Socks5/ss5.sh && bash ss5.sh
# 命令报错的话 请安装wget
yum -y install wget  或者  apt -y install wget




# 快速搭建
git clone -b master https://github.com/zz4279669/ss-fly.git<br>
ss-fly/ss-fly.sh -i  密码  端口

启动：/etc/init.d/ss-fly start

停止：/etc/init.d/ss-fly stop

重启：/etc/init.d/ss-fly restart

状态：/etc/init.d/ss-fly status

查看ss链接：ss-fly/ss-fly.sh -sslink

修改配置文件：vim /etc/shadowsocks.json

卸载 ss-fly/ss-fly.sh -uninstall
