Typora使用教程

[TOC]

## 一，相关介绍

1. Typora是基于*MarkDown语法*的一款轻便简洁的编辑器，设计简洁，便于使用，现阶段为免费开源。

2. 现阶段支持的平台有window，linux，os x三个主流平台

   ---

   

##二，语法教程

### 1，标题使用

Typora支持1~6级标题的使用，类似于HTML语言，有大致两种方式

首先是标记语言的方式：

```c
因不便于演示，利用代码块编写
#这是1级标题
##这是2级标题
###这是3级标题
####这是4级标题
#####这是5级标题
######这是6级标题
总结格式：[井号]+[字符]+[enter]
    根据井号的增加，变得越来越不重要，或者说越来越细
```

第二种是快捷键的方式：

ctrl + 1  ----------------   这是1级标题（以此类推）

格式：[ctrl + 数字]

***

### 2，字体使用

```c
加粗：将加粗的文字左右分别用两个*号包起来
斜体：将要倾斜的文字左右分别用一个*号包起来
斜体加粗：将既要斜体又要加粗的文字左右分别用三个*号包起来
删除线：将要加删除线的文字分别用两个~~号包起来
```

演示：（附上快捷键）

1. **加粗**                             ctrl + B
2. *斜体*                             ctrl + L  
3. ***加粗斜体***                      
4. ~~删除线~~

***

### 3，引用

在引用的文字前加>，引用也可以嵌套，如加两个>>三个>>> n个

such as：

> 这是个引用
>
> > 这也是个引用
> >
> > > 无线嵌套引用。。。

按下方向键可退出

***

### 4，分割线

```c
有三种方式，都是连续三个或三个以上连续符号
    ---
    ***
    ******
```



---

### 5，图片

格式：![图片alt]()

图片alt为图片下面的解释文字，选定图片地址后可在后面加”title“，效果为鼠标移动到文字后显示的内容。

---

### 6，超链接

格式：

```c
[超链接名](超链接地址"title")
```

”title“可省略

such as:

[百度](www.baidu.com)

---

### 7，代码块

```c
格式：```+所需语言
such as：
    ```c
    ```java
关于代码块的序号可以在文件设置里进行设置
```

---

### 8，列表

```c
无序列表：
- 列表内容
+ 列表内容
* 列表内容
注意：- + * 跟内容之间要有一个空格
```

such as:

- 这是一个无序列表

```c
有序列表
1. 列表内容
格式：数字+.+空格+内容
    按回车可自动填充换行
```

列表嵌套，在一级列表下方敲三个空格

* 一级
* * 二级

---

### 9，表格

```c
标题|标题|标题
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割标题和内容
-有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
```

以上方式都太麻烦了，直接鼠标右键创建即可

such：

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

---

### 10，任务列表

```c
格式：*[]
```

* [ ] {无序列表*+[此处需要空格]此处也需要空格}

---

### 11，常用快捷键方式

```c
加粗：ctrl + B
选中相同格式的文字：Ctrl + E
返回Typora顶部：Ctrl + Home
返回Typora底部：Ctrl + End
下划线：Ctrl + U
字体倾斜：Ctrl + I
搜索：Ctrl + F
查找和替换：ctrl + H
插入或创建链接：Ctrl + K
公式块：Ctrl + Shift + M
引用：Ctrl + Shift + Q
选中某句话：Ctrl + L
选中某个单词：Ctrl + D
选中所有：Ctrl + A
```

---

## 三，其它

此外Typora还具有其它功能，如导出为HTML等

同样Typora作为文本编辑器支持HTML标签等功能

简单的做笔记，掌握基础的MarkDown语法即可
