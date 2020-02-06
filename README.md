# 使用AI推动医疗智能

抗击新型冠状肺炎疫情，为武汉加油！

### 209nCoV-AI网址
- **Github**：https://2019ncov-ai.github.io/2019nCoV-AI/
- **在线X/CT影像检测**：https://www.ct2019ncov.com http://121.41.90.149



## 背景
2019年底，新型冠状病毒在武汉突发，短时间内全国上下全力防疫。
这个国家的英雄的人民，上前线不眠不休的护士，捡废品捐钱的老人，自发接送医生的志愿者司机，普通老百姓的义工，彻夜不停的建筑工人，捐钱捐物的海外学子，这疫情越凶险形势越残酷，我们心头的那捧血也越来越热。
此时此刻，我们要做点什么，安静而坚定。
    
我们想为疫情为防疫做出努力，我们查找相关的国内国外资料和专业论文，
幸运的找到吴恩达老师关于AI识别肺炎的论文（https://stanfordmlgroup.github.io/projects/chexnet/）。
这帮助我们从一小步开始，在吴恩达老师论文基础上快速开发一个通过CT影像照片快速判断肺炎的系统，辅助快速筛查是否感染肺炎，帮忙医生或病人提前做好准备，而在地市县级等医疗能力医疗资源紧张的区域，或许能缓解医疗压力。
    
我们自知能力有限，期望得到更多的帮助和支持，望万众一心打赢这场不见硝烟的战争！

未来，以此希望中国的医疗能够更加高效智能，并将“使用AI推动医疗智能”这一个小小的愿望埋在我们心里，愿世界更美好！



### 说明
我们生在武汉、长在武汉、学在武汉、成家在武汉、立业在武汉， 生于斯长于斯，我们的武汉只是病了，武汉本来就是一座英雄的城市！
我们是一群IT老兵，我们在通过GitHub开源社区，我们构建一个通过CT影像快速筛查的肺炎的开源系统，帮助医疗资源不足的市县级医院、社区医院和病人了解病情。

- **Slack社区**：[2019ncov-ai.slack.com](http://2010ncov-ai.slack.com)
- **[Slack邀请](https://join.slack.com/t/2019ncov-ai/shared_invite/enQtOTM3MTE3MTk2OTY3LTA0YmMwMGI3ZTJjNDI3NTJkNDM1MTNkYzdhNjA1ZGM2MzlhNWYzMTU4YTBlNTZiZDg2YjBjZDEzOTYyMjYwNTc)**



## 思路（现阶段）
- 第一步
  - **建立开源系统**
  搭建基础模块，提供简单界面可上传X/CT影像可识别肺炎。
- 第二步
  - **1 建立标准接口**
  提供标准接口，让参与到这个开源项目的单位和个人可调用算法识别。
  - **2 非冠肺炎识别**
  根据非冠肺炎的X/CT影像进行训练实现非冠识别。
- 第三步
  - **扩展及优化**
  对系统功能进行扩展实现14个病类的分析。
  对系统进行优化提供更多个性化功能。


## 该平台主要开源项目
- [2019nCoV-AI]
- [开源项目]
    - [前台入口]
    - [训练数据]
    - [算法优化]
    - [后台脚本]
- [参考文献]
- [接口文档]
