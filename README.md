# p3-weixin
Jeewx 微信插件式开发框架
-----------------------------------


框架技术：
-----------------------------------
   Springmvc_3.2.9.RELEASE + Mybatis_3 + Velicity_1.6.4（无jsp页面）
开发环境：
-----------------------------------
eclipse + maven构建

插件开发模式：
-----------------------------------
1.插件引入方式
    pom.xml文件中，引入新开发的插件
		<!-- P3 jar -->
 	    <dependency>
			<groupId>org.jeecgframework</groupId>
			<artifactId>P3-Biz-gzbargain</artifactId>
			<version>2.0.0</version>
		</dependency>
		
		
2.插件测试，启动Web项目，目前插件项目不能单独启动。		
3.数据库配置文件：src/main/resources/db.properties
4.项目启动访问地址：http://localhost:8080/P3-Web/{活动访问具体地址}