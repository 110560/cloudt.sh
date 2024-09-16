Cloud Torrent 一键安装脚本
支持 BT(磁力链接)、离线下载和边下边播

安装 
wget -N --no-check-certificate https://raw.githubusercontent.com/110560/cloudt.sh/main/cloudt.sh && chmod +x cloudt.sh && bash cloudt.sh


启动：/etc/init.d/cloudt start

停止：/etc/init.d/cloudt stop

重启：/etc/init.d/cloudt restart

查看状态：/etc/init.d/cloudt status

默认支持开机启动了

安装目录：/usr/local/cloudtorrent

下载目录：/usr/local/cloudtorrent/downloads

配置文件：/usr/local/cloudtorrent/cloud-torrent.json

配置文件：/usr/local/cloudtorrent/cloud-torrent.conf (这个为脚本所用的配置文件)

日志文件：/tmp/ct.log (日志存放在系统临时文件夹，重启VPS后自动清理)
