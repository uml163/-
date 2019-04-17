[课程作业网站](http://uml163.github.io/UML/.)




部署服务端过程：

1.根据自己的操作系统按教程安装docker 参考：https://baijiahao.baidu.com/s?id=1592846051245987256&wfr=spider&for=pc

2.获取镜像：
docker pull zfr0411/myrepository:mycentos

3.启动镜像service服务，并设置端口映射：docker run -itd -p X(未被占用的端口):5000 --name mycontainer --privileged  mycentos init

4.查看容器ID：docker ps -a。

5.进入mycontainer容器：docker exec -ti ID /bin/bash

6.cd到指定目录：cd root/myapp/test

7.执行命令运行程序：python3 manager.py runserver
