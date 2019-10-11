# 第5章 微服务容错保护-Hystrix源码说明

本章中的源码包含两个文件夹:**Hystrix**和**Hystrx-Feign**.
 
**Hystrix-Feign**是《在Feign中使用Hystrix回退》小节的源码，包含4个项目:    
1. parent: 父项目   
2. service-discovery: 服务治理服务器    
3. user-service: 用户微服务    
4. product-service: 商品微服务 

**Hystrix**则是本章其它章节所使用的示例项目，包含5个项目:    
1. parent: 父项目   
2. service-discovery: 服务治理服务器    
3. user-service: 用户微服务    
4. product-service: 商品微服务      
5. turbin-service: Turbin服务器 

在IDE中可以直接通过根目录下的`pom.xml`将整个工程导入。