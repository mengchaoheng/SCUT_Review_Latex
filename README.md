# 华南理工大学研究生学位（毕业）论文文献综述LaTeX模板

模板参考了华南理工大学硕/博士课程论文。但根据`附件2：研究生学位（毕业）论文文献综述.docx`进行了改动，该附件非常反人类。也有同学根本不管给出的案例：

```
一、前言
说明写作目的意义；
介绍有关的概念；

```

而直接根据课程论文写，似乎也可以。

但这里还是按照附件修改了模板。

## 快速使用：

1. 写封面cover.docx，生成cover.pdf文件，然后

2. 编写自己的body.tex文件，编译main.tex即可.

封面（以及博士课程论文的最后一页）使用doc文件另存为cover.pdf后，在main.tex调用，编译main.tex即可生成论文pdf文件：main.pdf

编译之前首先安装[texlive](https://www.tug.org/texlive/)，找到对应系统（Linux，win，macOS）的版本。注意macOS是MacTeX。

编译有两种方法：

1.使用VSCode。设置参考`settings.json`，使用方法详情参考学位论文[讨论区](https://github.com/mengchaoheng/SCUT_thesis/discussions)。点击XeLaTeX选项编译。

2.使用TeXstudio，首次编译建议从主文件`main.tex`开始编译，首先在`TeXstudio的Options->Configure TeXstudio->build`中，编译器(Dufault Compiler)选择`XeLaTeX`，默认文献工具(Default Bibliography Tool)选`Biber`。

