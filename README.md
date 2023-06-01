# 个人简介
李明宇，中科院计算所高级工程师，开源项目活跃开发者，20 余年编程与软件开发经验。历任国家重点实验室课题组负责人，上市公司事业群技术总监、首席技术专家。荣获中国软件协会“优秀CTO”等多项荣誉，兼任中国新一代IT产业联盟分委会秘书长、全国高校人工智能与大数据创新联盟专家委员、北京开源创新委员会委员。

# 当我们谈论GPT，我们在谈论什么？
## 几个相关的概念
**大模型**，或 “大型语言模型” LLM（Large Language Model）
各种大模型：

<img width="900" alt="image" src="https://luxiangdong.com/images/AILLMs.png">

Ref: https://www.luxiangdong.com/2023/04/16/llms/

还有很多，不断涌现，比如深信服安全GPT、HuggingFace的HuggingChat

能力评估：GPT为业界标杆，其他模型努力向GPT-3.5看齐。目前有一种评估方法即以GPT-4作为裁判，将各大模型能力和GPT-3.5作对比。数据集的影响：Brad vs GPT-4


**AIGC**，AI-generated Content“人工智能生成内容”，或“生成式人工智能”

**GPT**，“Generative **Pretraining** Transformer”生成式预训练Transformer模型

<img width="800" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/ab9f9c1e-1792-497b-a69d-b48c271ddf2c">

Ref: https://www.tsinghua.edu.cn/info/1175/102317.htm

**ChatGPT**: 
- 针对对话场景基于GPT经过“微调”的大语言模型，
- 基于 GPT-3.5 和 GPT-4 的 Web应用

**GAI**，“General Artificial Intelligence”通用人工智能

### GPT-3.5 的回答：

<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/b6e5b144-5faf-4f7f-a15f-4ca943a900a6">

### GPT-4 的回答：

<img width="600" alt="image" src="https://github.com/OpenRHINO/RHINO-Operator/assets/20229719/583d3a2c-4486-42be-80ac-bc099e79fbe7">

# Let's Chat
5 min 分配账号、测试

每组4人，分5个小组

10 min 自由提问

20 min 分享讨论

https://chat.openai.com/share/438ff19c-8b2b-4d0a-a198-652a4b6978e7

https://chat.openai.com/share/e7f8f149-14fe-4eb8-975c-369ced4efb3d

https://chat.openai.com/share/a5d2c957-476b-4e1e-b49f-20692117321d  

https://chat.openai.com/share/ef01510a-a471-4977-a2be-e6be543b8f9d 

https://chat.openai.com/share/a7dd7c6a-a21b-4853-868a-a402d0b42808 

**对内：**
- 培训、咨询（我问你答）
- 会议纪要、公文撰写、方案设计（缩写、扩写、换角度写）
- 面试、评估（你问我答）

**对外：**
- 客服
- 舆情监测
- 内容创作、检查
- 招投标、合同评审

**GPT for IT：**
- 数据分析
- 方案设计与软件开发
- 辅助运维

**一个比较完整的例子（模拟案例）：**

https://chat.openai.com/share/7b90b468-3223-415f-b8cf-a6ebb969bc29 

# GPT-3.5 和 GPT-4 的能力差异
一只熊在地上放了一罐蜂蜜，它往南走了一百米，又往西走了一百米，最后往北走了一百米，又回到了那罐蜂蜜那里。请问这只熊是什么颜色的？

生成代码的Bug数量（推理能力、序列长度）

## 能力/差距从何而来？

大

### 大

## 更大

| 模型  | 发布时间    | 参数量    | 预训练数据量 |
|------|-------------|----------|-------------|
| GPT  | 2018 年 6 月| 1.17 亿 | 约 5GB     |
| GPT-2| 2019 年 2 月| 15 亿   | 40GB       |
| GPT-3| 2020 年 5 月| 1,750 亿| 45TB       |

<img width="450" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/1e980fca-dba3-4e57-8ce7-fc4c08c73584">

https://chat.openai.com/share/a8dbdef7-74d8-4891-9654-0d0c8d936361

## "参数"是什么？
<img width="272" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/44854336-3dbd-495b-8033-7b3e9f335ce8"><br>
Neural Network<br>
<img width="400" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/b189edf2-45e6-4d7c-962e-4ceafeafc7a3"><br>
Deep Neural Network<br>
<img width="500" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/da9f5df0-567f-4199-9632-bcf9a2a910f6"><br>


<img width="700" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/e43db5c0-66b3-46ba-9a84-4a4d0d3a1034">

### “大力出奇迹”

# GPT的原理
<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/4aef49d5-e48f-440a-88bd-52c2b825d7d2"><br>
<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/eb00d66a-b8fe-44a2-a58a-fb67bcdf5018"><br>
<img width="600" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/ec4fcf11-dc38-44c5-8654-a171dd7fe765"><br>
<img width="500" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/7e83361c-b884-4110-81ff-ce210e4d02df"><br>
<img width="500" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/21516584-9b7a-494d-afd2-18ff0128d4b3"><br>
<img width="500" alt="image" src="https://github.com/LI-Mingyu/GPTdev-tutorial/assets/20229719/d8c7008c-e157-4afc-9462-07e542e1f3dc"><br>


# 个人主页 or shell 编程实操

# 一些实际案例
- https://chat.openai.com/c/a49e15a9-d374-46ae-a68c-25cf2cd30eac （具体程序实现）
- https://chat.openai.com/c/89074061-ba05-4a98-bce0-375f1628984e （方案设计）
- https://chat.openai.com/c/5219e499-45a6-409c-86ab-ae8b2d31da9d （市场监管从方案到代码，模拟）
- https://github.com/OpenRHINO/GPT-Assist （GPT辅助CICD）

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
### 设置OpenAI API环境

- 如何获取API密钥

https://platform.openai.com/account/api-keys

- 安装所需的库（例如Python的openai库）
```
pip install openai
```
- 配置环境变量
```
export OPENAI_API_KEY=your-api-key
```
```
set OPENAI_API_KEY=your-api-key
```

### OpenAI API的使用步骤

- 初始化API客户端

- 创建请求：选择模型、设置参数、构造输入
https://platform.openai.com/docs/api-reference

- 发送请求并获取响应

- 解析响应和构造最终结果

### 深入与提高

- 探索不同的API参数和选项

- 请求频率限制 & 请求和响应的大小限制

- 异常处理：API Key无效、参数错误、限流……

- 管理API请求以优化成本

### 实践：一个简单的OpenAI API调用示例
## 接入DevOps（两种Deployment/Job）

</br>

# 项目实战
## 需求理解与代码生成
## 代码review和改进
## 日志与故障分析
## 自动化测试

例子：weibo数据抓取与情感分析

# 扩展讨论
