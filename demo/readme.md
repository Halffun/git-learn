1. 在Windows上安装Git
在Windows上使用Git，可以从Git官网直接下载安装程序，然后按默认选项安装即可。

安装完成后，在开始菜单里找到“Git”->“Git Bash”，蹦出一个类似命令行窗口的东西，就说明Git安装成功！
安装完成后，还需要最后一步设置，在命令行输入：

$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
2. 要随时掌握工作区的状态，使用git status命令。

如果git status告诉你有文件被修改过，用git diff可以查看修改内容。
3. git diff  与上次代码不同
git log     之前提交的次数详情      git log --pretty=oneline
HEAD 表示当前版本  HEAD^上一个版本
git reset --hard HEAD^  回到上个版本
git reflog  所有版本号 关机了也可以用
git checkout -b dev  创建分支
git branch 查看所有分支
git merge dev  把DEV分支上的代码合并到master上
git branch -d dev 删除dev分支
