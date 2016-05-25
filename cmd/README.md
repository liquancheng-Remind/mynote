
# dos window 命令 总结 
- type 查看文件
- find "" 文本查找 
- 下面是vbs  用来 处理交互性命令  下面是 telnet 示例 
```
set sh=WScript.CreateObject("WScript.Shell")
sh.SendKeys "telnet.exe -e #  www.baidu.com 80{ENTER}"
sh.SendKeys "#"
sh.SendKeys "set logfile f.log{ENTER}"
sh.SendKeys "{ENTER}"
sh.SendKeys "GET / HTTP/1.1{ENTER}"
sh.SendKeys "HOST: www.baidu.com{ENTER}{ENTER}"
WScript.Sleep 3000
sh.SendKeys "{ENTER}"
WScript.Sleep 5000
sh.SendKeys "quit{ENTER}"
sh.SendKeys "{ENTER}"

```
-- 同理在window里 js 也是有宿主一样处理的 * (但是我喜欢用js一点) *

```
var sh = WScript.CreateObject("WScript.Shell");
sh.SendKeys("telnet.exe -e #  www.baidu.com 80{ENTER}");
sh.SendKeys("#");
sh.SendKeys("set logfile f.log{ENTER}");
sh.SendKeys("{ENTER}");
sh.SendKeys("GET / HTTP/1.1{ENTER}");
sh.SendKeys("HOST: www.baidu.com{ENTER}{ENTER}");
WScript.Sleep(3000);
sh.SendKeys("{ENTER}"););
WScript.Sleep(5000);
sh.SendKeys("quit{ENTER}");
sh.SendKeys("{ENTER}");

```
