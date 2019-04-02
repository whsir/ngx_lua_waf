[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu) 




原作者地址：https://github.com/loveshell/ngx_lua_waf

我这里重新打了个包，合并了一些用户的提交

增加功能如下：

1、增加黑白名单网段IP限制，能力有限，网段不能写成192.168.1.0/24，只能写成192.168.1.0-192.168.255.255了。
ipWhitelist={"127.0.0.1","192.168.1.0-192.168.255.255"}

2、增加User-Agent白名单，用来过滤蜘蛛的。
在wafconf文件夹下white-user-agent文件中添加


水平有限，仅仅是把别人提交的功能进行了合并，经验证无误。

这个ngx_lua_waf确实用着很不错，也希望有能力的大佬来接盘！

目前我的whsir一键包默认的nginx已经集成了此版本

whsir一键包，支持lnmp环境通过yum方式一键快速部署：https://bbs.whsir.com/thread-1-1-1.html
