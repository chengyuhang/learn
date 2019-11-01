#DAY-01
##1.课程介绍





##2.HTML认识


###2.1初识HTML
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>HTML学习</title>
</head>
<body>
    <h1>Hello</h1>
    <p>My HTML !</p>
</body>
</html>
```

###2.2什么是HTML
HTML指的是超文本标记语言（HyperText Markup Language)）
超文本指的是页面内可以包含图片、链接、音乐、视频等非文本元素。
标记指的是一种标记符，可以告诉浏览器如何显示其中内容。
如<h1></h1>
*	HTML不是一种编程语言，因为它没有变量，它是一种标记语言。	
*	HTML使用标记标签来描述网页内容

目前应用程序分为C/S与B/S架构
C/S:客户端和服务端架构 如QQ、迅雷。
B/S:浏览器/服务器加州，如taobao/jingdong/baidu等，可以直接通过浏览器使用的应用都是B/S架构。
随着互联网的发展，B/S架构应用会越来越多，拥有更丰富的功能以及更优秀的用户体验，学习HTML也会越来越多。

###2.3动态与静态网页区别
静态网页指的是html代码和内容写完后，页面内容和显示效果基本不会发生变化。	
动态网页是代码没有发生变化，但显示内容却随着时间、环境以及数据库操作的结果发生变化。	
注意：网页内有幻灯片、文字滚动效果，如果内容没有变化，也是属于静态网页。
###2.4HTML、XHTML、DHTML
HTML:超文本标记语言	
XHTML:XML+超文本标记语言（结构严谨的HMTL）	
XML:格式非常规范、严谨的语言（简单）	
DHTML:动态HTML（HTML+CSS+Javascript）		

###2.5HTML发展

HTML:		
HTML1.0	1993/06
HTML2.0	1995/11
HTML3.2	1997/01/14
HTML4.0	1997/12/18
HTML4.01	1999/12/24
HTML5		2014/10/29		



XHTML:			
XHTML1.0	2000/01/26	
XHTML1.1	2001/05/31		
XHTML2.0			

W3C:万维网联盟，是Web技术领域最具权威和影响力的国际中立性技术标准结构，该组织制定Web技术标准。




###2.6HTML开发工具
Dreamwear		
针对专业网页设计师特别发展的视觉化网页开发工具，Adobe。

HBuilder			
支持HTML5的Web开发IDE。HBuilder的编写用到了Java、C、Web和Ruby。HBuilder本身主体是由Java编写。它基于Eclipse，所以顺其自然地兼容了Eclipse的插件, DCloud。

PhpStorm			
商业的 PHP 集成开发工具，旨在提高用户效率，可深刻理解用户的编码，提供智能代码补全，快速导航以及即时错误检查，JetBrains。

Sublime 				
用于代码、标记和散文的精致文本编辑器，开发者Jon Skinner。

Vi/Vim 		
Linux著名文本/代码编辑器

###2.7浏览器认识

```
IE
Firefox	
Safari	
Opera 	
Google Chrome			
百度浏览器		
搜狗浏览器		
猎豹浏览器		
360浏览器		
UC浏览器		
傲游浏览器		
世界之窗浏览器
```

这些应该按照内核来划分，划重点，咨询。		

##3.HTML入门
###3.1HTML编写		
	1.新建文本
	2.后缀改为html或者htm
	3.在文本里输入内容
	4.保存，在网页打开

###3.2HTML语法
#### 3.2.1HTML文件格式		

HTML代码一般保存在.html 或者 .htm 文件下		
一般后缀默认以.html为主。

#### 3.2.2HTML标签格式		

##### 3.2.2.1什么是HTMl标签		

HTML标签也称作HTML标记，由开始标签以及结束标签组成，用于表现结构化内容，将内容构造成一个完整的网页。		
开始标签是被括号包围的元素名，如`<h1>`			
结束标签是被括号包围的斜杠和元素名，如`</h1>`	
注意：一些标签没有结束标签，如`<br/>`	

##### 3.2.2.2单标签与双标签		

单标签		
指的是没有结束标签的标签，如`<hr/> <br/>`		
双标签		
指的是由开始标签与结束标签组成的标签。

这两种是有规律的<br>
单标签一般应用在一个元素跟符号，不需要指定范围，直接使用。比如：换行符、水平线、图片、输入框；<br>
双标签需要指定一个范围的标签。

##### 3.2.2.3标签属性	

标签属性定义了属性描述标签的更多细节
比如字体标签<font>，如果需要设置字体大小，需要用size属性。
语法：<标签名 属性名="属性值" 属性名="属性值" ...>	<font size="3">字体大小</font>
属性值可以加双引号，也可以加单引号，也可以不加引号，但不要在一个值里面既加单引号又加双引号混合使用。**建议都使用双引号，便于交流**			
HTML标签既有通用属性，也就是每个标签都有属性，个别例外(Base,head,html,meta,script,style,title 不提供下面属性)		

| 属性  |          值           | 描述                   |
| ----- | :-------------------: | :--------------------- |
| class | class_rule strle_rule | 元素的类（class）      |
| id    |        id_name        | 元素的某个特定id       |
| style |       样式定义        | 内联样式定义           |
| title |       提示文本        | 显示于提示工具中的文本 |


​	
###3.3HTML基本结构
|                                                              |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <!DOCTYPE html><br/><html><br/><head><br/><meta charset="utf-8"><br/><title>HTML学习</title><br/></head><br/><body><br/>    <h1>Hello</h1><br/>    <p>My HTML !</p><br/></body><br/></html> | DOCTYPE:文档声明<br />html：标签告知浏览器自身是一个HTML文档<br />head：标签用于定义文档头部（文档描述信息）<br />body：标签用于定义文档的主体（文档主体内容） |

###3.4HTML基本结构的认识

```
<!--文档声明，告诉浏览器以什么标准来渲染HTML代码   
HTML4		

