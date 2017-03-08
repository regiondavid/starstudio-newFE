#前端新人进阶路线

 _此路线仅供参考，通过这个找到最适合自己的学习路线才是最重要的_

 ~~没时间解释了，快上车~~

###第零阶段(贯穿始终)
- 学习内容：
	- 明确自己的目标，保持学习的热情并坚持学下去
	- [Git的基本操作](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)以及配合[Github](https://github.com)的使用
	- 学会搜索的技巧，善于自己去寻找和发现
	- 学会提问的技巧，要善问会问 参考[张鑫旭的《如何提问才能进阶成为前端大神？》](http://www.zhangxinxu.com/wordpress/2015/05/how-to-ask-web-front-question/)
	- 关注一些大神的博客或者github，比如广受好评的[张鑫旭的博客](http://www.zhangxinxu.com/) 和一些知名博主或团队的博客，比如“民工叔”，“小胡子哥”，“玉伯”，“奇舞团”等等，在wiki上已经有了一些整理；订阅一些资讯,逛一逛技术社区或论坛，接触一些新东西，比如[奇舞周刊](http://old.75team.com/weekly/)，V2EX，GitHUb等等

###第一阶段
- 学习方法：此部分偏重html和css，可直接看[W3C](http://www.w3school.com.cn/html/index.asp)或从[慕课网](http://www.imooc.com/)等平台看视频学习。这阶段一定要常练习，几天不敲真的会手生的。
- 学习内容：
	- 学习基本的html语法，熟练掌握常用标签，保持良好的文档结构
	- 会写常见的样式，掌握css选择器的用法，理解盒模型的概念和用法
	- 学习常见的几种布局的写法，对position和float的用法作深入的研究
	- 深入研究position和盒模型，研究多种居中的写法，包括水平居中和垂直居中
	- 熟练切图，能够较好的还原设计图
	- 学习css的2D动画和3D动画
	- 学会使用[LESS](http://lesscss.cn/)、[SASS](http://sass.bootcss.com/docs/guide/)等CSS预处理器 
	- 学习使用响应式布局（如使用rem、flex、媒体查询等）
	- 对移动端页面进行处理，并总结出自己对移动端开发的心得
	- 了解[bootstrap](http://www.bootcss.com/)等常见的[UI框架](http://usablica.github.io/front-end-frameworks/compare.html)
	- 对命名进行规范，HTML的语义化、css的编码风格等参考[《编写高质量代码》](https://book.douban.com/subject/4881987/)
- 练手项目
	- [三栏式布局](http://ife.baidu.com/task/detail?taskId=3)
	- [文章展示](http://ife.baidu.com/task/detail?taskId=5)
	- [响应式网格（栅格化）布局](http://ife.baidu.com/task/detail?taskId=8)
	- [技术产品官网的页面架构及样式布局](http://ife.baidu.com/task/detail?taskId=7)
	- [模拟报纸排版](http://ife.baidu.com/task/detail?taskId=6)
	- [实现一个复杂页面](http://ife.baidu.com/task/detail?taskId=9)
	- [移动Web页面布局实践](http://ife.baidu.com/task/detail?taskId=11)

### 第二阶段
- 学习方法：此阶段主要学习js，主要找到相关的书去跟着学跟着敲。在[MDN](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)上有规范。
- 学习内容
	- 结合[《DOM编程艺术》](https://book.douban.com/subject/6038371/)了解JavaScript中的基本语法、DOM操作等等
	- 学习AJAX，了解并熟悉前后交互的多种方式，对AJAX的跨域问题和解决方案以及延伸出来的其他问题都去做了解。
	- 看着[《JavaScript高级程序设计》](https://book.douban.com/subject/10546125/)过一遍，把基础打牢，对于事件、闭包、作用域重点看。
	- 结合[《JavaScript设计模式与开发实践》](https://book.douban.com/subject/26382780/)对JavaScript的设计模式进行了解
	- JavaScript的动画的探索  [关于动画，你需要知道的](http://www.w3cplus.com/animaton/animations-you-should-know.html)
	- 学习jQuery(建议在对原生js学习到一定程度的时候再开始)
	- 根据自己需求去寻找其他书籍去学习，不一一列举了。也可以多去关注一些国外的资料，写的非常深入，值得花时间去阅读。
	- 顺便推荐去看《你不知道的JS》一书，写的非常棒，很多知识点都讲的比较深，建议基础学习到一定阶段或者遇到瓶颈了之后再开始。

### 第三阶段
其实这一阶段，严格来说并不是时间顺序上的第三阶段，当遇到瓶颈之后就可以去看看。更多的是去做一些东西，主动去了解去拓宽自己的眼界，主动去学一些东西。当你写的东西越复杂，踩的坑越多，并且尝试优化或者重构一两次之后，学到的东西是你无法想象的。

- 学习内容
	- 通过制作UI组件对代码进行抽象和封装
	- 综合运用html+css+js的知识
	- 学习前端自动化项目构建工具——[webpack](http://webpack.github.io/docs/)，并配合gulp/grunt 去搭配出一套自己的快速开发的脚手架。
	- 学习React、Angular、Vue(重点学一门)，结合[Github](https://api.github.com/)和[豆瓣](https://developers.douban.com/wiki/?title=guide&qq-pf-to=pcqq.discussion)等公开的API配合构建工具制作小demo，并尝试去做些复杂的项目，并对架构的设计进行优化。
	- 学习线上调试
	- 深入了解Ajax，并学习一门后端语言，了解前后端是如何合作的，可以顺便去学习一些计算机网络的知识。
	- 对SEO有一定了解
	- 对Node.js有一定了解。
	- 了解[canvas](http://www.w3school.com.cn/html5/html5_canvas.asp)、[SVG绘图](http://www.w3school.com.cn/svg/)和WebGL(通过[Three.js](https://github.com/mrdoob/three.js/)去学习)
	- 看一些人文方面的书籍，比如[《人月神话》](https://book.douban.com/subject/2230248/)、[《黑客与画家》](https://book.douban.com/subject/6021440/)、[《浪潮之巅》](https://book.douban.com/subject/6709783/)、[《程序员的呐喊》](https://book.douban.com/subject/25884108/)等等，不同样的世界依然精彩。
- 练手东西
	- [UI组件之浮出层](http://ife.baidu.com/task/detail?taskId=37)
	- [UI组件之排序表格](http://ife.baidu.com/task/detail?taskId=38)
	- [UI组件之日历组件](http://ife.baidu.com/task/detail?taskId=40)
	- 相册的多种布局——[拼图布局](http://ife.baidu.com/task/detail?taskId=43)、[瀑布布局](http://ife.baidu.com/task/detail?taskId=44)、[木桶布局](http://ife.baidu.com/task/detail?taskId=45)
	- 更加鼓励大家去多多的自己造轮子，千万不要把思想局限住。


### 第四阶段
- 学习内容
	- 颈椎康复指南（逃
