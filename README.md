# ACM-ICPC-problem-sheet-template

## 简介
这是一份ACM比赛出题需要打印版本的时候使用的模板，需要LaTeX和CTeX环境

现在放的是第七届ECNU Coder时我制作的打印版本

## 使用
main.tex为最终编译的文件，利用\input导入文件

为方便单独编译调试，可以利用template.tex为基础进行编码，文件可以独立编译，利用宏进行了防御，当全部导入到main.tex中后每个独立文件就会根据前后顺序自动标号
