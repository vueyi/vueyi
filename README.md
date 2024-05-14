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


   联络我
   https://t.me/kelubit

<!---
vueyi/vueyi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
