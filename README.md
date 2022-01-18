# Snell

### 说明 :
  Snell协议简介：Snell 是 Surge Network 团队开发的私有专属协议，而且官方声称还没有决定是否将Snell协议开源，官方只提供了编译过的二进制文件，现在 Snell V3正式版已发布。Snell 用到了 AEAD 加密方式和 OBFS-HTTP 混淆，相对Shadowsocks协议的优点是效率高、速度快，缺点是暂时不支持多用户管理，只能个人使用，不方便与朋友共享（多用户ACL已准备就绪，还没有正式发布）。

### 一键安装脚本 :
（1）安装 wget 依赖包
```
yum -y install wget #CentOS
apt-get install wget #Ubuntu/Debian
```
（2）执行Snell一键安装脚本

1）执行一键安装脚本命令

Debian & Ubuntu 用户依次执行命令：
```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```
