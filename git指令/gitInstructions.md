``` js
// 安装 git 配置
git init
// 缓存更改的部分
git add .
// 写备注，即本次更新内容
git commit -m "null"
// 设置提交分支
git branch -M main
// 清除源库地址，并设置新提交的库位置
git remote add origin git@github.com:1063885523/gitTest.git
// 推送更新到 main 分支
git push -u origin main
```

