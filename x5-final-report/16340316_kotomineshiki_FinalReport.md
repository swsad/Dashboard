##  个人小结

在该项目中，我主要负责UI设计、产品分析、验收测试的部分。整体上来看，我的git commit主要集中于前期对整个产品的需求分析和设计的部分，后期的一个波峰是对产品进行黑盒用例测试的设计和执行；从单个迭代来看我的提交波峰处于单次迭代的中前期，暗合与软件开发的流程和模型。

## PSP2.1 估计

|                                       | **Personal Software Process Stages**   | **Time (%)** |
| ------------------------------------- | -------------------------------------- | ------------ |
| **Planning**                          | **计划**                               | **15**        |
| estimate                              | 预估任务时间                           | 15            |
| **Development**                       | **开发**                               | **65**      |
| analysis                              | 需求分析                               | 15           |
| design spec                           | 生成设计文档                           | 15            |
| estimate                              | 设计复审                               | 5            |
| coding standard                       | 代码规范                               | 0            |
| design                                | 具体设计                               | 20           |
| coding                                | 具体编码                               | 0           |
| code review                           | 代码复审                               | 0           |
| test                                  | 测试                                   | 15           |
| **Report**                            | **报告**                               | **20**       |
| test report                           | 测试报告                               | 10         |
| size measurement                      | 计算工作量                             | 8            |
| postmortem & process improvement plan | 每次迭代结束后进行总结，并提出改进计划 | 2            |

## 主要工作清单

### [UI设计](https://github.com/swsad/Dashboard/blob/master/documents/UI_design/UI_design)

这一部分主要包含UI设计和用例设计，采用螺旋模型的迭代-反馈机制在每次迭代中对设计进行修改。同时后期还要兼顾功能的实现能力修改部分需求和对应的UI。

考量到Axure平台对微信小程序的交互模型资料和工具不多，本身也没法直接导出可用的前端代码，使用axure做可交互原型性价比不高，所以这次选用了制作静态原型的工具 Adobe AI。

### 竞品分析和前期调研

产出分别为：
[产品愿景](https://github.com/swsad/Dashboard/blob/master/documents/project_vision/projection_vision) 


[竞品分析](https://github.com/swsad/Dashboard/blob/master/documents/competitive_analysis/competitive_analysis)

这一部分主要是作为需求分析和设计的素材，采用了使用问卷星发布问卷的方式来进行调查。

### [黑盒测试](https://github.com/swsad/Dashboard/blob/master/documents/blackbox_design/blackbox_test)
这一部分主要对产品进行验收和测试。是弱鲁棒性的测试。

### 记录最得意/或有价值/或有苦劳的工作清单

UI设计是我工作量最大的部分。主要是因为每次迭代的开发阶段中都会对一些需求进行修改和微调，来回返工次数比较多，而且比较琐碎，UI设计处于整个流程的上游，所以也不太敢拖沓。我本身也是第一次制作UI原型，花费时间比较多。具体也要考量到实现的工作量和工作难度来调整设计。

最有价值的是黑盒测试，保证了产品的质量。我几乎对所有可动的部分都进行了测试，发现了很多因为没做鲁棒性处理导致的问题。

## 个人博客清单

[平面原型设计工具-Adobe AI入门]（https://blog.csdn.net/kotomineshiki/article/details/94333016）

[面向设计师、产品的GitHubDesktop入门培训] (https://blog.csdn.net/kotomineshiki/article/details/94358688 )

###  特别感谢
- FantasticGold，解决了项目收尾时的诸多琐碎的细微bug，站好最后一班。

- Boooooby，解决了诸多技术难点，使得产品不至于砍需求来保证可用性。

- Yasoxh6，尽可能调了微信的前端库，高效地完成了工作，使得我们的开发成本和规模大大降低。

- Castle, 敏锐地在设计时发现了诸多漏洞，御敌于千里之外。