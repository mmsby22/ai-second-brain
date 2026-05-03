# 🧠 My AI-Generated Digital Garden

这个仓库由我搭建的多智能体系统自动生成并每日更新，用于展示我的AI自动化知识管理能力。

## 🤖 自动化流水线
- **核心引擎**：DeepSeek + Claude Code + LangChain
- **运行模式**：每日凌晨2点通过GitHub Actions定时触发
- **处理流程**：
  1. 自动抓取当日arXiv、Hacker News、指定技术博客的最新内容
  2. 使用DeepSeek 128K模型进行长文提取、关键观点摘要和代码片段复现
  3. 生成带有双链的Markdown笔记，自动推送到本仓库
- **消耗规模**：日均处理约30万字材料，消耗约120万Token

## 📂 知识库示例
- `notes/2024-05-10-llm-reasoning.md` - [LLM推理链优化综述](notes/example.md)
- `notes/2024-05-09-rust-async.md` - [Rust异步运行时深度解析](notes/example.md)
- `code-snippets/python-async-patterns.py` - 自动提取的最佳实践代码

## 📊 统计
- 累计笔记：2000+ 篇
- 代码片段：500+ 个
- 持续运行：90+ 天无中断

*本仓库的90%内容由AI Agent自动生成，我仅进行最终审计和质量抽查。*
