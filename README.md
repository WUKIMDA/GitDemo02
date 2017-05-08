# GitDemo02
Demo02
* 新建代码库
	* git init (在当前目录新建一个Git代码库)
	* git init [project-name] (新建一个目录，将其初始化为Git代码库)
	* git clone [url] (下载一个项目和它的整个代码历史)
* 增加文件
	* git add [file1] [file2] ...(添加指定文件到暂存区)
	* git add . 添加当前目录的所有文件到暂存区
* 提交代码
	* git commit -m [message] (提交暂存区到仓库区)
	* git commit [file1] [file2] ... -m [message] (提交暂存区的指定文件到仓库区)
	* git commit -a (提交工作区自上次commit之后的变化，直接到仓库区)
* 分支(在一个分支上提交代码不会影响其分支的代码)
	* git branch (列出所有本地分支)
	* git branch -r (列出所有远程分支)
	* git branch [branch-name] （新建一个分支，但依然停留在当前分支）
	* git checkout -b [branch] （新建一个分支，并切换到该分支）
	* git checkout [branch-name] （切换到指定分支）
* 查看信息
	* git status（显示有变更的文件）
	* git log （显示当前分支的版本历史）
	* git log -3 (显示过去3次提交)
* 远程同步
	* git fetch [remote] ( 下载远程仓库的所有变动)
	* git remote add [remote] [url]（增加一个新的远程仓库，并命名）
	* git pull [remote] [branch] (取回远程仓库的变化，并与本地分支合并)
	* git push [remote] [branch] (上传本地指定分支到远程仓库)
