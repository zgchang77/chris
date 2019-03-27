//生成公钥和私钥  创建SSH key
ssh-keygen  -t  rsa  -C "zgchang@126.com"
//查看获取
ssh-rsa

//参数配置  设置签名
git config --global user.name  "常"
git config --global user.email  "zg@126.com"

//查看状态，查看工作区、暂存区状态
git status


//到登陆界面  将本地内容推送到github中
git push  origin master

//下载   把仓库拉动到本地
git clone http://gitee.com/zgchang/chris.git

//初始化这个目录为仓库
git init

//把文件添加到暂存区
git add readme.txt 

//把文件提交给仓库
git commit -m  “My First Commit” test.txt

//查看提交的信息
git log
//查看提交的记录
git log --pretty=oneline
//查看日志记录
git reflog



//增加远程地址别名
git remote add [别名] [远程地址]
git remote add origin https://github.com/zgchang77/chris.git
//查看当前所有远程地址别名
git remote -v



//创建分支git branch [分支名]
git branch hot_fix
//查看分支
git branch -v
//切换分支
git checkout hot_fix
//查看之前的内容
ll
//合并分支 git merge [有新内容的分支名]

//可以查看隐藏的目录
ls -la


//上传
1、把当前目录下，发生变化的文件添加到暂存区
     git  add .
2、注释
     git commit -m "本次提交的注释"
3、把项目推送到网上
     git push 
