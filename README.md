# Padavan-K2P

## 简介

K2P 自用固件，适合用于拿来当无线 AP (hanwckf 原版 Padavan 固件）

------

**默认信息**
```
默认IP地址：192.168.2.1
用户名：admin
密码：admin
默认无线密码：1234567890
```

## 你也可以自动编译
 1. fork本项目
 2. 在自己的代码库的 **Actions** 中执行 **Padavan 固件编译工作流** 
 3. 25分钟后,就可以在自己的 **release** 中得到全新编译的固件(**k2p,k2**).
 4. 脚本流程是: 自动下载**hanwckf**/rt-n56u.git源码然后利用github的虚拟机资源自动编译k2p,k2,并发布到release.

## 鸣谢
- [tick-guo/router-rom](https://github.com/tick-guo/router-rom)
- [hanwckf/rt-n56u](https://github.com/hanwckf/rt-n56u.git)
