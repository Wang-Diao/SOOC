# SOOC
基于微服务的小型开放式课堂是一个网络课堂系统，类似于慕课(MOOC)，网站提供了职业技能培训的相关课程，如：软件开发培训、职业资格证书培训、学历教育培训等课程。项目基于B2B2C的业务模式，培训机构可以在平台入驻、发布课程，运营人员对发布的课程进行审核，审核通过后课程才可以发布成功，课程包括免费和收费两种形式，对于免费课程可以直接选课学习，对于收费课程在选课后需要支付成功才可以继续学习。

本项目包括用户端、机构端、运营端三个端。核心模块包括：内容管理、媒资管理、课程搜索、订单支付、选课管理、认证授权等。采用前后端分离架构，后端采用SpringBoot、SpringCloud技术栈开发，数据库使用了MySQL，还使用了Redis、消息队列、分布式文件系统、Elasticsearch等中间件系统。

划分的微服务包括：内容管理服务、媒资管理服务、搜索服务、订单支付服务、 学习中心服务、系统管理服务、认证授权服务、网关服务、注册中心服务、配置中心服务等。
