# LLM_arsenal
Equip yourself with the power of all useful knowledge through LLM.

Some specific scenarios are marked with numbers. General content is not marked.

# 1. Code

## Technical Approach

Some tool approaches to achieve dialogue and associate project files with LLM interaction:
- cursor/windsurf
- vscode + copilot with built-in gpt4o, o1 preview, sonnet (free for edu email)
- vscode + roo cline + various LLMs (deepseek...) (OpenRoute or gemini flash API for free)

## Tools

- Better project file structure reading for large models [Repo Prompt](https://repoprompt.com/);
- GitHub code summarization master [Gitingest](https://gitingest.com/);
- [Tune a model | Google AI Studio](https://aistudio.google.com/tune) Google Gemini's web-based free fine-tuning tool, using `Gemini 1.5 Flash`.

# 2. Office Automation

## Tools

- Large model RPA [browser-use/browser-use: Make websites accessible for AI agents](https://github.com/browser-use/browser-use);
- [Review of the most expensive AI programming tool, seeing the future of coders【First on the internet】_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1FP6RYcEeV/) [Devin](https://devin.ai/)
  - Review: "Can solve pure text compilation errors, but struggles with runtime errors. Relies on pure memory to read."
  - "Lint, search, cut... Large models seem to only memorize, and these simple tools are temporarily unusable."

# 3. Research

## Writing

[【Practical Demonstration】Only 5min needed! Using ChatGPT to complete a SCI paper!_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1jC4y1J7Wc/?spm_id_from=333.1387.upload.video_card.click&vd_source=762d1c17ffbeb091e5b069e774a31b4d) The use of prompts here is excellent.

Key considerations:
- Whether references are generated accurately;
- It's best to provide related articles for reference or integration.

## Tools

- Large model review generator [stanford-oval/storm: An LLM-powered knowledge curation system that researches a topic and generates a full-length report with citations.](https://github.com/stanford-oval/storm);
- [binary-husky/gpt_academic: Provides practical interaction interfaces for GPT/GLM and other LLMs, especially optimized for paper reading/polishing/writing, modular design, supports custom shortcuts & function plugins, supports Python and C++ project analysis & self-translation, PDF/LaTex paper translation & summarization, supports parallel querying of multiple LLMs, supports local models like chatglm3. Integrates Tongyi Qianwen, deepseekcoder, Xunfei Xinghuo, Wenxin Yiyan, llama2, rwkv, claude2, moss, etc.](https://github.com/binary-husky/gpt_academic)
- [AutoSurveys/AutoSurvey](https://github.com/AutoSurveys/AutoSurvey)

# 4. Agent



## Tools

- [Quick Start | MetaGPT](https://docs.deepwisdom.ai/v0.7/zh/guide/get_started/quickstart.html) Create multi-agent integration tools.
- [Dify.AI · The Innovation Engine for Generative AI Applications](https://dify.ai/)



[主流Agent框架2024盘点: LangGraph、CrewAI、AutoGen、Dify、MetaGPT、OmAgent深度横评](https://www.msn.cn/zh-cn/news/other/主流agent框架2024盘点-langgraph-crewai-autogen-dify-metagpt-omagent深度横评/ar-BB1rfHWQ?ocid=BingNewsSerp)

# n. Others

## Tools

- [bolt.new](https://bolt.new/) Web tool development.

# Useful GPT Platforms

- [ChatGPT](https://chatgpt.com/)
- [Claude](https://claude.ai/)
- [Gemini](https://gemini.google.com/)
- [copilot.microsoft.com](https://copilot.microsoft.com/)
- [New Chat - Poe](https://poe.com/ChatGPT), collection.
  
- Chinese:
  - [DeepSeek - Exploring the Unknown](https://chat.deepseek.com/)
  - [Kimi.ai - Helping you see a bigger world](https://kimi.moonshot.cn/)

Additionally, [Untitled prompt | Google AI Studio](https://aistudio.google.com/prompts/new_chat) provides system instructions, temperature adjustment, multimodal tools, etc.:

![](http://cos01.mugpeng.top/img/20250116205557.png)

Currently, it is completely free. It even offers free fine-tuning tools.

# Free APIs

- [kkkunny/free-llm-collect: Collects free LLM (Large Language Model) APIs (GPT, Claude, BingCopilot, Llama, Gemini)](https://github.com/kkkunny/free-llm-collect)
- [OpenRouter](https://openrouter.ai/)
  - You can search for free models or sort by price: [Models: 'free' | OpenRouter](https://openrouter.ai/models?order=pricing-low-to-high&q=free)

- https://ai.google.dev/gemini-api/ Google provides free access to Gemini for all developers: as long as the frequency does not exceed 15 times per minute—sufficient for AI-assisted programming.

# Prompts

From @欲买桂花同载酒: /Resources/prompts.md

Copilot configuration rules:

[Tips & Tricks for GitHub Copilot Chat in Visual Studio - Visual Studio (Windows) | Microsoft Learn](https://learn.microsoft.com/en-us/visualstudio/ide/copilot-chat-context?view=vs-2022#prompting-guidance)

- Create `.github/copilot-instructions.md` in the project folder.
- Enable the feature in Visual Studio via **Tools** > **Options** > **GitHub** > **Copilot** > select **(Preview) Enable custom instructions to be loaded from .github/copilot-instructions.md files and added to requests.**

For cursor, simply configure the rules.

Other resources:

[17-year-old high school student writes a god-level Prompt, directly enhancing Claude to full-blooded o1.](https://mp.weixin.qq.com/s/IAKD0FfcYehs5FsDkLbTJQ)

[A "super prompt" that makes LLMs more creative](https://mp.weixin.qq.com/s/U99Qalq9RO9LIcDP6bPB1w)
The "super prompt" includes the following four core dimensions:
- Encourage curiosity: Push LLMs to dig deeper into thinking.
- Inspire association: Enhance LLMs' associative abilities to generate more creative content.
- Promote reflection: Guide LLMs to reflect and deepen problems, making more logical reasoning.
- Cultivate empathy: Make LLMs more human-like, generating responses with more emotional resonance.

The steps to use the "super prompt" are very simple: In tasks requiring divergent thinking or creativity, first input the "super prompt" to the LLM. Then ask related questions, and the LLM will provide deeper, more abstract answers under the guidance of the prompt. You can also build a GPT environment to continuously ask questions, allowing the LLM to generate highly creative answers.

Kimi's prompt experts are also very useful:

[Conversation with Prompt Experts - Kimi.ai](https://kimi.moonshot.cn/kimiplus/conpg00t7lagbbsfqkq0)

The structure is relatively simple, mainly including the following parts:

```
- Role
- Background
- Profile
- Skills
- Goals
- Constrains
- OutputFormat
- Workflow
- Examples
- Initialization
```

Since Kimi's default language is Chinese, you can specify the need for English writing in the declaration, such as "I need you to write R code based on my requirements, and I need you to write it in English."

For example: 点击链接查看和 Kimi 智能助手的对话 https://kimi.moonshot.cn/share/cu4gfvep4uo71f7kbo40



Some simple prompts for specific scenarios:

![](http://cos01.mugpeng.top/img/20250116210943.png)

# Learning Resources

- LLM Biomedical Related Articles

[aristoteleo/awesome-papers-on-biological-agent-models: This repo collects all latest research on agent system for biological studies](https://github.com/aristoteleo/awesome-papers-on-biological-agent-models)

# Other Projects

[Webioinfo01/easyLLM: Locally deployed storm.](https://github.com/Webioinfo01/easyLLM)

# Contributions

Welcome to pull or issue to provide better projects and tools.
