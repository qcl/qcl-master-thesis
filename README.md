qcl's master thesis
=======

## About the template

This is copy from @tzhuan 's [臺灣大學碩博士論文 XeLaTeX 模板](https://github.com/tzhuan/ntu-thesis). 
And copy some part of [台大碩博士論文LaTeX範本](https://code.google.com/p/ntu-thesis-latex-template/).
Thanks @cwahbong tolds me how to use pdftk.

## How to compile
### Ubuntu

* 安裝XeLaTex
    * sudo apt-get install texlive texlive-xetex texlive-latex-recommended texlive-latex-extra texlive-bibtex-extra texlive-science pdftk
* 安裝字形（標楷體、Times New Roman）
    * sudo mkdir -p /usr/share/fonts/truetype/win/ 
    * sudo cp [WINDOWS]/Windows/Fonts/kaiu.ttf /usr/share/fonts/truetype/win/
    * sudo cp [WINDOWS]/Windows/Fonts/times\*.ttf /usr/share/fonts/truetype/win/
    * fc-cache
    * fc-list //for check
* 編譯
    * make
* 編譯送圖書館版本（加上浮水印、保全）
    * make ntulib

### Mac OS

* 安裝[MacTEX](https://tug.org/mactex/)
* 安裝[PDFtk](http://www.pdflabs.com/tools/pdftk-server/)
* 編譯
    * make
* 編譯送圖書館版本（加上浮水印、保全）
    * make ntulib

### Windows

* 安裝[Cygwin](https://cygwin.com/)
* 安裝Cygwin套件 make texlive texlive-collection-xetex texlive-collection-latexrecommended texlive-collection-latexextra texlive-collection-bibtexextra texlive-collection-science texlive-collection-fontsrecommended pdftk
* 開啟Cygwin Terminal
* 安裝字形（標楷體、Times New Roman）
    * ln -s /cygdrive/[WINDOWS]/Windows/Fonts/ /usr/share/fonts/win
    * fc-cache
    * fc-list //for check
* 編譯
    * make
* 編譯送圖書館版本（加上浮水印、保全）
    * make ntulib

## Result

* Please checout `release` branch, thanks.
