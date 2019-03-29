# Android
从本地上传第一个Android测试程序
1. cd 到文件目录
2. git init //初始化
3. git add 内容
4. git commit -m "注释内容"
5. git remote add origin https://github.com/pl741/Android.git
6. git push -u origin master
若出现 error: failed to push some refs to...错误，先执行git pull --rebase origin master，再执行git push -u origin master
