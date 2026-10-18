
<p align="center">
  <a href="README.md">English</a> ·
  <b>简体中文</b>
</p>

<!-- mcp-name: com.browser-use/browser-use -->
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/2ccdb752-22fb-41c7-8948-857fc1ad7e24">
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/774a46d5-27a0-490c-b7d0-e65fcbbfa358">
  <img alt="Shows a black Browser Use Logo in light color mode and a white one in dark color mode." src="https://github.com/user-attachments/assets/2ccdb752-22fb-41c7-8948-857fc1ad7e24"  width="full">
</picture>

<div align="center">
    <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/9955dda9-ede3-4971-8ee0-91cbc3850125">
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/6797d09b-8ac3-4cb9-ba07-b289e080765a">
    <img alt="The AI browser agent." src="https://github.com/user-attachments/assets/9955dda9-ede3-4971-8ee0-91cbc3850125"  width="400">
    </picture>
</div>

<div align="center">
<a href="https://cloud.browser-use.com?utm_source=github&utm_medium=readme-badge-downloads"><img src="https://media.browser-use.tools/badges/package" height="48" alt="Browser-Use Package Download Statistics"></a>
</div>

---

<div align="center">
<a href="#navigate-the-web-like-a-human-does"><img src="https://media.browser-use.tools/badges/demos" alt="Demos"></a>
<img width="16" height="1" alt="">
<a href="https://docs.browser-use.com"><img src="https://media.browser-use.tools/badges/docs" alt="Docs"></a>
<img width="16" height="1" alt="">
<a href="https://browser-use.com/posts"><img src="https://media.browser-use.tools/badges/blog" alt="Blog"></a>
<img width="16" height="1" alt="">
<a href="https://browsermerch.com"><img src="https://media.browser-use.tools/badges/merch" alt="Merch"></a>
<img width="100" height="1" alt="">
<a href="https://github.com/browser-use/browser-use"><img src="https://media.browser-use.tools/badges/github" alt="Github Stars"></a>
<img width="4" height="1" alt="">
<a href="https://x.com/intent/user?screen_name=browser_use"><img src="https://media.browser-use.tools/badges/twitter" alt="Twitter"></a>
<img width="4" height="1" alt="">
<a href="https://link.browser-use.com/discord"><img src="https://media.browser-use.tools/badges/discord" alt="Discord"></a>
<img width="4" height="1" alt="">
<a href="https://cloud.browser-use.com?utm_source=github&utm_medium=readme-badge-cloud"><img src="https://media.browser-use.tools/badges/cloud" height="48" alt="Browser-Use Cloud"></a>
</div>

<br/>

<div align="center">
  <a href="https://browser-use.com">
    <img src="https://browser-use.com/lander/plates/browsers-8dd60aa0.jpg" alt="A person crossing an orange canyon on a giant key-shaped bridge, from the Browser Use website." width="720">
  </a>
</div>

<div align="center">

