![Screenshot_2024-05-06-22-43-26-47_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/vueyi/vueyi/assets/130923270/3e6b6ef0-df15-4e93-bae8-e1874f48f57a)
![Screenshot_2024-05-14-09-19-39-18_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/vueyi/vueyi/assets/130923270/80acd004-fa5d-42e0-a52b-9156d12f9bdb)
部署教程
--------------------------
1. 安装JDK,maven,并添加映射，安装redis
2. 网站文件 放到www/wwwroot目录下
3. 数据库mysql5.7  lower_case_table_names=1
4. 网站添加反向代理http://127.0.0.1:8085


重启后打开任务教程
--------------------------
1、ps -Af | grep "tomcat" | grep -v grep | awk '{print$2}' | xargs kill -9   查看已经启动的进程，并删除
2、cd /root/project/zookeeper/bin/
   sh zkServer.sh start
3、cd /www/server/tomcat/bin/
   sh startup.sh

4. conf linux tools
  domain: localhost localhost.localdomain localhost4 localhost4.localdomain4
   ip : 127.0.0.1
  domain : localhost localhost.localdomain localhost6 localhost6.localdomain6
   ip : :


新版外汇系统，所有币种均可用平台币种控制，系统功能齐全
产品构造与维护

newexcoin.org
vexus.kelubit.id
dapp.kelubit.id
前端vue
后端java




   联络我
   https://t.me/kelubit

<!---
vueyi/vueyi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
