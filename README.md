# SciGuide Skills - 《现代科研指北》AI 技能库

[English](#english) | [中文](#chinese)

---

<a name="english"></a>
## English

### About SciGuide Skills
**SciGuide Skills** is an open-source collection of AI Skills derived from the online book [**SciGuide: A Guide to Modern Research** (《现代科研指北》)](https://yufree.cn/sciguide/). It aims to provide researchers, students, and academics with a structured knowledge base and guidance system for academic career success, scientific thinking, and research management.

By transforming a static book into AI-ready "Skills," we allow AI assistants to provide proactive, context-aware mentoring based on the author's 10+ years of research experience.

### How to Use
There are two ways to leverage this repository:

#### 1. For AI Assistants (AI-Agent Integration)
If you are using an AI coding assistant or agent (like Antigravity or others that support Skill folders):
1. **Import**: Point your assistant to the `skills/` directory of this repository.
2. **Interact**: Ask questions related to research life, such as:
   - *"How should I choose a research topic?"*
   - *"Give me some honest advice on a PhD career."*
   - *"How to manage literature effectively?"*
3. **Execution**: The AI will automatically trigger the `sciguide` skill and use the logic/data from the [references](skills/sciguide/references/) to give you a "senior-mentor" style answer.

#### 2. Manual Reading
You can also read the source material directly:
- Read [SKILL.md](skills/sciguide/SKILL.md) to understand the guidance logic.
- Browse the [references/](skills/sciguide/references/) folder for detailed deep-dives into data analysis, scientific thinking, and career paths.

### Repository Structure
- `skills/`: Contains the individual skill modules.
  - `sciguide/`: The primary skill module based on the book.
    - `SKILL.md`: The main instruction file for the AI.
    - `references/`: Supporting documents and detailed guides.

### License
This project is licensed under the [MIT License](LICENSE).

---

<a name="chinese"></a>
## 中文

### 关于 SciGuide Skills
**SciGuide Skills** 是基于在线电子书 [**《现代科研指北》** (SciGuide)](https://yufree.cn/sciguide/) 开发的开源 AI 技能库。它旨在为研究人员、学生和学者提供一套关于学术生涯成功、科学思维和研究管理的结构化知识库和指导系统。

通过将静态的电子书转化为 AI 可读的“技能（Skills）”，我们让 AI 助手能够基于作者十余年的科研心得，为你提供具备实战经验、坦诚且深入的学术指导。

### 如何使用
你可以通过以下两种方式利用本仓库：

#### 1. 供 AI 助手使用 (AI-Agent 集成)
如果你正在使用支持“技能”或“插件”系统的 AI 助手（如 Antigravity）：
1. **导入**：将本项目克隆到本地，并将 AI 助手的技能搜索路径指向 `skills/` 目录。
2. **提问**：直接向 AI 提问科研生活相关的问题，例如：
   - *“我该如何选课题？”*
   - *“给我一些关于读博职业生涯的坦诚建议。”*
   - *“如何高效管理文献？”*
3. **效果**：AI 会自动触发 `sciguide` 技能，并根据 [references](skills/sciguide/references/) 中的逻辑和数据，以“资深学长/学姐”的口吻为你答疑解惑。

#### 2. 手动阅读
你也可以直接阅读这些经过整理的知识点：
- 阅读 [SKILL.md](skills/sciguide/SKILL.md) 了解 AI 的指导逻辑。
- 在 [references/](skills/sciguide/references/) 目录中查阅关于数据分析、思维工具、职业路径等深度内容。

### 仓库结构
- `skills/`: 包含各个独立的技能模块。
  - `sciguide/`: 核心科学指南技能模块。
    - `SKILL.md`: 供 AI 使用的主要指令文件。
    - `references/`: 配套的支持文档和详细指南。

### 开源协议
本项目采用 [MIT 协议](LICENSE) 开源。
