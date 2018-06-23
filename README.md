# 参考

参考[源码](https://github.com/Baeldung/spring-security-oauth)改造而成。

------



### 步骤

1. 需要启动mysql数据库，在oauth-server/src/main/resources/persistence.properties设置数据库访问用户名/密码
2. 依次启动：

- 授权服务器oauth-server(8081)
- 资源服务器oauth-resource(8082)
- AngularJS单页应用oauth-ui-implicit(0803)

1. 浏览器打开[http://localhost:8083](http://localhost:8083/) 开始实验
2. 登录用户名密码在oauth-server/.../WebSecurityConfig中配置