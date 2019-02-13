Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Creating a new branch is quick AND simple.

# git add 提交前需将git cd至文档所在目录下

# 为什么Git添加文件需要add，commit一共两步呢？
# 因为commit可以一次提交很多文件，所以你可以多次add不同的文件，
# 比如：
# $ git add file1.txt
# $ git add file2.txt file3.txt
# $ git commit -m "add 3 files."

# $ git add 文件添加，相当于将文件移至.git文件夹内的暂存区
# $ git commit 提交更改，即把暂存区所有内容提交至当前分支

# vi 模式
# 输入vi 进入vi的命令行模式（command mode），
# 稍等片刻后按字母【i】键切换至插入模式（Insert mode）
# 退出：先按【Esc】退至命令行模式，
    再按【Shift】+【；】即【：】键进入（Last line mode）（必须英文输入法下）
    最后输入【q】退出（输入【w】为保存）

# rm test.txt rm命令删除没用的文件 
