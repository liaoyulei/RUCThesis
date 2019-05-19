# RUCThesis  
## 中国人民大学LaTeX论文模板

此模板主要提供中国人民大学数学学院本科生使用。硕博建议直接使用原作者ZebinWang开发的[ructhesis](https://github.com/ZebinWang/ructhesis)。

**请直接使用ructhesis.cls文件。**  
**目前的版本使用了[2015国标](https://github.com/ustctug/gbt-7714-2015)的参考文献样式。**   
建议使用[TeX Live](http://www.tug.org/texlive/)，其自带编辑器TeXworks，或者自行安装编辑器[TeXstudio](http://texstudio.sourceforge.net/)。依次按照`XeLaTeX-BibTeX-XeLaTeX-XeLaTeX`的顺序编译main.tex。

## 重要信息  
**1、编辑器要用UTF-8的编码要不然你打开是乱码。**  
**2、排版引擎使用XeLaTeX，要不然会报错。**  
**3、慎重使用CTEX，大概率无法编译。**
**4、请使用`print.tex`将单面和双面打印部分分离. 直接在打印机上选择页码会出错.**


### 必要的字体文件，可以在[这里](https://pan.baidu.com/s/1eRFJXnW)下载。

字体 | PostScript名称 
------------ | ------------- 
Times New Roman | TimesNewRomanPSMT  
Arial | ArialMT
Courier New | CourierNewPSMT
宋体 | SimSun
黑体 | SimHei
仿宋 | FangSong

### 必要的宏包

**全部都是TeX Live自带的**
- ctexbook
- geometry
- hyperref
- graphicx
- titletoc
- ifxetex
- ifthen
- calc
- lscape
- multicol
- color
- pstricks

