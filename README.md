# 智慧树单元测试答案小工具V0.1
## 一.说明

* 此工具仅用于学习、交流使用，可用于查询智慧树单元测试的答案

## 二.使用方法

**第一步：登录智慧树，打开你要进行的单元测试**

随后F12打开控制台，找到如下请求标志

<img src="https://yun.515code.com/github/zhihuishu-answer/image-1.png" alt="image-1" style="zoom:50%;" />

注意：如果工具不能正常使用，请先在这里找到你的Cookie，替换掉py文件里的Cookie变量

随后，点击Preview并展开json字符串，你会发现每个题目有一个id，对应四个选项id

<img src="https://yun.515code.com/github/zhihuishu-answer/image-2.png" alt="image-2" style="zoom:50%;" />

你要做的，就是把题目id填到py文件里的questionId中，将四个选项id填到answerId中，下面是py文件里的示例图

![image-3](https://yun.515code.com/github/zhihuishu-answer/image-3.png)



**第二步：运行py程序，获取返回结果**

注意：返回的是一串图片字符串，需要复制到游览器并打开

<img src="https://yun.515code.com/github/zhihuishu-answer/image-4.png" style="zoom:50%;" />

你在游览器看到的正确选项，对应的是你填入answerId答案的位置，例如答案是A，那么正确选项就是你填入的第一个answerId，多选题也是一样



最后声明：本工具仅限交流学习使用！！！

想一起交流学习，或访问更多内容可以看看我的博客呀：https://www.515code.com/
