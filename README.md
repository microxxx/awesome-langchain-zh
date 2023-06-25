# awesome-langchain-zh
awesome-langchain 中文版

## 目录
- 🦜🔗 LangChain优秀项目 [4] 
- 目录[5]
- LangChain框架[6]
- 工具[7]
    - 低代码[8]
    - 服务[9]
    - 代理[10]
    - 模板[11]
- 开源项目[12]
    - 知识管理[13]
    - 其他 / 聊天机器人[14]
- 学习[15]
    - 笔记本[16]
    - 视频[17]
    - 文章[18]
- 替代品[19]
- 补充这个列表[20]

## LangChain框架
- LangChain[21]: 原始的🐍
- LangChain.js[22]: js版本的兄弟✨
- 概念[23]: Langchain概念文档
- Twitter账户[24]: 关注以获取最新更新
- Youtube频道[25]
- Discord[26]: 讨论
- Langchain博客[27]: 官方Langchain博客
- LangChainHub[28]: 收集所有对于使用LangChain原始概念（如提示，链和代理）有用的工件的集合
- LangChainHub[29]: 收集所有对于使用LangChain原始概念（如提示，链和代理）有用的工件的集合。LangChainHub的灵感来自于Hugging Face Hub，它是一个集合，包含所有对于使用LangChain原始概念（如提示，链和代理）有用的工件。这个仓库的目标是成为分享和发现高质量提示，链和代理的中心资源，这些元素结合在一起形成复杂的LLM应用。我们希望这个仓库能够开始收集提示，并期待LangChain社区能够增加这个集合。我们希望不久后能够扩展到链和代理。

## 工具
---------------
### 低代码
- Langflow[30]: LangFlow是一个为LangChain设计的用户界面，使用react-flow设计，通过拖放组件和聊天框，可以轻松地进行实验和原型流程。
- Flowise - LangchainJS UI[31]: Flowise是一个拖放用户界面，可以使用LangchainJS构建自定义的LLM流程。
- Databerry[32]: Databerry是一个无代码平台，用于构建自定义的LLM代理。它提供了一个用户友好的解决方案，可以快速在您的个人数据上设置语义搜索系统，无需任何技术知识。
- LangchainUI[33]: LangChain UI是一个开源的聊天AI工具包，基于LangChain构建，任何人都可以使用无代码类型的界面创建和托管聊天机器人。
- Yeager.ai[34]: Yeager.ai Agent是第一个为Langchain设计的代理创建器，旨在帮助您轻松构建、原型设计和部署AI驱动的代理。Yeager.ai Agent强调灵活性、交互性和无缝集成，是开发人员、研究人员和AI爱好者的理想工具。

### 服务
- GPTCache[35]: 一个用于创建LLM查询的语义缓存的库
- Gorilla[36]: 一个LLM的API商店
- LlamaHub[37]: 由社区制作的LLM数据加载器的库
- EVAL[38]: 具有Langchain的弹性多功能代理。将执行您的所有请求。
- Auto-evaluator[39]: 一个轻量级的用于使用Langchain进行问题回答评估的工具
- Langchain visualizer[40]: LangChain工作流的可视化和调试工具
- LLM Strategy[41]: 使用LLM实现策略模式
- datasetGPT[42]: 一个命令行界面，用于使用LLM生成文本和对话数据集。
- spellbook-forge[43]: 使您的LLM提示可执行和版本控制。
- Auto Evaluator[44]: Langchain自动评估器
- Jina[45]: 使用Jina在生产环境中的Langchain应用
- Gradio Tools[46]: Gradio 🤝 LLM代理
- steamship-langchain[47]: 为Steamship提供的LangChain适配器，使LangChain开发者能够快速地在Steamship上部署他们的应用程序，自动获得：
    - 生产就绪的API端点
    - 跨依赖项/后端的水平扩展
    - 应用状态（包括缓存）的持久存储
    - 内置的Authn/z支持
    - 多租户支持
    - 与其他Steamship技能（例如音频转录）的无缝集成
    - 使用指标和日志
    - 更多...
