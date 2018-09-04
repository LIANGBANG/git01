1）登陆 GitHub，在右上角找到“Create a new repo”按钮，创建一个新的仓库 
2）在 Repository name 填入 learngit，其他保持默认设置，点击“Createrepository” 按钮，就成功地创建了一个新的 Git 仓库 
3）$ git remote add origin git@github:<your github address>，添加远程库， 名 字叫做 origin 
4）$ git push -u origin master，把本地库推送到远程库上。由于远程库是空的，我 们第一次推送 master 分支时，加上了-u 参数，Git 不但会把本地的 master 分支内容 推送的远程新的 master 分支，还会把本地的 master 分支和远程的 master 分支关联 起来，在以后的推送或者拉取时就可以简化命令
 5）以后提交只用写，$ git push origin master
 6）克隆远程库，$ git clone git@github.com:<your github programe address>.git
