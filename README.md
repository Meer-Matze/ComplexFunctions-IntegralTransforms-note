# 复变函数与积分变换笔记

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

个人复变函数与积分变换学习笔记，使用 LaTeX 编写，基于[现成的 LaTeX 模板](https://zhuanlan.zhihu.com/p/604236564)制作。仓库同时提供 LaTeX 源文件和编译后的 `main.pdf`，内容仍在持续整理和完善中。

## 内容概览

笔记从复数基础开始，逐步介绍复变函数、复积分、复级数和留数理论，最后讨论 Fourier 变换与 Laplace 变换。正文目前包含以下章节：

1. [复数与复变函数](chap1/chap.tex)
2. [解析函数](chap2/chap.tex)
3. [复积分](chap3/chap.tex)
4. [幂级数](chap4/chap.tex)
5. [洛朗级数与孤立奇点](chap5/chap.tex)
6. [留数及其应用](chap6/chap.tex)
7. [傅里叶变换](chap7/chap.tex)
8. [Laplace 变换](chap8/chap.tex)

各章包含定义、定理、例题和部分练习，具体完成度以源文件内容为准。

## 项目结构

```text
main.tex                    主文档入口
main.pdf                    编译后的笔记
chap1/ ... chap8/           各章节正文
config/                     LaTeX 模板、宏命令、定理环境与封面配置
```

主文档通过 `main.tex` 按顺序载入 8 个章节；章节文件也保留了独立编译所需的配置入口。

## 编译

项目使用 `ctexbook` 文档类，建议使用 XeLaTeX 编译。在仓库根目录执行：

```bash
xelatex main.tex
xelatex main.tex
```

重复编译一次可以更新目录和交叉引用。也可以使用 VS Code 的 LaTeX Workshop 等工具构建 `main.tex`。

## 参考资料

- 《复变函数与积分变换》（科学出版社）第三版
- 《复变函数习题精选精讲》（山东科学技术出版社）第一版

## 许可与素材

本项目采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可。

封面来源于[アシマ / Ashima](https://www.pixiv.net/users/2642047)的作品[Assembly](https://www.pixiv.net/artworks/147092236)。如有侵权请联系我删除。