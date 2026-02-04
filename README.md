初始化tag
git tag v0.0.1; 
git push origin main; 
git push origin v0.0.1

更新本地 tag 到 main 最新提交：
git tag -f v0.0.1 main

推送并覆盖远端 tag：
git push -f origin v0.0.1

如果你要把 v0.0.1 更新到 main 最新提交，用这些命令：
git tag -f v0.0.1 main
git push -f origin v0.0.1