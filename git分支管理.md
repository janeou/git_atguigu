### git分支管理

#### 分支操作

* 查看分支

  `git branch -v`

* 创建分支

  `git branch dev`

* 切换分支

  `git checkout dev`  

* 合并分支

  - 切换到被合并分支

    `git checkout master`

  - 执行merge

    `git merge dev`

#### git remote

[remote官方](https://git-scm.com/docs/git-remote)

+ 管理远程仓库链接地址

  `git remote add weChat https://github.com/janeou/weChat.git                    `    

#### git push

+ 推送本地库到github

​     `git push weChat master                                                        `    

#### git clone

+ 克隆远程仓库到本地

  git clone https://github.com/janeou/weChat.git

#### git pull

```
fetch+merge
git fetch 远程仓库地址 远程仓库分支
git merge 远程仓库地址/远程仓库分支
```

