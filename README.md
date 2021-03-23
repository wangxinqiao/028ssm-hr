# 028ssm公司员工管理系统
028ssm公司员工管理系统


## 项目介绍
程序开发软件：IDEA/Eclipse/MyEclipse 数据库：mysql5.7
后台采用技术： SSM框架(SpringMVC + Spring + Mybatis)
前台采用技术： div + css + easyui框架

技术要点：
1 此系统采用了目前最流行的ssm框架,其中的spingMVC框架相对于struts2框架更灵活，更安全。
2 本项目springMVC框架采用了注解映射器，使用了RESTful风格的url对系统发起http请求,开发更灵活。
3 同时使用了了hibernate提供的校验框架，对客户端数据进行校验！
4 Mybati数据库DAO层采用的是Mapper代理开发方法，输入映射采用的是POJO包装类型实现,输出映射采用了resultMap类型，实现了数据库多对一映射。
5 spring容器内部使用拦截器，以Spring AOP的方式实现事务控制管理。

源码获取：[点此获取](http://www.shuyue.fun/index.php?type=productinfo&id=129)

系统实体对象：
部门: 部门编号,部门名称
职位: 职位id,所属部门,职位名称,基本工资,销售提成
员工: 员工编号,职位,姓名,性别,员工照片,出生日期,学历,员工介绍

## 运行截图

![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/094506_6053891e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/102155_839ce3d1_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/102206_bbc7bdae_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/102214_7cfa130e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/102223_99a10ae8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0316/102233_7351fe06_863230.png "屏幕截图.png")
