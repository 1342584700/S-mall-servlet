# 小小商城系统

练手JavaWEB项目，本版本为Servlet版（实现了SSM版85%的功能），基于原生JDBC数据库连接，通过手动实现Filter进行URL和Servlet之间的映射

---------------------------

演示（SSM版）：[搭建中][1]  
兄弟项目：  
[SSH版（实现了SSM版95%功能）][2]  
[SSM版（完整版）][3]  


----------------------------

本项目的亮点：

 * 功能齐全，页面丰富，实现了小商城的大部分功能
 * 前端仿天猫2017页面，基于原生CSS、Jquery、BootstrapJs构建
 * 本项目后端使用原生Servlet+JDBC+Filter实现，轻量化构建。
  

功能： 

 - [x] 首页/分类页、搜索页、产品页
 - [x] 购物车页面、下单页、支付页及支付成功页
 - [x] 我的订单页、确认收货及成功页、评价页
 - [x] 登陆页、注册页
 - [x] 全部数据库的后台可视化管理
 - [ ] 网站设置、精细数据校验、前端体验优化

------------------
 
 安装使用：
 
  1. 若使用IDE打开，需将WEB-INF下的LIB文件夹和Tomcat文件夹下的LIB文件夹到库依赖即可
  2. 若在Tomcat中部署，直接复制文件夹到Tomcat相应位置即可
  3. 导入数据库small.sql，在 src\util\DBUtil.java中配置数据库
  4. 默认后台地址 /admin ，账户密码为 admin 123456 ，新建用户在前台注册，需要后台权限需要在数据库的User表的group_列中将该用户的用户组设置为 superAdmin


  [1]: http://
  [2]: https://github.com/xenv/S-mall-ssh
  [3]: https://github.com/xenv/S-mall-ssm