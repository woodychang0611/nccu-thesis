政治大學碩博士論文 XeLaTeX 模版
==========


前言
----------
這份模板是從[交通大學碩博士論文 XeLaTeX 模版](https://github.com/Po-haoHuang/nctu-thesis) Fork 而來
，前身是 [tzhuan](http://github.com/tzhuan) 的
[臺灣大學碩博士論文 XeLaTeX 模板](https://github.com/tzhuan/ntu-thesis)。 <br>
最後則由 [walker088](https://github.com/Walker088) 在撰寫論文期間根據[政大圖書館](http://www.lib.nccu.edu.tw/thesis/download.html) 所提供的論文格式規範加以修改。


下載
----------
您可以直接 clone 這個 git repository，或者下載成 zip.

快速開始
----------
這份文件主要提供在 [overleaf](https://www.overleaf.com/) 上編輯撰寫，將這個 repo 下載成 zip 後就可以直接輸入 overleaf 順利編譯。

主要章節會在 ./chapter/ 資料夾裡面，可以自行新增。
章節順序請在 ./thesis.tex 內編排修改。

```
Note: 在 overleaf 上傳 zip file 後，
要點選右上角的齒輪將 latex engin 改成 Xelatex 
才可以順利通過編譯。 
```
詳細說明
----------
目前請先參考交大 [shaform](https://github.com/shaform) 所撰寫的 [wiki](https://github.com/shaform/ntu-thesis/wiki) 說明。


Changelog
----------
  * v1.0
    * The first fork release
    * Add Chinese support
    * Add NTU watermark & password protection
    * Add certification and spine .docx files
    * Add setup
    * Add hypertext links in the document
    * Adjust line spacing
  * v0.4
    * Rename \year, \month and \day to avoid the conflicts. Thanks to [shaform](https://github.com/shaform).
  * v0.3.1
    * Fix issue #2, thanks to [BachiLi](https://github.com/BachiLi).
  * v0.3
    * Fix issue #1, thanks to [simonxander](https://github.com/simonxander).
	* Set doublespacing by default, add singlespacing and onehalfspacing support.
	* Refine the cover page and the certification.
  * v0.2
    * Add proposal support
  * v0.1
    * The first release
