<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">pms v1.0(Prison Management System v1.0)</h1>
<h4 align="center">基于SpringBoot+Vue前后端分离的监狱管理系统</h4>


## 平台简介

* 本仓库为四川省XX监狱定制的监狱管理-执法保全系统v1
* 后端采用Spring Boot3、Spring Security、MySql8.0、Redis & Jwt。
* 权限认证使用Jwt，支持多终端认证系统。
* 支持加载动态权限菜单，多方式轻松权限控制。
* 高效率开发，使用代码生成器可以一键生成前后端代码。

# 版本分支

后端项目使用 Spring Boot 3.
前端项目提供 Vue 3 TypeScript。
本版本为私有主版本分支切出的公开版本分支，仅供面试使用，切勿商用，使用此版本商用造成的损失概不负责。

## 内置功能

罪犯信息管理：罪犯的基础信息：姓名，性别，年龄，收监原因……
罪犯就医记录：狱内就医，狱外就医，就医记录，就医视频。
罪犯管控信息：主管民警信息：姓名，警号。五专五定情况：固定床位、工位、活动区域、队列位置、互监组……
减假暂信息：减刑信息，假释信息，暂予监外执行信息。
教育改造信息：三课程教育，考核情况。
罪犯通信信息:信件情况，收信登记，寄信登记，违规信件查处。
罪犯情亲电话信息：审批表，拨打记录，拨打对象登记，录音记录。
罪犯亲情会见信息：现场会见，会见单，亲属关系证明，现场音视频记录，远程视频会见，亲属关系证明。
用户管理：用户是系统操作者，该功能主要完成系统用户配置。
部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
岗位管理：配置系统用户所属担任职务。
菜单管理：配置系统菜单，操作权限，按钮权限标识等。
角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
字典管理：对系统中经常使用的一些较为固定的数据进行维护。
参数管理：对系统动态配置常用参数。
通知公告：系统通知公告信息发布维护。
操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
登录日志：系统登录日志记录查询包含登录异常。
在线用户：当前系统中活跃用户状态监控。
定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
系统接口：根据业务代码自动生成相关的api接口文档。
服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
缓存监控：对系统的缓存信息查询，命令统计等。
在线构建器：拖动表单元素生成相应的HTML代码。
连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。



## 演示图

<table>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/cd1f90be5f2684f4560c9519c0f2a232ee8.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/1cbcf0e6f257c7d3a063c0e3f2ff989e4b3.jpg"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-8074972883b5ba0622e13246738ebba237a.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-9f88719cdfca9af2e58b352a20e23d43b12.png"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-39bf2584ec3a529b0d5a3b70d15c9b37646.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-936ec82d1f4872e1bc980927654b6007307.png"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-b2d62ceb95d2dd9b3fbe157bb70d26001e9.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-d67451d308b7a79ad6819723396f7c3d77a.png"/></td>
    </tr>	 
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/5e8c387724954459291aafd5eb52b456f53.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/644e78da53c2e92a95dfda4f76e6d117c4b.jpg"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-8370a0d02977eebf6dbf854c8450293c937.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-49003ed83f60f633e7153609a53a2b644f7.png"/></td>
    </tr>
	<tr>
        <td><img src="https://oscimg.oschina.net/oscnet/up-d4fe726319ece268d4746602c39cffc0621.png"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-c195234bbcd30be6927f037a6755e6ab69c.png"/></td>
    </tr>
    <tr>
        <td><img src="https://oscimg.oschina.net/oscnet/b6115bc8c31de52951982e509930b20684a.jpg"/></td>
        <td><img src="https://oscimg.oschina.net/oscnet/up-5e4daac0bb59612c5038448acbcef235e3a.png"/></td>
    </tr>
</table>


