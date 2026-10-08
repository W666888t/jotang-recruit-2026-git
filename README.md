# jotang-recruit-2026-git
糖工作室招新Git任务，记录Git学习笔记

## Git学习笔记
1. git config --global：全局配置用户名和邮箱，标记提交者身份——王俪曈
 Git 命令是一串分开的单词，空格用来分割命令里不同参数。
  git ：程序名
 config ：git 的子命令
 --global ：选项（全局配置）
  user.email ：配置项的名字
  "3570902241@qq.com" ：要设置的值
 👉 空格 = 分隔符，告诉 Git：这是独立的一段内容。
如果没有空格： user.email"3570902241@qq.com" 
Git 会把它当成一整个超长单词，它找不到叫  user.email"3570902241@qq.com"  的配置项，命令直接执行失败，不会等待输入。
2. git init：初始化本地git仓库
3. git add：将文件加入暂存区
4. git commit：提交暂存区内容到本地版本库，需要写清晰的提交说明
5. git log：查看全部提交历史记录
6. git clone：拉取远程仓库到本地
7. git remote add origin：关联本地仓库与远程GitHub仓库
8. git push：把本地提交上传到远程仓库