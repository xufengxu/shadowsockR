一键脚本安装shadowsocksR
---
## 本地机器下载/war下面对应shadowsocksR客户端安装包自行安装

## 支持系统
CentOS 6+(目前只用CentOS 6+有效，其他未知)

## 使用教程
服务器端：
1、安装git   yum -y install git

2、获取安装脚本  git clone https://github.com/xufengxu/shadowsockR.git

3、执行  shadowsockR/ssr-command/ss-fly.sh -ssr

4、按提示依次设置你的PassWord、Port、Protocol、obfs

5、最后会出现你设置的信息

客户端设置：

选择：PAC自动模式(国内网址走本地，被墙网址走VPS服务器)

服务器设置--》添加你上述第五步出现的信息

其他：卸载ssr服务：./shadowsocksR.sh uninstall
