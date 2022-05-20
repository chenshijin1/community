##4 使用Github托管代码
使用GitHub仓库之前，需要为用户配置ssh
因为不是所有的用户都能往仓库里面push内容
```shell script
git status
查看git状态

git add .
将改变放入缓存中

git status
查看git状态

git commit -m "add readme"
提交事务

git push
推送到仓库
```