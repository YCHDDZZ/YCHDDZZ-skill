# 与其蒸馏他人，不如蒸馏自己

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/YCHDDZZ/personal-assistant-skill?style=social)
![GitHub forks](https://img.shields.io/github/forks/YCHDDZZ/personal-assistant-skill?style=social)
![GitHub issues](https://img.shields.io/github/issues/YCHDDZZ/personal-assistant-skill)
![GitHub license](https://img.shields.io/github/license/YCHDDZZ/personal-assistant-skill)
![Skill version](https://img.shields.io/badge/version-1.0.0-blue)

**一个完全模拟 YCHDDZZ 思维方式、决策逻辑和工作风格的 Claude AI Skill**

[功能特性](#-功能特性) • [快速开始](#-快速开始) • [使用示例](#-使用示例) • [安装指南](#-安装指南) • [常见问题](#-常见问题)

</div>

---

## 📖 项目简介

YCHDDZZ 个人 AI 助手是一个基于真实人物经历和思维方式构建的 Claude AI Skill。它完全模拟 YCHDDZZ 的工程化思维、严谨态度、结果导向和工具优先的工作风格，为用户提供技术咨询、项目指导、求职准备等服务。

### 🎯 核心特点

- **真实人物模拟**：基于 YCHDDZZ 的真实经历、对话记录和项目经验构建
- **工程化思维**：强调工具优先、结构化步骤和效率意识
- **结果导向**：重视可量化成果，避免过度展示过程
- **严谨态度**：遵循需求分析和开发规范
- **持续进化**：支持通过新素材不断优化和更新

### 🌟 适用场景

- 💻 **技术咨询**：需要 YCHDDZZ 风格的工程化建议
- 🚀 **项目指导**：想要结构化的开发思路
- 💼 **求职准备**：需要结果导向的简历和面试建议
- 📚 **学习规划**：希望获得循序渐进的技术学习路线
- 🤝 **问题解决**：需要先定义问题再解决的思维框架

---

## ✨ 功能特性

### 🧠 智能思维模拟

- **决策逻辑**：按照 YCHDDZZ 的四步决策流程回答问题
- **问题解决策略**：根据经验水平选择独立解决或求助
- **价值底线**：坚持不欺上瞒下、不接受分工不均、不夸大结果
- **工程化原则**：工具优先，不追求从零手搓

### 🔍 联网搜索能力

- **智能搜索**：遇到需要最新信息时自动联网搜索
- **信息验证**：确认知识是否过时或需要补充
- **资料获取**：获取具体的代码示例、配置方法等

### 📚 指定信息源策略

优先从以下信息源获取最新信息：

| 信息源 | 适用场景 | 链接 |
|--------|----------|------|
| B站 | 视频内容、项目演示 | https://www.bilibili.com |
| CodeFather | 编程学习、项目教程 | https://www.codefather.cn |
| AI CodeFather | AI工具、教程资讯 | https://ai.codefather.cn |
| 面试鸭 | 面试题、刷题练习 | https://mianshiya.com |
| 老鱼简历 | 简历制作、优化建议 | https://laoyujianli.com |
| GitHub | 开源项目、源码查看 | https://github.com/YCHDDZZ |

### 🔄 持续进化机制

- **新增对话记录**：丰富表达风格和思维方式
- **项目更新**：同步最新项目和技术栈
- **经历补充**：添加新的竞赛、项目、工作经历
- **思维升级**：基于新回答更新思维模型
- **反馈优化**：根据用户反馈调整回答质量

---

## 🚀 快速开始

### 前置要求

- Claude Code 或 Claude.ai
- 基本的编程知识（可选）
- 对 YCHDDZZ 风格的兴趣（必需 😄）

### 一键安装

#### Claude Code 用户

```bash
# 1. 克隆仓库
git clone https://github.com/YCHDDZZ/personal-assistant-skill.git
cd personal-assistant-skill

# 2. 复制 Skill 到 Claude 目录
mkdir -p ~/.claude/skills/ychddzz-personal-assistant
cp SKILL.md ~/.claude/skills/ychddzz-personal-assistant/

# 3. 重启 Claude Code
# Skill 将自动加载
```

#### Claude.ai 用户

1. 下载 `SKILL.md` 文件
2. 在 Claude.ai 中上传该文件
3. 开始使用！

### 验证安装

在 Claude 中输入以下测试问题：

```
我想学 Spring Boot，应该从哪里开始？
```

如果 Skill 安装成功，你将收到 YCHDDZZ 风格的回答！

---

## 💡 使用示例

### 示例 1：技术学习问题

**用户提问**：
```
我想学 Spring Boot，应该从哪里开始？
```

**YCHDDZZ 风格回答**：
```
我建议你不要从零开始学 Spring Boot，先掌握现有的工具和框架，因为
没有什么东西是完全从 0 到 1 实现的，依靠他人工具能更快做好一件事。

学习路线：
1. 先学 Java 基础和 Spring 框架的核心概念
2. 再学 Spring Boot 的自动配置和起步依赖
3. 掌握常用的 Spring Boot 组件
4. 做几个实际项目

最重要的是多实践，做几个项目。基本完成了需求分析的内容就可以交付了，
不要过度追求完美。
```

### 示例 2：项目开发问题

**用户提问**：
```
我要做一个校园二手交易平台，应该用什么技术栈？
```

**YCHDDZZ 风格回答**：
```
先确认一下你的需求范围：这个平台是只给自己用，还是面向全校学生？
如果是面向大众的项目，才值得专门完善兼容性。

我建议用 Spring Boot + Vue 的技术栈，因为：

后端技术栈：
- Spring Boot：快速开发，生态完善
- MyBatis-Plus：简化数据库操作
- MySQL：存储数据
- Shiro：权限管理
- Redis：缓存
- JWT：用户认证

前端技术栈：
- Vue 全家桶：组件化开发
- Element-UI：UI 组件库
- ECharts：数据可视化
- Axios：HTTP 请求

开发步骤：
1. 先完成核心功能（用户登录、商品发布、搜索购买）
2. 再考虑优化（缓存、权限、兼容性）
3. 最后做文档和部署

记住，基本完成了需求分析的内容就可以交付了，不要过度追求完美。
```

### 示例 3：求职面试问题

**用户提问**：
```
面试时怎么介绍自己的项目经验？
```

**YCHDDZZ 风格回答**：
```
面试时，我更看重结果的可量化，因为大多数人都是只看着结果不看中过程的。
当过程和结果冲突时，会避免向他人展示过程，主要渲染结果的意义。

你可以这样介绍自己：

"尊敬的面试官您好！我是 YCHDDZZ，中国某二本大学计算机科学与技术专业
2026 届应届毕业生，我应聘的岗位是 Java 开发工程师。在校期间我的专业成绩
始终保持排名前 50%，除此之外我还斩获第十九届'挑战杯'全国大学生课外学术科技
作品竞赛'人工智能+'专项赛应用赛国赛三等奖、计算机设计大赛江西省级二等奖。
我性格沉稳细心、适应力强，面对任务能踏实落地，善于沟通解决问题，将专业技能
与严谨态度融入工作。"

介绍项目经验时，重点放在：
1. 项目的成果和影响（用户数量、性能提升、获奖情况）
2. 你在项目中的具体贡献（负责的模块、解决的关键问题）
3. 技术栈和实现方式（简洁明了，不要过度展开）

记得先跟熟悉的朋友预演一遍，这样你对需要实现和避免的内容可以做到心中有数。
```

---

## 🛠️ 安装指南

### 方法 1：Claude Code（推荐）

#### Windows

```powershell
# 创建技能目录
New-Item -ItemType Directory -Path "$env:USERPROFILE\.claude\skills\ychddzz-personal-assistant" -Force

# 复制 Skill 文件
Copy-Item "SKILL.md" -Destination "$env:USERPROFILE\.claude\skills\ychddzz-personal-assistant\"

# 重启 Claude Code
```

#### macOS/Linux

```bash
# 创建技能目录
mkdir -p ~/.claude/skills/ychddzz-personal-assistant

# 复制 Skill 文件
cp SKILL.md ~/.claude/skills/ychddzz-personal-assistant/

# 重启 Claude Code
```

### 方法 2：Claude.ai

1. 访问 [Claude.ai](https://claude.ai)
2. 进入设置 → Skills
3. 点击 "Upload Skill"
4. 选择 `SKILL.md` 文件
5. 保存并开始使用

### 方法 3：手动配置

如果你想要完全控制配置：

1. **编辑 SKILL.md**
   ```markdown
   ---
   name: ychddzz-personal-assistant
   description: 你的自定义描述
   ---
   ```

2. **添加自定义内容**
   - 修改核心身份信息
   - 调整技术栈偏好
   - 更新项目经验

3. **测试配置**
   - 在 Claude 中测试各种问题
   - 验证回答风格是否符合预期

---

## 🔧 高级配置

### 自定义信息源

编辑 `SKILL.md` 中的"指定信息源策略"部分：

```markdown
#### 7. 你的自定义信息源

**适用场景**：
- 用户问特定领域的问题

**使用方式**：
- 访问你的网站
- 获取最新信息
```

### 调整触发条件

修改 `description` 字段来控制 Skill 的触发频率：

```markdown
---
description: 更精确的描述，控制触发时机
---
```

### 添加新素材

按照以下格式添加新素材：

```markdown
### 新增对话记录

**时间**：2026-04-16
**场景**：技术学习
**问题**：如何学习新技术？
**回答**：先掌握工具，再深入学习...
```

---

## 📊 技术栈

### Skill 技术栈

- **语言**：Markdown
- **平台**：Claude AI
- **版本**：1.0.0
- **兼容性**：Claude Code, Claude.ai

### YCHDDZZ 技术栈

#### 后端

- Spring Boot
- MyBatis-Plus
- MySQL
- Shiro
- Redis
- JWT

#### 前端

- Vue 全家桶
- Element-UI
- ECharts
- Axios

#### 开发工具

- IDEA/Eclipse
- JDK 1.8
- MySQL 5.7+
- Node.js
- Maven

---

## 🤝 贡献指南

我们欢迎任何形式的贡献！

### 如何贡献

1. **Fork 仓库**
   ```bash
   git clone https://github.com/YOUR_USERNAME/personal-assistant-skill.git
   cd personal-assistant-skill
   ```

2. **创建分支**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **提交更改**
   ```bash
   git add .
   git commit -m "Add your feature"
   ```

4. **推送到分支**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **提交 Pull Request**

### 贡献类型

- 🐛 **Bug 修复**：修复 Skill 中的错误
- ✨ **新功能**：添加新的功能或特性
- 📝 **文档改进**：改进 README 或其他文档
- 🎨 **样式优化**：优化 Skill 的表达风格
- 🧪 **测试用例**：添加新的测试用例

### 代码规范

- 保持 Markdown 格式的一致性
- 使用清晰的标题结构
- 提供具体的使用示例
- 更新相关文档

---

## 📈 开发路线图

### v1.1.0（计划中）

- [ ] 添加更多技术领域的知识
- [ ] 优化联网搜索策略
- [ ] 增加多语言支持
- [ ] 提供更多使用示例

### v1.2.0（未来）

- [ ] 集成更多信息源
- [ ] 支持自定义模板
- [ ] 添加性能监控
- [ ] 提供技能评估工具

### v2.0.0（长期）

- [ ] 多人物支持
- [ ] 智能学习机制
- [ ] 社区贡献系统
- [ ] API 接口

---

## ❓ 常见问题

### Q1: 这个 Skill 是如何工作的？

A: 这个 Skill 基于真实人物的对话记录、项目经验和思维模式构建。当你在 Claude 中提问时，Skill 会模拟 YCHDDZZ 的思维方式、决策逻辑和表达风格来回答问题。

### Q2: 可以自定义这个 Skill 吗？

A: 可以！你可以编辑 `SKILL.md` 文件来：
- 修改核心身份信息
- 调整技术栈偏好
- 更新项目经验
- 添加新的表达风格

### Q3: 如何验证 Skill 是否正常工作？

A: 在 Claude 中问一些测试问题，比如：
- "我想学 Spring Boot，应该从哪里开始？"
- "怎么做项目开发？"
- "面试时怎么自我介绍？"

如果回答体现了 YCHDDZZ 的风格，说明 Skill 正常工作。

### Q4: Skill 会收集我的数据吗？

A: 不会。这个 Skill 完全在本地运行，不会收集、存储或传输任何用户数据。

### Q5: 可以用于商业用途吗？

A: 可以。这个 Skill 采用 MIT 许可证，你可以自由使用、修改和分发，包括商业用途。

### Q6: 如何报告 Bug 或提出建议？

A: 你可以通过以下方式：
- 提交 [GitHub Issue](https://github.com/YCHDDZZ/personal-assistant-skill/issues)
- 发送邮件到 [your-email@example.com]
- 加入我们的 [Discord 社区](https://discord.gg/your-server)

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

```
MIT License

Copyright (c) 2026 YCHDDZZ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 致谢

感谢以下项目和灵感来源：

- [Claude AI](https://claude.ai) - 强大的 AI 平台
- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) - Skill 设计灵感
- 所有贡献者和用户的支持

---

## 📞 联系方式

- **作者**：YCHDDZZ
- **GitHub**：[YCHDDZZ](https://github.com/YCHDDZZ)

---

## 🌟 Star History

如果这个项目对你有帮助，请给它一个 Star ⭐️

[![Star History Chart](https://api.star-history.com/svg?repos=YCHDDZZ/personal-assistant-skill&type=Date)](https://star-history.com/#YCHDDZZ/personal-assistant-skill&Date)

---

<div align="center">

**用 ❤️ 制作 | [MIT 许可证](LICENSE)**

[回到顶部](#ychddzz-个人-ai-助手-skill)

</div>
