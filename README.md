# tar
tar instruction review

tar -[指令]  [檔案名]
 
指令	說明

-c	建立新 .tar 檔案（create）

-x	解壓 .tar 檔案（extract）

-v	顯示處理過的檔案名（verbose）

-f	指定檔案名稱（file）

-z	使用 gzip 壓縮（.tar.gz）

-j	使用 bzip2 壓縮（.tar.bz2）

-J	使用 xz 壓縮（.tar.xz）

-C	指定解壓目錄（change directory）


用法	說明

tar -cvf archive.tar folder/	建立 archive.tar 檔案，打包 folder/

tar -czvf archive.tar.gz folder/	建立 .tar.gz 壓縮檔

tar -xvf archive.tar	解壓 .tar 檔案

tar -xzvf archive.tar.gz	解壓 .tar.gz 壓縮檔

tar -xvf archive.tar -C /path/to/dir	解壓到指定資料夾

tar -tvf archive.tar	查看 .tar 內容但不解壓

