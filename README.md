# uemacs-tw

uemacs 中文可用版

X3BL 研究室 https://hack-news.ols3.net/

+ 中日文支援
+ 支援在 OpenBSD 中也可以編譯執行
+ 使 HOME/END/Delete 三鍵有相對應的功用
+ 引用 Linux Tovalds 的 patch: https://github.com/ols3er/uemacs-tw/blob/main/util.c

安裝法:
- git clone https://github.com/ols3er/uemacs-tw.git
- cd uemacs-tw
- make
- sudo make install

執行:
- em sample.c 

------
已知問題:
1. 中文列太長時, wrap 的游標移動有 bug.
