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

``` js
// 查询 git 历史提交版本记录即编码
git log
// 退回至指定版本
git reset 编码
// 退回至上个版本
git reset --hard
// 如果报错 Unstaged changes after reset: 即为本分支不是主分支，无法获取当前版本先
git add .
// 再回退版本
git reset --hard
```

