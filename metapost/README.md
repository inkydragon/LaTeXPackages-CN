# metapost 大坑
文档基于
> MetaPost 1.9991 (TeX Live 2016/W32TeX) (kpathsea version 6.2.2)

## 需要翻译的内容
tutorial：
- mpintro.pdf - 13页 - [A Beginner’s Guide to METAPOST for Creating High-Quality Graphics](http://www.tug.org/docs/metapost/mpintro.pdf)


manual：
- mpman.pdf - 113页 -
[METAPOST a user’s manual](https://www.tug.org/docs/metapost/mpman.pdf)
- mpgraph.pdf - 17页 -
[Drawing Graphs with MetaPost](https://www.tug.org/docs/metapost/mpgraph.pdf)
- mpboxes.pdf - 9页 -
[Drawing Boxes with MetaPost](https://www.tug.org/docs/metapost/mpboxes.pdf)
- mplibapi.pdf - 30页 -
[MPlib API documentation](https://www.tug.org/docs/metapost/mplibapi.pdf)



## 编译
**需要 cgywin or 等效编译环境**
- manual  <- 需要texexec <- 需要[ruby](https://rubyinstaller.org/downloads/)
	然后根目录直接 `make pdf`
- tutorial 在我的电脑上 直接 `make pdf` 报错  
	把 Makefile 里面的 `pdflatex` 改为 `xelatex` 则可以正常编译

## 术语表
(不全是专业词汇啦)		
为保证兼容性 暂时用 Excel作为术语表 		
(对术语翻译有异议、非错误的，建议到[issue-MetaPost](https://github.com/latexstudio/LaTeXPackages-CN/issues/5)里提出，然后在修改，方便讨论

### 术语提取&术语表转换工具
[语帆术语宝](http://termbox.lingosail.com/console/extract)		
双语对照 –> 术语表
即从中英对照的整段翻译中提取词汇对照表，可在线保存 or 导出为 Excel(.xls)或(.tbx)

[在线对齐-Tmxmall](http://www.tmxmall.com/aligner)		
对齐后可导出为 .tmx \ .xlsx \ .txt

[下载 Microsoft 术语](https://www.microsoft.com/Language/zh-cn/Terminology.aspx)		
[zh_CN 简体中文词典 - StarDict Dictionaries – 星际译王词库 词典下载](http://download.huzheng.org/zh_CN/)
