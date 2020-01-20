# Tomcat-Source-Code

 为了学习tomcat源码，并再学习源码时对源码做注释，用于加深理解


### Quick Start

* 使用IDEA 或 eclipse （本人是IDEA）配置 VM options，
* 配置 maven.
* Run/Debug Configuration
  - click + 
  - select Application ,write Name : Bootstrap;
  - Main class org.apache.catalina.startup.Bootstrap

* VM options参数：
```
-Dcatalina.home=catalina-home -Dcatalina.base=catalina-home
-Djava.endorsed.dirs=catalina-home/endorsed -Djava.io.tmpdir=catalina-home/temp
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=catalina-home/conf/logging.properties

```

* use classpath of module:tomcat7


* 然后Run Bootstrap

* 启动完成以后: http://localhost:8080