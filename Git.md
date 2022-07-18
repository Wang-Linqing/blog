# Git 常用命令

# 拉取分支
- 拉取master分支
```
git clone --branch=master https://github.com/Wang-Linqing/blog.git
```

# 创建分支
- 
```

```

# 切换分支
- 
```

```
# 撤销修改
- 
```
git reset --soft HEAD^
```
# 同步云端修改到本地
```
git pull --rebase
发现冲突的地方后，进行修改，然后
git add .
git rebase --continue
```
# 打包修改和应用修改
- 
```

```
# 提交修改
- 提交修改 
```
git commit -m "say something"
```
- 提交修改，与上一个commit修改合并
```
git commit --amend
```
# 同步本地修改到服务器
- push 到githhub的master
```
git push origin master
```
