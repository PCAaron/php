# PHP
> PHP：超文本预处理器

## 开发环境
> 常用的PHP环境搭建有：LAMP(Linux+Apache+MySQL+php)，LNMP(Linux+Nginx+MySQL+php)，LNAMP(
Linux+Apache+Nginx+MySQL+php)，WAMP(Window+Apache+MySQL+php),独立安装，集成安装(wampserver，
xampp，phpstudy等)

## 什么是集成环境包
> 学习php需安装网页服务器、数据库服务器和php语言核心的解释器。而将这些合在一起的即集成环境包。
常用的集成环境包有AppServ，PHPStudy，APMserv，XAMPP，WAMPServer等（代表的不同集成环境包的名字）。
对入门开发来说，选择集成环境包的原则：1.更新快，版本新；2.操作简单易上手；3.选择项不多

### PHPstudy
> [http://www.phpstudy.net/ ](http://www.phpstudy.net/ )
集成：Apache+PHP+MySQL+phpMyAdmin+ZendOptimizer

## 开发工具(IDE)
> 1.NotePad++
> 2.phpstorm： [https://www.jetbrains.com/phpstorm/ ](https://www.jetbrains.com/phpstorm/ )
> 3.Atom:[https://atom.io/](https://atom.io/)

## PHP能做什么
1. 服务端脚本
> 需具备：PHP解析器（CGI或者服务器模块）、web服务器、web浏览器
2. 命令行脚本
> 仅需PHP解析器
3. 编写桌面应用程序
> 可通过PHP-GTK(PHP的扩展)来实现

## 语言参考
### 基本语法
1. PHP标记
2. 从HTML中分离
3. 指令分隔符
4. 注释
### 类型
1. Boolean布尔类型
2. Integer整型
3. Float浮点型
4. String字符串
5. Array数组
6. Object对象
7. Resource资源类型
8. NULL
9. Callback/Callable类型
10. 伪类型与变量
11. 类型转换的判别
### 变量
1. 预定义变量
2. 变量范围
3. 可变变量
4. PHP之外的变量
### 常量
1. 语法
2. 魔术常量
### 表达式
### 预算符
1. 运算符优先级
2. 算术运算符
3. 赋值运算符
4. 位运算符
5. 比较运算符
6. 错误控制运算符
7. 执行运算符
8. 递增/递减运算符
9. 逻辑运算符
10. 字符串运算符
11. 数组运算符
12. 类型运算符
### 流程控制
1. if
2. else
3. elseif/else if
4. 流程控制的替代语法
5. while
6. do-while
7. for
8. foreach
9. break
10. continue
11. switch
12. declare
13. return
14. require
15. include
16. require_once
17. include_once
18. goto
### 函数
1. 用户自定义函数
2. 函数的参数
3. 返回值
4. 可变函数
5. 内部（内置）函数
6. 匿名函数
### 类与对象
1. 基本概念
2. 属性
3. 类常量
4. 类的自动加载
5. 构造函数和析构函数
6. 访问控制（可见性）
7. 对象继承
8. 范围解析操作符（::）
9. Static（静态）关键字
10. 抽象类
11. 对象接口
12. Trait
13. 匿名类
14. 重载
15. 遍历对象
16. 魔术方法
17. Final 关键字
18. 对象复制
19. 对象比较
20. 类型约束
21. 后期静态绑定
22. 对象和引用
23. 对象序列化
24. OOP变更日志
### 命名空间
1. 定义命名空间
2. 定义子命名空间
3. 在同一个文件中定义多个命名空间
4. 使用命名空间：基础
5. 命名空间和动态语言特征
6. namespace关键字和__NAMESPACE__常量
7. 使用命名空间：别名/导入
8. 全局空间
9. 使用命名空间：后备全局函数/常量
10. 名称解析规则
### Errors
1. Basics
2. PHP 7错误处理
### 异常处理
### 生成器
### 引用的解释
### 预定义变量
1. 超全局变量-在全部作用域中始终可用的内置变量
2. $GLOBALS-引用全局作用域中可用的全部变量
3. $_server-服务器和执行环境信息
4. $_GET-HTPP GET变量
5. $_POST-HTTP POST变量
6. $_FILES--HTTP 文件上传变量
7. $_REQUEST-HTTP REQUEST变量
8. $_SESSION-session变量
9. $_ENV-环境变量
10. $_COOKIE-HTTP Cookies
11. $php_errormsg-前一个错误信息
12. $HTTP_RAW_POST_DATA-原生post数据
13. $http_response_header-HTTP响应头
14. $argc-传递给脚本的参数数目
15. $argv-传递给脚本的参数数组
### 预定义异常
### 预定义接口
1. 遍历-Traversable（遍历）接口
2. 迭代器-Iterator（迭代器）接口
3. 聚合式迭代器-IteratorAggregate（聚合式迭代器）接口
4. 数组式访问-ArrayAccess（数组式访问）接口
5. 序列化-序列化接口
6. Closure-Closure类
7. 生成器-生成器类
### 上下文选项和参数
### 支持的协议和封装协议
1. file:// -访问本地文件系统
2. http:// -访问HTTP（s）网址
3. ftp:// -访问FTP(s)URLs
4. php:// -访问各个输入/输出流（I/O streams）
5. zlib:// -压缩流
6. data:// -数据（PFC 2397）
7. glob:// -查找匹配的文件路径模式
8. phar:// -PHP归档
9. ssh2:// -Secure Shell 2
10. rar:// -RAR
11. ogg:// -音频流
12. expect:// -处理交互式的流
