# 近期下载的 GitHub 开源项目清单

> 扫描本机工作区 `E:\1workspace`，按 git reflog 首次记录（即克隆时间）排序。
> 统计区间：**2026-10-24 ～ 2026-10-26**，共 **25** 个第三方开源仓库（不含本人仓库）。
> Star 数与官方介绍取自 GitHub API，采集于 2026-10-26。

## 目录

- [AI Agent 与效率工具](#ai-agent-与效率工具)
- [股票 / 量化选股](#股票--量化选股)
- [游戏开发与 3D 素材](#游戏开发与-3d-素材)
- [学习资源与知识图谱](#学习资源与知识图谱)
- [微信自动化](#微信自动化)
- [输入法](#输入法)

---

## AI Agent 与效率工具

### 1. hermes-agent

- 🔗 <https://github.com/NousResearch/hermes-agent>
- ⭐ 257k · Python · 克隆于 2026-10-25
- 官方介绍：The agent that grows with you
- 中文说明：Nous Research 出品的官方 AI 智能体框架，主打随使用持续成长的个人 Agent。
- 本地路径：`E:\1workspace\hermes-agent`

### 2. ppt-master

- 🔗 <https://github.com/hugohe3/ppt-master>
- ⭐ 68.1k · Python · 克隆于 2026-10-25
- 官方介绍：AI turns documents or topics into real, native PowerPoint decks—with native shapes, transitions and animations, data-backed charts and tables on demand, audio narration from speaker notes, and support for your own .pptx templates.
- 中文说明：把文档或主题直接做成**原生 PPT**（非截图）的 Claude Code 技能，含原生形状、切换动画、数据图表、备注配音，支持自定义模板。
- 本地路径：`E:\1workspace\ppt-master`
- 本机备注：已 junction 安装到 `~/.claude/skills`，依赖 Python3.11，已用它产出 17 页雅思课件。

### 3. diagram-design

- 🔗 <https://github.com/cathrynlavery/diagram-design>
- ⭐ 61.1k · HTML · 克隆于 2026-10-25
- 官方介绍：Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.
- 中文说明：跨 AI 编程工具通用的图表设计技能，支持 45 种图表类型，输出自包含 HTML+SVG 的编辑级（editorial）信息图，拒绝千篇一律的 Mermaid。
- 本地路径：`E:\1workspace\diagram-design`
- 本机备注：已安装为 `diagram-design` 技能，默认 editorial 风格已被认可。

### 4. magpie

- 🔗 <https://github.com/yetone/magpie>
- ⭐ 21.4k · Go · 克隆于 2026-10-25
- 官方介绍：Every agent's model. One place. Codex on DeepSeek, Claude Code on Kimi, from the menu bar.
- 中文说明：yetone 出品的菜单栏工具，一处统一切换 Codex / Claude Code 等 Agent 背后的模型供应商（DeepSeek、Kimi 等）。
- 本地路径：`E:\1workspace\magpie`
- 本机备注：本机三 key 故障转移方案曾参考其首图。

### 5. BrowserSkill

- 🔗 <https://github.com/Tencent/BrowserSkill>
- ⭐ 9.6k · TypeScript · 克隆于 2026-10-25
- 官方介绍：Let AI agents use your real, logged-in browser without interrupting your work. CLI + extension for browser automation across any shell-capable AI agent.
- 中文说明：腾讯开源。让 AI Agent 直接操控用户**真实且已登录**的浏览器而不打断手头工作，由 CLI + 浏览器扩展组成，任何能跑 shell 的 Agent 都能用。
- 本地路径：`E:\1workspace\BrowserSkill`

### 6. claudecodeui

- 🔗 <https://github.com/siteboon/claudecodeui>
- ⭐ 14.3k · TypeScript · 克隆于 2026-10-25
- 官方介绍：Use Claude Code, OpenCode, Cursor CLI, and Codex on mobile and web with CloudCLI (aka Claude Code UI). A free open source webui/GUI that helps you manage your Claude Code session and projects remotely.
- 中文说明：在手机和网页端远程管理 Claude Code / OpenCode / Cursor CLI / Codex 会话与项目的开源 Web GUI。
- 本地路径：`E:\1workspace\claudecodeui`
- 本机备注：已跑通（:3001）；安装需 `ELECTRON_SKIP_BINARY_DOWNLOAD=1` 跳过 Electron 二进制下载。

### 7. Claude-Code-Game-Studios

- 🔗 <https://github.com/Donchitos/Claude-Code-Game-Studios>
- ⭐ 27.5k · Shell · 克隆于 2026-10-25
- 官方介绍：Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.
- 中文说明：把 Claude Code 变成完整游戏开发工作室的工作流包：49 个 AI 角色 Agent、72 个工作流技能，按真实工作室层级组织协作。
- 本地路径：`E:\1workspace\claude-code-game-studios`

### 8. hypit

- 🔗 <https://github.com/hypit-ai/hypit>
- ⭐ 25.6k · TypeScript · 克隆于 2026-10-25
- 官方介绍：Clone any viral video with AI agents. Not just a script, the whole workflow: swap the face, the words, the B-roll, ship 100 variants in one command, and get your 100M views.
- 中文说明：AI Agent 驱动的爆款视频复刻工具：换人换脸、改台词、换 B-roll，一条命令批量产出 100 个变体。
- 本地路径：`E:\1workspace\hypit`
- 本机备注：已克隆，待研究。

### 9. awesome-llm-apps

- 🔗 <https://github.com/Shubhamsaboo/awesome-llm-apps>
- ⭐ 143k · Python · 克隆于 2026-10-24
- 官方介绍：100+ AI Agents, Agent Skills and RAG Apps - Free and Open Source.
- 中文说明：100+ 免费开源的 AI Agent、Agent Skills 与 RAG 应用案例大全。
- 本地路径：`E:\1workspace\awesome-llm-apps`
- 本机备注：101 个案例；已按转型短板（RAG 指标 / LangGraph / MCP / 评测）整理研究清单。

---

## 股票 / 量化选股

> 2026-10-25 批量克隆于 `E:\1workspace\_ref-stocks\`，作为自研股市项目的参考实现。

### 10. Sequoia-X（红杉 X）

- 🔗 <https://github.com/sngyai/Sequoia-X>
- ⭐ 8.3k · Python
- 官方介绍：A股自动选股系统 — 多种技术形态自动扫描，收盘后自动运行并推送飞书
- 中文说明：多技术形态自动扫描的 A 股选股系统，收盘后定时运行并推送结果到飞书。
- 本地路径：`E:\1workspace\_ref-stocks\Sequoia-X`

### 11. go-stock

- 🔗 <https://github.com/ArvinLovegood/go-stock>
- ⭐ 7.9k · Go
- 官方介绍：AI 加持的股票分析/选股工具。行情获取、AI 热点资讯分析、AI 资金/财务分析、涨跌报警推送，支持 A 股/港股/美股与市场情绪分析，数据全部保留本地；支持 DeepSeek、OpenAI、Ollama、火山方舟等多种模型。
- 中文说明：Go 编写的桌面 AI 股票分析工具，亮点是本地数据、多模型平台接入与情绪分析。
- 本地路径：`E:\1workspace\_ref-stocks\go-stock`

### 12. KHunter

- 🔗 <https://github.com/ling-0729/KHunter>
- ⭐ 638 · Python
- 官方介绍：开箱即用的 A 股量化交易系统，集数据管理、策略选股、择时交易、风险控制、回测验证于一体的全流程解决方案。
- 中文说明：从数据到交易的全流程 A 股量化系统，含回测与风控。
- 本地路径：`E:\1workspace\_ref-stocks\KHunter`

### 13. serenity-stock-choke

- 🔗 <https://github.com/fadewalk/serenity-stock-choke>
- ⭐ 502 · Python
- 官方介绍：A股/港股/美股 卡脖子选股 Skill，基于 Serenity 供应链瓶颈理论，Claude Code / Codex 通用智能体可用，零依赖。
- 中文说明：以「供应链卡脖子」理论选股的 Agent Skill，A/港/美股通用、零依赖。
- 本地路径：`E:\1workspace\_ref-stocks\serenity-stock-choke`

### 14. a-share-quant-selector

- 🔗 <https://github.com/Dzy-HW-XD/a-share-quant-selector>
- ⭐ 467 · Python
- 官方介绍：A股量化选股系统 - 基于碗口反弹策略的智能选股工具，支持 Web 界面和钉钉通知。
- 中文说明：基于「碗口反弹」形态策略的 A 股选股工具，带 Web 界面与钉钉通知。
- 本地路径：`E:\1workspace\_ref-stocks\a-share-quant-selector`

---

## 游戏开发与 3D 素材

### 15. voxel-musou（体素三国无双）

- 🔗 <https://github.com/mike007jd/voxel-musou>
- ⭐ 157 · JavaScript · 克隆于 2026-10-25
- 官方介绍：Dynasty Warriors-style voxel action game in the browser: Zhao Yun vs 300 soldiers. Three.js, no build step.
- 中文说明：浏览器里的体素风「简化版三国无双」：赵云大战 300 小兵，Three.js 实现、零构建步骤，双击即玩。
- 本地路径：`E:\1workspace\voxel-musou`
- 本机备注：本机 :8860 开玩。

### 16. KayKit Adventurers Character Pack

- 🔗 <https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0>
- ⭐ 61 · 克隆于 2026-10-25
- 官方介绍：Bundle of 4 stylised low-poly adventurer character assets.
- 中文说明：KayKit 出品的 CC0 低多边形冒险者角色包，4 个角色自带骨骼与 76 个动画，可直接用于 three.js。
- 本地路径：`E:\1workspace\KayKit-Character-Pack-Adventures-1.0`（142MB）

### 17. KayKit Skeletons Character Pack

- 🔗 <https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Skeletons-1.0>
- ⭐ 28 · 克隆于 2026-10-25
- 官方介绍：Bundle of 4 stylised low-poly skeleton character assets.
- 中文说明：同系列骷髅角色包，4 个带骨骼、95 个动画的低模骷髅。
- 本地路径：`E:\1workspace\KayKit-Character-Pack-Skeletons-1.0`（131MB）

### 18. codex-pet-naiwa

- 🔗 <https://github.com/timerring/codex-pet-naiwa>
- ⭐ 169 · 克隆于 2026-10-26
- 官方介绍：一个为 Codex 打造的奶龙 / 奶蛙桌面宠物 Naifrog / Naiwa Codex pet
- 中文说明：趴在桌面上陪写代码的奶龙/奶蛙桌宠（Codex 版）。
- 本地路径：`E:\1workspace\codex-pet-naiwa`
- 本机备注：原方案太重已弃用，仅作参考；自研单进程 tkinter 裂变版在 `E:\1workspace\nailong-pet`。

---

## 学习资源与知识图谱

### 19. ChinaTextbook（电子课本教材库）

- 🔗 <https://github.com/TapXWorld/ChinaTextbook>
- ⭐ 83.5k · 克隆于 2026-10-25
- 官方介绍：所有小初高、大学 PDF 教材。
- 中文说明：覆盖小学到大学全学段的电子版教材 PDF 大全。
- 本地路径：`E:\1workspace\ChinaTextbook`
- 本机备注：用 blob:none 稀疏克隆，索引仅 20MB；大文件按需 checkout（首败需 cat-file 预热）。

### 20. cn-math-taxonomy

- 🔗 <https://github.com/xiaoyang111222/cn-math-taxonomy>
- ⭐ 3.7k · Python · 克隆于 2026-10-25
- 官方介绍：数学（小学到高中）、英语（三年级到高中）、初中物理的知识图谱：1644 个知识点、2403 条先修边、6723 道题，对齐课标，附自适应前置诊断。
- 中文说明：多学科 K12 知识点 DAG 图谱 + 题库，可做错题根因回溯与自适应诊断。
- 本地路径：`E:\1workspace\cn-math-taxonomy`
- 本机备注：本机 :8893 纯静态浏览。

### 21. AutoPiano（自由钢琴）

- 🔗 <https://github.com/AutoPiano/AutoPiano>
- ⭐ 6.0k · JavaScript · 克隆于 2026-10-25
- 官方介绍：🎹 自由钢琴 AutoPiano - Simple & Elegant Piano Online
- 中文说明：简洁优雅的在线自由钢琴，支持电脑键盘弹奏与自动演奏。
- 本地路径：`E:\1workspace\AutoPiano`
- 本机备注：npm start :5000，Node24 需 openssl-legacy-provider；简谱钢琴双手演奏项目的参考。

### 22. ChineseBQB（中国表情包大集合）

- 🔗 <https://github.com/zhaoolee/ChineseBQB>
- ⭐ 16.4k · TypeScript · 克隆于 2026-10-26
- 官方介绍：🇨🇳 Chinese sticker pack / 表情包的博物馆，Github 最有毒的仓库，中国表情包大集合。
- 中文说明：中文互联网表情包博物馆，按 7 大分类整理的梗图合集。
- 本地路径：`E:\1workspace\ChineseBQB`
- 本机备注：稀疏克隆只拉了 969 张（勿整拉 3GB），追加分类用 `git sparse-checkout set`。

---

## 微信自动化

### 23. pywechat

- 🔗 <https://github.com/Hello-Mr-Crab/pywechat>
- ⭐ 2.0k · Python · 克隆于 2026-10-24
- 官方介绍：仍然可用的微信 RPA！支持 4.0 系列微信。基于 pywinauto 实现的 Windows 桌面微信自动化操作工具，基本实现 PC 微信内置各项操作。
- 中文说明：适配微信 4.0 新版客户端的 Windows RPA 库，基于 pywinauto，覆盖 PC 微信主要操作。
- 本地路径：`E:\1workspace\pywechat`

### 24. wxauto4

- 🔗 <https://github.com/fly000001/wxauto4>
- ⭐ 9 · 克隆于 2026-10-24
- 官方介绍：适用于微信客户端 4.0 版本的 wxauto
- 中文说明：经典 wxauto 库适配微信 4.0 的社区 fork（官方 cluic/wxauto4 已停更，此为 fly000001 维护版），推模式回调转队列。
- 本地路径：`E:\1workspace\wxauto4`
- 本机备注：微信桥 v4 备用后端（`gateway4.py`，config 切 `gateway_backend=v4`）。

---

## 输入法

### 25. qingjian（青简输入法）

- 🔗 <https://github.com/qingjian-team/qingjian>
- ⭐ 7.2k · Rust · 克隆于 2026-10-24
- 官方介绍：青简 Qingjian：用 Rust 写的拼音输入法，候选词旁多一条正在学的语言的译词
- 中文说明：Rust + TSF 实现的 Windows 拼音输入法，特色是打拼音时候选词旁同步显示正在学习语言的译词，边打字边学外语。
- 本地路径：`E:\1workspace\qingjian`
- 本机备注：源码在 E 盘、运行部署在 `E:\Qingjian`；Rust TSF 无端口，DLL 注册一次即可。

---

## 统计

| 分类 | 数量 |
|------|------|
| AI Agent 与效率工具 | 9 |
| 股票 / 量化选股 | 5 |
| 游戏开发与 3D 素材 | 4 |
| 学习资源与知识图谱 | 4 |
| 微信自动化 | 2 |
| 输入法 | 1 |
| **合计** | **25** |
