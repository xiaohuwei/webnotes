!> HTML, 超文本标记语言（英语：HyperText Markup Language，简称：HTML）是一种用于创建网页的标准标记语言。HTML是一种基础技术，常与CSS、JavaScript一起被众多网站用于设计赏心悦目的网页、网页应用程序以及移动应用程序的用户界面。网页浏览器可以读取HTML文件，并将其渲染成可视化网页。HTML描述了一个网站的结构语义随着线索的呈现，使之成为一种标记语言而非编程语言。

###		基本结构

```html
<!DOCTYPE html> 声明文件语言类型 H5文档头
<html>  ####    包裹所有标签
   <head>  ### 头部标签 包裹网页相关信息
    #### 设置字符集 中文 gb2312 GBK（早期的）UTF-8(全世界所有语言的字符集编码)
   	<meta charset="UTF-8"/> 
	<title>这是我的第一个网页</title>####  设置网页名字
   </head>
   <body>###包裹网页内容 肉眼看到的
   </body>
</html>
```

###		基本元素属性

|  标签   |                             定义                             |
| :-----: | :----------------------------------------------------------: |
|  h1-h6  |                           标题标签                           |
|    a    | 超链接标签 通过 href属性控制跳转地址 可以在新的页面打开 也可以在当前页打开 |
|    p    |                           段落标签                           |
|    b    |                           字体加粗                           |
|    u    |                          字体下划线                          |
|    s    |                          字体删除线                          |
|    i    |                           字体斜体                           |
| `<hr/>` |                             横线                             |
| `<br/>` |                             换行                             |
|   div   |                          无意义标签                          |
|  span   |                          无意义标签                          |
|   img   |         图片一般通过src属性给图片路径 可单独设置宽高         |

###		行内元素和块级元素

!>独占一行的是块级标签（元素）行内标签（元素）可以跟其他元素在同一行

### 路径

> 1.绝对路径 相对于操作系统所处在的位置
>
> 2.相对路径 相对于当前文件 目标文件所在的位置 ../(返回上一级)./(当前目录)
>
> 3.网络路径