- LangForge[48]: 用于创建和部署LangChain应用的工具包
- BentoChain[49]: 在BentoML上部署LangChain
- LangCorn[50]: 使用FastApi自动服务LangChain应用
- Langchain Service[51]: 带有Qdrant向量存储和Kong网关的Langchain设置
- Lanarky[52]: 🚢 使用FastAPI快速部署生产就绪的LLM项目
- Dify[53]: 一个API用于插件和数据集，一个界面用于提示工程和视觉操作，所有这些都用于创建强大的AI应用。
- LangchainJS Worker[54]: 在cloudflare上的LangchainJS worker
- Chainlit[55]: 在几分钟内构建Python LLM应用 ⚡️
- Zep[56]: Zep: 一个用于LLM / 聊天机器人应用的长期记忆存储
- Langchain Decorators[57]: 这是一个在LangChain顶部提供语法糖的库，用于编写自定义的langchain提示和链。主要原则和优点包括：
    - 更Pythonic的编写代码方式
    - 编写多行提示，不会因为缩进而打断你的代码流
    - 利用IDE内置的提示、类型检查和弹出文档，快速查看函数以查看提示、消耗的参数等
    - 利用LangChain生态系统的全部力量
    - 添加对可选参数的支持
    - 通过将参数绑定到一个类，轻松地在提示之间共享参数
    - 这是一个非官方的附加到langchain库的插件，它并不试图竞争，只是试图使其使用更加容易。这里的许多想法都是完全主观的。

### 代理
- CollosalAI Chat[58]: 实现了与Colossal-AI项目驱动的LLM与RLHF的整合
- AgentGPT[59]: 使用Langchain和OpenAI的AI代理（Vercel / Nextjs）
- Local GPT[60]: 受Private GPT的启发，用Vicuna-7B模型替换了GPT4ALL模型，并使用InstructorEmbeddings代替LlamaEmbeddings
- ThinkGPT[61]: 代理技术可以增强你的LLM并将其推向极限
- Camel-AutoGPT[62]: 为LLMs和自动代理（如BabyAGI和AutoGPT）提供角色扮演方法
- Private GPT[63]: 使用GPT的力量私下与你的文件互动，100%私密，无数据泄漏
- RasaGPT[64]: RasaGPT是基于Rasa和Langchain构建的第一个无头LLM聊天机器人平台
- SkyAGI[65]: 在LLM代理中出现的人类行为模拟能力
- PyCodeAGI[66]: 一个小型的AGI实验，根据用户想要构建的应用生成Python应用
- BabyAGI UI[67]: 让在web应用中运行和开发babyagi变得更容易，就像ChatGPT一样
- SuperAgent[68]: 将LLM代理部署到生产环境
- Voyager[69]: 一个开放式的、具有大型语言模型的实体代理
- ix[70]: 自主的GPT-4代理平台
- DuetGPT[71]: 一个半自主的对话式开发助手，AI配对编程，无需复制粘贴。

### 模板
- create-t3-turbo-ai[72]: 基于 t3 的，适合 Langchain 的模板，用于构建类型安全，全栈，LLM 动力的带有 Nextjs 和 Prisma 的网络应用程序
- LangChain.js LLM 模板[73]: LangChain LLM 模板，可以让你训练你自己的定制 AI LLM 模型。
- Streamlit 模板[74]: 如何在 Streamlit 上部署 LangChain 的模板
- Codespaces 模板[75]: 一个 Codespaces 模板，帮你在几秒内启动并运行 LangChain！
- Gradio 模板[76]: 如何在 Gradio 上部署 LangChain 的模板

### 平台
- Modal[77]: 为云/ML 计算提供端到端的堆栈
- Metal[78]: Metal 是一种托管服务，使你无需烦恼地管理基础设施就能构建 AI 产品
- Graphsignal[79]: 针对 AI 代理和 LLM 驱动的应用的可观察性。在生产中追踪，监控和调试 LangChain。

## 开源项目
-------
### 知识管理
- Quiver[80]: 将你的大脑知识倾倒入你的 GenerativeAI Vault
- DocsGPT[81]: GPT 动力的聊天，用于文档搜索和帮助。
- Knowledge GPT[82]: 为你的文档提供准确的答案和即时引用。
- Knowledge[83]: Knowledge 是一个工具，用于保存，搜索，访问和探索你所有喜欢的网站，文档和文件。
- Anything LLM[84]: 一款全栈应用，将任何文档转化为智能聊天机器人，具有优雅的用户界面和更简单的工作区管理方式。

