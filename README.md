# GIT

# git是什么?
版本控制的工具,分布式.
git 是版本控制软件，目前最先进最流行的
github 是一个网站，用于广大开发者开源自己的代码，也提供私有仓库的付费功能，而它采用的版本控制软件就是git

# 目标
基本会使用git.


# 下载地址
[下载地址](https://git-scm.com/download/win)

# 版本控制的官网

国外的github https://github.com
国内码云 https://gitee.com


# 基本使用
    1.初始化版本库
 
    git init .
    
    2. 添加文件到暂存区

    git add .

    3. 提交到版本库

    git commit -m"版本的备注,越详细越好"

    4. 查看日志
    
    git log

    5. 查看当前工作区的状态

    git status

# 把代码推导远端的服务器

    6. 添加远端仓库源
  
    git remote add gitee https://gitee.com/pjkui/learn_git.git

    git remote add github ttps://github.com/SuperQQGroup/learn_git

    7.推送到仓库记录远端

    git push gitee //推送本地仓库到gitee

    git push github //推送本地仓库到github
