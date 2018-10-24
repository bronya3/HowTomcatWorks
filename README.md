# How Tomcat Works 

## 1.一个简答的Web服务器

问题：请求HttpServer没有看到响应的内容

原因：socket输出之前要有HTTP响应头

```java
output.write("HTTP/1.0 200 OK\r\nContent-Type: text/html\r\n\r\n".getBytes());
```

## 2.一个简单的Servlet容器

面向接口编程

反射

门面模式


## TODO

---


- [Source Code](http://brainysoftware.com/source/9780975212806.zip)
- [Original Repo](https://github.com/serivires/how-tomcat-works)