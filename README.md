## Hi there 👋

我是 **NingBye**，来自**南京邮电大学（NJUPT）**的本科生，隶属于 **NJUPT-SAST**。热衷于在多技术栈间快速切换，信奉 **Vibe Coding** —— 用直觉与激情驱动快速开发，在有限时间内将创意变为可运行的产品。

近期方向正逐渐聚焦于 **AI/LLM 工程**：从 Prompt 工程到 LangGraph 编排、RAG 增强检索、MCP 协议集成，持续探索 AI Agent 与实际工程系统的结合边界。

---

## 🔭 我目前在做什么

- 🧠 开发 **A Story Teller** - 以 LangGraph 为核心的多角色智能故事生成系统（Python + RAG + Ollama）
- 📹 迭代 **SeventhCenturyVideoGroup (SCVG)** - 为社团管理系统集成 AI-RAG 知识库与 MCP-Chain Agent（Vue 3 + Go + DeepSeek）
- 📊 维护 **yt-comment2audience** - YouTube 评论数据流水线与观众画像生成工具（Flask + DeepSeek）
- 🎮 优化 **Echo Trace** - 多人在线战术游戏，含 MCP 自然语言接口（Go + Python + Protobuf）

---

## 🌱 我正在深入学习

- LLM 应用编排框架（LangGraph、RAG 增强检索、ChromaDB 向量库）
- Model Context Protocol（MCP）标准化 Agent 接口设计
- 异步并行架构与高性能数据流水线
- Protobuf 二进制协议与游戏服务器优化
- HarmonyOS ArkTS 鸿蒙原生开发

---

## 💻 技术栈

### 编程语言
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white)

