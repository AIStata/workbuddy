# [【免费】DeepseekHarness-Workbuddy、AIStata MCP、DID Agent系列综合应用专题公开课](https://mp.weixin.qq.com/s/urEp1yhTq91T6jkxkQwtoQ)


# ✅️本仓库内容为Workbuddy专题的直播课资料

> 课程前后将更新全部内容！

---
&emsp;


> 来源：数量经济学微信公众号（计量经济学服务中心）
>
> 数量经济学 &emsp; [计量经济网](https://www.aistata.cn/)  || [AI 工具导航](https://www.aistata.cn/AITools/) || [2017-2026年，10年Stata经典课程](https://www.aistata.cn/)  || [DID专题知识库](https://www.aistata.cn/blogs/DID2023.html)  || [AI 知识库](https://www.aistata.cn/2025AI.html)


> ### [计量经济网](https://www.aistata.cn/)
>
> 10年间，计量经济网依托于微信公众平台等累积了计量经济学及Eviews、Stata、SPSS、Matlab、Geoda、Python、ArcGIS、R等相关方法及软件操作的优质资源，旨在为大家分享经管人文社科等领域的相关知识，希望能帮助读者更好的学习计量。

&emsp;



> ### [DeepseekHarness + Stata 专题公开课在线书籍](https://aistata.github.io/deepseek-harness-metrics/)



## 🌈❤️最新Stata课程--2017-2026年，数量经济学Stata课程已开设10年，10年Stata经典课程报名中！

![](https://stata101.oss-cn-chengdu.aliyuncs.com/fig-metrics/Stata%E8%AF%BE%E7%A8%8B%E5%AE%A3%E4%BC%A0%E5%9B%BE%E7%89%87.png)

&emsp;



# 2026-2027公开课简介



2026年下半年，数量经济学继续推出更多前沿系列公开课，包括 DeepseekHarness、Workbuddy、豆包工作等多智能体系列公开课，覆盖数量经济学微信公众号开发的 **AIStata MCP、Stata-Kernel-Jupyer** 等系列智能体综合应用。

会用 AI 的研究生，正在悄悄拉开差距：多智能体平台 × Stata 专业插件，重构经济学实证工作流，这也是本次系列公开课将讲到的科研"新杠杆"：智能体平台 + Stata 领域专业插件 / 智能体综合应用。



# **一、趋势：智能体平台，正在成为科研的"新操作系统"**

过去两年，AI 领域的竞争焦点已经从"谁的模型更聪明"转向"**谁能把事做完**"。

这个转向的技术支点，是一个叫 **MCP（Model Context Protocol）** 的开放协议。它做的事很朴素：**把"能力"标准化成可插拔的接口**。任何模型、任何平台，只要支持 MCP，就能调用同一个外部工具——读文件、跑数据库、发邮件、执行代码、操作软件。

这件事，放在 Stata 领域，主要采用 Stata MCP （或MCP For Stata等）作为与 Claude Code 等AI智能体交互的主要Stata工具，采用ClaudeCode + StataMCP 驱动一篇篇顶刊论文的复现与稳健性检验等工作。

但这些方法，都需要在 VsCode 等软件中，采用命令方式对 Claude Code、Codex等进行MCP 配置，这里面就会涉及UV 包管理等内容，对于 ClaudeCode 、Codex 等 AI 工具操作难易程度不一。

进入2026年9月，这件事有了质的飞跃——可以采用 AIStata MCP + 多智能体协作。

由数量经济学微信公众号团队开发的 **AIStata MCP** 全面适配 **Workbuddy、Trae、ClaudeCode、Codex** 等主流 AI 智能体（Workbuddy、Trae等国产工具更适合国内使用习惯），鼠标一点，即可进行环境检查，一键接入全部智能体。

利用 AIStata MCP 等多个AI智能体，从数据清洗到因果识别、结果输出和论文复现，全流程由多智能体协作完成（详见[AIStata MCP全面适配Workbuddy、Trae、ClaudeCode等主流AIAgent，附论文复现展示！](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770556&idx=1&sn=a4fb8f2bce01c511dd2f1d255e7d7c9a&scene=21#wechat_redirect)）。

目前，数量经济学微信公众号针对DeepseekHarness、Workbuddy、ClaudeCode、豆包工作、ClaudeCode、Codex等开发了多个插件、扩展、MCP、连接器等，全面适配这些主流智能体平台，将过去10年Stata经典课程中涉及的计量知识沉淀下来，全面融入AI 平台，这也就是本次公开课将为大家演示的 Stata 系列智能体综合应用。



# **二、多智能体平台：不是选一个最强的，而是配一套最顺的**

先看全貌（以下定位为实际使用观察，非官方参数）：

| 平台                 | 形态                    | 它最强的地方                                               | 在实证研究里的典型用法                                       |
| :------------------- | :---------------------- | :--------------------------------------------------------- | :----------------------------------------------------------- |
| **WorkBuddy**        | 桌面智能体工作台        | 连接器生态成熟、可挂载 MCP、有技能与专家体系、中文环境原生 | **当"总控台"**：把数据、Stata、文献、写作串成一条流程；公开课演讲开发的内置 AIStata / Stata-Kernel 连接器，可直接调度 Stata |
| **豆包工作**         | 桌面 AI 办公助手        | 中文表达与文档处理强、支持自定义 STDIO 连接器、上手门槛低  | 添加开发的AIStata / Stata-Kernel 连接器                      |
| **DeepSeek Harness** | 桌面 / 编码 Agent 环境  | 推理链扎实、长上下文、可挂 MCP                             | **当"审稿人"**：让它挑识别策略的漏洞、评估稳健性方案是否够用 |
| **Trae Work**        | AI IDE（国内版 / SOLO） | 编辑器内闭环，边写边跑、就地改代码                         | do 文件调试、交互式探索分析、边看结果边改模型设定            |
| **Claude Code**      | 终端编码 Agent          | 能读整个项目、长任务不跑偏、重构能力强                     | 复现包工程化、批量生成稳健性检验代码、do 文件规范化改造      |
| **Codex**            | 自主编码 Agent          | 任务托管、跨文件自主执行                                   | 长时任务托管：多模型批量估计、整份复现包构建                 |

**怎么理解这张表？**

在本次DeepseekHarness、Workbuddy、AIStata MCP、DID Agent系列综合应用专题公开课上，我们将针对性专题介绍这些主流智能体平台应用，其中就包括目前Stata领域，大家很少应用到的豆包工作、DeepseekHarness的综合应用等。



# **三、DeepseekHarness-Workbuddy、AIStata MCP、DID Agent系列专题公开课预告！**

# 1、DeepseekHarness-Stata公开课

# 2、Workbuddy-Stata公开课

[2027年 AIStata MCP+ Workbuddy+Claude等智能体+Stata学术应用](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770688&idx=2&sn=37010b36137e31be1959881929ae217e&scene=21#wechat_redirect)

[Workbuddy 接入 StataMCP 入门指南](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770675&idx=1&sn=19724e5feadc63e56c2847380c027a23&scene=21#wechat_redirect)

[AIStata MCP全面适配Workbuddy、Trae、ClaudeCode等主流AIAgent，附论文复现展示!](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770556&idx=1&sn=a4fb8f2bce01c511dd2f1d255e7d7c9a&scene=21#wechat_redirect)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/598Tr639EmPhbquo7Iw9OOkNHpkbWPs3Hb2XfqS3Zj6icdmG12yazN3e5VOQ4gS8TwbPf0HlCYnBjdCIrgv1ayNvQBUWqqeVkMszaRfGZ3Ag/640?wx_fmt=png&from=appmsg&watermark=1&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=2)

Workbuddy 中加入Stata-Kernel-Jupyter +AIStata  MCP、DID工作流 等相关MCP工具能力



# 3、豆包工作--智能体-前沿应用**

[豆包工作 + 论文复现](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770662&idx=1&sn=4c6c5cb65ecec2d7134c43dba543794f&scene=21#wechat_redirect)

[Stata-Kernel-Jupyter 在豆包工作中的使用入门指南](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770672&idx=1&sn=b8df4f050581543e44f008c6d0524713&scene=21#wechat_redirect)

[我在 豆包工作 里面跑 Stata 代码](https://mp.weixin.qq.com/s?__biz=MjM5NTM4NjU2OA==&mid=2650770651&idx=1&sn=179721060d58c1cc9f262b8d1f3080c8&scene=21#wechat_redirect)



# **4、Stata-Kernel-Jupyter智能体应用**

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/598Tr639EmMpqtdX0K0WXRnTmMmIs1hVSARGA6iarM4HQxPYVjMjCLq8eGsOkYbqnrP5PP1NxuuD7rFMAonqbFwuMqmfNgOvg7xDLo7XDzkk/640?wx_fmt=png&from=appmsg&watermark=1&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=6)

**Stata-Kernel-Jupyter，扩展插件Beta测试版已经免费上线2周+，可以免费下载**

使用过程中遇见问题，可以Workbuddy等解决，或者微信后台、公开课中反馈



# 5、Stata工作流智能体应用**

![图片](https://mmbiz.qpic.cn/mmbiz_png/598Tr639EmOfib9eKH2Z7sRIsg09DXW5YA4AEw2tClr3icTTf5sMXFeUAzeSefAXX0aWUANLicxicugSBTVFXXe5dftC6Dt7LSwykm5lTzVQDkY/640?wx_fmt=png&from=appmsg&watermark=1&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=7)

开发的 Stata 工作流扩展插件，可以实现Stata 全流程操作应用，并且也支持加入MCP相关能力



另外还包括之前经常介绍的高级计量经济专题、现代DID专题、双重机器学习 、AI智能体前沿应用等内容！







---


## 🎓 计量经济网

- 10年间，计量经济网依托于微信公众平台等累积了计量经济学及Eviews、Stata、SPSS、Matlab、Geoda、Python、ArcGIS、R等相关方法及软件操作的优质资源，旨在为大家分享经管人文社科等领域的相关知识，希望能帮助读者更好的学习计量。
- 📚 [计量经济网主页](https://www.aistata.cn) — 计量学术科研服务平台
- 🔧 [AI 工具导航](https://www.aistata.cn/AITools/) — AI 工具集合，助你效率翻倍
- 📈 [高级计量及Stata应用课程](https://www.aistata.cn/AITools/) — 2017-2026年，10年Stata经典课程

---



## 💡 温馨提示

> 更多资源，欢迎关注数量经济学微信公众号、计量经济网

---



## 📧 联系我们

如有疑问或建议，欢迎通过 [计量经济网](https://www.aistata.cn) 与我们取得联系。

---

⭐ 如果对你有帮助，请给本仓库一个 Star！





