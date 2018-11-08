# HTML5-study

## 一、何为html5?

万维网的核心语言、标准通用标记语言下的一个应用超文本标记语言HTML的**第五次重大修改**,2014年10月29日，万维网联盟宣布，经过接近8年的艰苦努力，该标准规范终于制定完成。

> 更多文本描述 --- [百度HTML5](https://baike.baidu.com/item/html5/4234903?fr=aladdin)

## 二、新增语义化标签

```
+ <header>
+ <nav>
+ <main>
+ <footer>
+ <aside>
+ <article>
+ x n ... 
```

### 标签兼容性

问题：大部分主流浏览器都兼容，IE9部分兼容，IE8则不兼容

解决：

​	1.手动方式添加所需的新标签

```
例如：
	document.createElement("header")
```

​	2.引入第三方JS库 **html5shiv.js**



