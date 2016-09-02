# june-notebook-1.0v
  JUNE1.0v版本（原蓝缘系统开源免费版）<br>
	严格执行开源大业！奋斗吧，少年<br>
 总的来说，还得要感谢蓝缘大人的无私的奉献精神，把最初的东西开源了。<br>
 抛砖引玉这种活儿，我是做不来的;我顶多就是做一些锦上添花的事情...<br>
 
### 160902 添加国际化支持
### 160901 修改若干bug，增强系统稳定性
 
## 下一步计划
	1 添加国际化支持；<br>
		在java代码中发现大量的中文字符，看着不舒服;<br>
	2 回归mybitas，尽量减少对源码的修改;<br>
	3 增加系统功能<br>
		权限管理可能需要重构<br>
===================================
#JUNE开源系统
	接管开源大业，任重而道远也 --june @ 2016-09-01<br>
		1.听说原系统要修费了，收费就收费吧，我们接着搞起...<br>
		2.版本1.0v：https://github.com/junehappylove/june_BMS<br>

##关于1.0新版本的说明：
###一大亮点：
	采用最新的技术流行框架：springMVC4.1.4+shiro1.2.3+spring4.x+Mybaits3.2.8+Ajax+html5<br>
	spring4.x的新特性请看：<br>
	http://jinnianshilongnian.iteye.com/blog/1989381 <br>
####说明：<br>
	这个版本主要是对原有的JUNE系统更换UI界面,功能上基本一致, 但此还在开发当中..... 关于以前版本,不再维护,致力于新版本的开发和维护..<br>
####优化：<br>
	封装好baseSerive,baseSeriveImpl,baseMapper..服务层，持久层统一调用,大大减少代码开发时间.<br>
	spring4.x的强类型注解，泛型限定式依赖注入<br>
	用mapper来代替dao,由mybaits自动管理各事务的操作,大大减少代码开发时间.<br>
	3.0版本不再使用spring Security3权限安全机制,采用了shiro权限机制, 为何愿意使用Apache Shiro ？请看：http://www.infoq.com/cn/articles/apache-shiro<br>
###技术要点：<br>
	1：此版本采用ajax+js分页,表格lyGrid分页插件是群主自己写的,有点模仿ligerui的分页实现<br>
	2：列表的表头固定,兼容IE,firefox,google,360的浏览器,其他暂没有测试.<br>
	3：表格排序功能<br>
	4：弹窗采用贤心的插件，网址：http://sentsin.com/jquery/layer/<br>
	5：加入druid技术,对sql语句的监控.<br>
	6：自定义注解导出excel<br>
	7：使用了ehcache缓存机制<br>
	8：新增支持oracle分页实现<br>
	9：新增支持SQLserver2008分页实现<br>
	10：解决分页参数没法传到后台的问题<br>
	11：异常统一处理<br>
	12：使用Spring Security3权限安全机制,采用了shiro权限机制<br>
	13： 封装好baseSerive,baseSeriveImpl,baseMapper..服务层，持久层统一调用<br>
	14：........<br>