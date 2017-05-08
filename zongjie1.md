# Markdown 总结
### 1.Markdown是什么？ 

Markdown 是一种轻量级标记语言 
 
### 2.Markdown的特点？
 * 纯文本内容，兼容所有文本编辑器与字处理软件
 * 可以放到版本管理系统中，汇总历史
 *轻松的倒出HTML，PDF和本身的 .md文件
 * 简洁、高效、可读、直观、学习成本低
 * 专注你的文本内容而不是排版样式
### 3.Markdown的用途？
 写日志，技术文稿，记录代码片段，撰写文稿
### 4.Markdown的编辑工具有哪些？
百度脑图，有道云笔记，github
### 5.Markdown的区块元素和区段元素分别包含哪些？
* 区块元素：段落和换行，标题，区块引用，列表，代码区块，分割线；
* 区段元素：链接，强调，代码，图片
# github(一)
### 1.github是什么？
  github 是IT技术人员的社交网站,是一个面向开源及私有软件项目的托管平台

### 2.git是什么？
  Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。可以有效、高速的处理从很小到非常大的项目版本管理。

### 3.github的好处？
  第一个好处就是版本控制，第二个就是作为开源代码库，

### 4.github的优势？
优势：只支持Git 完整协议支持 在线文件编辑 社交网络元素 特色工作模式私有仓库托管 Ruby on Rails

### 5.通过GitHub年度报告让你记忆最深刻的信息有哪些？
 报告中列出了最受欢迎的编程语言，排在前列的有javascript、java、python、ruby、php等一系列语言；
 2016年对开元贡献最多的是微软；
 中国作为增长用户最多的国家

### 6.github上有可以个人账号 还可以有（ ）账号？
  组织

### 7.github上面的两个组成要素是什么？
  个人、仓库

### 8.github上两个重要页面？
  个人主页与数字仪表板

### 9.主页菜单都包含什么？
  overview,repositories,stars,followers,following

### 10.仓库的心跳线代表什么？
  代表该用户在该项目的活跃程度

### 11.star的作用是？
  关注别人项目更新，具有收藏项目的功能

### 12.fork的作用是？
  克隆别人的代码库到自己的项目中，也可以参与到自己感兴趣的项目中

### 13.watch的作用是？
  设置接受邮件提醒

### 14.搜索结果分别有哪些类别？
  repositories,code,commits,lssues,wikis,users

### 15.你在github上挖到什么宝？
  在github中可以了解到很多IT行业中的大咖人物，关注他们的项目更新，star他们的项目 
# github（二）
### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
  New repository、Import repository、New gist、New organization
  新的仓库、导入库、新的依据、新的组织
### 2.如何能将仓库中的html文件直接解析成页面？
  Page链接
### 3.如何删除仓库？
  点击：Delete this repository
### 4.Bash是什么操作系统的命令
  shell的内建命令，又叫内部命令。linux系统命令
### 5.Pwd是什么命令？
  查询当前目录
### 6.Cd是什么命令？
  改变目录
### 7.Echo是什么命令？
  打印输出
### 8.配置git用户名的命令
  git config --global user.name "youname"
### 9.配置邮箱的命令
  git config --global user.email "youeamil@email.com"
### 10.命令行换行方式
   git config core.autocrlf命令用来改变Git换行处理的方式，该命令需要一个独立参数。
   在Windows上，仅仅需要设置ture，例如git config --global core.autocrlf true
### 11.命令行终结方式
   Ctrl+c
### 12.使用命令行比GUI方式有何优势？
   对于许多管理任务来说，使用命令行比图形界面还更简单,
     一是错误提示非常详细，详细到你知道错哪了，正确的用法是什么，一来二去很快就能熟悉
     二是写自动化脚本的时候，只能用命令行啊，比如自动测试和部署脚本，无论是shell脚本还是py脚本，GUI没法用的
### 13.提交到本地仓库时为什么有暂存区
   将工作区和commit仓库操作之间做了一个缓冲。即可以对代码进行版本的管理，又避免了多次琐碎的commit提交。
### 14.新建代码仓库的命令
   Git init
### 15.git clone [url] 这个命令的作用是？
   远程仓库克隆
### 16.添加指定文件到暂存区的命令
   Git add[file1][file2]
### 17.删除工作区文件，并且将这次删除放入暂存区的命令
   Git rm[file1][file2]
### 18.改名文件，并且将这个改名文件放入暂存区的命令
   Git mv[file1][file2]
### 19.提交暂存区到仓库的命令
   Git commit-m[message]
### 20.直接从工作区提交到仓库的命令
   Git commit-a -m[message]
### 21.显示变更信息的命令
   Git status
### 22.查看历史信息的命令
   Git log
### 23.Commit的意义是？
   提交当前工作空间的修改内容
### 24.Pull的意义是？
   是将代码从远程仓库同步至本地仓库并merge的命令
### 25.Push的意义是？
   push本地git至github远程仓库
