# ishadowsocks-local
```
基于shadowsocks实现科学上网

该软件的作用是 (定时，间隔一分钟)获取 shadowsocks 的帐号密码，感谢 （http://www.ishadowsocks.net/）
然后开启 sock 代理感谢（https://github.com/shadowsocks/shadowsocks-go）

```
# 使用方法

```
第一步：
windows：
    双击 bin/ 目录下的 科学上网.exe

其他：
    go run local.go

第二步：
    配置代理信息
    详见：
        https://ttt.tt/150/
    注意：
        只需要从插件配置开始即可：
        例如
        Chrome 下的 Proxy SwitchySharp 插件
        情景模式选 SOCKS 代理，地址填 127.0.0.1 端口填 1080
        在线规则列表可以使用（感谢知乎）
            https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt

第三步：
    科学上网

```
