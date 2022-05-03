Git is a distributed version control system.
Git is free software.

2022.05.01
1. 开始复习 Git 。

2022.05.02
1. 管理修改学习。
2. git add 是将工作区的修改提交的暂存区。
3. git commit 是将暂存区的文件提交到版本库。
4. git diff HEAD -- <file_name> 工作区和版本库中最新版本之间的区别。

2022.05.03
1. git 管理/跟踪的是有效的改动，比如在这个目录下添加了别的文件，然后又删了，git 认为是没有改动的。
2. 添加远程仓库：
git remote add origin https://github.com/jtw-george/LearnGit.git
git push -u origin master
git push origin master