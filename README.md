# OCR-Knelt1
> ### 大二下的数据库课程设计-学生成绩管理系统  
>> 一年两度的课设期又来了，本来用C#托几个控件做窗口应用挺简单的，但忽然心血(ZUO)来潮(SI)...
>> 于是叫上涛哥，用Java EE实现这个小系统

整个项目后台并没有用什么框架...可谓是相当初级  
后台搭配:Tomcat 8+Java EE+Sql Server+Idea 2016/2017  
前台配置:Bootstrap 3+Jqeury 2  
因为学艺不精, 整体过程是在挣扎中度过的, 不过知道了在JAVA EE中各个层次的交互方式  
数据库是和涛哥一起设计的，无奈涛哥不会前端，于是他去写后台，前台则是我写  
后台写了大量简陋的servlet，前台写了大量简陋的h5代码  
用类似SpringMVC的三层架构来说明的话就是  
##### UI<-->BLL<-->DAO<-->Database
>UI层中是JSP, 可以通过form来提交用户的数据  
>BLL层中是Servlet，可以接收表单提交数据，实现前台的功能业务并对应页面跳转  
>DAO层是操作数据库的业务代码  
>Database就单纯存数据了，也没有搞触发器，存储过程什么的  

其实还有问题的是在UI中没有分离JS，像登录验证也应该属于BLL的代码  
因为前端各种技术都写得渣，所以也没有封装成css和js外部文件，自己写行内或页内的形式了，所以会有代码冗余  
后台也是，涛哥写的也挺渣，写的自己都过目不去了  
学无止境, 嗯

