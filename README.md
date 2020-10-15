# git 使用总结
第一次使用git，建立连接可参考 https://blog.csdn.net/qq_41782425/article/details/85183250

建立连接后
1. 将本地库同步到远程git库上
（1）在本地Bush控制台上，先cd到本地库地址。如：cd c:/.../source/repos/leetcode(project name)2
（2）git add *  （星号表示添加所有文件，如果只是上传某个文件，则可: git add test.txt）
     注：此步骤可能会有warning。 解决方法：是因为unix系统与windows系统跨平台问题导致，执行git config core.autocrlf false后，再提交就不会报错了。
（3）git commit -m "本次更新操作说明"
（4）git push origin master
注：很多教程上没有步骤（2）（3），我这样操作虽然控制台上显示更新了，但实际上并没有，非常奇怪，必须得加上步骤（2）（3）才行。

2.将远程git库同步到本地
（1）
（2）

