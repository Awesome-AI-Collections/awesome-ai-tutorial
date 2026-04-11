---
title: "karpathy-llm-wiki"
slug: "karpathy-llm-wiki"
info_type: "awesome-ai-tutorial"
entity_type: "tool"
category: "Agents"
featured: false
last_reviewed_at: "2026-04-11T02:58:36+00:00"
---

# karpathy-llm-wiki

## 一句话总结

一个把 Karpathy 的 LLM Wiki 思路做成可安装 agent skill 的教程型项目，演示如何让 Claude Code、Cursor、Codex 等工具逐步构建和维护自己的知识 wiki。

## 它解决什么问题

- 很多人理解了 LLM Wiki 的概念，但不知道第一步该怎么把它落成可操作的工作流。
- 想用 Claude Code、Cursor、Codex 维护知识库时，往往缺少现成的 ingest、query、lint 规范。
- “第二大脑”类想法很容易停留在概念层，缺少一个可以直接安装、直接试的实现入口。

## 适合谁

- 想把个人资料库做成可持续演化知识 wiki 的开发者和研究者。
- 想学习如何把 agent 用在知识整理与长期研究流程的人。
- 正在使用 Claude Code、Cursor、Codex 并想安装现成 skill 上手的人。

## 核心能力

- 可安装 skill：通过 `npx add-skill` 直接把这套方法装进支持 Agent Skills 标准的工具链。
- 三段式工作流：把核心使用方式收敛成 Ingest、Query、Lint 三个高频动作。
- 目录结构示例：清楚展示 `raw/` 与 `wiki/` 两层结构，帮助读者理解“原始资料”和“编译后知识”的职责边界。
- 与 Karpathy 原始想法对齐：既给出可运行入口，也明确说明它是对原始模式的社区实现。

## 典型使用场景

- 给自己的研究主题建立一个会持续生长的个人 wiki，而不是只做一次性 RAG。
- 在 Claude Code 或 Codex 里安装现成 skill，快速试验 LLM Wiki 工作流。
- 参考它的 raw/wiki/index/log 结构，自己进一步定制长期知识管理流程。

## 为什么值得关注

- 它把一个高价值想法从“读完觉得对”推进到了“现在就能试”。
- README 写得很克制，重点都放在如何真正上手，而不是堆功能名。
- 对第一次尝试 LLM Wiki 的人来说，它比从零读抽象方法文档更容易起步。

## 类似项目

- [LLM Wiki (Karpathy idea)](llm-wiki-pattern.md) - 这是这个项目背后的原始方法说明；如果你想先理解模式，再看实现，两篇最好搭配着读。

## 官方链接

- **GitHub:** https://github.com/Astro-Han/karpathy-llm-wiki
- **README:** https://github.com/Astro-Han/karpathy-llm-wiki#readme
- **更新记录:** https://github.com/Astro-Han/karpathy-llm-wiki/releases
- **灵感来源:** https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f

## 标签

- `LLM Wiki`, `Agent Skills`, `Knowledge Management`, `Claude Code`, `Codex`, `Obsidian`

## 更新观察点

- 继续看它是否把当前的 skill 结构扩展成更完整的资料编译和 wiki 维护规范。
- 关注 Agent Skills 标准兼容范围是否继续扩大到更多工具。
- 如果后续出现更多真实示例仓或输出模板，值得补到正文里帮助读者更快落地。
