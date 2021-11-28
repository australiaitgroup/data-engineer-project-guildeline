# Data Engineer bootcamp project guideline
Data Engineer bootcamp project guideline

## 项目名称： 推荐系统实战项目 – 网络零售商品推荐

### 项目简介

此项目的商业目标是通过分析和处理网络零售商客户的三百多万条订单和销售数据，搭建一个推荐系统来辅助产品的市场销售。这个项目非常全面的涵盖了一个商业数据项目最实用的内容：从需求分析做起，一直到数据处理，数据架构搭建，机器建模和可视化。通过这个项目学生可以学习到如何在AWS云上搭建数据库以及数据流程，用大数据工具处理和转换数据，分析数据和搭建模型，最后把项目产品化并且创造价值。你将会了解到如何在AWS 上用搭建数据湖，用AWS service去处理数据，然后整合并且搭建数据ETL流程，最后用机器学习模型去建立一个数据产品的app。此项目包含了多个数据文件，处理和建模的过程中用到了很多云上的解决方案，项目综合性很高，有很好的广度和深度，考验了学生如何处理在真实的商业环境中所遇到的问题。学生们在项目中所汲取的经验可以直接被应用到工作中。

### 核心技术

1. AWS数据湖搭建
2. 数据流程协调整合
3. 数据模型构建
4. 大数据引擎应用
5. 数据产品开发
6. 机器学习模型构建
7. 在线/离线推荐

### 项目架构图

![blockchain](/project-architecture.png "区块链")

### 项目实施流程

- Week1：在AWS云上搭建数据湖
- Week2：用SQL对数据进行分析和处理，并且应用到AWS的服务中
- Week3：对数据进行处理并且搭建流程（ETL）
- Week4：使用云计算进行大数据的分析和处理
- Week5：机器学习在本地的应用
- Week6：机器学习在云端的应用和数据产品创建
- Week7：对数据产品进行迭代以及流程改进

### 项目数据下载链接
https://drive.google.com/file/d/1pNNVQxAnhbOvvAagUoTsvk-pPjSgr4GZ/view?usp=sharing

### Data Engineer注意事项
1. Data Engineer由于会有大量的云端操作的过程，养成好的工作日志记录习惯，会帮助你未来找工作，未来工作中Troubleshooting是有帮助的
2. DevOps是来Support工作的，Data Engineer需要保持自己组内的节奏进行工作。由于Data Engineer的工作很多跟云打交道，所以公司里DevOps是管理云服务的，Data Engineer日常工作中会经常跟DevOps打交道
3. 由于组员会有Data Engineer和DevOps Engineer参加，会对大家的沟通能力Commnunication有了新的挑战，也尝试在过程中总结出自己的高效沟通方法论

### DevOps任务

1. 帮助搭建针对于Lambda， API Gateway的CI/CD pipeline，搭建至少两个环境：UAT和Production
2. 组内workshop：帮助Data Engineer 同学理解什么是CI/CD pipeline以及什么是UAT和production环境
3. 帮助搭建针对于Steps function的CICD pipeline，搭建至少两个环境：UAT和Production
4. 使用Terraform或者AWS cloudformation或者Ansible对上述的服务进行 Infrastructure As Code改写
5. 组内workshop：帮助DE同学理解、学习、甚至使用Terraform等Infrastructure As Code
6. 帮助搭建不同环境的数据库等，根据DE项目使用的数据库而定，搭建至少两个环境：UAT和Production
7. 有余力的组，可以帮助搭建Grafana，Elastic Search 等系统monitor工具，监控项目的healthy情况，performance情况等

#### DevOps注意事项
1. 由于Data Engineer会使用众多云服务，而且云服务很多来自不同的服务商，这会对DevOps的工作有新的挑战，DevOps需要去快速学习使用的云服务，然后去判断是否需要介入DevOps。
2. Data Engineer并不是所有的服务都适合使用CI/CD Pipeline, 要从几点判断：
   1. DE本身使用的服务支不支持CICD，是不是可编程化或者可代码化服务
   2. DE所用到的某个服务是否有必要CICD
   3. 如果服务是纯GUI操作，那DevOps没有办法介入
3. DevOps是来Support Data Engineer的工作，并不是主导DE的工作
4. DevOps工作由于有大量的操作内容，DevOps需要养成做好工作日志记录的习惯，否则很快就会忘记自己做的内容，会帮助你未来找工作，未来工作中Troubleshooting是有帮助的
5. DevOps的在DE工作中会有新的communication的挑战
6. DevOps的组内Workshop经验，可以写到简历里，公司比较看重喜欢跟Team打成一片，并且能够带领Team学习，share knowledge的DevOps，这也是DevOps工作中常常做的分享活动。



[数据工程全栈班](https://jiangren.com.au/program-course/data-engineer-data-analyst)

