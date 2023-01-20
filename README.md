# 《ChatGPT AI 问答助手》开源项目

>大家好，我是技术UP主，小傅哥。13年毕业，大厂互联网T8架构师，全网40万粉编程知识博主。

- :bus: 作品：[`CodeGuide | 程序员编码指南`](https://github.com/fuzhengwei/CodeGuide) | [`RoadMap 编程路书`](https://github.com/fuzhengwei/RoadMap) | [`Java 数据结构和算法`](https://github.com/fuzhengwei/java-algorithms) | [`IM 仿微信`](https://github.com/fuzhengwei/NaiveChat) | [`Java 面经手册`](https://github.com/fuzhengwei/interview) | [`IntelliJ IDEA 插件开发`](https://github.com/fuzhengwei/guide-idea-plugin) | [`Lottery 抽奖系统 - 基于领域驱动设计的四层架构实践`](https://github.com/fuzhengwei/Lottery) | [`API网关`](https://github.com/fuzhengwei/api-gateway) | [`手写Spring`](https://github.com/fuzhengwei/small-spring) | [`手写MyBatis`](https://github.com/fuzhengwei/small-mybatis) | [`设计模式`](https://github.com/fuzhengwei/itstack-demo-design) | [`Netty 实战案例`](https://github.com/fuzhengwei/itstack-demo-netty) | [`字节码编程`](https://github.com/fuzhengwei/itstack-demo-bytecode) | [更多搜索...](https://github.com/fuzhengwei?tab=repositories)
- :seedling: 干货：[公众号『 bugstack虫洞栈 』](https://bugstack.cn/images/personal/qrcode.png)
- :pencil: 博客：[bugstack.cn](https://bugstack.cn/) - 足够硬核，内容老狠了！
- :tv: 视频：[B站 小傅哥の码场](https://space.bilibili.com/15637440)
- :love_letter: 微信：[fustack](https://bugstack.cn/images/personal/fustack.png) - 备注来意
- :feet: 我的编程知识星球：[实战生产级项目、手写框架级源码，可以向我 1对1 提问，解答技术/职场/规划问题](https://bugstack.cn/md/zsxq/introduce.html)

## ⛳ 目录

- [Github](https://github.com/fuzhengwei/chatbot-api) | [Gitcode](https://gitcode.net/fuzhengwei/chatbot-api)
- [1. 项目介绍](#1-项目介绍)
- [2. 课程目录](#2-课程目录)
- [3. 加入星球](#3-加入星球) - 体验 ChatGPT 使用
- [4. 版权说明](#4-版权说明)

### 1. 项目介绍

❤️ 这个项目本身是小傅哥为自己的知识星球开发的一个智能问答回复系统，用于帮助读者解决一些常见的技术问题，提高回答效率也减少小傅哥的对此类问题的时间投入。通过演示我们可以看到，有了这样一个智能AI问答助手，可以大大的减少很多对于这些通用类技术问题的回复，同时也可以把这样的问答内容沉淀到知识星球，方便其他人学习使用。

《ChatGPT AI 问答助手》这样一个项目，要用到哪些技术手段呢？它包含；SpringBoot、DDD架构、Github仓库使用、接口爬虫、AI接口对接、定时任务、镜像打包、Docker容器部署等内容。

可以说麻雀虽小，五脏俱全。代码量不大但流程很完整，对于正在学习Java的伙伴来说，非常具有学习价值。

为了让粉丝伙伴更好的学习这个项目，小傅哥把它免费开源出来，并且是录制好对应的视频课程，一行行带着大家手写代码学习这个项目。

包括工程的创建、Github仓库使用、push代码等，因为只有这样才能让更多新人有一条进入学习编程的大门。

**注意**：
1. 技术栈：Java、SpringBoot、爬虫、ChatGPT、job、Docker
2. OpenAi Keys 申请：[https://beta.openai.com/account/api-keys](https://beta.openai.com/account/api-keys) - 用于处理扫码知识星球问题进行调用获取答案。**如果你申请时遇到一些问，可以加小傅哥微信【fustack】付费20元申请**
3. 在学习的过程中，可以看到每一个章节都有一个对应的代码分支，可以把代码拉取到本地切换到对应的分支进行对照学习。

### 2. 课程目录

| 目录 - `点击章节进入到学习视频`                          | Github                                                       | Gitcode                                                      |
| -------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 开篇介绍，学习引导                                       |                                                              |                                                              |
| 第1节：SpringBoot DDD 工程创建和 Github/Gitcode 仓库使用 | [【23_xfg_init_project】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_init_project) | [【23_xfg_init_project】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_init_project) |
| 第2节：创建知识星球，爬取接口信息                        | [【23_xfg_zsxq_api】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_zsxq_api) | [【23_xfg_zsxq_api】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_zsxq_api) |
| 第3节：知识星球接口领域服务开发                          | [【23_xfg_zsxq_domain】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_zsxq_domain) | [【23_xfg_zsxq_domain】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_zsxq_domain) |
| 第4节：对接ChatGPT，调用接口                             | [【23_xfg_chatgpt】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_chatgpt) | [【23_xfg_chatgpt】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_chatgpt) |
| 第5节：整合知识星球与ChatGPT，完成自动化回答             | [【23_xfg_job】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_job) | [【23_xfg_job】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_job) |
| 第6节：打包镜像文件，部署服务到 Docker 容器              | [【23_xfg_docker】](https://github.com/fuzhengwei/chatbot-api/tree/23_xfg_docker) | [【23_xfg_docker】](https://gitcode.net/fuzhengwei/chatbot-api/-/tree/23_xfg_docker) |

### 3. 加入星球【ChatGPT AI 问答助手】

你可以通过微信扫码，加入知识星球【ChatGPT AI 问答助手】，在手机端对ChatGPT进行提问。

<div align="center">
    <img src="https://bugstack.cn/images/system/zsxq/zsxq-ai.jpeg?raw=true" width="350px">
</div>

### 4. 版权说明

此项目为 Apache License 2.0 开源协议项目，以学习为目的进行创作，禁止培训机构、私人号主、公司组织等以各类收费形式进行销售。如果你有合作诉求，请与小傅哥联系获得书面授权，微信：fustack 