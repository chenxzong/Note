[TOC]

#1. 添加文件到本地库：
> 添加文件到本地库

`git add pome.txt` 

>提交本地库文件

`git commit -m "提交操作" --author='chen <870267706@qq.com>`

#2. git 配置文件级别
>优先级别
	1)文件夹中: .git->config 
		> 优先级最高
		> 只对当前文件夹起作用
	2)登陆账号:home/directory/.gitconfig 
	3)安装文件夹: C:\Home\study\Git\etc 

## 2.1 git cofnig 指令用法:

> 显示当前Git设置值

 `git config --system -l`
 `git conifg --global -l`
 `git config -l`

> 配置git文件

``` shell
    #文档库中配置文件
     git config user.name 'chen'
     git config user.email '870267706@qq.com'
    
    #登录账号的 home directory 中的.gitconfig 文件
     git config --global user.name 'chenxzong'
     git config --global user.email '870267706@qq.com'

    #安装文件夹中 etc/gitconfig 文件
     git config --system user.name 'chenpc'
     git config --system user.email '870267706@qq.com'
```

> 关于 git 指令的长选项"--" 和短选项"-"

 `git config -m  === git config --message='说明'`



# 3.使用github
> 配置秘钥:

```
  ssh-keygen
  ssh-keygen
  git clone https://github.com/chenxzong/Note.git
```
>gitHub 创建文档库

```  
  git add .
  git status
  git commit -m 'note'
  git push -u origin master
  #history
```


```git

  git init
  git add .
  git remote add origin https://github.com/chenxzong/Python.git
  git push -u origin master
  git remote add origin https://github.com/chenxzong/Python.git
  git remote -v //查看origin连接
  git remote rm origin
  git remote add origin https://github.com/chenxzong/Python.git
  git push -u origin master
  git add .
  git commit -m "update"
  git push -u origin master
  history

Multi-line Code
```













