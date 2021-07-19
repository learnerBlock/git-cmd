# git-cmd
git入门操作

1 linux 安装git
  命令行安装：yum install -y git
  源码安装：下载源码 解压文件

2 移除git:
  如果需要移除git, 命令：yum remove git
  
3 查看是否安装成功
  git --version
  
4 创建repository
  git init
  成功后会产生.git文件 类似 .svn文件 作为后续版本对比基础信息

5 执行crud操作(类似svn操作 包括add update checkout reverse merge commit)
  进入仓库(路径或子路径) cd 
  创建文件  vim a.txt
  添加文件 git add a.txt (提交时需要在文件所在路径 pwd查看路径)
  提交文件 git commit -m '评论内容'
