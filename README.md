## vim 常用知识总结

1、在vim运行中，`:x` 和 `:wq` 是等价的，都是保存并退出的意思。

注: 这两个命令实际上并不完全等价，当文件被修改时两个命令时相同的。但如果未被修改，使用 `:x` 不会更改文件的修改时间，而使用 `:wq` 会改变文件的修改时间。

2、 使用vim修改host文件

    vim /etc/hosts

3、跳到上一个／下一个位置

当你编辑一个很大的文件时，经常要做的事是在某处进行修改，然后跳到另外一处。如果你想跳回之前修改的地方，使用命令:

	Ctrl+o

来回到之前修改的地方:

	Ctrl + i

4、vim 键盘

![vim 键盘](http://static.oschina.net/uploads/img/201508/19105004_eXTo.jpg)

5、键盘详解

* 基础

 命令                   | 表现                                  
 :---------------------| :-----------------------------------
 :e filename	         |Open filename for edition             
 :w	                   |Save file                             
 :q	                   |Exit Vim						            
 :!q			             |Quit without saving                   
 :x	                   |Write file (if changes has been made) and exit
 :save fileName        |Saves file as filename                  
