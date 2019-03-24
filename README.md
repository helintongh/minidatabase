# minidatabase
代码运行
Linux（Ubuntu，CentOS测试可行）
编译源码：clang minidatabase.c -o database
运行：./database minidb.db    (注：生成的.db随便取名字)

MAC OS
编译源码：gcc minidatabase.c -o database
运行：./database minidb.db

可支持语句有：
db > insert 1 agh hlt
Executed.
db > insert 2 cc ccc
Executed.
db > select
(1, agh, hlt)
(2, cc, ccc)
Executed.
db > .exit

仅支持三种命令：1.插入，2.select，select在这个数据库中是显示所有表的作用，3.是.exit是退出的命令

[从零写一个数据库详细的教程](https://zhuanlan.zhihu.com/c_1092493324325388288)


