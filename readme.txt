git init 初始化版本库
git add [something] 添加文件到版本库
git commit -m "" 提交文件到版本库 -m 后面是提交的说明
git status 查看版本库当前状态
git diff  查看被修改的内容

git版本回退测试测试

git log 查看提交日志
git reflog 查看命令历史
git reset --hard commit_id 回到commt_id时的版本库
HEAD 指向当前版本  HEAD^指向上个版本,以此类推，HEAD~number 指向前number个版本

git checkout -- filename 将文件工作区的修改撤销
git reset HEAD filename 将添加到satage的修改取消，重回工作区

git rm filename 删除一个文件

git clone url(ssh/https) 将远程仓库直接克隆到本地

