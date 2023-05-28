# 个人简介
李明宇，中科院计算所高级工程师，开源项目活跃开发者，20 余年编程与软件开发经验。历任国家重点实验室课题组负责人，上市公司事业群技术总监、首席技术专家。荣获中国软件协会“优秀CTO”等多项荣誉，兼任中国新一代IT产业联盟分委会秘书长、全国高校人工智能与大数据创新联盟专家委员、北京开源创新委员会委员。

# 当我们谈论GPT，我们在谈论什么？
GPT、ChatGPT、AIGC、LLM、GAI

GPT-3.5 的回答：

<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/b6e5b144-5faf-4f7f-a15f-4ca943a900a6">

GPT-4 的回答：

<img width="600" alt="image" src="https://github.com/OpenRHINO/RHINO-Operator/assets/20229719/583d3a2c-4486-42be-80ac-bc099e79fbe7">

各种大模型：

<img width="900" alt="image" src="https://luxiangdong.com/images/AILLMs.png">

Ref: https://www.luxiangdong.com/2023/04/16/llms/

# Let's Chat

10 min 自由提问

20 min 分享讨论

# GPT-3.5 和 GPT-4 的能力差异
一只熊在地上放了一罐蜂蜜，它往南走了一百米，又往西走了一百米，最后往北走了一百米，又回到了那罐蜂蜜那里。请问这只熊是什么颜色的？

生成代码的Bug数量（推理能力、序列长度）

## 能力/差距从何而来？
<font size="3">大</font>、<font size="5">大、</font><font size="6">更</font><font size="7">大</font>
| 模型  | 发布时间    | 参数量    | 预训练数据量 |
|------|-------------|----------|-------------|
| GPT  | 2018 年 6 月| 1.17 亿 | 约 5GB     |
| GPT-2| 2019 年 2 月| 15 亿   | 40GB       |
| GPT-3| 2020 年 5 月| 1,750 亿| 45TB       |

<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/e43db5c0-66b3-46ba-9a84-4a4d0d3a1034">

“大力出奇迹”

# GPT的原理
<img width="1483" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/4aef49d5-e48f-440a-88bd-52c2b825d7d2">
<img width="1178" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/eb00d66a-b8fe-44a2-a58a-fb67bcdf5018">
<img width="1558" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/ec4fcf11-dc38-44c5-8654-a171dd7fe765">
<img width="1186" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/7e83361c-b884-4110-81ff-ce210e4d02df">
<img width="1256" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/21516584-9b7a-494d-afd2-18ff0128d4b3">
<img width="1312" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/d8c7008c-e157-4afc-9462-07e542e1f3dc">


# 个人主页 or shell 编程实操

# 一些实际案例
- https://chat.openai.com/c/a49e15a9-d374-46ae-a68c-25cf2cd30eac
- https://github.com/OpenRHINO/GPT-Assist

## 实践总结
1. 由于目前API调用的限制，和Copilot-X等工具现在排队的现状，目前对于一线程序员来说，最快的用上GPT-4的方法仍然是通过ChatGPT。
2. 即便是与ChatGPT合作实现一个完整模块，起点也不一定是从一个自然语言需求出发，也可以是给他一段代码参考并且简单描述需要做的事情，或者从伪代码转成可以运行的代码，这样可能更合适。
3. 期间经常会有bug出现，但是GPT-4比GPT-3.5已经好很多了，这个就是编程领域里Chat兄“一本正经的胡说八道”的体现。所以完全依赖Chat从自然语言生成可执行代码尚不现实，需要人工review和调整。
4. 单元测试，如果你不想写的话，让它来干是再合适不过了！
5. 有时候沟通时间长了，它会“忘记”完整的上下文，需要不时帮他回顾，这个也算是prompt技巧之一吧。
6. 目前即便是GPT-4尚缺少面向对象的能力，所以架构方面的优化更指望不上了。但是在人类的提示下，它可以帮忙完成类的封装，类的具体代码实现。
7. 帮忙做代码review也是很重要的工作，包括虽然ChatGPT在出错的时候认错态度很好，但他认为自己“正确”的时候也会坚持自己的观点。
8. 防止沉迷，拒绝依赖

# 基于GPT的机器人开发基础
## API调用及实践
## 接入DevOps（两种Deployment/Job）


# 项目实战
## 需求理解与代码生成
## 代码review和改进
## 日志与故障分析
## 自动化测试

# 扩展讨论
- 方案设计与招投标评估
- 面试

- 大语言模型有视觉吗？
https://chat.openai.com/c/f34a90fa-8d63-4f34-b093-1ab10d829990
<img width="543" alt="image" src="https://github.com/LI-Mingyu/GPT-md/assets/20229719/23243d5f-1050-4d68-bb8d-48c3e968a718">
<img width="543" alt="image" src="https://github.com/LI-Mingyu/GPT-md/assets/20229719/8ecd7d91-1ce6-4030-b028-1562c8de44fb">

- AI和人谁更擅长“搞定人”

- 蒸汽机发明后世界究竟发生了什么变化？
