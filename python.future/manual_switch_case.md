## 手动 switch case
### 简介
python 似乎是没有 switch case 功能的。邢宇杰博士为 python.future 模块手动添加了这一功能。
### Example
```python
if num == '1':
   os.system("python3 $FLYOS/deploylinux/deploy.py")
elif num == '2':
   os.system("tmoe")
elif num == '3':
   os.system("python3 $FLYOS/softwareinstall/install.py")
elif num == '4':
   os.system("debian")
elif num == '5':
   os.system("python3 $FLYOS/chat/chat.py")
elif num == '6':
   os.system("python3 $FLYOS/console.py")
elif num == '7':
   os.system("apt update")
elif num == '8':
   os.system("pkg update")
elif num == '9':
   os.system("screenfetch")
elif num == '10':
   os.system("chsh")
elif num == '11':
   print("您可以更改FlyOS的默认User密码")
   os.system("passwd")
elif num == '12':
   website = input("欢迎使用FlyOS Browser浏览器，例如:http://www.bing.com --必应 输入网址开始浏览网页:")
   os.system("w3m " + website)
elif num == '13':
   os.system("python3 $FLYOS/webserver/main.py")
elif num == '14':
   os.system("sh $FLYOS/panel/server.py")
elif num == '15':
   os.system("aria2c --enable-rpc --rpc-listen-all")
elif num == '16':
   print("由于系统限制，请手动执行cd /data/data/com.termux/files/home/webui-aria2")
   print("和node node-server.js")
elif num == '17':
   os.system("python $FLYOS/virtualmachine/vm.py")
elif num == '18':
   os.system("mc")
elif num == '19':
   os.system("python $FLYOS/virtualmachine/web.py")
elif num == '20':
   os.system("nginx")
elif num == '21':
   os.system("python $FLYOS/.firstuse/register.py")
elif num == '00':
   print("关于:\n开发者创始人:Rainbow邢宇杰\n邮箱:xingyujie50@gmail.com\n当前版本:bilndv2.7")
elif num == '01':
   print("有BUG请反馈到:xingyujie50@gmail.com")
else:
   print("正在进入终端...")
# 真™冗长
```
### 其它
编者注：python 里类似 switch case 的功能可以通过字典实现。

前往观摩邢宇杰博士的高雅代码：https://github.com/xingyujie/flyos/commit/4ba016e4fa84264609e504fcfad615dd1a1f72f4#diff-791a30628664868e8cbd1c5addd326b0ac0a50ddc99ddb0ccfe5e88070084518
