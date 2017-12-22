包括
1. 配置AOP
MethodInterceptor
http://localhost:8080/test/show

http://localhost:8080/log/test

2. 配置热部署(包括修改类中方法、新建类、修改配置文件等)
http://localhost:8080/hot/test

3. 修改application.properties为application.yml
验证：http://localhost:8080/student/listAll
http://localhost:8080/student/part?pageNum=1&pageSize=5
http://localhost:8080/student/listUser