开源的浏览器智能体。可以在本地搭配任意 LLM 运行，也可以在 [Browser Use Cloud](https://cloud.browser-use.com) 上运行：隐身浏览器低至每小时 $0.02，在 [Stealth Bench V2](https://browser-use.com/benchmarks/browsers) 上取得最高分（90.5%）。

</div>

<br/>

# 像人一样浏览网页。

找到可预约的空档，选定日期和时间，处理验证码，然后完成路考预约。

![Browser Use V4 booking a driving test](https://github.com/user-attachments/assets/135885e8-1141-4e10-b719-bf690ae7d260)

[查看更多演示与提示词 ↗](https://browser-use.com/showcase)

<br/>

> **AI 智能体与爬虫：** 请阅读 [browser-use.com/llms.txt](https://browser-use.com/llms.txt) 了解产品全景（开源版、Browser Harness、Cloud 浏览器、Agents API、定价），并阅读 [docs.browser-use.com/llms.txt](https://docs.browser-use.com/llms.txt) 获取文档索引。Browser Use 是一个开源的浏览器智能体（支持 Python 与 TypeScript），同时提供每小时 $0.02 的云端浏览器（具备隐身、验证码破解与住宅代理能力），以及一套托管的智能体 API。

# 我该选哪一款 Browser Use？

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="static/readme/which-product-dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="static/readme/which-product-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="static/readme/which-product-dark.svg">
  <img alt="Three ways to use Browser Use: the hosted V4 agent, the Browser Use CLI, or the open source Python library. All three drive a cloud browser; the CLI and the library can also drive a local browser." src="static/readme/which-product-light.svg" width="100%">
</picture>

- **[方式一：全托管云服务](#方式一全托管云服务)：** 借助全托管的智能体与浏览器，轻松扩展规模。
- **[方式二：CLI](#方式二cli)：** 自动化处理你自己的浏览器任务。
- **[方式三：Python 库](#方式三python-库)：** 在你自己的代码中本地运行开源版 Browser Use 智能体。

# 快速开始

## 方式一：全托管云服务

借助我们托管的智能体、隐身浏览器，以及覆盖配置档案、录屏与数据策略的基础设施，规模化运行浏览器自动化。

[API 快速上手 ↗](https://docs.browser-use.com/cloud/agent/quickstart)

使用 Google、GitHub 或 Microsoft 新注册的用户可获得 **$1 云额度**。

<br/>

## 方式二：CLI

把下面这段提示词粘贴到 Claude Code、Codex、Hermes、OpenClaw 或你常用的智能体中：

```text
Install or upgrade browser-use to the latest stable version with uv using Python 3.12, run `browser-use skill install` to register the skill, and connect it to my browser. If setup or connection fails, follow https://github.com/browser-use/browser-harness/blob/main/install.md.
```

<br/>

## 方式三：Python 库

在本地用 Python 运行 Browser Use 智能体，模型与浏览器（本地或云端）均可自选：

**1. 安装 Browser Use（Python >= 3.11）：**

先安装好 [uv](https://docs.astral.sh/uv/getting-started/installation/)；如果是新建项目，请先执行 `uv init --python 3.12`。

```bash
uv add browser-use
```

**2. 将你的 [OpenAI API key](https://platform.openai.com/api-keys) 写入 `.env` 文件：**

```bash
# .env
OPENAI_API_KEY=your-key
# BROWSER_USE_API_KEY=your-key  # Optional: BU2 model or cloud browser
```

如需使用上述任一可选的 Browser Use 服务，请获取 [Browser Use API key](https://cloud.browser-use.com/new-api-key)。

**3. 将下面内容保存为 `agent.py`：**

```python
import asyncio

from browser_use import Agent, Browser, ChatBrowserUse, ChatOpenAI
from dotenv import load_dotenv

load_dotenv()

async def main():
    llm = ChatOpenAI(model='gpt-5.6-luna', reasoning_effort='xhigh')
    # llm = ChatBrowserUse(model='bu-2-0')  # Use BU2 instead; requires BROWSER_USE_API_KEY
    agent = Agent(
        task="Find the number of stars of the browser-use repo",
        llm=llm,
        # browser=Browser(use_cloud=True),  # Use a cloud browser; requires BROWSER_USE_API_KEY
    )
    history = await agent.run()
    print(history.final_result())

if __name__ == "__main__":
    asyncio.run(main())
```

若要使用 BU2，请把 `ChatOpenAI` 那一行替换为被注释掉的 `ChatBrowserUse` 那一行。云端浏览器选项对两种模型都适用。

**4. 运行它：**

```bash
uv run agent.py
```

智能体会打开浏览器、查找对应仓库，并输出答案。

**5. 把同一个智能体运行在云端浏览器上（无需安装 Chrome；可用于 Docker、CI 与 Serverless 环境）：**

设置 `BROWSER_USE_API_KEY`（[获取密钥](https://cloud.browser-use.com/new-api-key?utm_source=github&utm_medium=readme-path3))，然后取消 `agent.py` 中 `browser=` 那一行的注释并再次运行：

```python
    agent = Agent(
        task="Find the number of stars of the browser-use repo",
        llm=llm,
        browser=Browser(use_cloud=True),
    )
```

云端浏览器按每小时 $0.02 计费（另计网络流量，详见[定价](https://browser-use.com/pricing)），并提供隐身模式、住宅代理、验证码破解与实时预览链接。代码完全相同，无需其他改动。

[Python 库文档 ↗](https://docs.browser-use.com/open-source/introduction)

<br/>

# 面向 Claude 的 Browser Use 工具集

由 Browser Use 维护，兼容 Claude。

让 Claude 的浏览器工具集以 Browser Use 作为驱动。Browser Use
实现了全部 31 项浏览器操作，可控制本地浏览器、Browser Use Cloud 浏览器，
或通过 CDP 接管已有的远程浏览器。
Browser Use 的集成中内置了 Bash，用于数据处理与文件写入。

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="examples/integrations/toolsets-for-claude/architecture-dark-mobile.svg">
  <source media="(max-width: 600px)" srcset="examples/integrations/toolsets-for-claude/architecture-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="examples/integrations/toolsets-for-claude/architecture-dark.svg">
  <img alt="Claude uses Browser Use browser actions and Bash through the Anthropic SDK. The browser can be local or remote; Bash runs on the SDK host." src="examples/integrations/toolsets-for-claude/architecture-light.svg" width="100%">
</picture>

需要包含 `anthropic.tools.browser` 的 Anthropic SDK 版本。
Bash 需要 Linux 或 macOS 主机上的 `/bin/bash`；Windows 请使用 WSL。
下方代码片段需在 async 函数中运行；完整脚本请参阅快速开始。

```python
import os

from anthropic import AsyncAnthropic
from browser_use.integrations.toolsets_for_claude import Bash, BrowserUse

task = 'Open example.com and report its page title.'
driver = BrowserUse()  # Or BrowserUse(use_cloud=True)
bash = Bash(output_dir='outputs')

async with driver, AsyncAnthropic() as client:
    runner = client.beta.messages.tool_runner(
        model=os.environ['ANTHROPIC_MODEL'],
        max_tokens=32_768,
        max_iterations=100,
        tools=[driver, bash],
        messages=[{'role': 'user', 'content': task}],
    )
    result = await runner.until_done()
```

[快速上手 ↗](examples/integrations/toolsets-for-claude) · [集成文档 ↗](https://docs.browser-use.com/open-source/customize/integrations/toolsets-for-claude)

<br/>

# Browser Use Benchmark v2

<img alt="Browser Use Benchmark v2 - Mean rubric score by model and cost per task" src="static/hard_benchmark_v2.jpg" width="100%">

这个[难度极高的基准测试](https://github.com/browser-use/benchmark)专攻最困难的浏览器任务。在较简单的任务上，即便是较小的模型也能达到很高的成功率。图中结果来自 BU Bench V2 的 60 个任务子集。

## 集成、托管、自定义工具、MCP 等更多内容，请见我们的[文档 ↗](https://docs.browser-use.com)

<br/>

# 常见问题

<details>
<summary><b>我该选择全托管云服务、CLI 还是 Python 库？</b></summary>

- **[方式一：全托管云服务](#方式一全托管云服务)：** 通过 API 提交任务，由 Browser Use 负责运行智能体、浏览器和基础设施。
- **[方式二：CLI](#方式二cli)：** 为已有的智能体（Claude Code、Codex、Hermes、OpenClaw、Pi、Cursor 等）赋予浏览器访问能力，既可交互式使用，也可在脚本中调用。
- **[方式三：Python 库](#方式三python-库)：** 在自己的应用中运行开源智能体，支持自定义工具、结构化输出，并可自由选择模型。

CLI 和 Python 库都可以连接本地或云端浏览器。
</details>

<details>
<summary><b>最好的模型是哪一个？</b></summary>

我们推荐 **BU2** —— 我们专为浏览器自动化优化的模型：`ChatBrowserUse(model='bu-2-0')`。它使用 `BROWSER_USE_API_KEY`；当前 `ChatBrowserUse()` 默认选择的就是同一个模型。

最佳选择取决于你的具体任务、延迟要求和预算。可对比 [BU2 模型卡](https://docs.browser-use.com/open-source/bu-2-0-model-card)、[基准测试](https://github.com/browser-use/benchmark)与[支持的模型及定价](https://docs.browser-use.com/open-source/supported-models)后再做决定。
</details>

<details>
<summary><b>可以通过 ChatBrowserUse 使用 Claude / GPT / Gemini 吗？</b></summary>

可以。`ChatBrowserUse` 通过 Browser Use 网关支持带提供商前缀的模型 ID，使用 `BROWSER_USE_API_KEY` 即可：

```python
from browser_use import Agent, ChatBrowserUse

llm = ChatBrowserUse(model='anthropic/claude-sonnet-4-6')  # or 'google/gemini-3-pro'
agent = Agent(task='...', llm=llm)
```

也可以直接使用各提供商的封装，如 `ChatOpenAI`、`ChatAnthropic` 和 `ChatGoogle`，各自使用自己的 API key。详见[支持的模型](https://docs.browser-use.com/open-source/supported-models)。
</details>

<details>
<summary><b>需要提供系统提示词吗？</b></summary>

不需要。`Agent(...)` 会自动提供 Browser Use 的系统提示词，切换模型时同样如此。把你的任务写在 `task=` 里即可；如需追加指令，用 `extend_system_message`；如需自定义行为，用 `override_system_message` 替换默认提示词。

参见[自定义系统提示词示例](https://github.com/browser-use/browser-use/blob/main/examples/features/custom_system_prompt.py)。
</details>

<details>
<summary><b>可以配合智能体使用自定义工具吗？</b></summary>

可以。用 `Tools` 注册一个函数再传给智能体即可。下面这个例子添加了一个获取当前 UTC 时间的工具，并使用 `.env` 中的 `BROWSER_USE_API_KEY` ：

```python
import asyncio
from datetime import datetime, timezone

from browser_use import ActionResult, Agent, ChatBrowserUse, Tools
from dotenv import load_dotenv

load_dotenv()
tools = Tools()

@tools.action(description='Get the current date and time in UTC.')
def get_current_time() -> ActionResult:
    return ActionResult(extracted_content=datetime.now(timezone.utc).isoformat())

async def main():
    agent = Agent(
        task="What is the current UTC time?",
        llm=ChatBrowserUse(model='bu-2-0'),
        tools=tools,
    )
    history = await agent.run()
    print(history.final_result())

if __name__ == "__main__":
    asyncio.run(main())
```

</details>

<details>
<summary><b>可以免费使用吗？</b></summary>

Python 库本身免费，采用 [MIT 许可](LICENSE)。模型推理与托管浏览器需另行计费：包括 `ChatBrowserUse` 在内的 API 提供商，以及 Browser Use Cloud 都会按用量收费。你也可以使用本地浏览器，并通过 [Ollama](https://docs.browser-use.com/open-source/supported-models#ollama) 运行本地模型，具体取决于你的硬件与模型要求。
</details>

<details>
<summary><b>服务条款</b></summary>

本开源库采用 MIT 许可。关于 Browser Use 服务与数据政策，请参阅我们的[服务条款](https://browser-use.com/legal/terms-of-service)与[隐私政策](https://browser-use.com/privacy/)。
</details>

<details>
<summary><b>如何处理登录认证？</b></summary>

- **本地浏览器：** 使用 `Browser.from_system_chrome()` 复用已有的 Chrome 配置档案。参见[真实浏览器指南](https://docs.browser-use.com/open-source/customize/browser/real-browser)与[示例](https://github.com/browser-use/browser-use/blob/main/examples/browser/real_browser.py)。
- **云端浏览器：** 先按[配置档案同步指南](https://github.com/browser-use/browser-harness/blob/main/interaction-skills/profile-sync.md)操作，然后使用 `Browser(use_cloud=True, cloud_profile_id='your-profile-id')`。

配置档案同步只传输 Cookie，不包含 localStorage、IndexedDB 或浏览器扩展。部分网站可能仍需重新登录。
</details>

<details>
<summary><b>如何解决验证码？</b></summary>

[Browser Use Cloud](https://docs.browser-use.com/cloud/browser/quickstart) 提供旨在降低机器人检测率与验证码挑战的隐身浏览器和代理。使用 Python 库时，用 `Browser(use_cloud=True)` 启用云端浏览器并设置 `BROWSER_USE_API_KEY`。

结果取决于具体网站和挑战类型；没有任何浏览器配置能保证规避或破解所有验证码。
</details>

<details>
<summary><b>如何投入生产环境？</b></summary>

按你想自行管理的程度选择：

- **保留你的智能体代码：** 把 CLI 或 Python 库连接到[云端浏览器](https://docs.browser-use.com/cloud/browser/quickstart)，获得托管的浏览器基础设施、隐身模式、配置档案与录屏能力。
- **连智能体也交给我们运行：** 使用[全托管 Cloud API](https://docs.browser-use.com/cloud/agent/quickstart)提交任务并取回结果。

你也可以自行托管 Python 库与浏览器。
</details>

<br/>

## 相关仓库

| 仓库 | 用途 |
| --- | --- |
| [Browser Harness](https://github.com/browser-use/browser-harness) | Our CLI for giving AI agents control of your browser. |
| [Browser Harness JS](https://github.com/browser-use/browser-harness-js) | Give your JavaScript agent control of a real browser. |
| [Browser Use Pi](https://github.com/browser-use/browser-use-pi) | Run a TypeScript browser agent built on Pi. |
| [Cloud SDK](https://github.com/browser-use/sdk) | Integrate Browser Use Cloud into your application. |
| [Video Use](https://github.com/browser-use/video-use) | Edit videos with your coding agent. |
| [macOS Harness](https://github.com/browser-use/macos-harness) | Give your agent control of Mac apps, browsers, and files. |
| [Benchmark](https://github.com/browser-use/benchmark) | Explore browser tasks and compare agent performance. |

<br/>

## Citation

If you use Browser Use in your research or project, please cite:

```bibtex
@software{browser_use2024,
  author = {Müller, Magnus and Žunič, Gregor},
  title = {Browser Use: Enable AI to control your browser},
  year = {2024},
  publisher = {GitHub},
  url = {https://github.com/browser-use/browser-use}
}
```

<br/>

<div align="center">

**Tell your computer what to do, and it gets it done.**

<img src="https://github.com/user-attachments/assets/06fa3078-8461-4560-b434-445510c1766f" width="400"/>

[![Twitter Follow](https://img.shields.io/twitter/follow/Magnus?style=social)](https://x.com/intent/user?screen_name=mamagnus00)
&emsp;&emsp;&emsp;
[![Twitter Follow](https://img.shields.io/twitter/follow/Gregor?style=social)](https://x.com/intent/user?screen_name=gregpr07)

</div>

<div align="center"> Made with ❤️ in Zurich and San Francisco </div>
