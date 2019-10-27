# first-repository
my first repository create in 9-17

## git常用命令

- git config --global user.email 邮箱
- git config --global user.name 用户名
- git clone 仓库地址
- git add 文件路径
- git commit -m '提交描述信息'
- git add .     //将工作区中所有的文件提交到暂存区
- git status    //查看工作区的状态
- git checkout -- 文件路径      //撤销工作区修改，撤销文件到最近一次提交（跟编辑器中的ctrl z 类似）
- git reset head 文件目录       //暂存区文件撤销，将文件从暂存区踢出
- git log       //查看仓库中commit的版本
- git reflog        //映射查看仓库中commit的版本（更好看点儿）
- git reset --hard head^        //回退一个版本，一个尖角号表示一个版本
- git reset --hard head~2       //指定回退几个版本
- git reset --hard 版本号       //回退到指定版本，通过git reflog查看版本号
- git rebase -i head~3      //（变基）进入交互式界面，将最近三次提交的版本合并


### 版本回退
- git reset --(soft|mixed|hard) <head~number> | <版本号>
    - --hard 回退全部，包括head, index, working tree
    - --mixed (默认)回退部分，包括head，index
    - --soft 只回退head

## 将文件添加到暂存区

- git add .files

- test

- test2

- test3

- asfasfasfdasdfadfaf