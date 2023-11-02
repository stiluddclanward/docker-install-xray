# docker-install-xray
一键安装xray到docker容器，自动生成配置文件。配合容器技术，安装和卸载简单，并且卸载的干净。
#前置条件
已安装curl命令
操作系统支持Docker的安装

#一键安装步骤
```
bash <(curl -sL https://github.com/stiluddclanward/docker-install-xray/raw/main/install_xray_without_ssl.sh)
```
#结果如下
![image](https://github.com/stiluddclanward/docker-install-xray/assets/107162061/77c658e8-60b7-4adb-961a-4fa51c2c3f05)

#v2rayn客户端连接
![image](https://github.com/stiluddclanward/docker-install-xray/assets/107162061/82870ae7-8778-46a0-a1e9-8f4a12c4ede3)
测试翻墙上网
![image](https://github.com/stiluddclanward/docker-install-xray/assets/107162061/52aa3067-0d49-452e-9ef6-bae690521ae1)

#卸载
```
docker rm -f xray
rm -rf /etc/xray
```



