# hello-world
第一次用github，跟着向导先学个say hello
Git思维还蛮有意思的
## 借个地方做笔记
在Ubuntu Server 20.04 LTS里，默认没有nmcli，apt安装后发现nmcli g状态显示为disconnected，试了一整天，终于通过修改/etc/netplan/里的yaml文件解决了。具体为在version下面添加一行renderer: NetworkManager，保存退出后执行sudo systemctl daemon-load 和 sudo systemctl restart解决的。
