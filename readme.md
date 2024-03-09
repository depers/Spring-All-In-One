# Spring全家桶

## 项目列表

### chapter1 Spring入门

| 序号 | 目录         | 介绍                                               |
| ---- | ------------ | -------------------------------------------------- |
| 1    | hello-spring | 一个简单的Spring Boot项目，打印并输出一个hello接口 |   |

### chapter2 Spring中的数据操作
| 序号 | 目录                          | 介绍                                                         |
| ---- | ----------------------------- | ------------------------------------------------------------ |
| 1    | datasource-dome-1             | 演示了Spring Boot自动配置的数据源                            |
| 2    | datasource-dome-2             | 演示了通过h2数据库演示了如何在Spring Boot项目中自动配置数据源、事务管理器和JDBC操作的模板类。 |
| 3    | pure-spring-datasource-demo   | 演示了通过applicationContent.xml或是注解手动配置数据源。     |
| 4    | multi-datasource-demo         | 如何配置多数据源</br>方法一：配置@Primary类型的Bean</br>方法二：排除Spring Boot的自动配置，手动配置数据源和事务管理器。这里演示的是该方法。 |
| 5    | druid-demo                    | 这个项目中演示了Druid的使用，主要有密码加密、SQL防注入和自定义过滤器功能。 |
| 6    | simple-jdbc-demo              | 这个项目主要演示了JDBCTemplate和NamedParameterJdbcTemplate的使用方法。 |
| 7    | declarative-transaction-demo  | 演示了Spring声明式事务的简单使用                             |
| 6    | programmatic-transaction-demo | 演示了Spring编程式事务的简单使用                             |


### chapter3 使用Spring开发Web应用
| 序号 | 目录 | 介绍 |
| ---- | ---- | ---- |
|      |      |      |
### chapter4 使用Spring开发微服务
| 序号 | 目录                             | 介绍                                                         |
| ---- | -------------------------------- | ------------------------------------------------------------ |
| 1    | circuit-break-demo               | 通过切面实现自己的熔断策略                                   |
| 2    | consul-waiter-service            | 一个提供服务的下游系统                                       |
|      | hystrix-customer-service         | 介绍了Hystrix的熔断的两种配置方式</br>1.在controller层声明@HystrixCommand</br>2.在@FeignClient声明fallback |
| 4    | hystrix-dashboard-demo           | 该项目是一个用于单机熔断信息的监控                           |
| 5    | hystrix-stream-customer-service  | 这个服务和hystrix-customer-service项目的代码内容基本一样，不同的是他暴露了用于监控和管理应用程序的运行状态的所有端点（接口） |
| 6    | turbine-demo                     | 对集群实现熔断信息的监控                                     |
| 7    | resilience4j-circuitbreaker-demo | 使用resilience4j实现熔断机制                                 |
| 8    | bulkhead-customer-service        | 使用resilience4j实现针对下流系统调用的限流                   |
|      | ratelimiter-waiter-service       | 使用resilience4j实现对自身系统的一个限流功能                 |
