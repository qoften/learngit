Git is a version control system.
Git is free software.

# git add 提交前需将git cd至文档所在目录下

# 为什么Git添加文件需要add，commit一共两步呢？
#因为commit可以一次提交很多文件，所以你可以多次add不同的文件，
比如：

$ git add file1.txt
$ git add file2.txt file3.txt
$ git commit -m "add 3 files."