XHTML			
<!DOCTYPE html
PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">	

HTML5			<!DOCTYPE html>


-->
<!DOCTYPE html>
<html>
<!-- 
head标签：声明网页文档的头部信息（不会显示在网页上） 
网页文档编码/网页文档标题/文档关键词/文档描述/文档作者/缓存
 -->
<head>
<!--	
声明网页文档的编码集
 -->
<meta charset="utf-8">
<title>HTML学习</title>
</head>
<!--	
body标签：声明网页的内容部分
 -->
<body> 
<h1>Hello</h1> 
<p>My HTML !</p>
</body>
</html>
```



###3.5HTML注释

语法：`<!-- 注释 -->`

含义：注释标签用来在源文档中插入注释，注释会被浏览器忽略，可以在代码中用注释来进行解释，有利于代码后期识别编辑。

###3.6HTML编码问题



| UTF-8     | 字符集                            |
| --------- | --------------------------------- |
| UTF-8     | 国际通用编码字符集，UNICODE灵活版 |
| GBK       | 中文编码字符集                    |
| BIG5      | 中文繁体字符集                    |
| Iso8859-1 | 西方欧洲语言字符集                |
| UNICODE   | 大字符集，包括全球语言编码        |

<meta charset="UTF-8"/>
###3.7HTML规范

```
1.HTML 标签必须由尖括号包围关键词，如<html>。
2.HTML 标签通常成对出现，比如<b>和</b>。
	标签由开始标签与结束标签组成（双标签）或者没有结束标签的标签（单标签）
3.HTML 不区分大小写，但建议小写。
4.HTML 可以嵌套，但不允许交叉嵌套。
```




##4.HTML基本标签		
###4.1基础标签	

#### 4.1.1	hn	

```
hn 不是标签，指的是一类型的标签缩写。		

h1		一级标题	

h2		二级标题

h3		三级标题

h4		四级标题

h5		五级标题

h6		六级标题
```

例子：

```
<h1>HTML学习</h1>
<h2>HTML学习</h2>
<h3>HTML学习</h3>
<h4>HTML学习</h4>
<h5>HTML学习</h5>
<h6>HTML学习</h6>
```

展示：

<h1>HTML学习</h1>
<h2>HTML学习</h2>
<h3>HTML学习</h3>
<h4>HTML学习</h4>
<h5>HTML学习</h5>
<h6>HTML学习</h6>
#### 4.1.2	p	

```
<p>  	标签定义段落
```



#### 4.1.3	br	

```
换行符 	<br/>
```



#### 4.1.4	hr

```
水平分割线		<hr/>

