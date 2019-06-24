# JavaWeb Servlet Project - 酒店房间预定系统

Servlet 3.1 

标准JavaWebServlet项目，给有需要的人

没有用到maven，后续在加

IDEA导入此项目后需要做的一些配置：
https://blog.csdn.net/yhao2014/article/details/45740111

每部分包内可能包含一个子README.md，用于解释一些代码的意义

感谢https://github.com/moiseyenko/FinalProject

# 目录文件结构说明
```
.
├── README.md
├── sql
├── src
│   ├── by
│   │   └── epam
│   │       └── hotel
│   │           ├── command
│   │           ├── controller
│   │           ├── customtags
│   │           ├── dao
│   │           ├── entity
│   │           ├── exception
│   │           ├── filter
│   │           ├── listener
│   │           ├── pool
│   │           ├── service
│   │           └── util
│   │               ├── constant
│   │               ├── type
│   │               └── validator
│   ├── log4j2.xml
│   └── resource
│       ├── config.properties
│       ├── db.properties
│       ├── i18n
│       └── mail.properties
├── test
└── WebContent
    ├── css
    ├── index.jsp
    ├── jsp
    │   ├── admin
    │   ├── client
    │   ├── common
    │   └── error
    └── WEB-INF
        ├── classes
        ├── lib
        ├── tld
        └── web.xml

```

# 数据持久

纯JDBC，自己写的连接池。

这个可以自己改写成mybatis或者其他数据持久层框架

# 控制层

实现了一个小型的控制层框架。Controller类控制了所有的url请求，Router类控制了之后的转发！非常值得学习借鉴

# View层

Jsp，不谈了，我不喜欢Jsp

# 尾

整体架构就这些，非常不错的原生JavaWeb项目，用到的框架很少，纯javaWebServlet