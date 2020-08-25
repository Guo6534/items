## git实操

# 本地新仓库推送至远端GIT仓库

* pwd      // 查看当前目录

* git init // 在需要的目录下创建仓库 （不建议在中文目录下）

* git add <filename> // 添加文件到暂存区 可以多次添加不同的文件

* git commit -m // 提交代码到 HEAD

* git remote add origin <远端地址> // 添加(连接)远端仓库（需要登录）

* git push origin master // 推送代码至远端仓库

* git status // 查看更改状态

* git diff // 查看文件更改内容

# 从远端克隆（clone）仓库后推送

* git clone <远端地址>

* git add <filename> // 添加文件到暂存区 可以多次添加不同的文件

* git commit -m // 提交代码到 HEAD

* git push origin master // 推送代码至远端仓库

# 分支（branch）

* git checkout -b yx // 创建一个yx分支 并切换至yx

* git checkout master // 切换至master分支

* git branch -d yx // 删除yx分支

* git push origin yx // 推送分支至远端（若未推送分支到远端，分支在远端并不可见）

# 拉取（pull）

* git pull origin yx // 拉取yx分支

# 合并（merge）

* git merge master  // 将master分支合并到当前分支

# 冲突（conflicts）

* git add <filename> // 解决冲突后 将它们标记为合并成功

# 记录（log）

* git log // 获取推送记录