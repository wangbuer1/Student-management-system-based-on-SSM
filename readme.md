# 基于SSM的学生信息管理系统（简单版）

## 1、项目介绍

学生信息管理系统拥有两种角色，分别为学生和管理员，可以作为初学者使用学习。

**学生**：个人信息查看和修改、查看班级信息

**管理员**：管理员对学生信息、老师信息、学院年级信息的添加、修改、删除、多条件查询等功能

## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：easyui、layui、jsp

其它：mysql5-8、tomcat8-10、JDK1.8+

## 3、开发工具

Eclipse、idea和myEclipse都可以

## 4、功能介绍及视频演示

- 登录页面
  ![登录](image/%E7%99%BB%E5%BD%95.png)
  学生管理系统的中两种用户均可以通过此界面登录，系统将自动识别用户类型，经过密码和验证码正确性验证之后，将会跳转到不同的页面

- 管理员界面-学生列表
![管理员界面-学生列表](image/%E7%AE%A1%E7%90%86%E5%91%98%E7%95%8C%E9%9D%A2-%E5%AD%A6%E7%94%9F%E5%88%97%E8%A1%A8.png)
管理员可以添加、修改和删除学生信息，点击添加按钮，页面将会跳出添加学生页面，输入相关信息之后，便可将学生信息保存到数据库中。此外，管理员还可以通过学生名字、所属班级等条件查找学生。

- 管理员界面-年级列表
![管理员界面-年级列表](image/%E7%AE%A1%E7%90%86%E5%91%98%E7%95%8C%E9%9D%A2-%E5%B9%B4%E7%BA%A7%E5%88%97%E8%A1%A8.png)

管理员可以添加、修改和删除年级信息。点击添加按钮，页面将会跳出添加年级的页面，输入相关信息之后，便可将年级信息保存到数据库中。此外，管理员还可以通过年级名字查找相关信息。班级信息和用户信息同上。

- 学生界面-个人信息界面
![学生界面-个人信息界面](image/%E5%AD%A6%E7%94%9F%E7%95%8C%E9%9D%A2-%E4%B8%AA%E4%BA%BA%E4%BF%A1%E6%81%AF%E7%95%8C%E9%9D%A2.png)

学生可以查看班级通讯录以及个人的信息，并能够对个人信息进行修改，如上图点击“提交”按钮后，便可将数据更新到数据库中。

## 5、视频演示

[点击观看视频](https://mp.weixin.qq.com/s?__biz=MzkwMjM1MjM0Ng==&mid=2247483808&idx=1&sn=791ee70c95b999401fd36e4b3aecd9bd&chksm=c0a79d15f7d014035f0b57dc4a365d981dbd794f47c8a788acb495fe5c6dac894d62857425bb#rd)
（视频在 链接网页的下方）

## 6、获取方式

关注公众号： **程序员王不二** （ javaCodeSharing），回复 “学生管理4” ，即可免费获取完整版的项目代码

![img](https://img-blog.csdnimg.cn/7b5e4835dd0248459447658ca28d2ff0.png#pic_center)

