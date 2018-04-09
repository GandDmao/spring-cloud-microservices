# spring-cloud-microservices 
通过天气预报项目学习微服务治理相关知识

## 项目介绍
> 这是一个天气预报微服务治理项目，项目的业务功能很简单：用户可以通过城市列表选择查看城市天气信息(当然天气信息有第三方提供).
项目以SpringBoot为基础的框架，通过SpringCloud的各种组件将过往单体架构的项目(micro-weather-quartz)转换成分布式的多个微服务。
具体包含的微服务为：
* EurekaServer 服务注册与发现微服务
* CityService 城市数据api微服务
* DataService 天气数据api微服务
* CollectionService 数据采集微服务
* ReportService 天气预报微服务
* GateWayService 网关微服务

## 项目环境
* JDK 1.8
* IDEA 2017.3
* Gradle 4
* HttpClient 4.5.3
* Redis 3.2
* SpringBoot 2.0.0.RELEASE
* Spring Cloud Finchley.M9

## 项目实现(主要)

## 感谢
通过老卫的教学视频，让自己对微服务方面知识有一定的了解。


