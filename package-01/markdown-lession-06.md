
# 链接


### 一 ： 文字链接

**语法** :  
[链接文字](链接地址)  
[链接文字](链接地址 "可选的标题")

可选的标题的作用是：当鼠标悬停在链接上时显示提示信息

例如:
[百度](https://www.baidu.com)  
[淘宝](https://taobao.com)



从右面的效果中可以看出来，点击文字，会跳转到小括号里面对应的链接地址

<br/>

再例如：  

这是一个链接 [菜鸟教程](https://www.runoob.com)  
欢迎访问 [GitHub](https://github.com) 官网  
这是 [百度搜索](https://www.baidu.com "百度一下，你就知道")

<br/>


### 二：引用链接

上面的文字链接，是文字和对应的链接地址写到一起了。这么写有个坏处，就是如果
一篇文章，某个链接出现了很多次，那么，每个地方都要把链接地址写一遍。此时可以用
引用链接。

**语法** : 
[链接文字] : 链接地址
通常引用链接，都放在文章的最末尾，不过不放在末尾，也能起到效果

<br/>
例如：   

#### 在线教程
- [MDN Web Docs][mdn] - 权威的 Web 技术文档
- [RUNOOB][rnb] - 适合初学者的教程网站
- [freeCodeCamp][fcc] - 免费的编程学习平台

#### 代码托管
- [GitHub][github] - 最受欢迎的代码托管服务
- [GitLab][gitlab] - 企业级的代码管理平台

<!-- 链接定义区域 -->
[mdn]: https://developer.mozilla.org/
[rnb]: https://www.runoob.com/
[fcc]: https://www.freecodecamp.org/
[github]: https://github.com/
[gitlab]: https://gitlab.com/

简化写法：

当参考标签与链接文字相同时，可以省略第二个方括号：

例如：<br/>
markdown 我喜欢使用 [GitHub][] 来管理代码。<br/>

[GitHub]:https://github.com


再例如：<br/>

[谷歌]、[油管]  
[谷歌]、[油管]  
[谷歌]、[油管]  
[P站]


[谷歌]:https://www.google.com
[油管]:https://youtube.com
[P站]:https://pornhub.com

### 三、自动链接

现代 Markdown 解析器通常支持自动识别 URL 和邮箱地址：

URL 自动识别：

markdown直接输入网址：https://www.example.com
用尖括号包围：<https://www.example.com>
邮箱自动识别：

markdown联系邮箱：example@email.com
或者：<example@email.com>

> 自动识别功能依赖于具体的 Markdown 解析器,有些工具可能渲染不出来





