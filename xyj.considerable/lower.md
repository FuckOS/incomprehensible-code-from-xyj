## 大小写
### 简介
此段代码中的`'EXIT'.lower()`虽然略显诡异，但是并没有严重的问题，因此其正式加入仓库的必要性仍有待商榷。

但是，此段代码仍然有简化的余地。
### Code
```python
    while True:
        string = input('')
        message = name + ' : ' + string
        data = message.encode('utf-8')
        sock.sendto(data, addr)
        if string.lower() == 'EXIT'.lower():
            break
```
233，这个lower真的是典中典了 (゜▽゜*)

顺便一提，这个东西放在这只是用作模板的，迟早有一天把它正式加到仓库里
