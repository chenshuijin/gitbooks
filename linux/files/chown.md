# chown
> change file owner and group
Linux/Unix 是多人多工操作系统，所有的文件皆有拥有者。利用 chown 将指定文件的拥有者改为指定的用户或组，用户可以是用户名或者用户ID；组可以是组名或者组ID；文件是以空格分开的要改变权限的文件列表，支持通配符。 。
一般来说，这个指令只有是由系统管理者(root)所使用，一般使用者没有权限可以改变别人的文件拥有者，也没有权限可以自己的文件拥有者改设为别人。只有系统管理者(root)才有这样的权限。

----------------------------------
## 用法: 
```
chown [OPTION]... [OWNER][:[GROUP]] FILE...
chown [OPTION]... --reference=RFILE FILE...
```
### OPTION 可选项 
> owner : 新的文件拥有者的使用者 ID
group : 新的文件拥有者的使用者群体(group)
-c : 若该文件拥有者确实已经更改，才显示其更改动作
-f : 若该文件拥有者无法被更改也不要显示错误讯息
-h : 只对于连结(link)进行变更，而非该 link 真正指向的文件
-v : 显示拥有者变更的详细资料
-R : 对目前目录下的所有文件与子目录进行相同的拥有者变更(即以递回的方式逐个变更)
--help : 显示辅助说明
--version : 显示版本


--------------------------------
## 实例
将文件 file1.txt 的拥有者设为 users 群体的使用者 jessie :
```
chown jessie:users file1.txt
```
将目前目录下的所有文件与子目录的拥有者都改为 users 群体的使用者 lamport :
```
chown -R lamport:users *
```
[Linux命令大全](http://www.runoob.com/linux/linux-command-manual.html "Linux命令大全")