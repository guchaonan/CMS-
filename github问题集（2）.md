# Github问题集（2）
## 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
new repository 新建仓库  
import repository 导入仓库  
new gist 新代码  
new organization 发起组织  
## 2.如何能将仓库中的html文件直接解析成页面？
Settings -> source 
## 3.如何删除仓库
settings -> delete this repository
## 4.Bash是什么操作系统的命令
linux
## 5.Pwd是什么命令
显示当前工作目录
## 6.Cd是什么命令
改变目录，如果不带参数，则回到主目录，带参数则切换到参数所指目录
## 7.Echo是什么命令
打印、输出
## 8.配置git用户名的命令
git config --global user.name""
## 9.配置邮箱的命令
git config --global user.email""
## 10.命令行换行方式
\
## 11.命令行终结方式
Ctrl+C

## 12.使用命令行比GUI方式有何优势
GUI操作简单，可视化窗口  
命令行写一个命令对应一个操作，可以对多个文件同时操作  
## 13.提交到本地仓库时为什么有暂存区
·workspace可能编辑多个文件，一个commit多个文件,回撤影响所有文件
## 14. 新建代码仓库的命令
git init
## 15. git clone [url] 这个命令的作用是
克隆仓库 远程仓库克隆到本地
## 16. 添加指定文件到暂存区的命令
git add
## 17. 删除工作区文件，并且将这次删除放入暂存区的命令
git rm
## 18. 改名文件，并且将这个改名文件放入暂存区的命令
git mv
## 19. 提交暂存区到仓库的命令
git commit -m
## 20. 直接从工作区提交到仓库的命令
git commit -a -m
## 21. 显示变更信息的命令
git status
## 22. 查看历史信息的命令
git log
## 23. Commit的意义是
提交信息
从暂存区提交到仓库
## 24. Pull的意义是
git pull 将远程仓库的提交拉下到本地
## 25. Push的意义是
git push [remote] [branch]
将本地的提交推送到远程仓库