如下展示：
```

<hr/>
### 4.2文本标签

#### 4.2.1	b strong	

都是呈现粗体文字效果

```
<b>粗体</b>
<strong>粗体</strong>
如下展示：
```

<b>粗体</b>
<strong>粗体</strong>

```
<b>标签明确将包括在它与其结束标签之间的字符或者文本变成粗体，如浏览器不支持某中字体，会以其它方式来表现。并且其没有扩展意义；
HTML5中建议使用<strong>
```

#### 4.2.2	i em	

```
<i> <em> 定义强调内容，对于浏览器来说，就是把这段文字用斜体来显示。
HTML5 建议使用<em>
```

#### 4.2.3	small

```
小号字体 <small> 
可以连续嵌套，直到是最小字体
如果已经是最小字体，使用small 标签 不能让字体再变小。
```

#### 4.2.4	big	

```
大号字体 <big> 
可以连续嵌套，直到是最大字体
如果已经是最大字体，使用big 标签 不能让字体再变大。
```

#### 4.2.5	pre	

```
<pre></pre>
由于浏览器直接忽略源码空格 tab（制表符） 换行（回车符），使用pre会将这些显示出来。但在实际使用中，不会这样使用。
```

#### 4.2.6 	u	

```
<u></u>
定义下划线文本
避免为文本加下划线，会让用户习惯认为这是一个超链接。
```

#### 4.2.7	del	

```
<del></del>
删除线 
定义文档中已被删除的文本
```



#### 4.2.8	sub	

```
定义文档下标文本
```



#### 4.2.9	sup			

```
定义文档上标文本
```



### 4.3布局标签	

#### 4.3.1	span	

```
用来组合文档内的行内元素，没有固定格式，当对应某样式，就会产生视觉上的变化。
```

#### 4.3.2	div	

```
可定义文档中的分区或者节
可以把文档分割为独立的、不同的部分，用作严格的组织工具吗，不实用任何格式与其关联。
如果用id或class来标记<div>，那么该标签作用会更有效。
```

```
<div> <span> 两个标签都没有特殊功能，而是作为一个内容容器，主要与CSS配合使用。
<div> 块标签 	（独占一行，用于布局，宽度默认100%）
<span>行内标签	（不会独占一行，依附于内容，可以多个并排一行，宽高为内容大小，用于勾选需要CSS修饰的内容）
```



#### 4.3.3	header	

```	
HTML5 新增语义标签，定义头部，类似 div ，定义section 或 page 的页眉。
```

#### 4.3.4	footer		

```
HTML5 新增语义标签，定义尾部，类似 div ，定义section 或 page 的页脚。
```

#### 4.3.5	section

```		
HTML5 标签定义文档的节（section、区段），比如章节、页眉、页脚或文档中的其它部分。
```

#### 4.3.6	article

```		
定义文章内容
```

#### 4.3.7	details

```		
定义元素的细节
```

#### 4.3.8	summary

```	
为<details>元素定义可见的标题
```

### 4.4资源标签	

#### 4.4.1	script 	

```		
定义客户端脚本，如JavaScript。

script 元素可以包含脚本语句，也可以通过src属性指向外部脚本文件。
可以使用type属性规范脚本的MIME类型。
JavaScript常见应用于图像操作、表单验证、动态内容更新。
```

#### 4.4.2	style	

```
用于HTML文档定义的CSS样式
在style中，可以规定浏览器如何呈现HTML文档。
type 属性定义style 元素的内容，唯一的值是"text/css"
style 元素通常位于head部分中。
```

#### 4.4.2	link	

```
定义文档与外部资源的关系，引入外部CSS样式。
常见于链式样式表。
```

##5.特殊符号

```
格式：&符号名;

由于浏览器在解析渲染HTML代码时，有些符号是特殊符号，无法直接显示。
我们需要用这些符号，需要使用这些符号来处理。

<		&lt;
>		&gt;
空格		&nbsp;
大空格		&emsp;
版权符		&copy;
&				&amp;
···
```






#DAY-02
##1.课程介绍
##2.超链接
###2.1什么是超链接

超链接本质上属于一个网页的一部分，是一种允许我们同其它网页或站点之间进行连接的元素。各个网页链接在一起后，才能构成一个网站。		

按照连接的路径不同，网页中超链接一般分为内部链接、锚点链接、外部链接。

###2.2A标签

```
<a>标签定义超链接，有两种用法:
通过href属性，创建指向另外一个文档的链接（或超链接、跳转到其它网页）。
通过name属性，创建一个文档内部的书签（也就是可以指向文档片段的链接，在自身网页中跳转）。
注意：
<a>标签是行内标签，同时也是一个双标签。
<a>元素最重要的是href属性，它指向链接的目标，跳转是需要注意添加 http:// 或者 https:// 协议。



<a href="http://www.baidu.com" target="_blank">这儿显示标题</a>

href 引用网页
target 中 _blank 新建跳转网页 没有这个属性就是在本页跳转。
```



###2.3绝对路径与相对路径

URL：统一资源定位符，URL可以使用绝对路径或相对路径。

#### 2.3.1绝对路径

绝对路径以协议（http://、https://、file://）或者以“/”作为前缀。

http协议（一般网络路径）：

```
<a href="http://www.baidu.com">百度</a>
```

file协议（本地路径）

```
<a href="file://E:/HELLO.html">HELLO</a>
```

基于网站根路径（/）

```
<a href="/news.html">新闻</a>
```

例子：

```




```



#### 2.3.2相对路径

以文件本身为参照路径进行定位。

	当前页面所在同级目录路径
	<a href="01.html">02.html</a>
	
	当前页面所在下级路径
	<a href="./03/03.html">03.html</a>
	
	./ 当前目录，可以省略不写，访问下级目录要写目录名。
	
	
	.// 回到上一层目录
	<a href="../helloworld.html">hello</a>
	
例子：

```
三个文件相互做超级链接
｜--01
｜--｜--01.html
｜--02
｜--｜--02.html（以此为入口文件）
｜--｜--03
｜--｜--｜--03.html

