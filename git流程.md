### git 流程

+ 工作区  -------》  暂存区   ------》 本地仓库  -------》 远程仓库

  

#### 文件的四种工作状态

+ **Untracked** : 文件还没有加入到 git 仓库，还没有参与版本控制，即未跟踪状态，这个时候文件，通过 **git add** ，可以变为 Staged 状态
+ **Unmodified**: 文件已经加入 git 库，但是还没有被修改，就是说版本库文件的内容与文件夹种中还完全一致
+ **Modified**： 文件被修改了，就进入 modified 状态了，文件这个状态通过 **stage** 命令可以进入**staged** 状态
+ **staged**： 暂存状态，执行 **git commit** 则将修改同步到库中，这是库中的文件和本地文件又变为一致



### git 的基本命令                              

+ git init                                             初始化状态        

+ git add                                            添加到本地仓库          

+ git commit  -m  '输入信息'           提交到本地仓库

+ git log                                              查看版本 

+ git diff                                             查看修改内容

+ git status                                        查看状态

+ git reset  --hard^                           返回上一版本

+ git reset  --hard  指定版本id        返回指定版本

+ git reflog                                        查看切换版本的过程

+ git restore   xxx文件                     撤销文件的修改 **只能修改未被放入暂存区的文件**

+ git rm 指定文件                             删除指定文件

+ git clone                                         克隆代码

+ git push                                          推送到远程仓库

+ git pull / git fetch                           拉取远程仓库数据

+ git checkout -b dev                        创建并切换分支

+ git branch 分支名称                       创建分支

+ git branch -d 分支名称                   删除分支

+ git checkout 分支名称                    切换分支

+ git merge 分支名称                         合并分支

+ git stash                                            保存分支

+ git stash list                                       保存分支列表

+ git stash apply                                  恢复分支

     

  

 