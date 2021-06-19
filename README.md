# SpringBootWeb
用户管理权限系统
项目简介：根据每个用户登陆的角色权限不同来操作权限下对应的资源内容。
项目简述： 该的功能可分为：角色管理，用户管理和人员客户管理。登陆系统的用户分为管理员和普通用户角色登陆，管理员拥有菜单的所有资源和控制其他角色用户的菜单资源。普通登陆的用户可以根据自己拥有的资源来操作资源里的内容。

![image](https://user-images.githubusercontent.com/39553612/122638685-2edc0400-d128-11eb-93ef-a03b6489e008.png)
导入数据库后，很具数据库名称，用户名和密码来修改相对应的数据库。

其中在POM.xml文件中有      
<!-- mybatis-plus-generator -->
<!--        <dependency>-->
<!--            <groupId>com.baomidou</groupId>-->
<!--            <artifactId>mybatis-plus-generator</artifactId>-->
<!--            <version>3.4.1</version>-->
<!--        </dependency>-->

<!--        <dependency>-->
<!--            <groupId>org.freemarker</groupId>-->
<!--            <artifactId>freemarker</artifactId>-->
<!--        </dependency>-->
这两条是MyBatis-Plus代码文件生成器所用到的，以及配合改图片中的此类来生成基础代码。（一般生成代码后将依赖项和该文件的代码注释）

![image](https://user-images.githubusercontent.com/39553612/122638415-8d07e780-d126-11eb-8d6e-41d408da50e3.png)

最后是项目运行的结果。

![image](https://user-images.githubusercontent.com/39553612/122638462-c6405780-d126-11eb-829d-124d9beaaaad.png)


由于做了一个简单的用户权限管理系统，所以后续菜单可以添加。
主页默认界面：

![image](https://user-images.githubusercontent.com/39553612/122638504-fe479a80-d126-11eb-92f4-d470f35e240e.png)


上方导航条不会重复生成，如果没有导航条就创建，如果有则回到打开过的内容下。

![image](https://user-images.githubusercontent.com/39553612/122638530-2636fe00-d127-11eb-87c7-c25370112305.png)


1.首先是管理员的客户管理，比较简单，可以模糊查询，详情，编辑，添加和删除。查询时带分页的。
![image](https://user-images.githubusercontent.com/39553612/122638562-54b4d900-d127-11eb-8644-cb83aabcf918.png)
2.然后是账号管理
![image](https://user-images.githubusercontent.com/39553612/122638593-92196680-d127-11eb-8434-8f21f7a75da7.png)
3.拥有该资源的角色资源管理，可以修改账户下的资源角色资源权限。
![image](https://user-images.githubusercontent.com/39553612/122638601-a0678280-d127-11eb-80e0-24e070873552.png)
查看账户资源权限：
![image](https://user-images.githubusercontent.com/39553612/122638618-b5dcac80-d127-11eb-898a-9c08cc61a0db.png)
修改账户资源权限：
![image](https://user-images.githubusercontent.com/39553612/122638628-c7be4f80-d127-11eb-95ec-f2e1f76f5e5d.png)



