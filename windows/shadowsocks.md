# Shadowsocks 使用教程

> 教程适合浏览器使用用户

## 下载 Shadowsocks

> Shadowsocks 下载地址: [Shadowsocks Windows.zip](https://yadi.sk/d/oDpeA6vz41iEWw)

![程序下载](/assets/img/Snipaste_2018-11-16_10-34-52.png)

> 下载程序压缩包后，请解压全部文件到同一目录, 并且程序路径不得出现中文, 否则可能出现未知错误

>**请确保截图地址栏圈出来的部分没有出现中文, 且文件夹内文件保持完整，不能只解压 EXE 文件**

![程序解压](/assets/img/Snipaste_2018-11-16_10-38-50.png)

## 运行程序

> 双击运行程序 **Shadowsocks.exe** (如果出现 .NET Framework 错误提示, 请下载安装 [.NET Framework 4.7](https://www.microsoft.com/zh-CN/download/details.aspx?id=55167))

> 运行程序后, 系统右下角会出现 Shadowsocks 小飞机图标, 右键单击图标即可进行程序相应的配置

![右下角图标](/assets/img/Snipaste_2018-11-16_10-44-03.png)

## 添加节点

> 登录 JustShadow 客户中心, 选择购买的服务点击进入服务详情页

![客户中心](/assets/img/Snipaste_2017-12-08_15-12-14.png)

> 点击 **Shadowsocks配置** 下载按钮, 下载成功会看到 **gui-config.json** 文件

![gui-config.json](/assets/img/Snipaste_2018-11-16_10-47-58.png)

> 如果已经运行 **Shadowsocks.exe**, 请先右键单击系统右下角 Shadowsocks 小飞机图标退出程序

> 将下载的 **gui-config.json** 复制或剪切到刚才解压的 **Shadowsocks.exe** 程序同目录

> **如果下载文件名不是 gui-config.json, 请将文件名修改为 gui-config.json**

![gui-config.json2](/assets/img/Snipaste_2018-11-16_10-53-57.png)

> 也可以使用扫描二维码方式添加节点, 点击服务器详情页服务器列表显示 **SS二维码**, 在程序右键菜单中选择 **服务器 > 扫描屏幕上的二维码**

> 双击运行程序 **Shadowsocks.exe**

## 配置程序

> 右键单击 Shadowsocks 图标, 在弹出菜单中点击 **启动系统代理**

> 右键单击 Shadowsocks 图标, 在弹出菜单中选择 **服务器**, 选择想使用的节点

![选择节点](/assets/img/Snipaste_2018-11-16_11-00-34.png)

> 程序有不同的代理模式, 推荐使用 **PAC模式** (PAC 是指一个文本文件, 由 GFWList 转换而来, GFWList 是一个被 GWF 屏蔽的网址列表)

> 右键单击 Shadowsocks 图标, 在弹出菜单中选择 **系统代理模式 -> PAC模式** 

> 右键单击 Shadowsocks 图标, 在弹出菜单中选择 **PAC ->从 GFWlist 更新本地 PAC** 

## 进阶教程(Proxy SwitchyOmega)

> Chrome 和 Firefox 浏览器上的代理扩展程序, 可以轻松快捷的管理和切换多个代理设置

> 待完善