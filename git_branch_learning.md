# 本地Git仓库使用命令

- `open the new file and execute` `git init;`  `local new repository`
- `git add <filename>` `or` `git add .` `or` `git add *` `git commit -m "代码提交信息"`
- 添加到缓存区，实际提交改动描述提交到`HEAD`，未到`remote repository`
- `git push origin master`	推送到远程仓库
- `git diff <source_branch> <target_branch>`	合并前，下命令查看
- `git repository` 简单使用(适合使用过，用于回忆的)		
- `HEAD`、`pointer`、父节点、子节点
- `git commit;`	一次提交
- `git branch;` 建立分支(`after the branch`可以加分支名字)  `git branch -b branch` new分支并切过去
- `git branche -d`	delete分支
- `git checkout newImage;`(分支名字，切换到指定分支)  `git commit;`	(再提交)

# 远程仓库使用命令

- `git clone;` (仓库克隆url)选择一个文件夹，执行命令，联网克隆到本地；
- `comfirm` 继续
- `remote branch name` 命名规范
- `<remote name>/<branch name>` 远程仓库名称/分支名称
- 大多数开发人员将远程主机命名为`origin`
- `clone`的时候已经设置为origin
- `git checkout o/master;`  `git commit`
- 像上面直接提交会分离`HEAD`，`because`远程`repository`只有响应的分支`after the update`才会`update`；
- `git master;`  `git commit;`  `git checkout o/master;`   `git commit;`
- `git fetch`   实际将本地仓库中的远程分支update成了远程仓库相应分支最新`status`；
- `git fetch origin` `git reset --hard origin/master`  丢弃本地改动，获取服务器最新版并将本地分支指向它；
- `not update` 本地仓库状态，并不是本地与远程仓库同步，获取远程数据
- `Git detch`获取远程数据后，执行下面命令可以将远程分支new的提交，像合并本地分支一样，合并远程；
- `git cherry-pick o/master`   
- `git rebase o/master`
- `git merge o/master`    等等
- 先抓取后更新到本地，git提供了一个专门完成此两个操作`git pull;`
- `git fackTeamwork;`	可以指定提交的分支或数量  `git fakeTeamwork branch 3;` 提交3次记录到远程分支branch；

# 项目常用命令

- git branch 
- git clone
- git log --oneline --graph
- git checkout
- git branch -D
- git branch -add
- git push origin --delete 
- git branch -a   查看删除后分支们