--------------------------------------------------------------


```





###2.4nav标签（了解）

定义导航链接，HTML5新增属性

```
<nav>
	<a href="index.html">首页</a>
	<a href="about.html">关于</a>
	<a href="lianxi.html">联系我们</a>
</nav>
```




##3.图片与多媒体 img audio video
###3.1 img标签	

img可定义一副图片

语法：

```
<img src="图片路径" alt="图片文字说明"/>
```

注意事项：

**img**是一个行内标签，并且是一个单标签（自关闭）

多个图片格式都包含（jpg，bmp，png，gif，svg）



jpg: 有损压缩图片格式

bmp:不用

png:带alpha通道的高清透明图片格式

gif:动态图

svg:矢量图



属性**src**要有

当只修改图片宽度时，高度等比例缩放（反之亦然）（**width** **height**）

**title**:图片文字，一般鼠标放在上面显示文字

**alt**:当图片不存在的时候，显示它里面的文字



###3.2 audio标签

audio 定义声音内容

语法：

```
<audio src="音乐文件路径" autoplay="autoplay">您的浏览器不支持audio标签</audio>
```

| 属性     | 值       | 描述                                                         |
| -------- | -------- | ------------------------------------------------------------ |
| autoplay | autoplay | 音频就绪立即播放                                             |
| controls | controls | 向用户展示控件，比如播放按钮                                 |
| loop     | loop     | 当音频结束重新开始播放                                       |
| muted    | muted    | 规定视频输出应该被静音                                       |
| preload  | preload  | 音频在页面加载时进行加载，并预备播放。如果出现“autoplay”，则忽略该属性 |
| src      | url      | 要播放的音频URL                                              |

音频格式

|            | IE9  | Firefox.5 | Opera 0.5 | Chrome | Safari 3.0 |
| ---------- | ---- | --------- | --------- | ------ | ---------- |
| Ogg Vorbis |      | ✅         | ✅         | ✅      |            |
| MP3        | ✅    |           |           | ✅      | ✅          |
| Wav        |      | ✅         | ✅         |        | ✅          |



###3.3 video标签

video定义视频

语法：

```
<video src="视频文件路径" controls="controls">您的浏览器不支持video标签</video>
```

| 属性     | 值       | 描述                                                         |
| -------- | -------- | ------------------------------------------------------------ |
| autoplay | autoplay | 视频就绪立即播放                                             |
| controls | controls | 向用户展示控件，比如播放按钮                                 |
| height   | pixels   | 设置视频播放器高度                                           |
| loop     | loop     | 当视频结束重新开始播放                                       |
| muted    | muted    | 规定视频输出应该被静音                                       |
| poster   | URL      | 视频喜爱在时显示的图片，或者用户点击播放按钮前显示的图片     |
| preload  | preload  | 视频在页面加载时进行加载，并预备播放。如果出现“autoplay”，则忽略该属性 |
| src      | url      | 要播放的视频URL                                              |



###3.4 source标签

为媒介元素（<video>和<audio>）定义媒介资源，允许规定可替换的视频/音频文件供浏览器根据它对媒体类型或者编解码器的支持进行选择。

```
<audio controls="controls">
	<source src="horse.ogg" type="audio/ogg">
	<source src="horse.mp3" type="audio/mpeg">
	您的浏览器不支持audio标签
</audio>	

注意：src的值是音频资源地址，type是音频资源类型，可以指定多个资源，浏览器将自动选择支持的资源进行播放。
```



##4.列表标签	
###4.1什么是列表	

列表标签是网页开发中常用的标签，一般用于做某项数据的列表或者导航。

HTML中列表有3种形式，无序列表、有序列表、定义列表。

###4.2无序列表ul		

```
列表标签：ul ol li 块标签，必须【组合出现】

ul 标签是块标签（独占一行），是一个双标签
ul 标签有默认的内边距 外边距

注意：
1.ul li 必须搭配使用
2.ul标签内只能出现 li 标签
3.li标签可以出现所以的其它标签。

<ul>
	<li>苹果
		<ul>
		<li>小苹果</li>
		<li>红苹果</li>
		</ul>
	</li>		
	<li>香蕉</li>
	<li>火龙果</li>
</ul>
```

<ul>
	<li>苹果
		<ul>
		<li>小苹果</li>
		<li>红苹果</li>
		</ul>
	</li>		
	<li>香蕉</li>
	<li>火龙果</li>
</ul>

###4.3有序列表ol	

```
有序列表 ol
<ol></ol> 和 ul 一模一样

注意：
1.所以特性和ul一模一样
2.唯一不同的在于 引符号是数字


<ol>
	<li>苹果
		<ol>
		<li>小苹果</li>
		<li>红苹果</li>
		</ol>
	</li>		
	<li>香蕉</li>
	<li>火龙果</li>
