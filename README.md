# baidu_efe

成员  **庞威** **符伟** **代小鹤**  **冯振亚**  **张稳**

#git 常用操作命令    ----from 符伟




git status  查看当前状态  是否有修改东西
git -am ‘注释’ 从工作区直接提交到版本库
git log  查看提交历史  q键退出
git diff  对比  显示工作区和暂存区的差异对比
git diff --cached （或--staged这个写法）暂存区与版本区的对比
git diff master  工作区与版本库的对比
git reset HEAD 文件名   把暂存区的内容撤回到工作区
git checkout --文件名  回调文件
git checkout 版本号 文件名
git reset --hard 版本号  回调版本
gut reset --hard HEAD^ 回到过去的第一个版本
git reflog 显示所有版本提交操作记录
git branch 查看当前分支
gir branch 分支名  创建分支
git checkout -b 分支名  创建分支并且切换到新分支
git merge 分支名    合并分支
git branch --merged 查看master合并过的分支
git branch --no-merged  查看master没有合并过的分支
git branch -d 分支名 删除合并过的分支
git branch -D 强制删除分支
git commit -m '注释'--amend  把漏提交的再一起提交

删除
git rm '文件名'   工作区删除以后 （没有这个文件了）删除暂存区的文件
git rm -f 文件名   工作区和暂存区都有此文件 直接都删除文件   
git rm --cached 文件名  保留工作区文件

git remote 查看远程仓库名字  默认名字origin
git remote add 改名字
git remote -v 查看远程仓库地址
git push origin master 


git config --global user.name  查看当前用户
git config --global user.name '用户名'    更改用户
git config --global user.email "邮箱"




