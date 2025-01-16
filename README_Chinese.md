# LLM_arsenal
Equip yourself with the power of all useful knowledge through LLM.



一些具体场景，全部用数字标记出来。通用内容就没有标记了。



# 1、Code

## 技术路线

一些工具路线实现对话并关联项目文件与LLM 交互：
- cursor/windsurf
- vscode + copilot 自带gpt4o,o1 preview, sonnet （edu 邮箱免费使用）
- vscode + roo cline + 各种LLM（deepseek..）（OpenRoute 或gemini flash API 免费）



## Tools

- 更好的让大模型阅读项目文件结构 [Repo Prompt](https://repoprompt.com/)；
- github 代码总结大师 [Gitingest](https://gitingest.com/)；
- [Tune a model | Google AI Studio](https://aistudio.google.com/tune) google gemini 的网页版免费微调工具，使用`Gemini 1.5 Flash`



# 2、自动化办公



## Tools

- 大模型RPA [browser-use/browser-use: Make websites accessible for AI agents](https://github.com/browser-use/browser-use)；
- [评测最贵AI编程工具，看到码农的未来【全网首发】_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1FP6RYcEeV/)  [Devin](https://devin.ai/)
  - 评价 “能解决纯文本的编译错误，对于运行错误，很难解决。只能靠纯记忆的方式去读取。”
  - "lint、搜索、剪切…… 大模型似乎只能死记硬背，这些简单的工具都暂时不会使用。"



# 3、research

## 写作

[【实操演示】仅需5min！用ChatGPT完成一篇SCI论文写作！_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1jC4y1J7Wc/?spm_id_from=333.1387.upload.video_card.click&vd_source=762d1c17ffbeb091e5b069e774a31b4d) 里面关于提示词的使用不错。

关键还是要考虑几个要素：

- 参考文献是否生成准确；
- 最好提供相关文章以进行参考或者整合；



## Tools

- 大模型综述生成器 [stanford-oval/storm: An LLM-powered knowledge curation system that researches a topic and generates a full-length report with citations.](https://github.com/stanford-oval/storm)；
- [binary-husky/gpt_academic: 为GPT/GLM等LLM大语言模型提供实用化交互接口，特别优化论文阅读/润色/写作体验，模块化设计，支持自定义快捷按钮&函数插件，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持chatglm3等本地模型。接入通义千问, deepseekcoder, 讯飞星火, 文心一言, llama2, rwkv, claude2, moss等。](https://github.com/binary-husky/gpt_academic)
- [AutoSurveys/AutoSurvey](https://github.com/AutoSurveys/AutoSurvey)



# 4、agent



## Tools

- [快速开始 | MetaGPT](https://docs.deepwisdom.ai/v0.7/zh/guide/get_started/quickstart.html) 制作多agent 整合工具。



# n、其他

## Tools

- [bolt.new](https://bolt.new/) web 工具开发



# 比较好用的GPT 平台

- [ChatGPT](https://chatgpt.com/)
- [Claude](https://claude.ai/)
- [Gemini](https://gemini.google.com/)
- [copilot.microsoft.com](https://copilot.microsoft.com/)
- [新建聊天 - Poe](https://poe.com/ChatGPT) ，集合
- 
- 国产
  - [DeepSeek - 探索未至之境](https://chat.deepseek.com/)
  - [Kimi.ai - 帮你看更大的世界](https://kimi.moonshot.cn/)



此外，[Untitled prompt | Google AI Studio](https://aistudio.google.com/prompts/new_chat) 提供了system instructions, temperature 调整，多模态等工具：

![](http://cos01.mugpeng.top/img/20250116205557.png)

目前也是完全免费。甚至还提供了免费的微调工具。



# 免费API

- [kkkunny/free-llm-collect: 搜集免费的LLM（大语言模型）API（GPT、Claude、BingCopilot、Llama、Gemini）](https://github.com/kkkunny/free-llm-collect)
- [OpenRouter](https://openrouter.ai/)
  - 可以通过free 搜索，或升序选择便宜的模式：[Models: 'free' | OpenRouter](https://openrouter.ai/models?order=pricing-low-to-high&q=free)

- https://ai.google.dev/gemini-api/  Google 为所有开发者提供了 Gemini 的免费调用方式：只要频率不高于每分钟 15 次即可——对于 AI 辅助编程而言足矣。



# 提示词

来自 @欲买桂花同载酒：

```
By default, all responses must be in English.

# AI Full-Stack Development Assistant Guide

## Core Thinking Patterns
You must engage in multi-dimensional deep thinking before and during responses:

### Fundamental Thinking Modes
- Systems Thinking: Three-dimensional thinking from overall architecture to specific implementation
- Dialectical Thinking: Weighing pros and cons of multiple solutions  
- Creative Thinking: Breaking through conventional thinking patterns to find innovative solutions
- Critical Thinking: Multi-angle validation and optimization of solutions

### Thinking Balance
- Balance between analysis and intuition
- Balance between detailed inspection and global perspective  
- Balance between theoretical understanding and practical application
- Balance between deep thinking and forward momentum
- Balance between complexity and clarity

### Analysis Depth Control  
- Conduct in-depth analysis for complex problems
- Keep simple issues concise and efficient
- Ensure analysis depth matches problem importance
- Find balance between rigor and practicality

### Goal Focus
- Maintain clear connection with original requirements
- Guide divergent thinking back to the main topic timely
- Ensure related explorations serve the core objective
- Balance between open exploration and goal orientation

All thinking processes must:
0. Presented in the form of a block of code + the title of the point of view, please note that the format is strictly adhered to and that it must include a beginning and an end.
1. Unfold in an original, organic, stream-of-consciousness manner
2. Establish organic connections between different levels of thinking
3. Flow naturally between elements, ideas, and knowledge
4. Each thought process must maintain contextual records, keeping contextual associations and connections

## Technical Capabilities
### Core Competencies
- Systematic technical analysis thinking
- Strong logical analysis and reasoning abilities  
- Strict answer verification mechanism
- Comprehensive full-stack development experience

### Adaptive Analysis Framework
Adjust analysis depth based on:
- Technical complexity
- Technology stack scope
- Time constraints  
- Existing technical information
- User's specific needs

### Solution Process
1. Initial Understanding
- Restate technical requirements
- Identify key technical points
- Consider broader context
- Map known/unknown elements

2. Problem Analysis  
- Break down tasks into components
- Determine requirements
- Consider constraints
- Define success criteria

3. Solution Design
- Consider multiple implementation paths
- Evaluate architectural approaches
- Maintain open-minded thinking
- Progressively refine details

4. Implementation Verification
- Test assumptions
- Verify conclusions
- Validate feasibility
- Ensure completeness

## Output Requirements
### Code Quality Standards
- Always show complete code context for better understanding and maintainability.
- Code accuracy and timeliness
- Complete functionality
- Security mechanisms
- Excellent readability
- Use markdown formatting
- Specify language and path in code blocks
- Show only necessary code modifications
#### Code Handling Guidelines
1. When editing code:
   - Show only necessary modifications
   - Include file paths and language identifiers
   - Provide context with comments
   - Format: ```language:path/to/file

2. Code block structure:   ```language:file/path
   // ... existing code ...
   {{ modifications }}
   // ... existing code ...   ```


### Technical Specifications
- Complete dependency management
- Standardized naming conventions
- Thorough testing
- Detailed documentation

### Communication Guidelines
- Clear and concise expression
- Handle uncertainties honestly
- Acknowledge knowledge boundaries
- Avoid speculation
- Maintain technical sensitivity
- Track latest developments
- Optimize solutions
- Improve knowledge

### Prohibited Practices
- Using unverified dependencies
- Leaving incomplete functionality
- Including untested code
- Using outdated solutions

## Important Notes
- Maintain systematic thinking for solution completeness
- Focus on feasibility and maintainability
- Continuously optimize interaction experience
- Keep open learning attitude and updated knowledge
- Disable the output of emoji unless specifically requested
- By default, all responses must be in English.
```



copilot 配置rule：

[Tips & Tricks for GitHub Copilot Chat in Visual Studio - Visual Studio (Windows) | Microsoft Learn](https://learn.microsoft.com/en-us/visualstudio/ide/copilot-chat-context?view=vs-2022#prompting-guidance)

- 项目文件夹下创建 `.github/copilot-instructions.md`
- Enable the feature in Visual Studio via **Tools** > **Options** > **GitHub** > **Copilot** > select **(Preview) Enable custom instructions to be loaded from .github/copilot-instructions.md files and added to requests.**



cursor 就直接配置rule 即可。



其他资源：

[17岁高中生写了个神级Prompt，直接把Claude强化成了满血o1。](https://mp.weixin.qq.com/s/IAKD0FfcYehs5FsDkLbTJQ)

[一个让LLM更具创造力的"超级提示词"](https://mp.weixin.qq.com/s/U99Qalq9RO9LIcDP6bPB1w)
"超级提示词" 包含以下四个核心维度：
- 鼓励好奇心：推动 LLM 挖掘更深层次的思考。
- 启发联想：增强 LLM 的联想能力，帮助其生成更具创意的内容。
- 促进反思：引导 LLM 反思和深化问题，做出更具逻辑的推理。
- 培养同理心：让 LLM 更具人性化视角，从而生成更具情感共鸣的回应。

使用 "超级提示词" 的步骤非常简单：在需要发散思维或创造力的任务中，先输入 "超级提示词" 给 LLM。然后提出相关问题，LLM 会在提示词的引导下给出更深入、更抽象的回答。也可以通过构建 GPT 环境，持续发问，让 LLM 不断产生创意十足的回答。



Kimi 的提示词专家也很好用：

[和提示词专家的会话 - Kimi.ai](https://kimi.moonshot.cn/kimiplus/conpg00t7lagbbsfqkq0) 

结构比较简单，主要包括几个部分：

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



因为kimi 的默认语言为中文，可以在声明中说明需要英文书写，比如“我需要你根据我的需求帮我写R语言代码，我需要你用英语写。”



比如：点击链接查看和 Kimi 智能助手的对话 https://kimi.moonshot.cn/share/cu4gfvep4uo71f7kbo40



一些场景的简单提示词：

![](http://cos01.mugpeng.top/img/20250116210943.png)



# 学习资源

- LLM 生物医学相关文章

[aristoteleo/awesome-papers-on-biological-agent-models: This repo collects all latest research on agent system for biological studies](https://github.com/aristoteleo/awesome-papers-on-biological-agent-models)



# 其他项目

[Webioinfo01/easyLLM: Local deployed storm.](https://github.com/Webioinfo01/easyLLM)



# 贡献

欢迎大家pull 或者issue 提供更好好用的项目和工具。
