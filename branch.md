# git分支操作

+ git checkout -b <name> **创建并切换到该分支上**
+ git checkout <name> **切换分支**
+ git branch **查看所有分支**
+ git branch <name> **创建分支**
+ git branch -d <name> **删除分支**
+ git merge <name> **合并某分支到当前分支**

*git鼓励使用大量分支*

~~git 分支操作测试~~

---

# 解决冲突

+ git log --graph 查看git分支合并图

+ 解决冲突
   1. 手动修改冲突内容
   2. 提交


~~解决冲突测试~~

# 分支管理策略

git 默认使用**Fast Forward**模式合并分区,这样会丢失分区信息  
在合并分支时使用 --no-ff 参数禁用**Fasr Forward**,在提交时会创建新的commit，就可以看到分支信息  

~~--no-ff命令测试 ~~