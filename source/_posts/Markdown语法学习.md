
---
abbrlink: 1001
mathjax: 
tags: Markdown
---




<h1 align = "center">Markdown笔记</h1>

# 0-字体设置：
> ```<font face="方正楷体">这是方正楷体</font>```
<font face="方正楷体">这是方正楷体</font>


# 1-标题：
> ```# 一级标题```
# 一级标题




>>```## 二级标题```
## 二级标题

* 注意空格
* 至多6级；
	
# 2-标记：
>```\**这是加粗文本**```

**这是加粗文本**


>```*这是斜体文本*```

*这是斜体文本*


>```**正文*斜体加粗* 正文**```

**正文*斜体加粗* 正文**


>`~~删除线~~`
~~删除线~~




# 3-引用：
* 引用：
>``` >**这一块是引用的** ```
>**这一块是引用的**


* 引用代码：
(单独引用)
>use \`git here\` command
use `git here` command
* 引用代码块：

>\`
hexo clean
hexo g
hexo d
\`


```
hexo clean
hexo g
hexo d
```


\* 一行代码：    
>四个空格即可：


    1234


* 多重引用：
>\>P1 
\>>P2 
\>>>P3

>P1
>>P2
>>>P3


* 语法高亮：
>\```c
int main(){
printf("hello,world\n");
return 0;
}
\```



```c
int main(){
printf("hello,world\n");
return 0;
}
```

# 4-超链接：
> \[谷歌\](www.google.com "这是链接标题,鼠标经过显示内容")


* [谷歌](www.google.com "这是链接标题,鼠标经过显示内容")            




> `<http:www.baidu.com>`


* [URL链接](http:www.baidu.com  "这是百度")




> `![saber](https://cdn.jsdelivr.net/gh/Zhujie-ww/imagebed/friendslink.jpg "哈哈哈")`


![saber](https://cdn.jsdelivr.net/gh/Zhujie-ww/imagebed/friendslink.jpg "哈哈哈")

# 5-无序列表（+-*）
```
- HH
- CC
- FFS
- SDF
+ RRR```


- HH
- CC
- FFS
- SDF
+ RRR

# 6、有序列表：
```
1. 22
2. 34
3. 434
4. 34
5. 44
```

1. 22
2. 34
3. 434
4. 34
5. 44

# 7-列表分级：

```
- 第一         
    - 第二                
         - 第三

```


- 第一         
    - 第二                
         - 第三

(前后多次加多个空格！)


# 8-任务列表

```
- [ ] 学习毛泽东思想
- [x] \(Optional) Open a followup issue

```


- [ ] 学习毛泽东思想
- [x] (Optional) Open a followup issue




# 9-表情


```
:kissing:
:joy:
```


:kissing:
:joy:

# 10-转义字符：
```
\
```

`\`


# 11-图片引用：
* 绝对路径
* 相对路径：
    `![](/medias/1.jpg)`
    //同级；
   ` ![](/medias/1.jpg)`
    //下一级；
# 12-下划线：



`_ _ _`

___

# 13-表格：


```
|姓名 | 性别 |工资 |工龄|职位
|---|:--:|---|----|-|
|张三|男|2000|2|经理
| 默认左对齐|

```


|姓名 | 性别 |工资 |工龄|职位
|---|:--:|---|----|-|
|张三|男|2000|2|经理
| 默认左对齐|

# 14-排版：

* 回车：两个回车才是回车，一个=回车空格符号；
* 缩进：
    * 一个英文：
&ensp;缩进一格；
  * 一个中文：
&emsp;缩进2格；
  * 中文1/4位：
&nbsp;缩进1/4

```
缩进0格
&nbsp;缩进1/4个中文字符；
&ensp;缩进一格；
&emsp;缩进2格（一个中文字符)；```

* 居中：

```
<div align=center>
哈哈
</div>
```

<div align=center>
哈哈
</div>


# 15-脚注：
```
解释文本[^er]
[^er]:111

```

解释文本[^er]
[^er]:111


   





