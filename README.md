## Latex Template for UCAS Homework 

---

## 0x00 About
这个仓库是从[latex-homework-template](https://github.com/jdavis/latex-homework-template#adjustable-problem-numbers)修改而来的，目的是为了适用于国科大的作业。不过目前只改了封面的内容，后续会规范一下代码，增加新的功能（可以提ISSUE的好吧，欢迎给意见和建议）

## 0x01  Features
下面是关于这个模板的特点：
1. 封面

2. 支持大部分的数学公式以及有限状态机的图绘制

3. 问题的标题设置：

    ```latex
    \begin{homeworkProblem}
    \end{homeworkProblem}
    ```

    


## 0x02 demo
1. 封面

    ![](/images/README/1.png)

2. 问题示例

    ![](/images/README/2.png)

3. 自动机和伪代码问题

    ![](/images/README/3.png)

4. 统计方面的问题

    ![](/images/README/4.png)

5. 证明类的问题

    ![](/images/README/5.png)

6. 调整问题的序号

    ![](/images/README/6.png)


## 0x03  Installing
###  3.1 local
1. 安装Texlive（理解为语言环境），不要用CTex
2. 安装Texstudio（理解为IDE）

### 3.2  online
使用[Overleaf](https://www.overleaf.com/)。注册账号，然后把这个项目的文件夹上传即可

## 0x04 Usage
1. `homework.tex`中的是模板主要的框架，包括一些自定义变量(比如`\hmwkTitle`，`homeworkProblem`)的定义，还有对章节的引用：`\include{chapters/ch01}`
2. `image/`下存放图片，如果你想改成你们学校的作业模板，那么学校的logo就在`image/title`下存放着，替换掉即可，记得改一下`homework.tex`中引用的文件名哦~
3. `chapters/`下存放各个章节的内容

## 0x05 TODO
~~1. 规范代码~~


## 0x06 Feedback
邮件联系：`hzyhhh@foxmail.com` 或者直接提交Issue



## 0x07 License

Copyright (C) Huang Zhenyang (hzyhhh at foxmail dot com)

License: GNU General Public License, version 2