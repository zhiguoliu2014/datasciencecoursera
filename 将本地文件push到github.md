##将本地文件同步到github上
首先在github上建立库
然后在本地建立同名库，并与gitbub关联
将要push的新文件复制到本地库中，运行以下代码：
$git add filename                   #建立索引
$git commit –m “message you want other people know”    #放入本地库
第三，push即可
$git push origin master          #同步整个master
