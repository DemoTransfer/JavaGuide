### 草帽团~

![草帽~](https://github.com/DemoTransfer/Java-Guide/blob/master/docs/Monkey%20D%20Luffy/%E8%8D%89%E5%B8%BD~.jpg)


> Java-Guide来源于<a href="https://github.com/Snailclimb/JavaGuide">SnailClimb的JavaGuide项目</a>，Java-Guide是2020年2月份开始原创和转载文章，也是新冠病毒较为严重的时候，希望武汉加油！中国加油！

### 开始阅读之前必看

1. <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Good-Link.md">优秀链接</a>

2. <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/java/interview/%E5%86%99%E5%9C%A8%E5%89%8D%E9%9D%A2.md">3W+2H</a>

### 目录

* Java

    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Java-basic.md">Java基础</a>
    
    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Java-collections.md">Java集合</a>
    
    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Java-IO.md">Java IO</a>
    
    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Java-concurrent.md">Java并发</a>
    
    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/JVM.md">JVM</a>

* 常见框架

    * <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Spring.md">Spring</a>
    
      Spring源码阅读
      ------

      * <a href="https://github.com/seaswalker/spring-analysis">Spring源码阅读Github笔记</a>

      Spring事务管理
      ------

      * <a href="https://www.imooc.com/learn/478">Spring事务管理慕课网视频</a>

      * Spring事务管理介绍

      * 回顾数据库事务相关概念

      * 事务API介绍

         * 接口介绍

         * PlatformTransactionManager

         * TransactionDefinition

         * TransactionStatus

         * 编程式事务管理

         需要手动编写代码进行事务的管理（一般不用）

         * 声明式事务管理

            * 基于TransactionProxyFactoryBean的方式

            需要为每个事务管理的类配置一个TransactionProxyFactoryBean进行管理。使用时还需要在类中注入该代理类。

            * 基于AspectJ的方式（常使用）

            配置好之后，按照方法的名字进行管理，无需再类中添加任何东西。

            * 基于注解的方式（经常使用）

            配置简单，在业务层类上添加注解@Transactional。

      Spring知识点扫盲
      ------

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%40Autowired%E5%92%8C%40Resource%E5%8C%BA%E5%88%AB.md">@Autowired和@Resource区别</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%40Repository%E5%92%8C%40Componet%E5%92%8C%40Service%E5%92%8C%40Controller%E4%B9%8B%E9%97%B4%E5%8C%BA%E5%88%AB%E5%92%8C%E8%81%94%E7%B3%BB.md">@Repository和@Componet和@Service和@Controller之间区别和联系</a>

      * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/java/interview/Spring/Spring%20%E4%BA%8B%E5%8A%A1%E9%9D%A2%E8%AF%95%E8%80%83%E7%82%B9.md">Spring事务面试考点</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Springboot%E5%92%8CSpring%E5%8C%BA%E5%88%AB.md">Springboot和Spring区别</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E4%B8%AD%3Cbean%3E%E5%85%83%E7%B4%A0%E5%8F%AF%E4%BB%A5%E9%85%8D%E7%BD%AE%E7%9A%84%E5%B1%9E%E6%80%A7.md">Spring中<bean>元素可以配置的属性</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E4%B8%ADBeanFactory%E5%92%8CApplicationContext%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB.md">Spring中BeanFactory和ApplicationContext有什么区别</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E4%B8%ADIoC%E5%92%8CAOP%E6%A6%82%E5%BF%B5%E4%BB%8B%E7%BB%8D.md">Spring中IOC和AOP概念介绍</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E4%B8%AD%E5%B8%B8%E7%94%A8%E6%B3%A8%E8%A7%A3.md">Spring中常用注解</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E5%A6%82%E4%BD%95%E7%AE%A1%E7%90%86Bean%E7%A4%BA%E4%BE%8B.md">Spring如何管理Bean示例</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/Spring%E6%94%AF%E6%8C%81%E5%93%AA%E4%BA%9BBean%E4%BD%9C%E7%94%A8%E5%9F%9F.md">Spring支持哪些Bean作用域</a>

      * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/java/interview/Spring/Spring%E5%BC%82%E6%AD%A5%E8%B0%83%E7%94%A8%40Async.md">Spring异步调用@Async</a>

      * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/java/interview/Spring/Spring%E6%94%AF%E6%8C%81%E5%93%AA%E4%BA%9BBean%E4%BD%9C%E7%94%A8%E5%9F%9F.md">Spring支持哪些Bean作用域</a>

      * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/java/interview/Spring/%E5%BC%82%E6%AD%A5%E8%AF%B7%E6%B1%82%E4%B8%8E%E5%BC%82%E6%AD%A5%E8%B0%83%E7%94%A8%E7%9A%84%E5%8C%BA%E5%88%AB.md">异步请求和异步调用的区别</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E7%AE%80%E5%8D%95%E4%BB%8B%E7%BB%8D%E4%B8%8Bservlet%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%EF%BC%8Cservlet%E6%98%AF%E5%90%A6%E4%BC%9A%E5%A4%9A%E6%AC%A1%E5%88%9D%E5%A7%8B%E5%8C%96%EF%BC%9F.md">简单介绍下servlet的生命周期，servlet是否会多次初始化</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E4%B8%ADBean%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.md">探探Spring中Bean的生命周期</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E4%B8%AD%E5%B8%B8%E7%94%A8%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md">谈谈Spring中常用设计模式</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E5%BE%AA%E7%8E%AF%E4%BE%9D%E8%B5%96.md">谈谈Spring循环依赖</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E6%A1%86%E6%9E%B6%E7%9A%84BeanFactory.md">谈谈Spring框架的BeanFactory</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E6%A1%86%E6%9E%B6%E7%9A%84FactoryBean.md">谈谈Spring框架的FactoryBean</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%B0%88%E8%B0%88Spring%E6%A1%86%E6%9E%B6%E7%9A%84%E4%BE%9D%E8%B5%96%E6%B3%A8%E5%85%A5%EF%BC%88DI%EF%BC%89.md">谈谈Spring框架的依赖注入（DI）</a>

      * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/Spring/%E8%BF%87%E6%BB%A4%E5%99%A8%E3%80%81%E7%9B%91%E5%90%AC%E5%99%A8%E3%80%81%E6%8B%A6%E6%88%AA%E5%99%A8%E7%9A%84%E5%8C%BA%E5%88%AB.md">过滤器、监听器、拦截器的区别</a>

    
    * <a href="https://github.com/DemoTransfer/Java-Guide/tree/master/java/MyBatis">MyBatis</a>
    
 * <a href="">开发规范</a>   
    
 * web服务器
 
    * <a href="https://github.com/DemoTransfer/Java-Guide/tree/master/java/web%20server/tomcat">Tomcat</a>
    
    * <a href="https://github.com/DemoTransfer/Java-Guide/tree/master/java/web%20server/netty">Netty</a>

* <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/Database.md">数据库</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E9%9D%A2%E8%AF%95%E9%A2%98(%E5%BC%80%E5%8F%91%E8%80%85%E5%BF%85%E7%9C%8B)%20.md">数据库面试题（开发者必看）</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E4%B8%80%E5%8D%83%E8%A1%8CMySQL%E5%91%BD%E4%BB%A4.md">一千行MySQL命令</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%A4%E5%A4%A7%E7%A5%9E%E5%99%A8%E4%B9%8B%E7%B4%A2%E5%BC%95.md">数据库两大神器之索引</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%A4%E5%A4%A7%E7%A5%9E%E5%99%A8%E4%B9%8B%E9%94%81.md">数据库两大神器之锁</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E5%88%86%E5%BA%93%E5%88%86%E8%A1%A8%E5%B8%B8%E8%A7%81%E6%96%B9%E6%A1%88.md">数据库常见分库分表方案</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B4%A2%E5%BC%95%E5%A4%B1%E6%95%88%E6%80%BB%E7%BB%93.md">数据库索引失效总结</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AF%AD%E5%8F%A5%E4%BC%98%E5%8C%96%E6%89%8B%E6%AE%B5.md">数据库语句优化手段</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E6%95%B0%E6%8D%AE%E5%BA%93/%E7%B4%A2%E5%BC%95.md">索引</a>

* <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/contents/Network.md">网络</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C%E5%B8%B8%E8%A7%81%E9%9D%A2%E8%AF%95%E9%A2%98.md">计算机网络常见面试题</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/HTTP%E9%95%BF%E8%BF%9E%E6%8E%A5%E3%80%81%E7%9F%AD%E8%BF%9E%E6%8E%A5%E7%A9%B6%E7%AB%9F%E6%98%AF%E4%BB%80%E4%B9%88.md">Http长连接、短连接究竟是什么？</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/TCP%20%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%92%8C%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B.md">TCP三次握手和四次挥手</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/TCP%E5%92%8CUDP%E5%8C%BA%E5%88%AB.md">TCP和UDP区别</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/http%E5%92%8Chttps%E5%8C%BA%E5%88%AB%E5%92%8C%E8%81%94%E7%B3%BB.md">http和https区别和联系</a>

   * <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/java/interview/%E9%80%9A%E4%BF%A1%E7%BD%91%E7%BB%9C/http%E5%92%8Csocket%E4%B9%8B%E9%95%BF%E8%BF%9E%E6%8E%A5%E5%92%8C%E7%9F%AD%E8%BF%9E%E6%8E%A5%E5%8C%BA%E5%88%AB.md">http和socket之长连接和短连接区别</a>

* <a href="">加解密</a>

* <a href="https://github.com/DemoTransfer/JavaGuide/blob/master/contents/desgin-pattern.md">设计模式</a>

* <a href="https://github.com/DemoTransfer/LearningRecord/tree/master/sort">数据结构和算法</a>

* <a href="https://github.com/DemoTransfer/LearningRecord/tree/master/linux/%E9%97%AE%E9%A2%98%E6%8E%92%E6%9F%A5%E8%B5%B7%E6%89%8B%E5%BC%8F%E5%91%BD%E4%BB%A4">操作系统</a>

* <a href="https://github.com/DemoTransfer/LearningRecord/blob/master/docs/outside-reading/%E7%9E%8E%E7%9C%8B%E7%B3%BB%E5%88%97.md">杂文系列</a>

* <a href="https://github.com/DemoTransfer/Java-Guide/tree/master/java/SPI">SPI</a>

   * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/java/SPI/%E4%BA%86%E8%A7%A3%E7%AE%80%E5%8D%95%E7%9A%84SPI%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86%E5%92%8C%E8%BF%90%E7%94%A8.md">了解简单的SPI实现原理和运用</a>

* <a href="https://github.com/DemoTransfer/Java-Guide/tree/master/docs/BFF">BFF</a>

   * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/docs/BFF/BFF%20%E2%80%94%E2%80%94%20Backend%20For%20Frontend.MD">BFF —— Backend For Frontend</a>

   * <a href="https://github.com/DemoTransfer/Java-Guide/blob/master/docs/BFF/BFF%E2%80%94%E2%80%94%E6%9C%8D%E5%8A%A1%E4%BA%8E%E5%89%8D%E7%AB%AF%E7%9A%84%E5%90%8E%E7%AB%AF.MD">BFF——服务于前端的后端</a>

* <a href="">Serverless</a>

* 工具

   * <a href="">Git</a>

   * <a href="">Maven</a>
   
   * <a href="">Docker</a>

* <a href="https://github.com/DemoTransfer/JavaGuide/new/master/contents">素材文章来源</a>

### 关于转载

如果你需要转载本仓库的一些文章到自己的博客的话，记得注明原文地址就可以了。




