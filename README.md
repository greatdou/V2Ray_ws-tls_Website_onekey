# V2RAY 基于 NGINX 的 VMESS+WS+TLS+Website(Use Host) 
### （HTTP header分流，自带 Website，自带 rinetd bbr加速，自动清除残余的http服务）

使用：1.解析好域名； 2.运行一键安装脚本；
```
bash <(curl https://raw.githubusercontent.com/dylanbai8/V2Ray_ws-tls_Website_onekey/master/install.sh)
```
尽量使用 Debian8+ , 如果需要修改配置，运行脚本重新安装一次即可。

### 申明：

此为 wulabing/V2Ray_ws-tls_bash_onekey 的另一个分歧版本

源作者网址：https://github.com/wulabing/V2Ray_ws-tls_bash_onekey
```
修改内容如下：
1.修改路径分流为 HTTP header分流；
2.增加 Website 伪装站点；
3.增加 rinetd bbr端口加速；
4.自动清除残余的http服务（某些系统自带的apache2以及重装脚本时需要清除的nginx）
```

### 其它与原版一致，详细说明请步移 https://github.com/wulabing/V2Ray_ws-tls_bash_onekey

