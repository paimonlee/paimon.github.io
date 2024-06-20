stash命令用于暂时隐藏修改，一般情况下的命令是
```shell
# 使用上一个commit的信息
git stash
# 使用指定信息
git stash -m ""
```

git stash支持隐藏指定文件，在隐藏指定文件时，不能省略push参数，必须使用完整的命令
```shell
git stash push **/*.java
git stash push -m "" **/*.java
```