---
description: SSR Windows客户端使用教程
---

# SSR Windows

## 下载与安装

[点击这里下载客户端](https://down.touhou.asia/ssr-download/ssr-win.7z)

1、将文件下载到非中文目录。

  

![&#x4E0B;&#x8F7D;&#x5230;&#x975E;&#x4E2D;&#x6587;&#x76EE;&#x5F55;&#x5E76;&#x89E3;&#x538B;](../.gitbook/assets/jie-ya.png)

2、运行ShadowsocksR.exe（同时为了安全起见，请不要使用360、百度、2345等全家桶）

   

![&#x8FD0;&#x884C;](../.gitbook/assets/yun-hang.png)

3、第一次运行可能需要允许通过防火墙，勾选全部网络，点击允许访问。

 

![&#x9632;&#x706B;&#x5899;&#x8BBE;&#x7F6E;](../.gitbook/assets/fang-huo-qiang.png)

4、 **注意：** 客户端配置完成前，建议先使用直连模式，以免导致无法访问一些网站，配置完成后使用PAC模式或全局模式。  
右键小飞机→系统代理模式→直连模式

 

![&#x5207;&#x6362;&#x76F4;&#x8FDE;](../.gitbook/assets/qie-huan-zhi-lian.png)

## 设置服务器订阅

1、右键右下角托盘处的白色小飞机图标→服务器订阅→SSR服务器订阅设置

 

![&#x670D;&#x52A1;&#x5668;&#x8BA2;&#x9605;&#x9009;&#x9879;](../.gitbook/assets/fu-wu-qi-ding-yue-she-zhi.png)

2、 先点击Add，再将订阅地址（点击 [这里](https://wiki.touhou.tw/wang-zhan-shi-yong/xuan-ze-jie-dian) 查看如何获取订阅地址）复制进“网址”栏，点击确定。  
**注意：** 一定要确保将订阅地址复制进“网址”栏，替换掉点击Add时自动产生的地址。

 

![&#x8BA2;&#x9605;&#x8BBE;&#x7F6E;](../.gitbook/assets/ding-yue-she-zhi.png)

3、右键小飞机→服务器订阅→更新SSR服务器订阅

 

![&#x66F4;&#x65B0;&#x8BA2;&#x9605;](../.gitbook/assets/geng-xin-ding-yue.png)

 

![&#x66F4;&#x65B0;&#x6210;&#x529F;&#x540E;&#x63D0;&#x793A;&#x5982;&#x4E0B;](../.gitbook/assets/geng-xin-cheng-gong.png)

## 选择节点

 1、右键小飞机→服务器→有顶天网络，选择合适的节点（点击这里查看如何选择合适的节点）。

 

![&#x8282;&#x70B9;&#x9009;&#x62E9;](../.gitbook/assets/jie-dian-xuan-ze.png)

2、**有的客户端默认开启负载均衡，意思是将流量分配到不同的节点上，这将导致使用IP变动或速度低下。 为了使用指定的节点，防止遇到奇怪的问题，请关闭负载均衡。**

## 选择代理模式

以下代理模式选择其中一种 推荐设置：平时使用PAC模式，只代理被墙网站，当需要代理没有被墙的网站时切换成全局模式，使用完后切换回PAC模式。

* **PAC模式**

此模式只代理被墙网站

右键小飞机→系统代理模式→PAC模式

 

![&#x6A21;&#x5F0F;&#x5207;&#x6362;&#x4E3A;PAC&#x6A21;&#x5F0F;](../.gitbook/assets/xuan-ze-pac-dai-li-mo-shi.png)

第一次使用需要更新PAC 右键小飞机→PAC→更新PAC为GFWList

 

![&#x66F4;&#x65B0;&#x4E3A;GFWList&#x89C4;&#x5219;](../.gitbook/assets/geng-xin-wei-gfwlist.png)

如果你是海外用户，想要翻回国内，请选择更新PAC为仅通过大陆常见域名（国外访问大陆）。

 

![&#x66F4;&#x65B0;&#x4E3A;&#x5927;&#x9646;&#x5E38;&#x89C1;&#x57DF;&#x540D;](../.gitbook/assets/geng-xin-wei-guo-wai-fang-wen-da-lu.png)

此时可以正常上网

 

![&#x66F4;&#x65B0;PAC&#x6210;&#x529F;&#x540E;&#x63D0;&#x793A;&#x5982;&#x4E0B;&#xFF08;Win10&#xFF09;](../.gitbook/assets/geng-xin-pac-cheng-gong.png)

 

![&#x6B63;&#x5E38;&#x4E0A;&#x7F51;.jpg](../.gitbook/assets/zheng-chang-shang-wang.png)

* **全局模式**

此模式代理所有国外网站  
如果使用此模式时遇到打开国内网站慢的情况，请使用PAC模式，并在需要时在两种模式间切换。

右键小飞机→系统代理模式→全局模式

 

![&#x9009;&#x62E9;&#x5168;&#x5C40;&#x6A21;&#x5F0F;](../.gitbook/assets/xuan-ze-quan-ju-mo-shi.png)

右键小飞机→代理规则→绕过局域网和大陆

 

![&#x7ED5;&#x8FC7;&#x5C40;&#x57DF;&#x7F51;&#x548C;&#x5927;&#x9646;](../.gitbook/assets/rao-guo-ju-yu-wang-he-da-lu.png)

如果你是海外用户，想要翻回国内，请选择绕过局域网和非大陆。

 

![&#x7ED5;&#x8FC7;&#x5C40;&#x57DF;&#x7F51;&#x548C;&#x975E;&#x5927;&#x9646;](../.gitbook/assets/rao-guo-ju-yu-wang-he-fei-da-lu.png)

此时可以正常上网

 

![&#x6CA1;&#x9519;&#x53C8;&#x662F;&#x6211;.jpg](../.gitbook/assets/zheng-chang-shang-wang%20%281%29.png)

## 使用SOCKS5代理 <a id="&#x4F7F;&#x7528;-socks-5-&#x4EE3;&#x7406;"></a>

软件运行时提供一个本地SOCKS5代理，地址为127.0.0.1，端口为1080。 如果你的软件支持SOCKS5代理，就可以设置使用。 以Telegram为例

 

![&#x4E0D;&#x8981;&#x770B;&#x6211;&#x8FA3;&#xFF01;&#x770B;&#x56FE;w\(&#xFF9F;&#x414;&#xFF9F;\)w](../.gitbook/assets/telegram-set-proxy.png)

## 设置开机启动 <a id="&#x8BBE;&#x7F6E;&#x5F00;&#x673A;&#x542F;&#x52A8;"></a>

为了方便使用建议设置开机启动

右键小飞机→选项设置

 

![&#x9009;&#x9879;&#x8BBE;&#x7F6E;&#x5728;&#x8FD9;&#x91CC;&#x54E6;ww](../.gitbook/assets/dian-kai-xuan-xiang-she-zhi.png)

勾选开机启动，点击确定。

 

![&#x5C31;&#x662F;&#x8FD9;&#x6837;w](../.gitbook/assets/kai-ji-qi-dong.png)

## 断开连接与退出 <a id="&#x65AD;&#x5F00;&#x8FDE;&#x63A5;&#x4E0E;&#x9000;&#x51FA;"></a>

右键小飞机→系统代理模式→直连模式

此时软件不再代理，效果与退出软件相同。

 

![&#x63A8;&#x8350;&#x8FD9;&#x4E2A;&#x6837;&#x5B50;&#x54E6;~](../.gitbook/assets/geng-gai-wei-zhi-lian-mo-shi.png)

 右键小飞机→退出  
下次使用直接打开该软件，选择代理模式和节点即可。  
**注意：** 退出软件前需要先设置为直连模式

 

![&#x8FD9;&#x6837;&#x5B50;&#x70B9;&#x51FB;&#x5DE6;&#x952E;&#x5C31;&#x9000;&#x51FA;&#x8FA3;&#xFF01;](../.gitbook/assets/tui-chu.png)

