# springboot-docker-demo
上传项目到linux上（已安装docker和maven）  

```mvn package docker:build -DpushImage```

dockering

```docker run -p 8080:8080 spring-boot-docker/gs-spring-boot-docker```
浏览器输入网址:```http://ip:8080```
