# v2ray
极客青年专版v2ray：最好用的 V2Ray 一键安装脚本 &amp; 管理脚本，通过原版修改而来，取消部分网站的屏蔽。

## 原版脚本说明
[V2Ray 一键安装脚本](https://github.com/233boy/v2ray/wiki/V2Ray%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC)

## 搭建教程
[V2Ray搭建详细图文教程](https://github.com/233boy/v2ray/wiki/V2Ray%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B)

## 更多 V2Ray 教程文章
https://github.com/233boy/v2ray/wiki

## 取消轮子屏蔽
config/server/include/ban.json
参考：<https://github.com/233boy/v2ray/issues/186#issuecomment-498109456>

提示：
暂不支持树莓派  
![image](https://user-images.githubusercontent.com/12899262/58779526-c6855d00-8608-11e9-8496-cf171e10867d.png)

## 快速安装极客青年专版【取消屏蔽】
root 登录服务器  
```sh
git clone https://github.com/geekyouth/v2ray.git  
cd v2ray && ls -al  
chmod +x install.sh  
./install.sh  
```

接下来会有中文提示，傻瓜操作  

## 推荐安装加速模块，提速10倍
v2ray bbr  
推荐选择第一个bbr ，装完重启，关闭防火墙【centos7】：systemctl stop firewalld.service  
  
可以开车了！！！  
