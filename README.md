# text-captcha
目前的验证码都是图片的，作为服务器RD，很了解图片处理带来的压力，我尝试用原始的字符串来生成验证码，不再选择图片

目前只是初始阶段，可以生成简短的问题与答案
例如：
```
4、7、4、7里最小的数
4
```

```
5、5、0、7里最大的数和6、2、5、3里最大的数的和
13
```

```
今天几号
24
```

```
U、2、T、T里第3个内容和6、6、9、7里的奇数的连接
T97
```

希望能一起做到防止语言的机器识别，做到取代图片类的验证码
