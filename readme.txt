关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
克隆一个本地库：git clone git@server-name:path/repo-name.git；