### 其他 / 聊天机器人
- AudioGPT[85]: 理解和生成语音，音乐，声音和会说话的头部
- Paper QA[86]: 用于回答带有引用文献的文档问题的 LLM Chain
- Chat Langchain[87]: 专注于在 LangChain 文档上回答问题的本地托管聊天机器人
- Langchain Chat[88]: 另一个用于 LangChain 聊天的 Next.js 前端.
- Book GPT[89]: 丢一本书，开始提问.
- Chat LangchainJS[90]: Chat Langchain 的 NextJS 版本
- Doc Search[91]: 与书籍对话 - 使用 GPT-3 构建
- Fact Checker[92]: 使用 langchain 核实 LLM 输出的事实
- MM ReAct[93]: 多模态 ReAct 设计
- QABot[94]: 使用 langchain 和 openai 通过自然语言查询查询本地或远程文件或数据库
- GPT Automator[95]: 你的语音控制 Mac 助手.
- Teams LangchainJS[96]: 展示 LangChainJS 与 Teams / Bot Framework bots 的演示
- ChatGPT[97]: 适用于 node.js & Docker的 ChatGPT & langchain 示例
- FlowGPT[98]: 使用 AI 生成图表
- langchain-text-summarizer[99]: 使用 LangChain 汇总文本的样本 streamlit 应用程序
- Langchain Chat Websocket[100]: 关于 LangChain LLM 聊天，通过 websockets 进行流响应
- langchain_yt_tools[101]: Langchain 工具，用于搜索/提取/转录 Youtube 视频的文本副本
- SmartPilot[102]: 利用 OpenAI 的语言模型生成，分析，并选择给定问题的最佳答案的 Python 程序
- Howdol[103]: 一个能回答问题的帮助聊天机器人
- MrsStax[104]: QA Slack 机器人
- ThoughtSource⚡[105]: 机器思维科学的框架
- ChatGPT Langchain[106]: 在 Huggingface 上使用 langchain 的 ChatGPT 克隆
- Chat Math Techniques[107]: 在 Huggingface 上使用数学技术的 langchain 聊天
- Notion QA[108]: Notion 问题回答机器人
- QNimGPT[109]: 与 IBM 量子计算机模拟器或 OpenAI GPT-3.5 玩 Nim 游戏
- ChatPDF[110]: 结合 Azure OpenAI 的 ChatGPT + 企业数据
- Chat with Scanned Documents[111]: 与使用 Dynamic Web TWAIN 扫描的文档进行对话的演示。
- snowChat ❄️[112]: 与你的 Snowflake 数据库聊天
- DB GPT[113]: 使用本地 GPT 与您的数据和环境互动，无数据泄漏，100% 私有，100% 安全
- Psychic[114]: 面向非结构化数据的通用 API。将 SaaS 工具的文档同步到 SQL 或向量数据库，这样就可以很容易地由像 ChatGPT 这样的 AI 应用程序查询。
- Airtable-QnA[115]: 🌟 一个用于你的 Airtable 内容的问答工具
- WingmanAI[116]: 用于与系统和麦克风音频的实时转录进行交互的工具
- TutorGPT[117]: 用于辅导任务的动态少数元提示。
- Cheshire Cat[118]: 具有即用型聊天集成和插件开发平台的自定义 AGI 机器人。
- Got Chaat Bot[119]: 用于创建权力的游戏聊天机器人的仓库（例如：和 Tyrion Lannister 对话）
- Dialoqbase[120]: 允许你用自己的知识库创建自定义聊天机器人的网页应用
- CSV-AI 🧠[121]: CSV-AI 是由 LangChain 驱动的终极应用，它可以帮助你在 CSV 文件中发现隐藏的洞察。
- MindGeniusAI[122]: 用 ChatGPT 自动生成 MindMap

## 学习
-----
### 笔记本
- Langchain 教程[123]: 对 LangChain 库的概述和教程
- LangChain 中文入门指南[124]: 面向初学者的中文 LangChain 教程
- Flan5 LLM[125]: 使用 LangChain 进行 PDF 问答，进行思维链条和多任务指导，Flan5 在 HuggingFace 上
- LangChain 手册[126]: Pinecone / James Briggs 的 LangChain 手册
- 查询 YouTube 视频字幕[127]: 查询 YouTube 视频字幕，返回时间戳作为来源以证实答案
- llm-lobbyist[128]: 大型语言模型作为公司游说者
- Langchain 语义搜索[129]: 使用 GPT3，LangChain 和 Python 搜索和索引你自己的 Google Drive 文件
- GPT 政治指南针[130]
- llm-grovers-search-party[131]: 利用 Qiskit，OpenAI 和 LangChain 展示 Grover 算法
- TextWorld ReAct Agent[132]
- LangChain <> Wolfram Alpha[133]
- 自建知识图谱[134]

