# springboot-book-manager-demo
这是一个基于SpringBoot的后端图书管理系统的小demo，配合前端vue-book-manager-demo使用。

MySQL和port配置属性如下：
~~~
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/sell?useSSL=false&useUnicode=true&characterEncoding=UTF-8
    username: root
    password: 123456
    driver-class-name: com.mysql.cj.jdbc.Driver
  jpa:
    show-sql: true
    properties:
      hibernate:
        format_sql: true
    hibernate:
      ddl-auto: update
server:
  port: 8181
~~~
