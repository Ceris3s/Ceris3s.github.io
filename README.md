# Cerises.github.io







## git

要关联一个远程库，使用命令`git remote add origin git@server-name:path/repo-name.git`；

关联一个远程库时必须给远程库指定一个名字，`origin`是默认习惯命名；

关联后，使用命令`git push -u origin master`第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令`git push origin master`推送最新修改；

https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440

如果用git@关联，要手动添加一个ssh公钥，参考https://blog.csdn.net/u013778905/article/details/83501204