### 视频
- 用于 LLM 应用开发的 LangChain[135]
- Sam Witteveen 的 LangChain 系列[136]
- LangChain 教程播放列表[137]
- James Briggs 的 LangChain 播放列表[138]
- 什么是 LangChain? - LangChain + ChatGPT 概述[139]
- LangChain 演示 + Harrison Chase 的问答[140]
- 用于 LLM 的 LangChain...基本上就是一个 Ansible 剧本[141] (David Shapiro)
- 独立数据播放列表[142]
- Langchain Agent 网络研讨会[143]
- 带有 LangChain 的 BabyAGI[144]
- Python 中的 LangChain 教程 - 快速教程[145]
- LangChain 快速课程：构建 AutoGPT [146] (Nicholas Renotte)
- LangChain 和 LLM Agent 的未来[147]

### 文章
- 使用 GPT3、LangChain 和 Python 构建 GitHub 支持机器人[148]
- 大型语言模型（LLM）API 构建框架的崛起[149]
- 如何使用 LangChain 🦜🔗 和 GPT-3 自动化我的老板 🤖[150]
- 使用 Cohere 和 Langchain 的多语言语义搜索[151]
- Haystack 和 LangChain 如何赋能大型语言模型[152]
- DataIndependent 教程[153]
- 使用 Redis、LangChain 和 OpenAI 构建电商聊天机器人[154]
- LangChain 入门：构建 LLM 驱动的应用的初学者指南[155]
- 如何使用 LangChain 和 LLM Agent 监控微调您的 LLM 应用[156]
- 使用记忆构建一个简单的 ChatGPT CLI[157]
- 使用 BentoML、LangChain 和 Gradio 部署语音聊天机器人[158]
- PromptChap 上的 LangChain 教程[159]
- 使用 Pyodide、LangChain 和 OpenAI 创建代码解释器聊天机器人[160]
- LangChain 已添加 Cypher 搜索[161]
- Langchain 解码[162]
- 使用 Python 和 Langchain 在本地实现 GPT4All[163]
- 用 LangChain 让你的 GDrive 拥有 GPT 功能[164]

## 替代品
----
- Transformers Agents[165]：在 transformers 的基础上提供自然语言 API
- LlamaIndex[166]：为你的 LLM 提供一个集中接口来连接外部数据。
- Botpress[167]：构建聊天机器人的构建块
- Haystack[168]：使用 Transformer 模型和 LLM 与你的数据进行交互的 NLP 框架
- Semantic Kernel[169]：Microsoft 的 C# SDK，可快速轻松地将最先进的 LLM 技术集成到你的应用中
- Promptify[170]：Prompt Engineering | 使用 GPT 或其他基于提示的模型获取结构化输出。
- PromptSource[171]：关于创建、共享和使用自然语言提示的工具包。
- Agent-LLM[172]：一个人工智能自动化平台。
- LLM Agents[173]：构建由 LLM 控制的代理
- MiniChain[174]：用于与大型语言模型编码的微小库。
- Griptape[175]：Python 框架，用于具有链式思维推理、外部工具和记忆的 AI 工作流和管道。
- llm-chain[176]：一个强大的 rust 库，用于在 LLM 中构建链，让你能够总结文本和完成复杂任务。
- BoxCars[177]：Ruby 宝石，使用 Boxcars 和 LLM 构建可组合的应用程序。受 LangChain 启发。
- LangTorch[178]：使用 Java / JVM 构建可组合的 LLM 应用程序。受 LangChain 启发。
- Langchain Go[179]：Golang Langchain
- LangchainRb[180]：Ruby Langchain
- PromptFlow[181]：创建可执行的流程图，将 LLM (大型语言模型)，提示符，Python 函数和条件逻辑链接在一起。
- OpenLM[182]：一个可以从任何其他托管推断 API 调用 LLM 的开源兼容 OpenAI 的库。同样支持 Typescript[183]
- Dust[184]：设计和部署大型语言模型应用程序
- e2b[185]：开源平台，用于构建和部署虚拟开发者代理
- SuperAGI[186]：一个以开发者为先的开源自主人工智能代理框架。
- SmartGPT[187]：一个程序，提供 LLM 通过插件完成复杂任务的能力。
- TermGPT[188]：赋予 GPT-4 等大型语言模型计划和执行终端命令的能力
- ReLLM[189]：用于语言模型完成的正则表达式。
- OpenDAN[190]：开源的个人 AI 操作系统，将各种 AI 模块整合在一个地方供您个人使用。

## 补充此列表
--------
- Open LLMs[191]: 一份可供商业使用的公开LLM列表
- Awesome LLM[192]: Awesome-LLM：精选的大型语言模型资源列表。
- LLaMA Cult and More[193]: 跟踪适价LLM、羊驼Cult等更多内容。
