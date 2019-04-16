[课程作业网站](http://uml163.github.io/UML/.)


由于国内注册不了docker账号，先将镜像文件上传至百度云盘供大家下载：

百度云地址：

密码：

部署服务端过程：

1.根据自己的操作系统按教程安装docker 参考：https://baijiahao.baidu.com/s?id=1592846051245987256&wfr=spider&for=pc

2.启动docker ，将镜像传入主机。命令： docker load  --input mycentos.tar

3.启动镜像service服务，并设置端口映射。命令：docker run -itd -p X(未被占用的端口):5000 --name mycontainer --privileged  mycentos init

4.查看容器ID。命令：docker ps -a。

5.进入mycontainer容器。命令：docker exec -ti ID /bin/bash

6.cd到指定目录。命令：cd root/myapp/test

7.执行命令运行程序：python3 manager.py runserver
