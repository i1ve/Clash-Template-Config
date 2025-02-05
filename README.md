# Clash-Template-Config
> 自用Clash配置文件模板

[Clash Template Config](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Clash-Template-Config.yml)

# App Filter
> 应用分流规则

+ [AdBlock](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/AdBlock.yaml)
+ [Adobe](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Adobe.yaml)
+ [Amazon](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Amazon.yaml)
+ [Apple](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Apple.yaml)
+ [BiliBili](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Bilibili.yaml)
+ [China](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/China.yaml)
+ [DownLoadClient](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/DownLoadClient.yaml)
+ [Direct](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Direct.yaml)
+ [Discord](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Discord.yaml)
+ [DisneyPlus](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/DisneyPlus.yaml)
+ [Facebook](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Facebook.yaml)
+ [GitHub](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/GitHub.yaml)
+ [Google](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Google.yaml)
+ [HBO](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/HBO.yaml)
+ [Hulu](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Hulu.yaml)
+ [IDM](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/IDM.yaml)
+ [Netflix](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Netflix.yaml)
+ [Microsoft](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Microsoft.yaml)
+ [PayPal](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/PayPal.yaml)
+ [Proxy](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Proxy.yaml)
+ [ProxyClient](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/ProxyClient.yaml)
+ [Spotify](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Spotify.yaml)
+ [Speedtest](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Speedtest.yaml)
+ [Steam](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Steam.yaml)
+ [Telegram](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Telegram.yaml)
+ [Twitter](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Twitter.yaml)
+ [Tencent](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/Tencent.yaml)
+ [TikTok](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/TikTok.yaml)
+ [YouTube](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Filter/YouTube.yaml)

> PS: 
> 1. Hulu 和 HBO 包含了不同地区的域名规则，建议实际应用中拆分开，因暂无这两个流媒体的实际应用需求，故未将其分开
> 2. IDM 并不支持BT和磁力链接，因此单独区分开，并设置相应的策略组，默认走直连，也可以前端手动改成走国内流量
> 3. 添加锚点，提高复用率，降低单次修改的成本 2022-09-20修改
> 4. 现在可以通过 powershell 执行 `powershell -nop -c "iex(iwr 'https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Script/ini-clash-provider.ps1')"` 来完成 `provider` 的初始化和调用clash安装模板文件，也可以下载 `ini-clash-provider.exe` 到本地执行
> 5. Android 建议复制 [Clash Template Config](https://cdn.jsdelivr.net/gh/zuluion/Clash-Template-Config@master/Clash-Template-Config.yml) 的代码，并填写自己的机场订阅，以此创建自己的Gist使用，实际上其它客户端也可以类似操作，从而跳过初始化的过程，此前的初始化是用于CFW，并使用Diff来合并自己机场订阅用的
