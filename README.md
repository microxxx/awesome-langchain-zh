# awesome-langchain-zh
awesome-langchain 中文版

🔥🔥🔥 [企业级llm工具Llmware](https://github.com/llmware-ai/llmware)🔥🔥🔥   

## 目录
- [awesome-langchain-zh](#awesome-langchain-zh)
  - [目录](#目录)
  - [LangChain框架](#langchain框架)
  - [其他语言移植版本](#其他语言移植版本)
  - [工具](#工具)
    - [低代码](#低代码)
    - [服务](#服务)
    - [代理](#代理)
    - [模板](#模板)
    - [平台](#平台)
  - [开源项目](#开源项目)
    - [知识管理](#知识管理)
    - [其他聊天机器人](#其他聊天机器人)
  - [学习](#学习)
    - [笔记本](#笔记本)
    - [视频](#视频)
    - [文章](#文章)
  - [其他LLM框架](#其他llm框架)
  - [补充](#补充)
  - [不维护](#不维护)

## LangChain框架
- [LangChain](https://github.com/langchain-ai/langchain)  ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social):  原始的🐍
- [LangChain.js](https://github.com/langchain-ai/langchainjs)  ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchainjs?style=social): js版本的兄弟✨
- [langgraph](https://github.com/langchain-ai/langgraph)  ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=social): 基于langchain 的 rag或agent框架
- [概念](https://docs.langchain.com/docs/): Langchain概念文档
- [Twitter账户](https://twitter.com/LangChainAI): 关注以获取最新更新
- [Youtube频道](https://www.youtube.com/channel/UCC-lyoTfSrcJzA1ab3APAgw)
- [Discord](https://discord.gg/6adMQxSpJS): 讨论
- [Langchain博客](https://blog.langchain.dev/): 官方Langchain博客
- [LangChainHub](https://github.com/hwchase17/langchain-hub)  ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain-hub?style=social): 收集所有对于使用LangChain原始概念（如提示，链和代理）有用的工件的集合,LangChainHub的灵感来自于Hugging Face Hub，它是一个集合，包含所有对于使用LangChain原始概念（如提示，链和代理）有用的工件。这个仓库的目标是成为分享和发现高质量提示，链和代理的中心资源，这些元素结合在一起形成复杂的LLM应用。我们希望这个仓库能够开始收集提示，并期待LangChain社区能够增加这个集合。我们希望不久后能够扩展到链和代理。
- [LangServe](https://github.com/langchain-ai/langserve) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langserve?style=social): LangServe 帮助开发者把LLM应用部署成REST API. 

## 其他语言移植版本
langchain 其他语言的移植版本.
- [Langchain Go](https://github.com/tmc/langchaingo) ![GitHub Repo stars](https://img.shields.io/github/stars/tmc/langchaingo?style=social):Golang Langchain
- [LangchainRb](https://github.com/andreibondarev/langchainrb) ![GitHub Repo stars](https://img.shields.io/github/stars/andreibondarev/langchainrb?style=social):Ruby Langchain
- [BoxCars](https://github.com/BoxcarsAI/boxcars) ![GitHub Repo stars](https://img.shields.io/github/stars/BoxcarsAI/boxcars?style=social):Ruby 宝石，使用 Boxcars 和 LLM 构建可组合的应用程序。受 LangChain 启发。
- [LangTorch](https://github.com/Knowly-ai/langtorch) ![GitHub Repo stars](https://img.shields.io/github/stars/Knowly-ai/langtorch?style=social):使用 Java / JVM 构建可组合的 LLM 应用程序。受 LangChain 启发。
- [LangChain4j](https://github.com/langchain4j/langchain4j) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain4j/langchain4j?style=social): 用于java的LangChain
- [LangChainJSDotNet](https://github.com/iassafc/LangChainJSDotNet) ![GitHub Repo stars](https://img.shields.io/github/stars/iassafc/LangChainJSDotNet?style=social): .NET Langchain
- [LangChainDart](https://github.com/davidmigloz/langchain_dart) ![GitHub Repo stars](https://img.shields.io/github/stars/davidmigloz/langchain_dart?style=social): Dart/Flutter langchain. 


## 工具

### 低代码
- [Langflow](https://github.com/logspace-ai/langflow) ![GitHub Repo stars](https://img.shields.io/github/stars/logspace-ai/langflow?style=social): LangFlow是一个为LangChain设计的用户界面，使用react-flow设计，通过拖放组件和聊天框，可以轻松地进行实验和原型流程。
- [Flowise](https://github.com/FlowiseAI/Flowise) ![GitHub Repo stars](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social): Flowise是一个拖放用户界面，可以使用LangchainJS构建自定义的LLM流程。
- [FlowTest](https://github.com/FlowTestAI/FlowTest)  ![GitHub Repo stars](https://img.shields.io/github/stars/FlowTestAI/FlowTest?style=social): 基于LLM的API 工作流 管理IDE工具

### 服务
- [GPTCache](https://github.com/zilliztech/GPTCache)  ![GitHub Repo stars](https://img.shields.io/github/stars/zilliztech/GPTCache?style=social) : 一个用于创建LLM查询的语义缓存的库
- [Gorilla](https://github.com/ShishirPatil/gorilla) ![GitHub Repo stars](https://img.shields.io/github/stars/ShishirPatil/gorilla?style=social) : 一个LLM的API商店
- [LlamaHub](https://github.com/emptycrown/llama-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/emptycrown/llama-hub?style=social): 由社区制作的LLM数据加载器的库
- [EVAL](https://github.com/corca-ai/EVAL) ![GitHub Repo stars](https://img.shields.io/github/stars/corca-ai/EVAL?style=social): 具有Langchain的弹性多功能代理。将执行您的所有请求。
- [Auto-evaluator](https://github.com/PineappleExpress808/auto-evaluator) ![GitHub Repo stars](https://img.shields.io/github/stars/PineappleExpress808/auto-evaluator?style=social): 一个轻量级的用于使用Langchain进行问题回答评估的工具
- [Langchain visualizer](https://github.com/amosjyng/langchain-visualizer) ![GitHub Repo stars](https://img.shields.io/github/stars/amosjyng/langchain-visualizer?style=social): LangChain工作流的可视化和调试工具
- [LLM Strategy](https://github.com/BlackHC/llm-strategy) ![GitHub Repo stars](https://img.shields.io/github/stars/BlackHC/llm-strategy?style=social): 使用LLM实现策略模式
- [datasetGPT](https://github.com/radi-cho/datasetGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/radi-cho/datasetGPT?style=social): 一个命令行界面，用于使用LLM生成文本和对话数据集。
- [spellbook-forge](https://github.com/rafalzawadzki/spellbook-forge) ![GitHub Repo stars](https://img.shields.io/github/stars/rafalzawadzki/spellbook-forge?style=social): 使您的LLM提示可执行和版本控制。
- [Auto Evaluator](https://github.com/langchain-ai/auto-evaluator) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/auto-evaluator?style=social): Langchain自动评估器
- [Jina](https://github.com/jina-ai/langchain-serve) ![GitHub Repo stars](https://img.shields.io/github/stars/jina-ai/langchain-serve?style=social): 使用Jina在生产环境中的Langchain应用
- [Gradio Tools](https://github.com/freddyaboulton/gradio-tools) ![GitHub Repo stars](https://img.shields.io/github/stars/freddyaboulton/gradio-tools?style=social): Gradio 🤝 LLM代理
- [steamship-langchain](https://github.com/steamship-core/steamship-langchain) ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-core/steamship-langchain?style=social): 为Steamship提供的LangChain适配器，使LangChain开发者能够快速地在Steamship上部署他们的应用程序，自动获得:
    - 生产就绪的API端点
    - 跨依赖项/后端的水平扩展
    - 应用状态（包括缓存）的持久存储
    - 内置的Authn/z支持
    - 多租户支持
    - 与其他Steamship技能（例如音频转录）的无缝集成
    - 使用指标和日志
    - 更多...
- [LangForge](https://github.com/mme/langforge) ![GitHub Repo stars](https://img.shields.io/github/stars/mme/langforge?style=social): 用于创建和部署LangChain应用的工具包
- [BentoChain](https://github.com/ssheng/BentoChain) ![GitHub Repo stars](https://img.shields.io/github/stars/ssheng/BentoChain?style=social): 在BentoML上部署LangChain
- [LangCorn](https://github.com/msoedov/langcorn) ![GitHub Repo stars](https://img.shields.io/github/stars/msoedov/langcorn?style=social): 使用FastApi自动服务LangChain应用
- [Langchain Service](https://github.com/kyrolabs/langchain-service) ![GitHub Repo stars](https://img.shields.io/github/stars/kyrolabs/langchain-service?style=social): 带有Qdrant向量存储和Kong网关的Langchain服务
- [Lanarky](https://github.com/ajndkr/lanarky) ![GitHub Repo stars](https://img.shields.io/github/stars/ajndkr/lanarky?style=social): 🚢 使用FastAPI快速部署生产就绪的LLM项目
- [Dify](https://github.com/langgenius/dify) ![GitHub Repo stars](https://img.shields.io/github/stars/langgenius/dify?style=social): 一个API用于插件和数据集，一个界面用于提示工程和视觉操作，所有这些都用于创建强大的AI应用。
- [FastGPT](https://github.com/labring/FastGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/labring/FastGPT?style=social)  :一个gpt服务,支持各种本地数据集
- [LangchainJS Worker](https://github.com/rickyrobinett/langchainjs-workers) ![GitHub Repo stars](https://img.shields.io/github/stars/rickyrobinett/langchainjs-workers?style=social) : 在cloudflare上的LangchainJS worker
- [Chainlit](https://github.com/Chainlit/chainlit) ![GitHub Repo stars](https://img.shields.io/github/stars/Chainlit/chainlit?style=social) : 在几分钟内构建Python LLM应用 ⚡️
- [Zep](https://github.com/getzep/zep) ![GitHub Repo stars](https://img.shields.io/github/stars/getzep/zep?style=social): 一个用于LLM / 聊天机器人应用的长期记忆存储
- [Langchain Decorators](https://github.com/ju-bezdek/langchain-decorators) ![GitHub Repo stars](https://img.shields.io/github/stars/ju-bezdek/langchain-decorators?style=social): 这是一个在LangChain上提供语法糖的库，用于编写自定义的langchain提示和链。主要原则和优点包括:
    - 更Pythonic的编写代码方式
    - 编写多行提示，不会因为缩进而打断你的代码流
    - 利用IDE内置的提示、类型检查和弹出文档，快速查看函数以查看提示、消耗的参数等
    - 利用LangChain生态系统的全部力量
    - 添加对可选参数的支持
    - 通过将参数绑定到一个类，轻松地在提示之间共享参数
    - 这是一个非官方的附加到langchain库的插件，它并不试图竞争，只是试图使其使用更加容易。这里的许多想法都是完全主观的。
- [FastAPI + Chroma](https://github.com/experienced-dev/chatgpt-plugin-fastapi-langchain-chroma) ![GitHub Repo stars](https://img.shields.io/github/stars/experienced-dev/chatgpt-plugin-fastapi-langchain-chroma?style=social): 一个采用fastapi,langchain,chroma 的chatgpt插件 
- [AilingBot](https://github.com/ericzhang-cn/ailingbot) ![GitHub Repo stars](https://img.shields.io/github/stars/ericzhang-cn/ailingbot?style=social): 一个基于langchain的AI聊天机器人，可以集成的im如slack,企业微信,飞书,钉钉

- [Llama2 Embedding Server](https://github.com/Dicklesworthstone/llama_embeddings_fastapi_service) ![GitHub Repo stars](https://img.shields.io/github/stars/Dicklesworthstone/llama_embeddings_fastapi_service?style=social): 基于langchain和fastapi的Llama2 embeding服务

- [ChatAbstractions](https://github.com/andrewnguonly/ChatAbstractions) ![GitHub Repo stars](https://img.shields.io/github/stars/andrewnguonly/ChatAbstractions?style=social): langchain 聊天模型的工程能力演示
- [MindSQL](https://github.com/Mindinventory/MindSQL) ![GitHub Repo stars](https://img.shields.io/github/stars/mindinventory/mindsql?style=social): 一个文本生成SQL的库


### 代理
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat) ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=social): 实现了与Colossal-AI项目驱动的LLM与RLHF的整合
- [AgentGPT](https://github.com/reworkd/AgentGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social): 使用Langchain和OpenAI的AI代理（Vercel / Nextjs）
- [Local GPT](https://github.com/PromtEngineer/localGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=social): 受Private GPT的启发，用Vicuna-7B模型替换了GPT4ALL模型，并使用InstructorEmbeddings代替LlamaEmbeddings
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social): GPT Researcher 是一个适用于多种研究任务的匿名代理
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt) ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=social): 代理技术可以增强你的LLM并将其推向极限
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=social): 为LLMs和自动代理（如BabyAGI和AutoGPT）提供角色扮演方法
- [Private GPT](https://github.com/imartinez/privateGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=social): 使用GPT私下与你的文件互动，100%私密，无数据泄漏
- [RasaGPT](https://github.com/paulpierre/RasaGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=social): RasaGPT是基于Rasa和Langchain构建的第一个LLM聊天机器人平台
- [SkyAGI](https://github.com/litanlitudan/skyagi) ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=social): 在LLM代理中出现的人类行为模拟能力
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI) ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=social): 一个小型的AGI实验，根据用户想要构建的应用生成Python应用
- [BabyAGI UI](https://github.com/miurla/babyagi-ui) ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=social): 让在web应用中运行和开发babyagi变得更容易，就像ChatGPT一样
- [SuperAgent](https://github.com/homanp/superagent) ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=social): 将LLM代理部署到生产环境
- [Voyager](https://github.com/MineDojo/Voyager) ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=social): 一个开放式的、具有大型语言模型的实体代理
- [ix](https://github.com/kreneskyp/ix) ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=social): 自主GPT-4代理平台
- [DuetGPT](https://github.com/kristoferlund/duet-gpt) ![GitHub Repo stars](https://img.shields.io/github/stars/kristoferlund/duet-gpt?style=social): 一个半自主的对话式开发助手，AI配对编程，无需复制粘贴。
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter)  ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=social): 在telegram 上使用langchain代理
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=social): demogpt 基于langchain采用ToT的思想让你用prompt快速创建应用原型。
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=social):  一个自动化AI代理的框架
- [BlockAGI](https://github.com/blockpipe/blockagi) ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=social): BlockAGI 可以针对特定领域进行研究，并输出详细的叙述性报告来展示其研究结果。 
- [waggledance.ai](https://github.com/agi-merge/waggle-dance) ![GitHub Repo stars](https://img.shields.io/github/stars/agi-merge/waggle-dance?style=social) : 这是一个有主见、可实现并发的系统。它基于数据和三方工具实现了 计划-验证-解决 的范式。
- [Elasticsearch Agent](https://github.com/onepointconsulting/elasticsearch-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/onepointconsulting/elasticsearch-agent?style=social): 一个基于 elasticsearch,langchain,gpt4的gpt 代理
- [CrewAI](https://github.com/joaomdmoura/crewai) ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=social): 一个多代理AI框架


### 模板
- [AI](https://github.com/vercel-labs/ai) ![GitHub Repo stars](https://img.shields.io/github/stars/vercel-labs/ai?style=social) :  采用 React, Svelte, and Vue, 等技术 Vercel template ，优先支持 LangChain 。
- [create-t3-turbo-ai](https://github.com/zckly/create-t3-turbo-ai) ![GitHub Repo stars](https://img.shields.io/github/stars/zckly/create-t3-turbo-ai?style=social): 基于 t3 ，适合 Langchain 的模板，用于构建类型安全，全栈，LLM 动力的带有 Nextjs 和 Prisma 的网络应用程序
- [LangChain.js LLM Template](https://github.com/Conner1115/LangChain.js-LLM-Template) ![GitHub Repo stars](https://img.shields.io/github/stars/Conner1115/LangChain.js-LLM-Template?style=social): LangChain LLM 模板，可以让你训练你自己的定制 AI LLM 模型。
- [Streamlit Template](https://github.com/hwchase17/langchain-streamlit-template) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain-streamlit-template?style=social): 如何在 Streamlit 上部署 LangChain 的模板
- [Codespaces Template](https://github.com/lostintangent/codespaces-langchain) ![GitHub Repo stars](https://img.shields.io/github/stars/lostintangent/codespaces-langchain?style=social): 一个 Codespaces 模板，帮你在几秒内启动并运行 LangChain！
- [Gradio Template](https://github.com/hwchase17/langchain-gradio-template) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain-gradio-template?style=social): 如何在 Gradio 上部署 LangChain 的模板
- [AI Getting Started](https://github.com/a16z-infra/ai-getting-started) ![GitHub Repo stars](https://img.shields.io/github/stars/a16z-infra/ai-getting-started?style=social): 这是一个适用于周末项目的Javascript AI入门工具栈，包括图像/文本模型、向量存储、认证和部署配置等功能。
- [Embedchain](https://github.com/embedchain/embedchain) ![GitHub Repo stars](https://img.shields.io/github/stars/embedchain/embedchain?style=social): 这是一个可轻松创建基于任何数据集的llm应用的框架. 


### 平台
- [Modal](https://modal.com/docs/guide/ex/potus_speech_qanda): 为云/ML 计算提供端到端的堆栈
- [Metal](https://getmetal.io/): Metal 是一种托管服务，使你无需烦恼地管理基础设施就能构建 AI 产品
- [Graphsignal](https://graphsignal.com/): 针对 AI 代理和 LLM 驱动的应用的可观察性产品。在生产中追踪，监控和调试 LangChain。
- [Mona](https://github.com/monalabs/mona-openai) ![GitHub Repo stars](https://img.shields.io/github/stars/monalabs/mona-openai?style=social): 实时监控我们的openai使用情况
- [Openllmetry](https://github.com/traceloop/openllmetry) ![GitHub Repo stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social): 一个基于OpenTelemetry 的llm应用探测系统
- [MindsDB](https://docs.mindsdb.com/integrations/ai-engines/langchain): 如何更容易地部署，微调模型.

## 开源项目

### 知识管理
- [Quiver](https://github.com/StanGirard/quiver) ![GitHub Repo stars](https://img.shields.io/github/stars/StanGirard/quiver?style=social): 你的第二大脑，将你的知识倾倒入你的 GenerativeAI 
- [DocsGPT](https://github.com/arc53/docsgpt) ![GitHub Repo stars](https://img.shields.io/github/stars/arc53/docsgpt?style=social): 基于GPT 的聊天，用于文档搜索和帮助。
- [Chaindesk](https://github.com/gmpetrov/databerry) ![GitHub Repo stars](https://img.shields.io/github/stars/gmpetrov/databerry?style=social) : Databerry是一个无代码平台，用于构建自定义的LLM代理。它提供了一个用户友好的解决方案，可以快速在您的个人数据上设置语义搜索系统，无需任何技术知识。
- [Knowledge GPT](https://github.com/mmz-001/knowledge_gpt) ![GitHub Repo stars](https://img.shields.io/github/stars/mmz-001/knowledge_gpt?style=social): 为你的文档提供准确的答案和即时引用。
- [Knowledge](https://github.com/KnowledgeCanvas/knowledge) ![GitHub Repo stars](https://img.shields.io/github/stars/KnowledgeCanvas/knowledge?style=social): Knowledge 是一个工具，用于保存，搜索，访问和探索你所有喜欢的网站，文档和文件。
- [Anything LLM](https://github.com/Mintplex-Labs/anything-llm) ![GitHub Repo stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social): 一款全栈应用，将任何文档转化为智能聊天机器人，具有优雅的用户界面和更简单的工作区管理方式。
- [DocNavigator](https://github.com/vgulerianb/DocNavigator) ![GitHub Repo stars](https://img.shields.io/github/stars/vgulerianb/DocNavigator?style=social): 使用GPT改进你的产品文档和网站
- [ChatFiles](https://github.com/guangzhengli/ChatFiles) ![GitHub Repo stars](https://img.shields.io/github/stars/guangzhengli/ChatFiles?style=social) :上传你的文档，直接聊天～ Powered by GPT / Embedding / TS / NextJS.
- [DataChad](https://github.com/gustavz/DataChad) ![GitHub Repo stars](https://img.shields.io/github/stars/gustavz/DataChad?style=social): 一个可以让你和任何数据沟通的 streamlit 应用，支持openai和GPT4ALL的模型 
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent) [GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=social): 一个基于OpenAI and ChromaDB  的streamlit 应用基于支持直接和你的笔记进行对话。 
- [examor](https://github.com/codeacme17/examor) ![GitHub Repo stars](https://img.shields.io/github/stars/codeacme17/examor?style=social): 一个可以基于笔记出考试题的web应用。可以考验我们学习到了哪些。
- [Repochat](https://github.com/pnkvalavala/repochat)  ![GitHub Repo stars](https://img.shields.io/github/stars/pnkvalavala/repochat?style=social): 可以和github仓库沟chat机器人
- [SolidGPT](https://github.com/AI-Citizen/SolidGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/AI-Citizen/SolidGPT?style=social): 和代码仓库聊天，讨论需求

  
### 其他聊天机器人
- [AudioGPT](https://github.com/AIGC-Audio/AudioGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT?style=social): 理解和生成语音，音乐，声音和会说话的头部
- [Paper QA](https://github.com/whitead/paper-qa) ![GitHub Repo stars](https://img.shields.io/github/stars/whitead/paper-qa?style=social): 用于回答带有引用文献的文档问题的 LLM Chain
- [Chat Langchain](https://github.com/hwchase17/chat-langchain) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/chat-langchain?style=social): 专注于在 LangChain 文档上回答问题的本地托管聊天机器人
- [Langchain Chat](https://github.com/zahidkhawaja/langchain-chat-nextjs) ![GitHub Repo stars](https://img.shields.io/github/stars/zahidkhawaja/langchain-chat-nextjs?style=social): 另一个用于 LangChain 聊天的 Next.js 前端.
- [Book GPT](https://github.com/fraserxu/book-gpt) ![GitHub Repo stars](https://img.shields.io/github/stars/fraserxu/book-gpt?style=social): 丢一本书，开始提问.
- [Chat LangchainJS](https://github.com/sullivan-sean/chat-langchainjs) ![GitHub Repo stars](https://img.shields.io/github/stars/sullivan-sean/chat-langchainjs?style=social): Chat Langchain 的 NextJS 版本
- [Doc Search](https://github.com/namuan/dr-doc-search) ![GitHub Repo stars](https://img.shields.io/github/stars/namuan/dr-doc-search?style=social): 与书籍对话 - 使用 GPT-3 构建
- [Fact Checker](https://github.com/jagilley/fact-checker) ![GitHub Repo stars](https://img.shields.io/github/stars/jagilley/fact-checker?style=social): 使用 langchain 核实 LLM 输出的事实
- [MM ReAct](https://github.com/microsoft/MM-REACT) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MM-REACT?style=social): 基于ReAct模型的多模态  应用程序
- [QABot](https://github.com/hardbyte/qabot) ![GitHub Repo stars](https://img.shields.io/github/stars/hardbyte/qabot?style=social): 使用 langchain 和 openai 通过自然语言查询查询本地或远程文件或数据库
- [GPT Automator](https://github.com/chidiwilliams/GPT-Automator) ![GitHub Repo stars](https://img.shields.io/github/stars/chidiwilliams/GPT-Automator?style=social): 你的语音控制 Mac 助手.
- [Teams LangchainJS](https://github.com/SidU/teams-langchain-js) ![GitHub Repo stars](https://img.shields.io/github/stars/SidU/teams-langchain-js?style=social): 展示 LangChainJS 与 Teams / Bot Framework bots 的演示
- [ChatGPT](https://github.com/biff-ai/chatgpt-langchainjs-example) ![GitHub Repo stars](https://img.shields.io/github/stars/biff-ai/chatgpt-langchainjs-example?style=social): 适用于 node.js & Docker的 ChatGPT & langchain 示例
- [FlowGPT](https://github.com/nilooy/flowgpt) ![GitHub Repo stars](https://img.shields.io/github/stars/nilooy/flowgpt?style=social): 使用 AI 生成图表
- [langchain-text-summarizer](https://github.com/alphasecio/langchain-text-summarizer)  ![GitHub Repo stars](https://img.shields.io/github/stars/alphasecio/langchain-text-summarizer?style=social): 使用 LangChain 汇总文本的样本 streamlit 应用程序
- [Langchain Chat Websocket](https://github.com/pors/langchain-chat-websockets) ![GitHub Repo stars](https://img.shields.io/github/stars/pors/langchain-chat-websockets?style=social): 关于 LangChain LLM 聊天，通过 websockets 进行流响应
- [langchain_yt_tools](https://github.com/venuv/langchain_yt_tools) ![GitHub Repo stars](https://img.shields.io/github/stars/venuv/langchain_yt_tools?style=social): Langchain 工具，用于搜索/提取/转录 Youtube 视频的文本副本
- [SmartPilot](https://github.com/jaredkirby/SmartPilot) ![GitHub Repo stars](https://img.shields.io/github/stars/jaredkirby/SmartPilot?style=social): 利用 OpenAI 的语言模型生成，分析，并选择给定问题的最佳答案的 Python 程序
- [Howdol](https://github.com/bborn/howdoi.ai) ![GitHub Repo stars](https://img.shields.io/github/stars/bborn/howdoi.ai?style=social): 一个能回答问题的帮助聊天机器人
- [MrsStax](https://github.com/normandmickey/MrsStax) ![GitHub Repo stars](https://img.shields.io/github/stars/normandmickey/MrsStax?style=social): QA Slack 机器人
- [ThoughtSource⚡](https://github.com/OpenBioLink/ThoughtSource) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBioLink/ThoughtSource?style=social): 机器思维科学的框架
- [ChatGPT Langchain](https://huggingface.co/spaces/JavaFXpert/Chat-GPT-LangChain): 在 Huggingface 上使用 langchain 的 ChatGPT 克隆
- [Chat Math Techniques](https://huggingface.co/spaces/JavaFXpert/gpt-math-techniques) : 在 Huggingface 上使用数学能力的 langchain 聊天
- [Notion QA](https://github.com/hwchase17/notion-qa) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/notion-qa?style=social): Notion 问题回答机器人
- [QNimGPT](https://huggingface.co/spaces/rituthombre/QNim): 与 IBM 量子计算机模拟器或 OpenAI GPT-3.5 玩 Nim 游戏
- [ChatPDF](https://github.com/akshata29/chatpdf) ![GitHub Repo stars](https://img.shields.io/github/stars/akshata29/chatpdf?style=social): 结合 Azure OpenAI 的 ChatGPT + 企业数据
- [Chat with Scanned Documents](https://github.com/tony-xlh/Chat-with-Scanned-Documents) ![GitHub Repo stars](https://img.shields.io/github/stars/tony-xlh/Chat-with-Scanned-Documents?style=social): 与使用 Dynamic Web TWAIN 扫描的文档进行对话的演示。
- [snowChat ❄️](https://github.com/kaarthik108/snowChat) ![GitHub Repo stars](https://img.shields.io/github/stars/kaarthik108/snowChat?style=social): 与你的 Snowflake 数据库聊天
- [DB GPT](https://github.com/csunny/DB-GPT) ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=social): 使用本地 GPT 与您的数据和环境互动，无数据泄漏，100% 私有，100% 安全
- [Psychic](https://github.com/psychic-api/psychic) ![GitHub Repo stars](https://img.shields.io/github/stars/psychic-api/psychic?style=social): 面向非结构化数据的通用 API。将 SaaS 工具的文档同步到 SQL 或向量数据库，这样就可以很容易地由像 ChatGPT 这样的 AI 应用程序查询。
- [Airtable-QnA](https://github.com/ikram-shah/airtable-qna) ![GitHub Repo stars](https://img.shields.io/github/stars/ikram-shah/airtable-qna?style=social): 🌟 一个用于你的 Airtable 内容的问答工具
- [WingmanAI](https://github.com/e-johnstonn/wingmanAI) ![GitHub Repo stars](https://img.shields.io/github/stars/e-johnstonn/wingmanAI?style=social): 用于与系统和麦克风音频的实时转录进行交互的工具
- [TutorGPT](https://github.com/plastic-labs/tutor-gpt) ![GitHub Repo stars](https://img.shields.io/github/stars/plastic-labs/tutor-gpt?style=social): 用于辅导任务的动态元提示工具。
- [Cheshire Cat](https://github.com/cheshire-cat-ai/core) ![GitHub Repo stars](https://img.shields.io/github/stars/cheshire-cat-ai/core?style=social): 具有即用型聊天集成和插件开发平台的自定义 AGI 机器人。
- [Got Chat Bot](https://github.com/parker84/GoT-chat-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/parker84/GoT-chat-bot?style=social): 用于创建权力的游戏聊天机器人的仓库（例如:和 Tyrion Lannister 对话）
- [Dialoqbase](https://github.com/n4ze3m/dialoqbase) ![GitHub Repo stars](https://img.shields.io/github/stars/n4ze3m/dialoqbase?style=social): 允许你用自己的知识库创建自定义聊天机器人的网页应用
- [CSV-AI 🧠](https://python.langchain.com/en/latest/modules/indexes/document_loaders/examples/snowflake.html): CSV-AI 是由 LangChain 驱动的终极应用，它可以帮助你在 CSV 文件中发现隐藏的洞察。
- [MindGeniusAI](https://github.com/xianjianlf2/MindGeniusAI) ![GitHub Repo stars](https://img.shields.io/github/stars/xianjianlf2/MindGeniusAI?style=social): 用 ChatGPT 自动生成 MindMap
- [Robby-Chatbot](https://github.com/yvann-hub/Robby-chatbot)  ![GitHub Repo stars](https://img.shields.io/github/stars/yvann-hub/Robby-chatbot?style=social): 采用 Langchain🦜 ，OpenAI , Streamlit ⚡，直接和 CSV, PDF, TXT files 📄 and YTB videos 🎥 聊天
- [AI Chatbot](https://github.com/vercel-labs/ai-chatbot) ![GitHub Repo stars](https://img.shields.io/github/stars/vercel-labs/ai-chatbot?style=social): 这是一个由Vercel Labs构建的功能齐全、可定制的Next.js AI聊天机器人。 
- [Instrukt](https://github.com/blob42/Instrukt) ![GitHub Repo stars](https://img.shields.io/github/stars/blob42/Instrukt?style=social): 这是一个完整的AI环境，可以在终端中使用。您可以在其中构建、测试和指导智能体。
- [OpenChat](https://github.com/openchatai/OpenChat/)  ![GitHub Repo stars](https://img.shields.io/github/stars/openchatai/OpenChat?style=social): LLMs 定制机器人控制台。
- [Twitter Agent](https://github.com/ahmedbesbes/twitter-agent/) ![GitHub Repo stars](https://img.shields.io/github/stars/ahmedbesbes/twitter-agent?style=social): 抓取twitter内容，并和twitter内容进行聊天
- [GPT Migrate](https://github.com/0xpayne/gpt-migrate)  ![GitHub Repo stars](https://img.shields.io/github/stars/0xpayne/gpt-migrate?style=social): 帮你把代码从一个语言或一个框架迁移到另外一个
- [Code Interpreter API](https://github.com/shroominic/codeinterpreter-api) ![GitHub Repo stars](https://img.shields.io/github/stars/shroominic/codeinterpreter-api?style=social):  ChatGPT Code Interpreter  的开源实现
- [Recommender](https://github.com/vishwasg217/recommender) ![GitHub Repo stars](https://img.shields.io/github/stars/vishwasg217/recommender?style=social): 根据业务需求创建引人入胜的电子邮件营销活动
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot) ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=social): 一个回答人力问题的聊天机器人
- [Lobe Chat](https://github.com/lobehub/lobe-chat) ![GitHub Repo stars](https://img.shields.io/github/stars/lobehub/lobe-chat?style=social): 一个开源、可扩展、高性能的聊天机器人框架
- [Funcchain](https://github.com/shroominic/funcchain) [GitHub Repo stars](https://img.shields.io/github/stars/shroominic/funcchain?style=social): 用python得形式写prompts
- [PersonalityChatbot](https://github.com/btrcm00/chatbot-with-langchain) ![GitHub Repo stars](https://img.shields.io/github/stars/btrcm00/chatbot-with-langchain?style=social): 采用 Langchain | LangSmith | MongoDB 的个性化聊天机器人. 
- [XAgent](https://github.com/OpenBMB/XAgent) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=social): 一个可以解决复杂问题的agent
  
- [InkChatGPT](https://github.com/vinhnx/InkChatGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/vinhnx/InkChatGPT?style=social): 一个简单的RAG聊天机器人

## 学习

### 笔记本
- [Langchain Tutorials](https://github.com/gkamradt/langchain-tutorials) ![GitHub Repo stars](https://img.shields.io/github/stars/gkamradt/langchain-tutorials?style=social): 对 LangChain 库的概述和教程
- [LangChain Chinese Getting Started Guide](https://github.com/liaokongVFX/LangChain-Chinese-Getting-Started-Guide) ![GitHub Repo stars](https://img.shields.io/github/stars/liaokongVFX/LangChain-Chinese-Getting-Started-Guide?style=social): 面向初学者的中文 LangChain 教程
- [Flan5 LLM](https://colab.research.google.com/drive/1AVh9dOsG9DKzfK7gOFrJuitPIcLPqlbO?usp=sharing): 使用 LangChain 进行 PDF 问答，进行思维链条和多任务指导，Flan5 在 HuggingFace 上
- [LangChain Handbook](https://github.com/pinecone-io/examples/tree/master/generation/langchain/handbook) ![GitHub Repo stars](https://img.shields.io/github/stars/pinecone-io/examples?style=social): Pinecone / James Briggs 的 LangChain 手册
- [Query the YouTube video transcripts](https://colab.research.google.com/drive/1sKSTjt9cPstl_WMZ86JsgEqFG-aSAwkn?usp=sharing) : 查询YouTube视频的转录文本，返回时间戳作为来源以证明答案的正确性。
- [llm-lobbyist](https://github.com/JohnNay/llm-lobbyist) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnNay/llm-lobbyist?style=social): 大型语言模型作为公司游说者
- [Langchain Semantic Search](https://github.com/venuv/langchain_semantic_search) ![GitHub Repo stars](https://img.shields.io/github/stars/venuv/langchain_semantic_search?style=social): 使用 GPT3，LangChain 和 Python 搜索和索引你自己的 Google Drive 文件
- [GPT 政策指南](https://colab.research.google.com/drive/1xt2IsFPGYMEQdoJFNgWNAjWGxa60VXdV)
- [llm-grovers-search-party](https://github.com/JavaFXpert/llm-grovers-search-party) ![GitHub Repo stars](https://img.shields.io/github/stars/JavaFXpert/llm-grovers-search-party?style=social): 利用 Qiskit，OpenAI 和 LangChain 展示 Grover 算法
- [TextWorld ReAct Agent](https://colab.research.google.com/drive/19WTIWC3prw5LDMHmRMvqNV2loD9FHls6?usp=sharing)
- [LangChain <> Wolfram Alpha](https://colab.research.google.com/drive/1AAyEdTz-Z6ShKvewbt1ZHUICqak0MiwR?usp=sharing)
- [BYO 知识图谱](https://github.com/prof-frink-lab/slangchain/blob/main/docs/modules/knowledge_graph/examples/byo_knowledge_graph.ipynb) ![GitHub Repo stars](https://img.shields.io/github/stars/prof-frink-lab/slangchain?style=social): 使用 BYO 知识图谱

- [Large Language Models Course](https://github.com/peremartra/Large-Language-Model-Notebooks-Course) ![GitHub Repo stars](https://img.shields.io/github/stars/peremartra/Large-Language-Model-Notebooks-Course?style=social): 大语言模型课程

### 视频
- [用于 LLM 应用开发的 LangChain](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
- [Sam Witteveen 的 LangChain 系列](https://www.youtube.com/watch?v=J_0qvRt4LNk&list=PL8motc6AQftk1Bs42EW45kwYbyJ4jOdiZ)
- [LangChain 教程播放列表](https://www.youtube.com/playlist?list=PL611FKPtL866MnlDPHvI3KwVGqCB-QJAx)
- [James Briggs 的 LangChain 播放列表](https://www.youtube.com/watch?v=nE2skSRWTTs&list=PLIUOU7oqGTLieV9uTIFMm6_4PXg-hlN6F)
- [什么是 LangChain? - LangChain + ChatGPT 概述](https://www.youtube.com/watch?v=_v_fgW2SkkQ)
- [LangChain 演示 + Harrison Chase 的问答](https://www.youtube.com/watch?v=zaYTXQFR0_s)
- [用于 LLM 的 LangChain...基本上就是一个 Ansible 剧本](https://www.youtube.com/watch?v=X51N9C-OhlE) (David Shapiro) (David Shapiro)
- [独立数据播放列表](https://www.youtube.com/watch?v=_v_fgW2SkkQ&list=PLqZXAkvF1bPNQER9mLmDbntNfSpzdDIU5)


### 文章
- [使用 GPT3、LangChain 和 Python 构建 GitHub 支持机器人](https://dagster.io/blog/chatgpt-langchain)
- [大型语言模型（LLM）API 构建框架的崛起](https://cobusgreyling.medium.com/the-emergence-of-large-language-model-llm-api-build-frameworks-78d83d68eeda)
- [如何使用 LangChain 🦜🔗 和 GPT-3 自动化我的老板 🤖](https://dev.to/ironcladdev/how-i-used-langchain-and-gpt-3-to-automate-my-boss-3bk4)
- [使用 Cohere 和 Langchain 的多语言语义搜索](https://txt.cohere.ai/search-cohere-langchain/)
- [Haystack 和 LangChain 如何赋能大型语言模型](https://mantiumai.com/blog/how-haystack-and-langchain-are-empowering-large-language-models/)
- [DataIndependent 教程](https://github.com/gkamradt/langchain-tutorials)
- [使用 Redis、LangChain 和 OpenAI 构建电商聊天机器人](https://redis.com/blog/build-ecommerce-chatbot-with-redis/)
- [LangChain 入门:构建 LLM 驱动的应用的初学者指南](https://towardsdatascience.com/getting-started-with-langchain-a-beginners-guide-to-building-llm-powered-applications-95fc8898732c)
- [如何使用 LangChain 和 LLM Agent 监控微调您的 LLM 应用](https://arize.com/blog-course/langchain-llm-agent-monitoring/)
- [使用记忆构建一个简单的 ChatGPT CLI](https://getmetal.io/posts/07-tutorial-motorhead-cli)
- [使用 BentoML、LangChain 和 Gradio 部署语音聊天机器人](https://towardsdatascience.com/deploy-a-voice-based-chatbot-with-bentoml-langchain-and-gradio-7f25af3e45df)
- [PromptChap 上的 LangChain 教程](https://promptchap.com)
- [使用 Pyodide、LangChain 和 OpenAI 创建代码解释器聊天机器人](https://dylancastillo.co/code-interpreter-chatbot-pyodide-langchain-openai/)
- [LangChain 已添加 Cypher 搜索](https://towardsdatascience.com/langchain-has-added-cypher-search-cb9d821120d5)
- [Langchain 解码](https://alphasec.io/langchain-decoded-the-muggles-guide-to-langchain/)
- [使用 Python 和 Langchain 在本地实现 GPT4All](https://medium.datadriveninvestor.com/offline-ai-magic-implementing-gpt4all-locally-with-python-b51971ce80af)
- [用 LangChain 让你的 GDrive 拥有 GPT 功能](https://www.haihai.ai/gpt-gdrive/)
- [一个构建langchain应用的方法](https://wyh.life/article/2023/07/02/llm-app-development)
- [构建一个hr代理](https://medium.com/towards-artificial-intelligence/creating-a-mostly-autonomous-hr-assistant-with-chatgpt-and-langchains-agents-and-tools-1cdda0aa70ef)


## 其他LLM框架

- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents) :在 transformers 的基础上提供自然语言 API
- [LlamaIndex](https://github.com/jerryjliu/llama_index) ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=social):为你的 LLM 提供一个集中接口来连接外部数据。
- [Botpress](https://github.com/botpress/botpress) ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=social):构建聊天机器人的构建块
- [Haystack](https://github.com/deepset-ai/haystack) ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social):使用 Transformer 模型和 LLM 与你的数据进行交互的 NLP 框架
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social):Microsoft 的 C# SDK，可快速轻松地将最先进的 LLM 技术集成到你的应用中
- [Promptify](https://github.com/promptslab/Promptify) ![GitHub Repo stars](https://img.shields.io/github/stars/promptslab/Promptify?style=social):Prompt Engineering | 使用 GPT 或其他基于提示的模型获取结构化输出。
- [PromptSource](https://github.com/bigscience-workshop/promptsource) ![GitHub Repo stars](https://img.shields.io/github/stars/bigscience-workshop/promptsource?style=social):关于创建、共享和使用自然语言提示的工具包。
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM) ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=social):一个人工智能自动化平台。
- [LLM Agents](https://github.com/mpaepper/llm_agents) ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=social):构建由 LLM 控制的代理
- [MiniChain](https://github.com/srush/MiniChain) ![GitHub Repo stars](https://img.shields.io/github/stars/srush/MiniChain?style=social):用于与大型语言模型编码的微小库。
- [Griptape](https://github.com/griptape-ai/griptape) ![GitHub Repo stars](https://img.shields.io/github/stars/griptape-ai/griptape?style=social):Python 框架，用于具有链式思维推理、外部工具和记忆的 AI 工作流和管道。
- [llm-chain](https://github.com/sobelio/llm-chain) ![GitHub Repo stars](https://img.shields.io/github/stars/sobelio/llm-chain?style=social):一个强大的 rust 库，用于在 LLM 中构建链，让你能够总结文本和完成复杂任务。
- [PromptFlow](https://github.com/InsuranceToolkits/promptflow) ![GitHub Repo stars](https://img.shields.io/github/stars/InsuranceToolkits/promptflow?style=social):创建可执行的流程图，将 LLM (大型语言模型)，提示符，Python 函数和条件逻辑链接在一起。
- [OpenLM](https://github.com/r2d4/openlm) ![GitHub Repo stars](https://img.shields.io/github/stars/r2d4/openlm?style=social):一个可以从任何其他托管推断 API 调用 LLM 的开源兼容 OpenAI 的库。同样支持 Typescript[183]
- [Dust](https://github.com/dust-tt/dust) ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=social):设计和部署大型语言模型应用程序
- [e2b](https://github.com/e2b-dev/e2b) ![GitHub Repo stars](https://img.shields.io/github/stars/e2b-dev/e2b?style=social):开源平台，用于构建和部署虚拟开发者代理
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=social):一个以开发者为先的开源自主人工智能代理框架。
- [SmartGPT](https://github.com/Cormanz/smartgpt) ![GitHub Repo stars](https://img.shields.io/github/stars/Cormanz/smartgpt?style=social):一个程序，提供 LLM 通过插件完成复杂任务的能力。
- [TermGPT](https://github.com/Sentdex/TermGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/Sentdex/TermGPT?style=social):赋予 GPT-4 等大型语言模型计划和执行终端命令的能力
- [ReLLM](https://github.com/r2d4/rellm) ![GitHub Repo stars](https://img.shields.io/github/stars/r2d4/rellm?style=social):用于语言模型完成的正则表达式。
- [OpenDAN](https://github.com/fiatrete/OpenDAN-Personal-AI-OS) ![GitHub Repo stars](https://img.shields.io/github/stars/fiatrete/OpenDAN-Personal-AI-OS?style=social):开源的个人 AI 操作系统，将各种 AI 模块整合在一个地方供您个人使用。

- [OpenLLM](https://github.com/bentoml/OpenLLM)  ![GitHub Repo stars](https://img.shields.io/github/stars/bentoml/OpenLLM?style=social):  OpenLLM是一个用于在生产环境中操作大型语言模型（LLM）的开放平台。使用OpenLLM，您可以轻松地微调、服务、部署和监控任何LLM。
- [FlagAI](https://github.com/FlagAI-Open/FlagAI)   ![GitHub Repo stars](https://img.shields.io/github/stars/FlagAI-Open/FlagAI?style=social): FlagAI是一个快速、易于使用和可扩展的大型模型工具包。
- [AI.JSX](https://github.com/fixie-ai/ai-jsx) ![GitHub Repo stars](https://img.shields.io/github/stars/fixie-ai/ai-jsx?style=social): 一个js 的Ai应用框架
- [Outlines](https://github.com/normal-computing/outlines) ![GitHub Repo stars](https://img.shields.io/github/stars/normal-computing/outlines?style=social): 生成式模型编程 (Python) 
- [AI Utils](https://github.com/lgrammel/ai-utils.js) ![GitHub Repo stars](https://img.shields.io/github/stars/lgrammel/ai-utils.js?style=social): 一个TS的AI应用框架
- [MetaGPT](https://github.com/geekan/MetaGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social): 一个多代理的元编程框架 :给一行需求，生成prd,设计图，任务列表和代码库以及上线发布方式 
- [gpt-engineer](https://github.com/AntonOsika/gpt-engineer) ![GitHub Repo stars](https://img.shields.io/github/stars/AntonOsika/gpt-engineer):  一个gpt 自动写代码工具
- [Hyv](https://github.com/failfa-st/hyv) ![GitHub Repo stars](https://img.shields.io/github/stars/failfa-st/hyv?style=social):  node的 AI应用框架 
- [Autochain](https://github.com/Forethought-Technologies/AutoChain) ![GitHub Repo stars](https://img.shields.io/github/stars/Forethought-Technologies/AutoChain?style=social): 建设可扩展，可测试的轻量级agent.
- [TypeChat](https://github.com/microsoft/TypeChat) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TypeChat?style=social): TypeChat 是一个为typescript开发人员提供的自然语言交互库.
- [Marvin](https://github.com/PrefectHQ/marvin) ![GitHub Repo stars](https://img.shields.io/github/stars/PrefectHQ/marvin?style=social): ✨在应用中添加可信，实时的AI特性
- [LMQL](https://github.com/eth-sri/lmql) ![GitHub Repo stars](https://img.shields.io/github/stars/eth-sri/lmql?style=social): 一个为大模型设计的编程语言
- [LLMFlow](https://github.com/stoyan-stoyanov/llmflows) ![GitHub Repo stars](https://img.shields.io/github/stars/stoyan-stoyanov/llmflows?style=social): 做最少的抽象，建设可用的llm应用。
- [Ax](https://github.com/axilla-io/ax) ![GitHub Repo stars](https://img.shields.io/github/stars/axilla-io/ax?style=social): 一个为ts设计的AI 框架
- [TextAI](https://github.com/neuml/txtai) ![GitHub Repo stars](https://img.shields.io/github/stars/neuml/txtai?style=social): 💡 用于语义分析，llm编排，llm工作流的 emedding 数据库 
- [AgentFlow](https://github.com/simonmesmith/agentflow) ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=social): 通过json生成llm工作流
- [SimpleAIChat](https://github.com/minimaxir/simpleaichat) ![GitHub Repo stars](https://img.shields.io/github/stars/minimaxir/simpleaichat?style=social): 便于和llm交互的python 包. 
- [LLFn](https://github.com/orgexyz/LLFn) ![GitHub Repo stars](https://img.shields.io/github/stars/orgexyz/LLFn?style=social): 使用llm模型的轻量级应用
- [LLMStack](https://github.com/trypromptly/LLMStack)  ![GitHub Repo stars](https://img.shields.io/github/stars/trypromptly/LLMStack?style=social): 建设定制数据集llm应用的无代码平台
- [Lagent](https://github.com/InternLM/lagent) ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=social): 建设llm agent 的轻量级框架
- [Embedbase](https://github.com/different-ai/embedbase) ![GitHub Repo stars](https://img.shields.io/github/stars/different-ai/embedbase?style=social): 一个建立ai应用的qing轻量级应用
- [Rivet](https://github.com/Ironclad/rivet) ![GitHub Repo stars](https://img.shields.io/github/stars/Ironclad/rivet?style=social): 支持创建可嵌入应用的ai agent和prompt 工作流的ide.
- [Promptfoo](https://github.com/promptfoo/promptfoo) ![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social): prompt 测试评估改善的工具。
- [RestGPT](https://github.com/Yifan-Song793/RestGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=social): 一个可以控制真实世界应用的匿名代理.
- [LangStream](https://github.com/LangStream/langstream) ![GitHub Repo stars](https://img.shields.io/github/stars/LangStream/langstream?style=social): 搭建运行事件驱动的llm应用的框架
- [Magentic](https://github.com/jackmpcollins/magentic) ![GitHub Repo stars](https://img.shields.io/github/stars/jackmpcollins/magentic?style=social): 像python函数一样无缝集成llm应用
- [Autogen](https://github.com/microsoft/autogen) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=social): 搭建下一代大模型应用 
- [AgentVerse](https://github.com/openbmb/agentverse) ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=social):   方便搭建多代理环境的框架.
- [Flappy](https://github.com/pleisto/flappy) ![Github Repo stars]![](https://img.shields.io/github/stars/pleisto/flappy.svg?style=social): llm 代理sdk
- [MemGPT](https://github.com/cpacker/MemGPT) ![GitHub Repo stars](https://img.shields.io/github/stars/cpacker/MemGPT?style=social): 使llm支持无边界上下文的内存管理工具
- [Agentlabs](https://github.com/agentlabs-inc/agentlabs) ![GitHub Repo stars](https://img.shields.io/github/stars/agentlabs-inc/agentlabs?style=social): 通用的agent前端
- [axflow](https://github.com/axflow/axflow) ![GitHub Repo stars](https://img.shields.io/github/stars/axflow/axflow?style=social): 用于AI开发的ts框架
- [bondai](https://github.com/krohling/bondai) ![GitHub Repo stars](https://img.shields.io/github/stars/krohling/bondai?style=social): 可无缝接入应用的AI助理
- [Chidori](https://github.com/ThousandBirdsInc/chidori) ![GitHub Repo stars](https://img.shields.io/github/stars/ThousandBirdsInc/chidori?style=social): 一个rust ,ts AI代理应用运行框架
- [Langroid](https://github.com/langroid/langroid) ![GitHub Repo stars](https://img.shields.io/github/stars/langroid/langroid?style=social): 一个轻量级，可扩展的python llm 框架。
- [Langstream](https://github.com/rogeriochaves/langstream) ![GitHub Repo stars](https://img.shields.io/github/stars/rogeriochaves/langstream?style=social): 一个容易学习的流式 python llm 框架
- [Agency](https://github.com/neurocult/agency) ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=social):  一个go 语言llm 框架 
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=social): 一个无缝计划和执行数据分析任务的代码优先的框架
- [MicroAgent](https://github.com/aymenfurter/microagents)  ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=social): 能自行修正prompt和python的agent
- [modelscope-agent](https://github.com/modelscope/modelscope-agent)  ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/modelscope-agent?style=social): 一个简易的多代理执行框架
- [Casibase](https://github.com/casibase/casibase)  ![GitHub Repo stars](https://img.shields.io/github/stars/casibase/casibase?style=social): 开源RAG知识库，支持 OpenAI, Azure, LLaMA, Google Gemini, HuggingFace, Claude, Groq 的api
- [Fructose](https://github.com/bananaml/fructose) ![GitHub Repo stars](https://img.shields.io/github/stars/bananaml/fructose?style=social): Fructose是一个基于llm的强类型接口.
- [R2R](https://github.com/SciPhi-AI/R2R)  ![GitHub Repo stars](https://img.shields.io/github/stars/SciPhi-AI/R2R?style=social): 快速开发rag系统的框架
- [uAgents](https://github.com/fetchai/uAgents)  ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=social): 一个轻量级多代理框架.
- [Codel](https://github.com/semanser/codel) ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=social): ✨ 全自动化执行终端，浏览，编辑框架.
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch) ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=social): 采用agent的搜索聚合器
- [Plandex](https://github.com/plandex-ai/plandex) ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=social): 复杂任务的ai编码引擎
- [Maestro](https://github.com/Doriandarko/maestro) ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=social): 一个基于claude 多代理框架
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=social): ai开发工具，可用于vscode
- [SWE Agent](https://github.com/princeton-nlp/swe-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=social): 自动执行代码，修复bug的框架.
- [Gateway](https://github.com/Portkey-AI/gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/Portkey-AI/gateway?style=social): 一个强大的ai网关.
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun) ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=social): 最容易地安全执行ai生成代码的方法
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=social):  llama-cpp 代理 框架 
- [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) ![GitHub Repo stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=social): 金融应用的ai代理平台
- [Groq Ruby](https://github.com/drnic/groq-ruby) ![GitHub Repo stars](https://img.shields.io/github/stars/drnic/groq-ruby?style=social): 和Groq Cloud 交互的库.
  
- [AgentScope](https://github.com/modelscope/agentscope) ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=social): 阿里的AI匿名代理框架
- [Memary](https://github.com/kingjulio8238/memary) ![GitHub Repo stars](https://img.shields.io/github/stars/kingjulio8238/memary?style=social): 一个匿名代理的长期存储
- [Llmware](https://github.com/llmware-ai/llmware) ![GitHub Repo stars](https://img.shields.io/github/stars/llmware-ai/llmware?style=social): 企业级的LLM开发框架，模型微调的工具。
- [Pipecat](https://github.com/pipecat-ai/pipecat) ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social): 语音和多模态对话AI的开源框架.
- [Phidata](https://github.com/phidatahq/phidata) ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=social): 一个构建AI助手的工具


## 补充

- [Open LLMs](https://github.com/eugeneyan/open-llms) ![GitHub Repo stars](https://img.shields.io/github/stars/eugeneyan/open-llms?style=social): 一份可供商业使用的公开LLM列表
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) ![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/Awesome-LLM?style=social): Awesome-LLM:精选的大型语言模型资源列表。
- [LLaMA Cult and More](https://github.com/shm007g/LLaMA-Cult-and-More) ![GitHub Repo stars](https://img.shields.io/github/stars/shm007g/LLaMA-Cult-and-More?style=social): 跟踪适价LLM、羊驼Cult等更多内容。
- [Awesome Language Agents](https://github.com/ysymyth/awesome-language-agents) ![GitHub Repo stars](https://img.shields.io/github/stars/ysymyth/awesome-language-agents?style=social): 基于认知架构的llm agent列表。


## 不维护
- [LangchainUI](https://github.com/homanp/langchain-ui) ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/langchain-ui?style=social) : LangChain UI是一个开源的聊天AI工具包，基于LangChain构建，任何人都可以使用无代码类型的界面创建和托管聊天机器人。
- [Yeager.ai](https://github.com/yeagerai/yeagerai-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/yeagerai/yeagerai-agent?style=social): Yeager.ai Agent是第一个为Langchain设计的代理创建器，旨在帮助您轻松构建、原型设计和部署AI驱动的代理。Yeager.ai Agent强调灵活性、交互性和无缝集成，是开发人员、研究人员和AI爱好者的理想工具。

- **[QWK ($QWK) Autonomous MEV & Resource Escrow Agent / MCP](https://github.com/chase-tqg/QWIK-MEV-Core)** - Autonomous Web3 DeFi & MEV infrastructure agent, OpenAPI 3.1.0 tool (`openapi.json`), `SKILL.md`, and MCP server (`verify_enterprise_backing`, `get_escrow_contract_details`, `generate_seed_deposit_tx`) with on-chain Merkle commitments (`0x1Cc436b4D9316ee623CFeB760C44F84c9bD9C20A`) for $400,000+ in project-reported Google Cloud, NVIDIA, and Cloudflare resources and 0%-fee Morpho Blue flash-loan execution.
