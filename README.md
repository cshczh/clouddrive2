# 一键脚本安装
脚本非官方出品，由于官方帮助太少故写此脚本。指在帮助用户快速使用 clouddrive2 挂载网盘。   
      
## 推荐码
使用推荐码购买cd2会员最高可以优惠100元。   
我的推荐码：**Xm3K25D3**   
    
支持
- [x] Linux
- [x] MacOS
- [x] OpenWRT-docker
- [x] Android-Tremux
      
### 安装
默认安装在 /opt/clouddrive   
Mac、Linux、OpenWRT等 在「终端」运行下面的「命令」   
```shell
curl -fsSL "https://ghproxy.com/https://raw.githubusercontent.com/sublaim/clouddrive2/main/cd2.sh" | bash -s install
```
   
### 卸载
```shell
curl -fsSL "https://ghproxy.com/https://raw.githubusercontent.com/sublaim/clouddrive2/main/cd2.sh" | bash -s uninstall
```
   
### 更新
请使用官方内置的更新方式
   
## 安卓
安卓在termux里运行下面的「命令」
### 安装 (未ROOT设备)
```shell
curl -fsSL "https://ghproxy.com/https://raw.githubusercontent.com/sublaim/clouddrive2/main/cd2-termux.sh" | bash -s install
```
   
### 安装 (已ROOT设备)
```shell
curl -fsSL "https://ghproxy.com/https://raw.githubusercontent.com/sublaim/clouddrive2/main/cd2-termux.sh" | bash -s install root
```
   
### 卸载
```shell
curl -fsSL "https://ghproxy.com/https://raw.githubusercontent.com/sublaim/clouddrive2/main/cd2-termux.sh" | bash -s uninstall
```
Tip: `脚本安装完成后需要重启一次termux`

## 问题反馈群
QQ群：943950333
   
## 问与答
问：是否需要开代理？   
答：不需要。脚本已内置了镜像加速。   
   
问：为什么termux无法挂载？   
答：非Root用户无法挂载。   
