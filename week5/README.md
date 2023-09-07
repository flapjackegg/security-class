## 第一题


## 第二题

报告为当前目录下 `detail_vul_by_host.html`


## 第三题

**全局代理设置说明（Mac环境）**

 -> 系统设置 -> 网络 -> WiFi/网卡 -> 详细信息 -> 代理
将 网页代理(HTTP) 网页代理(HTTPS) 设置上代理的 IP:Port
如下图所示：

<img width="670" alt="image" src="https://github.com/flapjackegg/security-class/assets/33110052/3a805d36-23fd-4311-9cf3-ac5255233a3a">

**局部代理设置说明（Mac环境）**

火狐可以搜索代理设置，直接设置上  burp 或者 xray 的代理 IP:Port
也可以采用浏览器插件的方式，火狐使用 FoxyProxy, Chrome 使用 Proxy SwitchOmega 等，可以针对不同的场景，设置不同的代理
如下图所示：

<img width="687" alt="image" src="https://github.com/flapjackegg/security-class/assets/33110052/79ed1ba3-61af-4d92-a61f-2086480f204c">
<img width="336" alt="image" src="https://github.com/flapjackegg/security-class/assets/33110052/218397fc-cd4f-49b4-b5db-a3df7e6d3f63">



## 第四题

如下图，已开启对 HTTPS 站点的抓包

打开 burp，浏览器访问 http://burp 下载证书，火狐 或者 Chrome，设置里搜索证书设置，信任并导入刚刚下载的证书

<img width="1512" alt="image" src="https://github.com/flapjackegg/security-class/assets/33110052/9a3b9f65-320e-4124-97a0-296d1d83561a">
