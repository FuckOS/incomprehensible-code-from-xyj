## 究极奥义之明文密码和文本文件数据库
### 简介
传统的加密方法，如哈希、base64一类的，在邢宇杰博士这里基本上是毫无意义的。这些东西对他来说累赘而又多余。邢宇杰博士通过一些

简单的方法，巧妙消除了当下加密算法带来的诸多不便。
### Example
```python
f = open('/data/data/com.termux/files/usr/etc/flyos/database/password.db', 'w')# 干脆直接写文本文件里吧，你这样完全多余啊
    f.write(password)# 明文密码
    f.close()
```
### 其它
编者注：
1. 人质可能会被劫匪杀掉，影响很不好。我们直接杀掉人质就巧妙解决了这一问题。
2. 这个东西不仅写入的时候是明文，读取的时候也是明文，邢卫兵和邢小将们可以不用洗了。
附：邢宇杰博士的高雅源代码的链接 https://github.com/xingyujie/flyos/commit/4ba016e4fa84264609e504fcfad615dd1a1f72f4#diff-27db339cd722c4825855308a95800597d452763f626f2f7a1279d317b9e6fa8a
