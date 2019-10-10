# 网上书城项目

**作者：vili &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 联系方式1976763043@qq.com**

[TOC]

## 一、项目功能

### 1.前台功能

1. 图书基本展示,包括推荐图书展示和类图书类型展示.
2. 推荐图书包括条幅推荐,热销推荐和新品推荐.
3. 按照图书类型展示商品.
4. 图书详细信息展示.
5. 图书加入购物车.
6. 修改购物车内图书信息,例如数量等.
7. 用户登录.
8. 用户注册.
9. 修改个人信息,包括密码和收获信息.
10. 购物车付款.
11. 用户订单查询.
12. 根据关键字搜索图书.

### 2.后台功能

*当管理员用户登录后会显示后台管理按钮,点击介意进入后台管理页面*

1. 订单操作:包括按状态查询订单,修改订单状态(发货,完成,删除).
2. 用户操作:包括查询所有用户,新增用户,修改用户密码,修改用户信息和删除用户.
3. 图书类目操作:包括查看所有类目,增加图书类目,修改图书类目信息以及删除图书类目.
4. 图书操作:包括查询所有图书,新增图书,修改现有图书信息以及删除图书.

*注意,删除用户时需要先删除用户下的所有订单，才可以删除用户。删除图书类目时，要先删除类目下的图书，才能删除图书类目。删除商品时，可直接删除，他的推荐信息也会直接删除!（不要问为什么做的这么蠢，当时脑子抽风了！）*

## 二、项目开发环境

1. 项目使用IDEA 2018.3.5进行开发。
2. Maven版本为 3.6.2。
3. Tomcat版本为 8.5.42。
4. 数据库为mysql 5.7。
5. JDK版本为1.8_211。
6. 项目使用Spring+SpringMVC+Mybits框架。

## 三、项目还原设置

1. 将bookshop.sql文件还原至数据库中。
2. 打开BookShop/src/main/java/com/vilicode/config/jdbc.properties文件进行配置：
   1. url更换为自己的数据库连接字符串。
   2. user更换为自己数据库的用户名。
   3. password更换为自己的密码。
3. 使用IDEA打开项目并重新指定jdk。
4. 在IDEA中配置Maven路径并下载所需依赖文件。
5. 下载Tomcat并在IDEA中配置。
6. 运行项目。

## 四、项目截图

- 前端界面模板与CakeShop的模板相同，项目链接：https://dev.tencent.com/u/vi-li/p/CakesShop