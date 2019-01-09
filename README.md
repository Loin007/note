## 主要内容
> #### 什么是Markdown？
> #### 为什么用Markdown？
> #### 如何使用Markdown？

## 正文
### 什么是Markdown？
Markdown是一种轻量级标记语言，它允许人们使用易读易写的纯文本编写文档，通过部分简单的英文`符号`标记纯文本，使普通纯文本具有一定格式。    

### 为什么用Markdown？
+ 语法简单、纯文本编辑支持任何编辑器、符号标记快速排版；
+ 可以轻松导出 PDF、Word、HTML 等常文件格式；
+ 各大平台支持，Github文档默认是Markdown格式的，方便技术同学编写文档说明、可以使用GitHub与Gitbook写电子书。

### 如何使用Markdown？

#### 链接（links）   
两种形式：      
1）内联方式:
> \[唯品会正品特卖\]\(http:://www.vip.com "唯品会"\)   

效果:
> [唯品会正品特卖](http:://www.vip.com "唯品会")

2）引用方式：
> \[唯品会正品特卖\]\[1\]   
> \[1\]:http:://www.vip.com "唯品会" 

效果如下:
> [唯品会正品特卖][1]       

[1]:https://www.vip.com "唯品会"

#### 自动链接（Automatic Links）
链接地址或者email地址用`<>`括起来
> \<http://www.vip.com\>        
> <D13202512770@163.com\> 

效果如下:
> <http://www.vip.com>      
> <D13202512770@163.com>    

#### 强调（Emphasis）：
在需要强调文字的两侧加`*`或`_`代表强调
> \*斜体* ,\_斜体_    
> \*\*加粗**,\_\_加粗__    
> \*\*\*斜体&加粗***, \_\_\_斜体&加粗___

效果    
> *斜体* ,_斜体_    
> **加粗**,__加粗__     
> ***斜体&加粗***, ___斜体&加粗___      

#### 代码（code）：
需要标识的文字两侧使用 ` 符号来标识
> \`这段文字被标记了\`,\`\`这样也会被标记\`\`    

效果
> `这段文字被标记了`,``这样也会被标记`` 

#### 图片（Images）：
在链接（links）的语法前面加符号`!`
> \!\[唯品会正品特卖\]\(./vip_banner.jpg "唯品会"\) 

效果
> ![唯品会正品特卖](./vip_banner.jpg "唯品会") 

**注意：** 该标记不支持设置图片的大小，如有需要请直接使用`html`的`<img/>`标签（mrkedown里面支持直接使用`html`标签）。   

### 标题（Headers）
1)[select](https://en.wikipedia.org/wiki/Setext)样式:使用符号`=`和`-`在文字下方标记为一级和二级标题，如下所示：
> 一级标题  
> \======  
> 二级标题  
> \-------

效果如下：
> 一级标题  
> =======  
> 二级标题
> -------    
2 atx样式:使用1-6个`#`在文字的开头分别表示1-6级标题,如下所示:
> \# 一级标题   
> \## 二级标题  
> \### 三级标题 
> \#### 四级标题  
> \##### 五级标题   
> \###### 六级标题  

效果如下：
> # 一级标题   
> ## 二级标题  
> ### 三级标题 
> #### 四级标题  
> ##### 五级标题   
> ###### 六级标题  

###  段落（Paragraphs and Line Breaks）
段落前后需要是空行，段落内强制换行的方法是两个空格+回车。

###  引用（Blockquotes）
使用符号`<`在加每行文字或者段落前面表示引用，可通过叠加多个`>`嵌套引用，如下所示：
>  一级引用     
>> 二级引用 
>>> 三级引用  
###  列表（lists）
无序列表:使用符号`+`或`-`或`*`标识在列表每项最前面，如下所示：
>\+ 列表第一项  
>\+ 列表第二项  
>\+ 列表第三项  

效果如下：
> + 列表第一项
> + 列表第二项
> + 列表第三项

有序列表：使用符号组合为`数字.`表示在列表项最前面，如下所示：
> 1\. 列表第一项  
> 2\. 列表第二项  
> 3\. 列表第三项 

效果如下:
> 1. 列表第一项  
> 2. 列表第二项  
> 3. 列表第三项 

**注意**：一行这样的文字有可能会触发为列表标识`2016. 多么帮的一年呀`，需要对`.`进行转义，改成 `2016\. 多么帮的一年呀`即可！

###  代码块（Code Blocks）
使用`Tab制表符`或者4个空格标识需要预格式化的内容，如下所示：    

    该内容被预格式化啦

###  水平线（Horizontal Rules）
通过在一行上放置三个或更多连字符生成水平线，字符可以是`-`,`*`,`_` ,如下所示：
 
> \---  
> \***      
> \___

效果如下：
> ---   
> ***   
> ___

### 转义字符
MarkDown语法中，部分字符作为标记有特殊的意义，如果需要使用该字符原本的意思，就需要用字符`\`对其进行转义！


## 参考文章
[Markdown语法](https://daringfireball.net/projects/markdown/syntax)






























