qcl's master thesis
=======

## About the template

This is copy from @tzhuan 's [臺灣大學碩博士論文 XeLaTeX 模板](https://github.com/tzhuan/ntu-thesis).

## How to compile
### Ubuntu

* 安裝XeLaTex
    * sudo apt-get install texlive texlive-xetex texlive-latex-recommended texlive-latex-extra texlive-bibtex-extra texlive-science
* 安裝字形（標楷體、Times New Roman）
    * sudo mkdir -p /usr/share/fonts/truetype/win/ 
    * sudo cp [WINDOWS]/Windows/Fonts/kaiu.ttf /usr/share/truetype/win/
    * sudo cp [WINDOWS]/Windows/Fonts/times\*.ttf /usr/share/truetype/win/
    * fc-cache
    * fc-list //for check
* 編譯
    * make

### Mac OS

* 安裝[MacTEX](https://tug.org/mactex/)
* 編譯
    * make

### Windows

* 留下字形檔案，下載[Ubuntu](http://www.ubuntu.com/)並安裝或找一台[蘋果電腦](http://www.apple.com/tw/mac/)。

