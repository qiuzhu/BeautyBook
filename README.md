# BeautyBook 说明

## 模板来源
来自网上2014年的ElegantBook。本次修改主要设计移除废弃宏包，修正首行缩进，测试Adobe公司最新发布的思源宋体
## 编译环境 

- 使用 XeLatex编译，本模板已经在TexLive 2016编译通过，Ubuntu 16.04 和Windows均可
- 程序中正文使用了Adobe 思源宋体，需要下载

## 程序中使用的字体代码（需要修改的自行修改）

需要修改的自行修改
```latex
\RequirePackage{xeCJK}
\setCJKmainfont{思源宋体}%使用Adobe 思源黑体
\setCJKsansfont{思源宋体}
\setCJKmonofont{思源宋体} %全部使用Adobe 思源黑体
\XeTeXlinebreaklocale "zh"
\XeTeXlinebreakskip = 0pt plus 1pt

\setCJKfamilyfont{new}{Adobe Kaiti Std}  %普通都没这种字体，换掉Adobe系列
\setCJKfamilyfont{note}{思源宋体}
\newfontfamily\gara{Adobe Garamond Pro}  %免费字体
```

# 字体的问题，fontspec的英文字体系统特征需要指定