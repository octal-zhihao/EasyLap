# 🧠 EasyLap 
<div align="center">
  <h1><img src="https://picbed.octalzhihao.top/img/202510041912871.png" width="180" alt="EasyLap Logo" /></h1>
  <h3>基于知识图谱的笔记本智能推荐搜索引擎</h3>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Flask-blue?logo=flask" alt="Flask Badge"/>
  <img src="https://img.shields.io/badge/Frontend-Vue-green?logo=vue.js" alt="Vue Badge"/>
  <img src="https://img.shields.io/badge/LLM-InternLM3--8B-orange?logo=OpenAI" alt="InternLM Badge"/>
  <img src="https://img.shields.io/badge/Graph-neo4j-lightblue?logo=neo4j" alt="Neo4j Badge"/>
</p>

## 🔮 Background
笔记本电脑市场竞争激烈，用户在选购时需综合考虑性能、价格、品牌、用途等多维度因素。

目前，主流笔记本推荐系统多基于**英文市场**开发，如 *Specranks*，采用固定提问的方式逐步筛选产品。这类方案存在以下不足：

1. 🇨🇳 **缺乏中文市场适配性**：无法覆盖中文表达方式与习惯；
2. 💬 **固定问答限制灵活性**：用户的复杂综合需求难以被捕捉（如“适合设计工作的高性能笔记本，预算8000元以内”）。

> 🧩 **EasyLap** 针对中文用户进行优化，结合自然语言处理与知识图谱技术，支持用户自由表达需求，通过**微调的InternLM**理解语义，并生成精准的查询语句，实现个性化推荐。
---

## 🌟 Value
EasyLap项目的主要价值体现在：

* ⏱️ **提升购买效率**：显著减少用户筛选产品的时间与精力；
* 🎯 **提升推荐准确度**：结合知识图谱与语义理解，精准匹配个性化需求；
* 💬 **优化用户体验**：将复杂的筛选逻辑转化为自然语言对话，提升交互友好度。
---

## 🏗️ Project Architecture Diagram

<div align="center">
  <img src="https://picbed.octalzhihao.top/img/202510041905431.jpg" width="80%" alt="Project Architecture Diagram"/>
</div>

---

## 🎯 Anticipated outcome

<div align="center">
  <img src="https://picbed.octalzhihao.top/img/202503051025502.png" width="80%" alt="Anticipated Outcome"/>
</div>

## 🚀 Tech Stack Overview

| 模块 | 技术栈 | 说明 |
|------|--------|------|
| 前端 | Vue3 + Element Plus | 构建智能搜索与推荐可视化界面 |
| 后端 | Flask | 提供接口服务与模型推理 |
| 模型 | InternLM3-8B + LoRA 微调 | 实现中文语义理解与查询生成 |
| 知识图谱 | Neo4j | 存储笔记本实体与属性关系 |
| 数据源 | DrissionPage 自动化爬取 | 从主流电商平台采集笔记本数据 |

---

## 📌 Highlights

- 🧭 自然语言查询 → 图数据库语义匹配  
- 🧩 中文用户友好设计  
- 🔍 支持多维度筛选与个性化推荐  
- 🤖 可扩展微调模型以适配多领域需求  

---

<div align="center">
  <b>💡 EasyLap：让每一次笔记本选择都更智能 💡</b>
</div>
