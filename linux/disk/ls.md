# ls 
> list directory contents
Linux ls命令用于显示指定工作目录下之内容（列出目前工作目录所含之文件及子目录)。

----------------------------------
## 用法: 
```
ls [OPTION]...   [FILE]...
```
列出 FILE 的信息，默认是当前目录（即 .）
### OPTION 可选项
> 
-a 显示所有文件及目录 (ls内定将文件名或目录名称开头为"."的视为隐藏档，不会列出)
-l 除文件名称外，亦将文件型态、权限、拥有者、文件大小等资讯详细列出
-r 将文件以相反次序显示(原定依英文字母次序)
-t 将文件依建立时间之先后次序列出
-A 同 -a ，但不列出 "." (目前目录) 及 ".." (父目录)
-F 在列出的文件名称后加一符号；例如可执行档则加 "*", 目录则加 "/"
-R 若目录下有文件，则以下之文件亦皆依序列出

------------------------------------------------------
## 例子
使用举例
```
ls
bin               dev   lib         media  net   root     srv  upload  www
boot              etc   lib64       misc   opt   sbin     sys  usr
home  lost+found  mnt    proc  selinux  tmp  var
```
```
ls -a
.  ..  bin  games  include  lib  lib32  libx32  local  sbin  share  src
```
```
ls -al
total 112
drwxr-xr-x  12 root root  4096 Dec 23  2015 .
drwxr-xr-x  26 root root  4096 Sep 20 10:52 ..
drwxr-xr-x   2 root root 36864 Sep 14 15:50 bin
drwxr-xr-x   2 root root  4096 Sep 14 15:53 games
drwxr-xr-x  44 root root 20480 Aug 23 15:13 include
drwxr-xr-x  82 root root 12288 Aug 23 15:13 lib
drwxr-xr-x   3 root root  4096 Jul 18 08:54 lib32
drwxr-xr-x   3 root root  4096 Jul 18 08:54 libx32
drwxr-xr-x  14 root root  4096 Aug 23 11:44 local
drwxr-xr-x   2 root root 12288 Aug 23 15:12 sbin
drwxr-xr-x 153 root root  4096 Sep 14 15:50 share
drwxr-xr-x   6 root root  4096 Jul 18 09:07 src
```
[Linux命令大全](http://www.runoob.com/linux/linux-command-manual.html "Linux命令大全")