# 项目介绍及团队分工

## （一）项目介绍及现状描述

本项目为**永澄老师公众号文章备份项目**，即将易仁永澄微信公众号**永澄老师（YCmentor）** 中，所有文章包括文章留言的部分全部备份到github上。

本项目由易仁永澄发起，由若晓沐担当项目经理，负责整个项目的推进、协同和管理。本项目从2017年03月15日启动，原计划项目截止时间暂不确定，由项目成员许小小丽负责公众号的所有文章备份，截止2017年04月10日，已完成9篇文章的备份。但由于许小小丽个人正恰好处于实习期，需要20天左右无法参与项目推进，因此项目组决定许小小丽实习期间项目暂时搁置。

2017年04月10日，项目发起人给出了关于项目截止时间的最新期待，即争取15天之内完成所有文章的备份工作。因此为了加快项目进度，项目组决定扩大项目团队，重新安排团队的工作分配。经过项目调整，现项目团队邀请加入了3位新成员加入，即 moonlight、kcalm、李牛牛三位伙伴。项目截止时间定为4月28日。

## （二）项目成员角色分配

### 1. 项目发起人

- 所属成员：易仁永澄
- 工作职责：负责验收整个项目成果，对项目成果质量进行把控和评估
- 任务分工
  - 协同项目经理制定项目中的各种标准化流程、规则和工作模板
  - 定期验收项目阶段性成果
  - 对整个项目管理提供指导性建议


### 2. 项目经理

- 所属成员：若晓沐

- 工作职责：负责整个项目的进度管理、质量把控、以及团队沟通协同

- 任务分工

  - 制定项目中的所有标准化流程、规则和工作模板
  - 监控团队成员的工作进度和质量
  - 扫除项目协同中的各项障碍，促进团队成员的任务推进


### 3. 内容生产者

- 所属成员：易仁永澄
- 工作职责：负责公众号文章的内容编辑和文章评论筛选
- 任务分工

  - 提供公众号备份文章及文章评论
  - 提供待备份文章的关键数据到Github for runwithcc的指定仓库的issues中


### 4. 内容管理者

- 所属成员：许丽、 moonlight、kcalm、李牛牛、若晓沐
- 工作职责：负责公众号文章及文章评论的备份和整理工作
- 任务分工

  - 公众号文章备份
  - 文章留言备份
  - 公众号基本数据管理
- 具体任务分配：详见
  

## （三）主要任务描述

### 1. 文章备份流程
将永澄老师（YCmentor）公众号中的所有文章托管在github上。

![文章备份](https://raw.githubusercontent.com/ruoxiaomu/IPIC/master/flowsheet/article-backups.png)


### 2. 文章留言备份流程
对永澄老师（YCmentor）公众号中所有文章的上墙精选留言进行托管。

![留言备份](https://github.com/ruoxiaomu/IPIC/blob/master/flowsheet/message-backups%20.png)

### 3. 公众号基本数据管理
统计汇总永澄老师（YCmentor）公众号所有文章的基本信息数据，并登记在公众号登记.xlsx中

## （四）协同方式流程

![分支协同](https://raw.githubusercontent.com/ruoxiaomu/IPIC/master/flowsheet/github-workflow-2.png)

- step1：登录github，在页面上方搜索栏搜索“runwithcc”。
- step2：在搜索结果中，选中User，找到用户名为【runwithcc】的用户，并点击进入个人主页。
- step3：在Repositories中找到名为 【ZP_weixinRiGeng】的仓库，并点击进入。
- step4：找到页面右上方的Fork按钮，进行仓库派生。
- step5：在派生的ZP_weixinRiGeng中，将Branch从master切换到由自己昵称命名的分支
- step6：根据task-allocation .md的任务安排和[New workflow.md的操作指南推进任务
- step7：完成任务后，点击New pull request
- step8：选择pull request 分支。base分支为自己昵称命名的分支，compare分支为runwithcc。
- step9：点击 create pull request 完成 pull request 创建。

