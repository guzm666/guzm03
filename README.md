# Lesson4-周四（7.15）
## 昨日技术总结
1. CSS选择器（标记、id、class）
2. CSS代码放置位置
3. 边框样式（文本框变红）
4. 工作后，网页界面由美工（UI）来做，我们在他的基础上开发后端程序
5. 我怎么样把自己做的网页，有个网址，别人用这个网址就能看到我的网页？
  第一步：开发自己的网页
  第二部：购买云主机linux系统（阿里云主机），获得一个IP地址
  第三步：把自己做好的网页，远程上传到阿里云主机
  第四步：百度搜索域名注册，注册一个自己的域名
   域名在工信部备案，取得备案号；把自己的域名和IP做绑定，
   通过阿里云完成；此时，你的网站就可以访问

## 一、CSS显示 
1. display：隐藏后释放区域
2. visibility：隐藏后不释放区域
3. 面试题：上面俩个有什么区别？

## 二、CSS的浮动（float）
1. 网页美工必须要精通
2. 主要用于：网页布局（CSS+DIV)
3. CSS+DIV做网页布局离不开浮动，要理解浮动的意思；
 看网页效果，返回了理解用意
 
## 三、Bootstrap技术
### 1.Bootstrap介绍
— 用Bootstrap做的网页，可以自动适应屏幕大小（自适应、响应式）
— 移动端优先（Bootstrap伴随着智能手机时代而来）
— Bootstrap技术是基于：HTML、CSS、JavaScript
— Bootstrap本质：写好的CSS样式库
— Bootstrap不是编程语言，是一种技术。

### 2.Bootstrap如何来用
 - 把Bootstrap文件从官网下载来，复制到自己的项目里
 - 直接使用CDN（内容分发网络，其实就是：放在公网的文件）
 如果使用CDN方式，电脑必须联网，不能断网
### 3.如何学Bootstrap？
 - 看官网文档
### 4.Bootstrap工作原理？
— 网格系统（屏幕分成12列，使用者可以按自己的需求组合列）
— 使用Bootstrap后，CSS样式不用我们自己写
### 5.如何在github上搭建静态网站
— 注册github账号
— 创建一个项目
— 把写好的网页上传到项目里
— 在设置中找到pages，点击main，点save



# Lesson3-周三（7.14）
## 一、CSS到底是什么
 1.层叠式样式表，简称为样式。(Cascading Style Sheets)
 2.由W3C组织制定标准，最新版CSS3.
 3.由浏览器执行
 4.作用：美化网页（HTML不具备美化网页功能）
 
## 二、CSS选择器（*****）
1. 标记选择器
2. id选择器
3. class选择器
三种选择器必须会用！

## 三、CSS代码放置的位置
1. 页内位置：放在hand之间，用style标记
2. 行内样式：放在标记的style属性里，优先级最高
3. 外部样式：放在单独的CSS文件中，在网页上用link引入

## 四、开发常用样式
1. 背景颜色（background-color）
2. 文本样式（color、text-align、text-decoration）
3. 字体样式（font-family\font-size)
   网页上的文字默认16像素，在工程上，网页上的文字一般是12px或14px 
4. 链接样式（a:hover)
5. 表格样式（细线表格border-collapse：collapse）
6. 边框样式（边框变红border：1px solid red）

## 五、CSS盒子模型
1. 与网页布局密切相关
2. 美工必须精通
3. 开发工程师要理解并会用
4. 两个重要：外边距margin，内边距padding；内外边距是相对的，
看站在哪一方来说。边距有4个方向：上下左右

## 六、登录网页
1. 用到了盒子模型（内部外部边距等）
2. HTML表单元素（用户名，密码，登录按钮）
   


# Lesson2-周二（7.13）

## 总结
  1.HTML只能做网页结构，大小写不区分，由浏览器执行
  2.开发重点：表单、表格、超链接、图片、列表、iframe等
  3. 要把2.写出来
  4.对开发人员的用途：做项目的界面

