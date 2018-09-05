# dois2018SZ

# 容器部署（预置插件，配置，demo jobs等） #

docker pull huaqiangli/jenkins:dois2018-sz-2

docker run -d -p 8080:8080 -p 50000:50000  huaqiangli/jenkins:dois2018-sz-2

# 访问Jenkins #

http://<your ip>:8080/

登录: admin/jenkins2018

修改全局配置的 Jenkins URL 为 http://<your ip>:8080/
