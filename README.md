<a name="readme-top"></a>

<div align="center">
  <img src="./assets/AutoAgent_logo.svg" alt="Logo" width="200">
  <h1 align="center">AutoAgent: 全自动 & 零代码</br> 大语言模型代理框架 </h1>
</div>




<div align="center">
  <a href="https://autoagent-ai.github.io"><img src="https://img.shields.io/badge/项目-页面-blue?style=for-the-badge&color=FFE165&logo=homepage&logoColor=white" alt="Credits"></a>
  <a href="https://join.slack.com/t/metachain-workspace/shared_invite/zt-2zibtmutw-v7xOJObBf9jE2w3x7nctFQ"><img src="https://img.shields.io/badge/Slack-加入我们-red?logo=slack&logoColor=white&style=for-the-badge" alt="加入我们的Slack社区"></a>
  <a href="https://discord.gg/jQJdXyDB"><img src="https://img.shields.io/badge/Discord-加入我们-purple?logo=discord&logoColor=white&style=for-the-badge" alt="加入我们的Discord社区"></a>
  <a href="https://github.com/HKUDS/AutoAgent/blob/main/assets/autoagent-wechat.jpg"><img src="https://img.shields.io/badge/微信-加入我们-green?logo=wechat&logoColor=white&style=for-the-badge" alt="加入我们的微信社区"></a>
  <br/>
  <a href="https://autoagent-ai.github.io/docs"><img src="https://img.shields.io/badge/文档-000?logo=googledocs&logoColor=FFE165&style=for-the-badge" alt="查看文档"></a>
  <a href="https://arxiv.org/abs/2502.05957"><img src="https://img.shields.io/badge/Arxiv论文-000?logoColor=FFE165&logo=arxiv&style=for-the-badge" alt="论文"></a>
  <a href="https://gaia-benchmark-leaderboard.hf.space/"><img src="https://img.shields.io/badge/GAIA基准测试-000?logoColor=FFE165&logo=huggingface&style=for-the-badge" alt="评估基准分数"></a>
  <hr>
</div>

欢迎体验AutoAgent！AutoAgent 是一个**全自动**且高度**自我发展**的框架，使用户能够仅通过**自然语言**创建和部署大语言模型代理。

## ✨核心功能

* 🏆 GAIA基准测试中的顶级表现
</br>AutoAgent 在开源方法中名列前茅，性能可媲美 **OpenAI的Deep Research**。

* 📚 原生自管理向量数据库的Agentic-RAG
</br>AutoAgent 配备原生自管理向量数据库，性能超越行业领先解决方案，如 **LangChain**。

* ✨ 轻松创建代理和工作流程
</br>AutoAgent 利用自然语言轻松构建即用型**工具**、**代理**和**工作流程**，无需编码。

* 🌐 通用的LLM支持
</br>AutoAgent 无缝集成**多种**大语言模型（例如 OpenAI、Anthropic、Deepseek、vLLM、Grok、Huggingface 等）。

* 🔀 灵活的交互方式
</br>支持**函数调用**和 **ReAct** 两种交互模式。

* 🤖 动态、可扩展、轻量级
</br>AutoAgent 是您的**个人AI助手**，设计为动态、可扩展、定制化且轻量级。

🚀 解锁LLM代理的未来。现在就试试 🔥AutoAgent🔥！

<div align="center">
  <!-- <img src="./assets/AutoAgentnew-intro.pdf" alt="Logo" width="100%"> -->
  <figure>
    <img src="./assets/autoagent-intro.svg" alt="Logo" style="max-width: 100%; height: auto;">
    <figcaption><em>AutoAgent快速概览。</em></figcaption>
  </figure>
</div>



## 🔥 新闻

<div class="scrollable">
    <ul>
      <li><strong>[2025年2月17日]</strong>:  🎉🎉我们已更新并发布了AutoAgent v0.2.0（原名MetaChain）。详细变更包括：1）修复来自问题报告的不同LLM提供者的错误；2）根据问题报告在容器环境中添加AutoAgent的自动安装；3）为CLI模式添加更多易用命令；4）将项目更名为AutoAgent以便更好地理解。</li>
      <li><strong>[2025年2月10日]</strong>:  🎉🎉我们发布了 <b>MetaChain！</b>，包括框架、评估代码和CLI模式！查看我们的<a href="https://arxiv.org/abs/2502.05957">论文</a>了解更多详情。</li>
    </ul>