</ol>
```

<ol>
	<li>苹果
		<ol>
		<li>小苹果</li>
		<li>红苹果</li>
		</ol>
	</li>		
	<li>香蕉</li>
	<li>火龙果</li>
</ol>

###4.4定义列表dl	

```
配合 dt dd 标签来使用

<dl>
	<dt>标签</dt>
	<dd>内容</dd>
</dl>

特征：
1.dd  默认的左边外边距
2.dl  有默认的上下外边距
```




##5.表格table
###5.1表格标签

表格最重要的目的是显示表格类数据，比如个人信息。

```

<table> 	定义表格
		border 			设置表格边框
		width				设置表格宽度
		cellpadding 设置表格中单元格距离内容之间的空白
		cellspacing 设置单元格之间的间隙
<tr> 			定义表格的行

<td> 			定义表格的行

<td> 			定义表格的单元

<th> 			定义表格的表头单元格

<thead> 	定义表格的表头内容

<tbody> 	定义表格主体内容

<tfoot> 	定义表格的表注内容

<caption>	定义表格标题

```

5.2表格合并行列	

```
跨行与跨列属性在td标签中
colspan 跨行合并 
rowspan 跨列合并

```



#DAY-03
##1.课程介绍
##2.表单标签Form
###2.1什么是表单

表单在网页上主要负责数据采集功能，一个表单有3个基本组成部分。

1>表单标签：这里面包含了处理表单数据所用PHP程序的URL以及数据提交到服务器方法。

2>表单域：包含文本框、密码框、隐藏域、多行文本框、复选框、单选框、下拉选择框、文件上传框等。

3>表单按钮：包含提交按钮、复位按钮、一般按钮。用于将数据传送到服务器上的处理程序或者取消输入，还可以用表单按钮来控制其它定义脚本的处理工作。

###2.2Form标签

功能：用于声明表单区域，定义采集数据的范围。也就是<form>和</form>里面包含的数据将提交到服务器，

语法：

```
<form action="URL" method="get/post"></form>
```

| 属性           | 值                                                           | 描述                                     |
| -------------- | ------------------------------------------------------------ | ---------------------------------------- |
| accept-charset | charset_list                                                 | 规定服务器可处理的表单数据字符集         |
| action         | URL                                                          | 规定当提交表单时向何处发送表单数据       |
| autocomplete   | on   off                                                     | 规定是否启用表单的自动完成功能           |
| enctype        | application/x-www-form-urlencoded<br/>multipart/form-data<br/>text/plain | 规定在发送表单数据之前如何对其进行编码   |
| method         | get <br/>post                                                | 规定用于发送 form-data 的 HTTP 方法。    |
| name           | form_name                                                    | 规定表单的名称。                         |
| novalidate     | novalidate                                                   | 如果使用该属性，则提交表单时不进行验证。 |
| targert        | _blank<br/> _self<br/> _parent<br/> _top<br/> *framename*    | 规定在何处打开 action URL。              |

method:

1.get方法：

将数据附加在网址后面进行传输

语法：

URL网址?参数名1=参数值1&参数名2=参数值2

注意：

1>所有出现文件名的地方都打?进行get方式传值。

2>只能用来传输少量数据（2kb以下）

3>在网址后面可以直接看到，不安全

2.post方法

不会附加在网址后面（隐性传值）

注意：

1>post方式可以传大量数据（上传文件）

2>隐性传输，非常安全

3>form表单通常使用post方式，除了**搜索框**



##3.表单元素

###3.1输入框 input	

定义：用于搜集用户信息

根据不同的type属性，输入字断可以拥有多种形式，可以是文本字段，复选框，掩码后文本控件，单选按钮，按钮等。

```
<imput>是行内元素，也是单标签，需要自关闭。
<input type="" name="" value=""/>
```

Type

| 属性                                                         | 值                                                           | 描述                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [accept](https://www.w3school.com.cn/tags/att_input_accept.asp) | *mime_type*                                                  | 规定通过文件上传来提交的文件的类型。                         |
| [align](https://www.w3school.com.cn/tags/att_input_align.asp) | leftrighttopmiddlebottom                                     | 不赞成使用。规定图像输入的对齐方式。                         |
| [alt](https://www.w3school.com.cn/tags/att_input_alt.asp)    | text                                                         | 定义图像输入的替代文本。                                     |
| [autocomplete](https://www.w3school.com.cn/tags/att_input_autocomplete.asp) | onoff                                                        | 规定是否使用输入字段的自动完成功能。                         |
| [autofocus](https://www.w3school.com.cn/tags/att_input_autofocus.asp) | autofocus                                                    | 规定输入字段在页面加载时是否获得焦点。（不适用于 type="hidden"） |
| [checked](https://www.w3school.com.cn/tags/att_input_checked.asp) | checked                                                      | 规定此 input 元素首次加载时应当被选中。                      |
| [disabled](https://www.w3school.com.cn/tags/att_input_disabled.asp) | disabled                                                     | 当 input 元素加载时禁用此元素。                              |
| [form](https://www.w3school.com.cn/tags/att_input_form.asp)  | *formname*                                                   | 规定输入字段所属的一个或多个表单。                           |
| [formaction](https://www.w3school.com.cn/tags/att_input_formaction.asp) | *URL*                                                        | 覆盖表单的 action 属性。（适用于 type="submit" 和 type="image"） |
| [formenctype](https://www.w3school.com.cn/tags/att_input_formenctype.asp) | 见注释                                                       | 覆盖表单的 enctype 属性。（适用于 type="submit" 和 type="image"） |
| [formmethod](https://www.w3school.com.cn/tags/att_input_formmethod.asp) | getpost                                                      | 覆盖表单的 method 属性。（适用于 type="submit" 和 type="image"） |
| [formnovalidate](https://www.w3school.com.cn/tags/att_input_formnovalidate.asp) | formnovalidate                                               | 覆盖表单的 novalidate 属性。如果使用该属性，则提交表单时不进行验证。 |
| [formtarget](https://www.w3school.com.cn/tags/att_input_formtarget.asp) | _blank_self_parent_top*framename*                            | 覆盖表单的 target 属性。（适用于 type="submit" 和 type="image"） |
| [height](https://www.w3school.com.cn/tags/att_input_height.asp) | *pixels**%*                                                  | 定义 input 字段的高度。（适用于 type="image"）               |
| [list](https://www.w3school.com.cn/tags/att_input_list.asp)  | *datalist-id*                                                | 引用包含输入字段的预定义选项的 datalist 。                   |
| [max](https://www.w3school.com.cn/tags/att_input_max.asp)    | *number**date*                                               | 规定输入字段的最大值。请与 "min" 属性配合使用，来创建合法值的范围。 |
| [maxlength](https://www.w3school.com.cn/tags/att_input_maxlength.asp) | number                                                       | 规定输入字段中的字符的最大长度。                             |
| [min](https://www.w3school.com.cn/tags/att_input_min.asp)    | *number**date*                                               | 规定输入字段的最小值。请与 "max" 属性配合使用，来创建合法值的范围。 |
| [multiple](https://www.w3school.com.cn/tags/att_input_multiple.asp) | multiple                                                     | 如果使用该属性，则允许一个以上的值。                         |
| [name](https://www.w3school.com.cn/tags/att_input_name.asp)  | field_name                                                   | 定义 input 元素的名称。                                      |
| [pattern](https://www.w3school.com.cn/tags/att_input_pattern.asp) | *regexp_pattern*                                             | 规定输入字段的值的模式或格式。例如 pattern="[0-9]" 表示输入值必须是 0 与 9 之间的数字。 |
| [placeholder](https://www.w3school.com.cn/tags/att_input_placeholder.asp) | *text*                                                       | 规定帮助用户填写输入字段的提示。                             |
| [readonly](https://www.w3school.com.cn/tags/att_input_readonly.asp) | readonly                                                     | 规定输入字段为只读。                                         |
| [required](https://www.w3school.com.cn/tags/att_input_required.asp) | required                                                     | 指示输入字段的值是必需的。                                   |
| [size](https://www.w3school.com.cn/tags/att_input_size.asp)  | number_of_char                                               | 定义输入字段的宽度。                                         |
| [src](https://www.w3school.com.cn/tags/att_input_src.asp)    | URL                                                          | 定义以提交按钮形式显示的图像的 URL。                         |
| [step](https://www.w3school.com.cn/tags/att_input_step.asp)  | *number*                                                     | 规定输入字的的合法数字间隔。                                 |
| [type](https://www.w3school.com.cn/tags/att_input_type.asp)  | <br/>button<br/>checkbox<br/>file<br/>hidden<br/>image<br/>password<br/>radio<br/>reset<br/>submit<br/>text | <br/>规定 input 元素的类型。<br/>普通按钮<br/>多选<br/>文件上传框<br/>隐藏域<br/>图片按钮<br/>密码框<br/>单选<br/>重置按钮<br/>提交按钮<br/>文本框<br/> |
| [value](https://www.w3school.com.cn/tags/att_input_value.asp) | *value*                                                      | 规定 input 元素的值。                                        |
| [width](https://www.w3school.com.cn/tags/att_input_width.asp) | *pixels**%*                                                  | 定义 input 字段的宽度。（适用于 type="image"）               |

###3.2下拉框 select

select 元素可创建单选或多选菜单

```
<select>和<option>一起使用,为select提供下拉选项
```

select属性：

| 属性                                                         | 值        | 描述                                   |
| :----------------------------------------------------------- | :-------- | :------------------------------------- |
| [autofocus](https://www.w3school.com.cn/tags/att_select_autofocus.asp) | autofocus | 规定在页面加载后文本区域自动获得焦点。 |
| [disabled](https://www.w3school.com.cn/tags/att_select_disabled.asp) | disabled  | 规定禁用该下拉列表。                   |
| [form](https://www.w3school.com.cn/tags/att_select_form.asp) | *form_id* | 规定文本区域所属的一个或多个表单。     |
| [multiple](https://www.w3school.com.cn/tags/att_select_multiple.asp) | multiple  | 规定可选择多个选项。                   |
| [name](https://www.w3school.com.cn/tags/att_select_name.asp) | *name*    | 规定下拉列表的名称。                   |
| [required](https://www.w3school.com.cn/tags/att_select_required.asp) | required  | 规定文本区域是必填的。                 |
| [size](https://www.w3school.com.cn/tags/att_select_size.asp) | *number*  | 规定下拉列表中可见选项的数目。         |



#### 3.2.1option标签

	<option>定义下拉选项
	value:为下拉选项定义要提交的值，如果没有value属性则提交中间的文字
	selected:为下拉框设置默认选项
###3.3多行文本域 textarea

```
定义多行文本输入控件

