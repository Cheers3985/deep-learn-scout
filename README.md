# Deep Learn Scout — 广度+深度学习侦察兵

> 系统学习任何技术领域的一站式 skill：广度搜索 → 深度挖掘 → 评分排序 → 学习路线图

## 解决什么问题

想学一个新技术领域（如多模态、强化学习、RAG）时，面临：
- 信息分散在 GitHub / arXiv / B站 / Medium 各处
- 资源质量参差不齐，不知道该先看哪个
- 论文太多不知道哪篇是奠基性工作
- 没有系统的学习路线，容易陷入「收藏夹综合征」

## 安装

```bash
npx skills add https://github.com/{your-username}/deep-learn-scout --skill deep-learn-scout
```

## 使用示例

```text
# 基础用法
帮我系统学习多模态大模型，我是有深度学习基础的工程师

# 指定重点
整理一份 RAG（检索增强生成）的学习资源，偏工程实践方向

# 快速模式
给我一份强化学习的广度深度搜索结果，整理成学习文档
```

## 输出内容

每次运行产出一份结构化 Markdown 文档：

```
{topic} 系统学习指南
├── 领域综述（定义 + 发展 + 核心方向）
├── 资源库
│   ├── 🛠 开源项目（Top 5，含评分）
│   ├── 🎓 课程/教程（Top 5，含评分）
│   ├── 📄 核心论文（Top 5，含观点萃取）
│   └── 📰 资讯/博客（Top 5，含评分）
├── 全局 Top 10 排行榜
├── 学习路线图（3阶段，含时间估算）
└── 快速启动（Next 3 Actions）
```

## 工作流概览

```
Phase 1: 理解目标 & 拆解关键词
    ↓
Phase 2: 广度搜索（4类并行：项目/课程/资讯/社区）
    ↓
Phase 3: 深度挖掘（论文核心观点萃取）
    ↓
Phase 4: 多维评分（质量/实用性/新鲜度/适配度/社区）
    ↓
Phase 5: 整合输出文档
```

## 目录结构

```
deep-learn-scout/
├── SKILL.md                          # 主 skill 文件
├── README.md                         # 本文件
└── references/
    ├── output-template.md            # 输出文档模板
    ├── scoring-rubric.md             # 评分标准手册
    └── search-query-bank.md          # 搜索 query 模板库
```

## 依赖的 MCP / 工具

- **Exa MCP**（推荐）：高质量语义搜索
- **WebSearch**（备选）：标准网页搜索
- **WebFetch**：抓取具体页面内容

## 版本

- v1.0 — 2025-02 初始版本