### AI / LLM 工程
![LangGraph](https://img.shields.io/badge/-LangGraph-FF6B35?style=flat&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat&logoColor=white)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-4285F4?style=flat&logoColor=white)
![DeepSeek](https://img.shields.io/badge/-DeepSeek-0066CC?style=flat&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP_Protocol-8A2BE2?style=flat&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

### 前端技术
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Flet](https://img.shields.io/badge/-Flet-0078D4?style=flat&logoColor=white)
![Slint](https://img.shields.io/badge/-Slint-0078D4?style=flat&logoColor=white)

### 后端技术
![Echo](https://img.shields.io/badge/-Echo_(Go)-00ADD8?style=flat&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/-Gin-00ADD8?style=flat&logo=go&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat&logo=spring&logoColor=white)

### 数据库 & 运维
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Protobuf](https://img.shields.io/badge/-Protobuf-4285F4?style=flat&logoColor=white)

---

## 📂 项目展示

### 🧠 [A Story Teller](https://github.com/luoli0706/A_Stroy_Teller) `最新`
> **智能故事生成系统** - 以角色为中心、多视角协同创作的 AI 叙事引擎（Alpha 2.5）  
> `Python` `LangGraph` `RAG` `ChromaDB` `Ollama` `Pydantic V2` `Flet` `AsyncIO`

**核心亮点**：
- 🎭 **演员扮演架构**：角色与剧本解耦，动态身份适配，自动推演角色社交关系网
- ⚡ **高性能异步流水线**：LangGraph Async 全异步编排，多角色并行生成，效率较原型提升 400%
- 💾 **工业级持久化**：`AsyncSqliteSaver` 节点级快照，支持中断续写，无惧崩溃
- 🧠 **增量 RAG 记忆**：SHA-256 增量索引 + `story_id` 元数据过滤，精准语境召回

---

### 📹 [SeventhCenturyVideoGroup (SCVG)](https://github.com/luoli0706/SeventhCenturyVideoGroup) ⭐ 1 star `持续迭代`
> **柒世纪视频组社团管理系统** - 全栈 Web 应用，近期集成 AI-RAG 知识库与 MCP-Chain Agent  
> `Vue 3` `Vite` `Arco Design` `Go` `Echo` `GORM` `SQLite` `DeepSeek` `RAG` `n8n`

**最新特性（v2.0.0）**：
- 🤖 集成 DeepSeek Embedding API，构建社团知识库，支持热更新
- 🔗 实现 MCP-Chain Agent，支持自然语言驱动的复合任务编排
- 📊 成员信息自动同步至 RAG 向量库，AI 助手实时感知最新数据
- 🏗️ 三层 MVC 架构 + 完整 VitePress 开发者文档

---

### 🎮 [Echo Trace](https://github.com/luoli0706/Echo_Trace) ⭐ 1 star
> **迷雾战争多人在线战术游戏** - 含战争迷雾、AOI 空间感知、AI Boss 与 MCP 自然语言接口  
> `Go 1.23+` `Python` `Pygame` `Protobuf` `FastAPI` `DeepSeek` `SQLite` `WebSocket`

**技术架构亮点**：
- 🌲 四叉树空间索引（AOI），查询性能提升 50-90%
- 📦 Protobuf 二进制协议，带宽降低 75%，50ms Tick 高性能服务器
- 🤖 AI Boss "柠白号（NingBye）"巡逻战场；MCP Server 支持自然语言指令（"传送到最近的玩家"）
- 🎁 T1-T4 稀有度道具系统 + 三种战术永久加成

---

### 📊 [yt-comment2audience](https://github.com/luoli0706/yt-comment2audience) ⭐ 1 star
> **YouTube 观众画像生成工具** - 从评论数据到受众分析的一站式 AI 流水线  
> `Python` `Flask` `SQLite` `DeepSeek` `YouTube Data API v3` `Flet`

**数据流水线**：采集（YouTube API）→ 清洗（规格化入库）→ 画像（DeepSeek 结构化输出）→ 可视化（Flet 图表）

---

### 🔧 [Ning Prompt](https://github.com/luoli0706/Ning_Prompt) ⭐ 2 stars
> **桌面端提示词优化工具** - 基于 MCP 标准设计的 Prompt 实验平台  
> `Python` `Flet` `MCP Protocol` `DeepSeek`

**四大模式**：语义增强 / 语义泛化 / 语义修复 / 语义剪枝；支持自定义 `.md` 模板；引入 MCP 标准化 Agent 接口

---

### 🎵 [Sound PNG](https://github.com/luoli0706/Sound_PNG) ⭐ 2 stars
> **通用跨平台隐写工具** - 将任意文件隐藏到 PNG/WAV 中  
> `Rust` `Slint` `AES 加密` `Deflate` `流式处理` `插件系统`

从 Beta 1.0 迭代至 **v1.3.1**；支持 GB 级流式处理、序列帧插件、Python 桥接插件；完整用户手册与开发者文档

---

### 📱 [OTO Exchange](https://github.com/luoli0706/OTO_Exchange)
> **线下二手交易平台** - 课设 MVP，HarmonyOS 鸿蒙应用 + Go 后端  
> `HarmonyOS ArkTS` `Go` `Echo` `SQLite` `Redis` `JWT` `Docker`

探索鸿蒙原生开发；Go Echo 后端含完整认证与资源管理骨架

---

### 🎄 [Christmas Link](https://github.com/luoli0706/ChristmasLink) ⭐ 1 star
> **圣诞随机匹配池系统** - 已部署生产环境 7×24 小时稳定运行  
> `Go` `React 19` `TypeScript` `Gin` `GORM` `SQLite` `Docker` `systemd`

[在线体验 →](http://7thcv.cn:721) | 2 周完成，支持 100+ 并发，解决 IPv4/IPv6 双栈绑定问题

---

### 🎮 [OverFlowPaint](https://github.com/luoli0706/OverFlowPaint-) ⭐ 6 stars
> **溢彩画小游戏** - 仿《鸣潮》四色染色机制  
> `Vue 3` `Spring Boot 3` `Java` `MySQL` `JPA`

10×8 棋盘 CMYK 四色染色 + 四连通 DFS/BFS 区域填充算法；Java 课程大作业

---

### 🧰 [Magic Box](https://github.com/luoli0706/-Magic_box)
> **Qt 桌面应用** - 南邮程序设计课题，团队协作开发  
> `C++` `Qt 6.7.1` `CMake`

3 人团队协作，实现完整的登录校验与用户管理功能

---

## 📊 GitHub 统计

<div align="center">

![NingBye's GitHub stats](https://github-readme-stats.vercel.app/api?username=luoli0706&show_icons=true&theme=radical&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=luoli0706&layout=compact&theme=radical&hide_border=true)

</div>

---

## 🎯 开发哲学

**"快速迭代 × 持续集成 × AI 增强"**

1. **Vibe Coding**：跟随直觉，用最短时间将创意转化为可运行原型
2. **文档驱动**：每个项目都配备完整的 README、用户手册与开发者文档
3. **生产导向**：不止于 Demo，追求可实际部署运行的系统（Docker + 云服务器）
4. **AI 先行**：优先探索如何将 LLM 能力融入传统软件架构（RAG、MCP、Agent 编排）

---

## 💬 擅长领域

- 🤖 **AI/LLM 工程**：LangGraph 编排、RAG 增强检索、MCP Agent 设计
- 🏗️ **全栈开发**：前后端分离架构（Vue3/React + Go/Python）
- 🎮 **游戏服务器**：WebSocket + 空间索引 + 二进制协议优化
- 🔐 **信息安全**：隐写术、AES 加密、数据流水线
- 🐳 **DevOps**：Docker 容器化、systemd 守护进程、云服务器运维
- 📊 **数据处理**：API 数据采集、清洗、AI 结构化画像

---

## 📫 联系方式

- 📧 Email：[luoli6710@gmail.com](mailto:luoli6710@gmail.com)
- 🌐 GitHub：[@luoli0706](https://github.com/luoli0706)
- 🏫 学校：南京邮电大学（NJUPT）
- 🎓 组织：NJUPT-SAST

---

## 🎓 教育背景

- **南京邮电大学（NJUPT）** - 本科在读
- **组织**：NJUPT-SAST 成员

---

## ⚡ Fun Facts

- 游戏 Echo Trace 里的 AI Boss 叫 **"柠白号（NingBye）"** —— 我把自己做进了自己的游戏
- 相信"代码即文档"，每个项目都力求清晰易读，但本简历一开始确实是 AI 生成的（
- 曾在 2 周内完成支持 100+ 并发的生产级随机匹配系统
- 热衷从游戏和 ACG 文化中汲取创作灵感

---

## 🚀 近期动态

- 🧠 **A Story Teller v0.3** - Established-facts-driven RAG + 章节整合
- 🔗 **SCVG v2.0** - AI-RAG 知识库 + MCP-Chain Agent 集成完成
- 📊 **yt-comment2audience** - YouTube → DeepSeek 观众画像流水线上线
- 🎮 **Echo Trace v1.3** - 四叉树 AOI + Protobuf 协议升级，性能大幅提升

---

**如果我的项目对你有帮助，欢迎点个 ⭐ 支持！**

<!--
**luoli0706/luoli0706** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
