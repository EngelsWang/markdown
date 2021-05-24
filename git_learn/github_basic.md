# 添加远程库
~~~
git remote add [shortname] [url]
~~~
## 生成SSH Key
~~~
$ ssh-keygen -t rsa -C "youremail@example.com"
~~~

后面的 your_email@youremail.com 改为你在 Github 上注册的邮箱，之后会要求确认路径和输入密码，我们这使用默认的一路回车就行。

成功的话会在 ~/ 下生成 .ssh 文件夹，进去，打开 id_rsa.pub，复制里面的 key。

回到 github 上，进入 Account => Settings（账户配置）。

# 查看当前远程库
~~~
git remote
git remote -v
~~~

# 提取远程仓库
从远程仓库下载新分支与数据
~~~
git fetch
~~~
从远端仓库提取数据并尝试合并到当前分支
~~~
git merge
~~~

# 推送与拉取
~~~
git push [alias] [branch]
~~~
# 删除
~~~
git remote rm [别名]
~~~

# 实例
~~~
$ git init                                  # 初始化
$ git add README.md                         # 添加文件
$ git commit -m "添加 README.md 文件"        # 提交并备注信息
[master (root-commit) 0205aab] 添加 README.md 文件
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

# 提交到 Github
$ git remote add origin git@github.com:tianqixin/runoob-git-test.git
$ git push -u origin master
~~~