## 一、1HTML表格
```html
   <table></table>表格标记
   <tr></tr>表格行
   <td></td>表格列
  在<table>里放<tr>,在<tr>里放<td> 
  合并单元格<td colspan="2"></td>
```

## 二、HTML的超链接(*****)
1.链接可以到自己的网页，也可以是外部网站
2.语法
```html
   <a href=""></a>
```

## 三、HTML图片(*****)
1.语法
```html
   <img src="" width="" height="">
```
2.图片带链接
在超链接标记<a>中放入<img>

## 四、HTML列表
有序列表和无序列表
```html
 有序列表<ol></ol>  无序列表<ul></ul>  列表项<li></li>
```
 
 
## 五、标题
HTML共6级标题；从h1-h6

## 六、段落与块div
段落p：会自动换行
块div：会真的换行
span和label(不会自动换行)

## 七、HTML颜色
颜色表示两种：用颜色名；颜色的值（主要），是16进制，以#开头
颜色是由3种色调调配而成：RGB(red、green、blue)
- 

## 八、字符实体
面试题：HTML中的空格怎么表示？&nbsp;
-HTML是W3C的标准，但W3C不是强制标准，每个浏览器对它的支持
程度都不尽相同，而且HTML语法比较宽松。浏览器是执行网页代码的。

## 九、iframe框架（常用） 
<iframe src="" name="">

## 高频面试题：post和get有什么区别？
1.post方式提交表单，表单数据在地址栏不显示；
  get方式提交表单，数据会显示在地址栏上，不安全
  
2.post提交数据，数据大小不限；get一般为2k，一般用post。  


# Lesson1-周一（7.12）

## 问题总结
     对网页设计有了大概了解，但是因为首次接触，有很多不熟悉的方面。

## 一、markdown学习
1.Markdown是什么？
 写软件用的，软件工程师的标配。
 它有自己的语法，但非常简单。
 浏览器就能识别Markdown代码。
 
2.什么时候用？
写专业软件文档用；github或gitee上写文档用；
日常写笔记、总结或写书。
 
## 二、HTML介绍
1. HYML是什么？What
     叫做：超文本标记语言。 
  HTML代码由谁执行？浏览器。 主流的5大浏览器：
  Chrome、Firefox、Opera、Safari、Edge
        建议：从现在起停止使用360、qq等浏览器。
   
2. 为什么用它？
 要做Web项目，界面必须得用它。
 
3. 谁来用？
  后端开发人员一定要会、Web前段开发工程师、网页美工（UI）
  
4. 什么时候用？
  做项目需要的时候。
  
5. 用在哪里？
  网页上，搭建网页结构或元素。
 
6. 怎么用 ？
      按教程，在项目中实战使用。通过实际使用来学。

## 三、HTML标准
   HTML是由W3C制定的国际标准。W3C：国际万维网组织。
 最新版：HTML5
 
## 四、HTML表单的开发（*****）
1.表单怎么写？
```
<from ></form>
```
2.文本框怎么写？
```
<input type="text">
```
3.单项按钮怎么写？
```
<input type="radio" name="">
```
4.密码框怎么写？
```
<input type="password">
```
5.下拉选择怎么写？
```
<select>
<option>选项</option>
</select>
```
6.复位框怎么写？
```
<input type="checkbox">
```
7.文本域怎么写？
```
<textarea rows="行数" cols="列数">
    内容 
</textarea>
```   
8.上传文件怎么写？
```
<input type="file">
```
9.提交按钮怎么写？
```
<input type="submit" value="提交">
```
10. 重置按钮怎么写？
```
<input type="reset" value="重置">
```
11.如何跳转网页
```
<form action="所跳转的网页名称">
```

## 五、提醒
1. 不要背代码！！！通过多写，来永久记忆。
2. 学编程最佳方式：多写！！！一定要动手做！ （听不会，看不会）
3. 理解的基础上记忆，理解得越多，死记的越少！
4. 每日提交（和公司一样）

## 六、课后任务
写12306注册表单（不考虑效果和样式，只考虑元素）
