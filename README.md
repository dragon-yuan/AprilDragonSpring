# AprilDragonSpring
![](https://github.com/dragon-yuan/AprilDragonSpring/raw/master/src/main/webapp/images/pic.jpg)
<br>
```html
此项目为初识SPRINGBOOT+HIBERNATE时期的入门框架整合，存在部分不成熟思想
推荐您查看成熟一点后整合的框架项目，传送门：[NovSpringBoot](https://github.com/dragon-yuan/NovSpringBoot).
```
master
---

- 修正了Service层事务注解 
- 新增了装饰器，对页面进行布局和装饰 

delta
---

- 修正了分页存在的问题 
- 新增了异步处理分页的方法，现在可以自定义每页显示数据的数量 
- 新增了Spring Boot原汁定时器的使用情景 

gamma
---

- 修正了对Dao层的注解 
* 新增异步处理，封装了对AJAX的请求 
	* 页面调用getData(url, data)和postData(url, data)两种请求方式 
	* 后端使用ajaxSuccess(Object msg)、ajaxError(Object msg)、ajaxParam(String flag, Object msg, Object param)三种方法处理方式
* 新增分页功能，详见page 

beta
---

- 添加了GenericDao，现可以通过继承此基类来实现CURD 
- 更正了注解，现可以自动注入Dao和Service 

alpha
---

- 框架环境：Spring Boot + JPA(Hibernate) 
- 配置了支持JSP的依赖 
- 配置了Druid连接池 
