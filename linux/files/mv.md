# mv
> move (rename) files
Linux mv命令用来为文件或目录改名、或将文件或目录移入其它位置。

----------------------------------
## 用法: 
```
mv [options] source dest
mv [options] source... directory
```
### OPTION 可选项 
> -i: 若指定目录已有同名文件，则先询问是否覆盖旧文件;
-f: 在mv操作要覆盖某已有的目标文件时不给任何指示;

mv参数设置与运行结果

|命令格式 |运行结果 |
|------
|mv 文件名 文件名|将源文件名改为目标文件
|mv 文件名 目录名|将文件移动到目标目录
|mv 目录名 目录名|目标目录已存在，将源目录移动到目标目录；目标目录不存在则改名
|mv 目录名 文件名|出错

--------------------------------
## 实例
将文件 aaa 更名为 bbb :
```
mv aaa bbb
```
将info目录放入logs目录中。注意，如果logs目录不存在，则该命令将info改名为logs。
```
mv info/ logs 
```
再如将/usr/student下的所有文件和目录移到当前目录下，命令行为：
```
$ mv /usr/student/*  . 
```
[Linux命令大全](http://www.runoob.com/linux/linux-command-manual.html "Linux命令大全")