</div>
<span id='table-of-contents'/>

## 📑 目录

* <a href='#features'>✨ 功能</a>
* <a href='#news'>🔥 新闻</a>
* <a href='#how-to-use'>🔍 如何使用AutoAgent</a>
  * <a href='#user-mode'>1. `用户模式` (SOTA 🏆 Open Deep Research)</a>
  * <a href='#agent-editor'>2. `代理编辑器` (无工作流程的代理创建)</a>
  * <a href='#workflow-editor'>3. `工作流程编辑器` (带工作流程的代理创建)</a>
* <a href='#quick-start'>⚡ 快速入门</a>
  * <a href='#installation'>安装</a>
  * <a href='#api-keys-setup'>API密钥设置</a>
  * <a href='#start-with-cli-mode'>以CLI模式启动</a>
* <a href='#todo'>☑️ 待办事项</a>
* <a href='#reproduce'>🔬 如何重现论文中的结果</a>
* <a href='#documentation'>📖 文档</a>
* <a href='#community'>🤝 加入社区</a>
* <a href='#acknowledgements'>🙏 致谢</a>
* <a href='#cite'>🌟 引用</a>

<span id='how-to-use'/>

## 🔍 如何使用AutoAgent

<span id='user-mode'/>

### 1. `用户模式` (SOTA 🏆 Open Deep Research)

