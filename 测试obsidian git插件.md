### 进入终端命令行



##### 1、cd 路径
//注释：路径为当前obsidian库所在位置

##### 2、git init
//注释：在当前目录中创建git仓库

##### 3、git add .
//注释：将需要提交的文件放到暂存区：

##### 4、git status
//注释：查看git状态

##### 5、git commit-m '注释'
//注释：提交代码到暂存区

##### 6、git remote add origin url
//注释：关联到远程版本库，origin：obsidian库名，url：git@github.com:zjy-spec/obsidian_share_git.git

##### 7、git push origin master
//注释：推送到远程版本库，origin：obsidian库名

##### 8、git tag -a '版本' -m '描述'
//注释：打标签

##### 9、git push --tags
//注释：提交标签

##### 10、git branch --set-upstream-to=origin/remote_branch  local_branch