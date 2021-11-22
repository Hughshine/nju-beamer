# NJU Beamer Theme

在[这个模板](https://github.com/Trinkle23897/THU-Beamer-Theme)基础上做了简单调整：

1. 颜色等转换与南京大学匹配
2. 中文正文一致使用楷体，对于非正文部分文字（比如表头），需要在其中使用`\kaishu`

目前使用默认的英文数字的字体。如果使用Roman字体，需在正文使用`textrm{...}`。该设置未加入模板文件之中。

编译流程：xe -> bibtex(不是biber) -> xe -> xe

推荐环境配置：vscode + latex workshop + texlive2020. 

比较简陋，欢迎更新