文本区中可容纳无限数量的文本，其中的文本的默认字体是等宽字体（通常是 Courier）。
可以通过 cols 和 rows 属性来规定 textarea 的尺寸，不过更好的办法是使用 CSS 的 height 和 width 属性。
注释：在文本输入区内的文本行间，用 "%OD%OA" （回车/换行）进行分隔。
```

| 属性                                                         | 值                 | 描述                                               |
| :----------------------------------------------------------- | :----------------- | :------------------------------------------------- |
| [autofocus](https://www.w3school.com.cn/tags/att_textarea_autofocus.asp) | autofocus          | 规定在页面加载后文本区域自动获得焦点。             |
| [cols](https://www.w3school.com.cn/tags/att_textarea_cols.asp) | *number*           | 规定文本区内的可见宽度。                           |
| [disabled](https://www.w3school.com.cn/tags/att_textarea_disabled.asp) | disabled           | 规定禁用该文本区。                                 |
| [form](https://www.w3school.com.cn/tags/att_textarea_form.asp) | *form_id*          | 规定文本区域所属的一个或多个表单。                 |
| [maxlength](https://www.w3school.com.cn/tags/att_textarea_maxlength.asp) | *number*           | 规定文本区域的最大字符数。                         |
| [name](https://www.w3school.com.cn/tags/att_textarea_name.asp) | *name_of_textarea* | 规定文本区的名称。                                 |
| [placeholder](https://www.w3school.com.cn/tags/att_textarea_placeholder.asp) | *text*             | 规定描述文本区域预期值的简短提示。                 |
| [readonly](https://www.w3school.com.cn/tags/att_textarea_readonly.asp) | readonly           | 规定文本区为只读。                                 |
| [required](https://www.w3school.com.cn/tags/att_textarea_required.asp) | required           | 规定文本区域是必填的。                             |
| [rows](https://www.w3school.com.cn/tags/att_textarea_rows.asp) | *number*           | 规定文本区内的可见行数。                           |
| [wrap](https://www.w3school.com.cn/tags/att_textarea_wrap.asp) | hardsoft           | 规定当在表单中提交时，文本区域中的文本如何换行。。 |

###3.4lable标签

为input 元素定义标注（标记）

label 元素不会向用户呈现任何特殊效果。不过，它为鼠标用户改进了可用性。如果您在 label 元素内点击文本，就会触发此控件。就是说，当用户选择该标签时，浏览器就会自动将焦点转到和标签相关的表单控件上。

<label> 标签的 for 属性应当与相关元素的 id 属性相同。



| 属性                                                        | 值       | 描述                                  |
| :---------------------------------------------------------- | :------- | :------------------------------------ |
| [for](https://www.w3school.com.cn/tags/att_label_for.asp)   | *id*     | 规定 label 绑定到哪个表单元素。       |
| [form](https://www.w3school.com.cn/tags/att_label_form.asp) | *formid* | 规定 label 字段所属的一个或多个表单。 |

###3.5按钮button

定义一个按钮。

在 button 元素内部，您可以放置内容，比如文本或图像。这是该元素与使用 input 元素创建的按钮之间的不同之处。

<button> 控件 与 <input type="button"> 相比，提供了更为强大的功能和更丰富的内容。<button> 与 </button> 标签之间的所有内容都是按钮的内容，其中包括任何可接受的正文内容，比如文本或多媒体内容。例如，我们可以在按钮中包括一个图像和相关的文本，用它们在按钮中创建一个吸引人的标记图像。

唯一禁止使用的元素是图像映射，因为它对鼠标和键盘敏感的动作会干扰表单按钮的行为。

请始终为按钮规定 type 属性。Internet Explorer 的默认类型是 "button"，而其他浏览器中（包括 W3C 规范）的默认值是 "submit"。



| 属性                                                         | 值                                | 描述                                                         |
| :----------------------------------------------------------- | :-------------------------------- | :----------------------------------------------------------- |
| [autofocus](https://www.w3school.com.cn/tags/att_button_autofocus.asp) | autofocus                         | 规定当页面加载时按钮应当自动地获得焦点。                     |
| [disabled](https://www.w3school.com.cn/tags/att_button_disabled.asp) | disabled                          | 规定应该禁用该按钮。                                         |
| [form](https://www.w3school.com.cn/tags/att_button_form.asp) | *form_name*                       | 规定按钮属于一个或多个表单。                                 |
| [formaction](https://www.w3school.com.cn/tags/att_button_formaction.asp) | *url*                             | 覆盖 form 元素的 action 属性。**注释：**该属性与 type="submit" 配合使用。 |
| [formenctype](https://www.w3school.com.cn/tags/att_button_formenctype.asp) | 见注释                            | 覆盖 form 元素的 enctype 属性。**注释：**该属性与 type="submit" 配合使用。 |
| [formmethod](https://www.w3school.com.cn/tags/att_button_formmethod.asp) | getpost                           | 覆盖 form 元素的 method 属性。**注释：**该属性与 type="submit" 配合使用。 |
| [formnovalidate](https://www.w3school.com.cn/tags/att_button_formnovalidate.asp) | formnovalidate                    | 覆盖 form 元素的 novalidate 属性。**注释：**该属性与 type="submit" 配合使用。 |
| [formtarget](https://www.w3school.com.cn/tags/att_button_formtarget.asp) | _blank_self_parent_top*framename* | 覆盖 form 元素的 target 属性。**注释：**该属性与 type="submit" 配合使用。 |
| [name](https://www.w3school.com.cn/tags/att_button_name.asp) | *button_name*                     | 规定按钮的名称。                                             |
| [type](https://www.w3school.com.cn/tags/att_button_type.asp) | buttonresetsubmit                 | 规定按钮的类型。                                             |
| [value](https://www.w3school.com.cn/tags/att_button_value.asp) | *text*                            | 规定按钮的初始值。可由脚本进行修改。                         |

**注释：**formenctype 属性可能的值：

- application/x-www-form-urlencoded
- multipart/form-data
- text/plain



##4.框架	
#####4.1活动框架 iframe

iframe 元素会创建包含另外一个文档的内联框架（即行内框架）。





| 属性                                                         | 值                                                           | 描述                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [align](https://www.w3school.com.cn/tags/att_iframe_align.asp) | leftrighttopmiddlebottom                                     | 不赞成使用。请使用样式代替。规定如何根据周围的元素来对齐此框架。 |
| [frameborder](https://www.w3school.com.cn/tags/att_iframe_frameborder.asp) | 10                                                           | 规定是否显示框架周围的边框。                                 |
| [height](https://www.w3school.com.cn/tags/att_iframe_height.asp) | *pixels**%*                                                  | 规定 iframe 的高度。                                         |
| [longdesc](https://www.w3school.com.cn/tags/att_iframe_longdesc.asp) | *URL*                                                        | 规定一个页面，该页面包含了有关 iframe 的较长描述。           |
| [marginheight](https://www.w3school.com.cn/tags/att_iframe_marginheight.asp) | *pixels*                                                     | 定义 iframe 的顶部和底部的边距。                             |
| [marginwidth](https://www.w3school.com.cn/tags/att_iframe_marginwidth.asp) | *pixels*                                                     | 定义 iframe 的左侧和右侧的边距。                             |
| [name](https://www.w3school.com.cn/tags/att_iframe_name.asp) | *frame_name*                                                 | 规定 iframe 的名称。                                         |
| [sandbox](https://www.w3school.com.cn/tags/att_iframe_sandbox.asp) | ""allow-formsallow-same-originallow-scriptsallow-top-navigation | 启用一系列对 <iframe> 中内容的额外限制。                     |
| [scrolling](https://www.w3school.com.cn/tags/att_iframe_scrolling.asp) | yesnoauto                                                    | 规定是否在 iframe 中显示滚动条。                             |
| [seamless](https://www.w3school.com.cn/tags/att_iframe_seamless.asp) | seamless                                                     | 规定 <iframe> 看上去像是包含文档的一部分。                   |
| [src](https://www.w3school.com.cn/tags/att_iframe_src.asp)   | *URL*                                                        | 规定在 iframe 中显示的文档的 URL。                           |
| [srcdoc](https://www.w3school.com.cn/tags/att_iframe_srcdoc.asp) | *HTML_code*                                                  | 规定在 <iframe> 中显示的页面的 HTML 内容。                   |
| [width](https://www.w3school.com.cn/tags/att_iframe_width.asp) | *pixels**%*                                                  | 定义 iframe 的宽度。                                         |

#####4.2框架集		<后期了解>

<frameset>

<frame>