AutoAgent 提供了一个开箱即用的多代理系统，您可以在起始页面选择 `用户模式` 来使用它。这个多代理系统是一个通用AI助手，与 **OpenAI的Deep Research** 具有相同功能，并且在 [GAIA](https://gaia-benchmark-leaderboard.hf.space/) 基准测试中性能与之相当。

- 🚀 **高性能**：使用 Claude 3.5 而非 OpenAI 的 o3 模型，与 Deep Research 性能匹配。
- 🔄 **模型灵活性**：兼容任何大语言模型（包括 Deepseek-R1、Grok、Gemini 等）。
- 💰 **成本效益**：开源替代 Deep Research 的 $200/月订阅。
- 🎯 **用户友好**：易于部署的CLI界面，实现无缝交互。
- 📁 **文件支持**：支持文件上传以增强数据交互。

<div align="center">
  <video width="80%" controls>
    <source src="./assets/video_v1_compressed.mp4" type="video/mp4">
  </video>
  <p><em>🎥 Deep Research（即用户模式）</em></p>
</div>



<span id='agent-editor'/>

### 2. `代理编辑器` (无工作流程的代理创建)

AutoAgent 最独特的功能是其自然语言定制能力。与其他代理框架不同，AutoAgent 允许您仅使用自然语言创建工具、代理和工作流程。只需选择 `代理编辑器` 或 `工作流程编辑器` 模式，即可通过对话开始构建代理的旅程。

您可以按照下图所示使用 `代理编辑器`。

<table>
<tr align="center">
    <td width="33%">
        <img src="./assets/agent_editor/1-requirement.png" alt="requirement" width="100%"/>
        <br>
        <em>输入您想要创建的代理类型。</em>
    </td>
    <td width="33%">
        <img src="./assets/agent_editor/2-profiling.png" alt="profiling" width="100%"/>
        <br>
        <em>自动代理分析。</em>
    </td>
    <td width="33%">
        <img src="./assets/agent_editor/3-profiles.png" alt="profiles" width="100%"/>
        <br>
        <em>输出代理配置文件。</em>
    </td>
</tr>
</table>
<table>
<tr align="center">
    <td width="33%">
        <img src="./assets/agent_editor/4-tools.png" alt="tools" width="100%"/>
        <br>
        <em>创建所需的工具。</em>
    </td>
    <td width="33%">
        <img src="./assets/agent_editor/5-task.png" alt="task" width="100%"/>
        <br>
        <em>输入您希望代理完成的任务。（可选）</em>
    </td>
    <td width="33%">
        <img src="./assets/agent_editor/6-output-next.png" alt="output" width="100%"/>
        <br>
        <em>创建所需的代理并进入下一步。</em>
    </td>
</tr>
</table>

<span id='workflow-editor'/>

### 3. `工作流程编辑器` (带工作流程的代理创建)

您还可以使用 `工作流程编辑器` 模式通过自然语言描述创建代理工作流程，如下图所示。（提示：此模式暂时不支持工具创建。）

<table>
<tr align="center">
    <td width="33%">
        <img src="./assets/workflow_editor/1-requirement.png" alt="requirement" width="100%"/>
        <br>
        <em>输入您想要创建的工作流程类型。</em>
    </td>
    <td width="33%">
        <img src="./assets/workflow_editor/2-profiling.png" alt="profiling" width="100%"/>
        <br>
        <em>自动工作流程分析。</em>
    </td>
    <td width="33%">
        <img src="./assets/workflow_editor/3-profiles.png" alt="profiles" width="100%"/>
        <br>
        <em>输出工作流程配置文件。</em>
    </td>
</tr>
</table>
<table>
<tr align="center">
    <td width="33%">
        <img src="./assets/workflow_editor/4-task.png" alt="task" width="66%"/>
        <br>
        <em>输入您希望工作流程完成的任务。（可选）</em>
    </td>
    <td width="33%">
        <img src="./assets/workflow_editor/5-output-next.png" alt="output" width="66%"/>
        <br>
        <em>创建所需的工作流程并进入下一步。</em>
    </td>
</tr>
</table>

<span id='quick-start'/>

## ⚡ 快速入门

<span id='installation'/>

### 安装

#### AutoAgent 安装

```bash
git clone https://github.com/HKUDS/AutoAgent.git
cd AutoAgent
pip install -e .
```

#### Docker 安装

我们使用 Docker 将代理交互环境容器化。因此，请先安装 [Docker](https://www.docker.com/)。您无需手动拉取预构建的镜像，因为我们已让 Auto-Deep-Research **根据您机器的架构自动拉取预构建镜像**。

<span id='api-keys-setup'/>

### API 密钥设置

创建一个环境变量文件，例如 `.env.template`，并为您想使用的大语言模型设置 API 密钥。并非每个 LLM 的 API 密钥都是必需的，只需使用您需要的即可。

```bash
# 必需的个人 Github 令牌
GITHUB_AI_TOKEN=

# 可选的 API 密钥
OPENAI_API_KEY=
DEEPSEEK_API_KEY=
ANTHROPIC_API_KEY=
GEMINI_API_KEY=
HUGGINGFACE_API_KEY=
GROQ_API_KEY=
XAI_API_KEY=
```

<span id='start-with-cli-mode'/>

### 以CLI模式启动

> [🚨 **新闻**：] 我们更新了一个更易用的命令来启动CLI模式，并修复了来自问题报告的不同LLM提供者的错误。您可以按照以下步骤使用不同的LLM提供者启动CLI模式，配置更少。

#### 命令选项：

您可以运行 `auto main` 来启动AutoAgent的完整功能，包括 `用户模式`、`代理编辑器` 和 `工作流程编辑器`。另外，您也可以运行 `auto deep-research` 来启动更轻量级的 `用户模式`，类似于 [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) 项目。以下是该命令的一些配置说明。

- `--container_name`：Docker容器的名称（默认：'deepresearch'）
- `--port`：容器的端口（默认：12346）
- `COMPLETION_MODEL`：指定要使用的大语言模型，您应遵循 [Litellm](https://github.com/BerriAI/litellm) 的命名规则设置模型名称。（默认：`claude-3-5-sonnet-20241022`）
- `DEBUG`：启用调试模式以获取详细日志（默认：False）
- `API_BASE_URL`：LLM提供者的基础URL（默认：None）
- `FN_CALL`：启用函数调用（默认：None）。大多数情况下，您可以忽略此选项，因为我们已根据模型名称设置了默认值。
- `git_clone`：将AutoAgent仓库克隆到本地环境（仅支持 `auto main` 命令，默认：True）
- `test_pull_name`：测试拉取的名称。（仅支持 `auto main` 命令，默认：'autoagent_mirror'）

#### 关于 `git_clone` 和 `test_pull_name` 的更多细节

在 `代理编辑器` 和 `工作流程编辑器` 模式下，我们需要将AutoAgent仓库的镜像克隆到本地代理交互环境中，并让 **AutoAgent** 自动更新自身，例如创建新工具、代理和工作流程。因此，如果您想使用 `代理编辑器` 和 `工作流程编辑器` 模式，应将 `git_clone` 设置为 True，并将 `test_pull_name` 设置为 'autoagent_mirror' 或其他分支。

#### 使用 `auto main` 和不同LLM提供者

接下来，我将展示如何使用 `auto main` 命令和不同的LLM提供者运行AutoAgent的完整功能。如果您想使用 `auto deep-research` 命令，可以参考 [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) 项目获取更多详情。

##### Anthropic

* 在 `.env` 文件中设置 `ANTHROPIC_API_KEY`。

```bash
ANTHROPIC_API_KEY=您的_anthropic_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
auto main # 默认模型为 claude-3-5-sonnet-20241022
```

##### OpenAI

* 在 `.env` 文件中设置 `OPENAI_API_KEY`。

```bash
OPENAI_API_KEY=您的_openai_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=gpt-4o auto main
```

##### Mistral

* 在 `.env` 文件中设置 `MISTRAL_API_KEY`。

```bash
MISTRAL_API_KEY=您的_mistral_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=mistral/mistral-large-2407 auto main
```

##### Gemini - Google AI Studio

* 在 `.env` 文件中设置 `GEMINI_API_KEY`。

```bash
GEMINI_API_KEY=您的_gemini_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=gemini/gemini-2.0-flash auto main
```

##### Huggingface

* 在 `.env` 文件中设置 `HUGGINGFACE_API_KEY`。

```bash
HUGGINGFACE_API_KEY=您的_huggingface_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=huggingface/meta-llama/Llama-3.3-70B-Instruct auto main
```

##### Groq

* 在 `.env` 文件中设置 `GROQ_API_KEY`。

```bash
GROQ_API_KEY=您的_groq_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=groq/deepseek-r1-distill-llama-70b auto main
```

##### OpenAI兼容端点（例如，Grok）

* 在 `.env` 文件中设置 `OPENAI_API_KEY`。

```bash
OPENAI_API_KEY=您的_openai_兼容端点的_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=openai/grok-2-latest API_BASE_URL=https://api.x.ai/v1 auto main
```

##### OpenRouter（例如，DeepSeek-R1）

我们暂时推荐使用 OpenRouter 作为 DeepSeek-R1 的 LLM 提供者。因为 DeepSeek-R1 的官方 API 无法高效使用。

* 在 `.env` 文件中设置 `OPENROUTER_API_KEY`。

```bash
OPENROUTER_API_KEY=您的_openrouter_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=openrouter/deepseek/deepseek-r1 auto main
```

##### DeepSeek

* 在 `.env` 文件中设置 `DEEPSEEK_API_KEY`。

```bash
DEEPSEEK_API_KEY=您的_deepseek_api_key
```

* 运行以下命令启动 Auto-Deep-Research。

```bash
COMPLETION_MODEL=deepseek/deepseek-chat auto main
```


CLI模式启动后，您可以看到AutoAgent的起始页面：

<div align="center">
  <!-- <img src="./assets/AutoAgentnew-intro.pdf" alt="Logo" width="100%"> -->
  <figure>
    <img src="./assets/cover.png" alt="Logo" style="max-width: 100%; height: auto;">
    <figcaption><em>AutoAgent的起始页面。</em></figcaption>
  </figure>
</div>

### 小贴士

#### 将浏览器cookie导入浏览器环境

您可以将浏览器cookie导入浏览器环境，让代理更好地访问某些特定网站。更多详情，请参考 [cookies](./AutoAgent/environment/cookie_json/README.md) 文件夹。

#### 为第三方工具平台添加您自己的API密钥

如果您想从第三方工具平台（如 RapidAPI）创建工具，您需要从平台订阅工具并通过运行 [process_tool_docs.py](./process_tool_docs.py) 添加您自己的API密钥。

```bash
python process_tool_docs.py
```

更多功能即将来临！🚀 **Web GUI界面** 正在开发中。



<span id='todo'/>

## ☑️ 待办事项列表

AutoAgent 在不断进化！以下是即将推出的内容：

- 📊 **更多基准测试**：扩展评估至 **SWE-bench**、**WebArena** 等
- 🖥️ **GUI代理**：支持带有GUI交互的 *Computer-Use* 代理
- 🔧 **工具平台**：与更多平台（如 **Composio**）集成
- 🏗️ **代码沙盒**：支持更多环境，如 **E2B**
- 🎨 **Web界面**：开发全面的GUI以提升用户体验

有想法或建议？欢迎提出问题！敬请期待更多激动人心的更新！🚀

<span id='reproduce'/>

## 🔬 如何重现论文中的结果

### GAIA基准测试
对于GAIA基准测试，您可以运行以下命令进行推理。

```bash
cd path/to/AutoAgent && sh evaluation/gaia/scripts/run_infer.sh
```

对于评估，您可以运行以下命令。

```bash
cd path/to/AutoAgent && python evaluation/gaia/get_score.py
```

### Agentic-RAG

对于Agentic-RAG任务，您可以运行以下命令进行推理。

步骤1. 转到 [此页面](https://huggingface.co/datasets/yixuantt/MultiHopRAG) 并下载数据。将它们保存到您的数据路径中。

步骤2. 运行以下命令进行推理。

```bash
cd path/to/AutoAgent && sh evaluation/multihoprag/scripts/run_rag.sh
```

步骤3. 结果将保存在 `evaluation/multihoprag/result.json` 中。

<span id='documentation'/>

## 📖 文档

更详细的文档即将来临 🚀，我们将在 [文档](https://AutoAgent-ai.github.io/docs) 页面中更新。

<span id='community'/>

## 🤝 加入社区

我们希望为AutoAgent建立一个社区，欢迎所有人加入我们。您可以通过以下方式加入我们的社区：

- [加入我们的Slack工作区](https://join.slack.com/t/AutoAgent-workspace/shared_invite/zt-2zibtmutw-v7xOJObBf9jE2w3x7nctFQ) - 在这里我们讨论研究、架构和未来发展。
- [加入我们的Discord服务器](https://discord.gg/z68KRvwB) - 这是一个社区运营的服务器，用于一般讨论、提问和反馈。
- [阅读或发布Github问题](https://github.com/HKUDS/AutoAgent/issues) - 查看我们正在处理的问题，或添加您自己的想法。

<span id='acknowledgements'/>



## 杂项

<div align="center">

[![Stargazers repo roster for @HKUDS/AutoAgent](https://reporoster.com/stars/HKUDS/AutoAgent)](https://github.com/HKUDS/AutoAgent/stargazers)

[![Forkers repo roster for @HKUDS/AutoAgent](https://reporoster.com/forks/HKUDS/AutoAgent)](https://github.com/HKUDS/AutoAgent/network/members)

[![Star History Chart](https://api.star-history.com/svg?repos=HKUDS/AutoAgent&type=Date)](https://star-history.com/#HKUDS/AutoAgent&Date)

</div>

## 🙏 致谢

罗马不是一天建成的。AutoAgent 站在巨人的肩膀上，我们衷心感谢前人杰出的工作。我们的框架架构受到 [OpenAI Swarm](https://github.com/openai/swarm) 的启发，而用户模式的三代理设计则受益于 [Magentic-one](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one) 的见解。我们还从 [OpenHands](https://github.com/All-Hands-AI/OpenHands) 中学习了文档结构，以及许多其他优秀项目在代理-环境交互设计方面的经验。我们对所有这些塑造了 AutoAgent 的开创性工作表示诚挚的感激和敬意。


<span id='cite'/>

## 🌟 引用

```tex
@misc{AutoAgent,
      title={{AutoAgent: 全自动零代码大语言模型代理框架}},
      author={唐佳斌, 范天宇, 黄超},
      year={2025},
      eprint={202502.05957},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2502.05957},
}
```





