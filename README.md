# Burp-Exten
Burp good Extensions
Burp好用的扩展

环境：
BURP：BURP 2025.2AI版本Mac（https://github.com/h3110w0r1d-y/BurpLoaderKeygen）
JAVA环境下载是用的injdk.cn JDK21
Jython环境是：www.jyhon.org/download
AI中转地址：https://yunwu.ai/register?aff=0QG9（我的推荐吗，各家的API都可以从这中转还可以免翻墙）

TsojanScan
一个集成的BurpSuite漏洞探测插件
https://github.com/Tsojan/TsojanScan
功能挺多，还带有dnslog综合利用等等，试不试就给我个惊喜，比如thinkphp框架或者注入，durid未授权，Springboot等等

gatherBurp
一款强大的 Web 安全测试套件，集成多种安全测试功能，支持自动化扫描和手动测试。
https://github.com/kN6jq/gatherBurp
只用SQL 注入检测（支持 GET、POST、Cookie、多层级 JSON），比土司瞎爷的xia_sql好用点更直观，其他的功能没发现多好用

APIKit
APIKit可以主动/被动扫描发现应用泄露的API文档，并将API文档解析成BurpSuite中的数据包用于API安全测试。
https://github.com/API-Security/APIKit
好用到无需多言，自动化测试YYDS，就是特么的注意别开AUTO，如果接口有delete真的会要命，虽然是测试的id=2但是我上次好巧不巧的powerjob就是list=2删除了，呜呜

JsRouteScan 
Burpsuite - Js Route Scan 正则匹配获取响应中的路由进行探测或递归目录探测的burp插件
https://github.com/F6JO/JsRouteScan
只能说会用的真的会觉得好用的不得了，打败同事的必备武器，只要心系思路骚，用好他无敌

RouteVulScan
插件可以通过被动扫描的方式，递归对每一层路径进行路径探测，并通过设定好的正则表达式匹配响应包的关键字，展示在VulDisplay界面。可以自定义相关路径、匹配信息、与漏洞名称等。
插件重点是那些简单而有害的漏洞。这些漏洞通常不是固定路径，但可能位于路径的任何层。在这种情况下，非常容易忽视这些漏洞，而如果使用路径爆破，则非常耗时和麻烦。
https://github.com/F6JO/RouteVulScan
说真的我没感觉有啥用，或者我没用好，但是我会默认去增加这个扩展

Hackvertor
Hackvertor 是一种用 Java 编写的基于标签的转换工具，作为 Burp Suite 扩展实现。标签的构造如下：@ 符号用作标识符，表明它是一个 Hackvertor 标签，后跟标签的名称，在本例中为 base64
https://github.com/hackvertor/hackvertor
用了最新的BURP 2025.2新增的Ai功能，但是我还是没用明白，BURP官方都在推荐的插件，慢慢尝试中

HaE
通过运用多引擎的自定义正则表达式，HaE能够准确匹配并处理HTTP请求与响应报文（包含WebSocket），对匹配成功的内容进行有效的标记和信息抽取，从而提升网络安全（数据安全）领域下的漏洞和数据分析效率。
https://github.com/gh0stkey/HaE
懂得都懂，我不相信作为中国脚本小子你的破解版BURP中会没有这个插件！同时推荐谷歌、edge、火狐的插件Findsomething平替

ShiroScan
burp插件 Shiroscan 主要用于框架、无dnslog key检测
https://github.com/Daybr4ak/ShiroScan
不见得多好用，但是万一呢？会增加在Burp扩展中，打海外目标X国会有奇效

Upload_Auto_Fuzz
本Burp Suite插件专为文件上传漏洞检测设计，提供自动化Fuzz测试，共300+条payload
https://github.com/T3nk0/Upload_Auto_Fuzz
刚出的插件看起来吊吊的，省的自己在测试上传的时候还要自己手动的改图片头，加;.、%00这些了

不常用但是想用看看列表（因为AI？）
=========================================================================================
ReconAIzer
ReconAIzer 是 Burp Suite 的强大 Jython 扩展，它利用 OpenAI 帮助漏洞赏金猎人优化他们的侦察流程。此扩展可自动执行各种任务，使安全研究人员能够更轻松、更快速地识别和利用漏洞。
安装后，ReconAIzer 会添加一个上下文菜单和一个专用选项卡来查看结果
https://github.com/hisxo/ReconAIzer
或许是Cursor的Claude-3.7太牛逼了最近总是想看看这些和AI有关的插件

Enhanced BurpGPT
Enhanced BurpGPT 是一个 Burp Suite 插件，它能帮助你使用 AI（人工智能）来分析 Web 应用的安全问题。简单来说，当你测试网站时，你可以在指定的请求响应对，点击send to gpt，交由AI分析，找出潜在的安全漏洞。
https://github.com/yxdm02/EnhancedBurpGPT/tree/main
这个顾名思义，直接就用上了GPT的API接口，但是需要你安装jython环境和有 GPT API 的密钥

AutorizePro
越权漏洞在黑盒测试、SRC挖掘中几乎是必测的一项，但手工逐个测试越权漏洞往往会耗费大量时间，而自动化工具又存在大量误报, 基于此产生了AutorizePro。AutorizePro 是一款专注于越权检测的 Burp 插件，基于Autorize插件进行二次开发，方便安装易于使用
AutorizePro 是一款创新性的内置AI分析模块的专注于越权检测的 Burp 插件 (已有多个白帽反馈用工具嘎嘎挖到src洞, 每周末更新, 欢迎Star🌟以便持续跟踪项目最新版本功能)
https://github.com/WuliRuler/AutorizePro
还是说支持AI分析！！！YYDS

https://burpgpt.app/
这个需要79美金一年，暂时还没测试
