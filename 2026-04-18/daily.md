# AI 日报 — 2026-04-18

> 共 18 条资讯 | 覆盖 5 个领域 + 行业观点 + Twitter

---

## AI Agent


- **蚂蚁 CodeFuse 提出 NES：连按 Tab 完成跨文件重构，不用写 Prompt。**
  关键词: FSE 2026 论文 (arxiv 2508.02473) | NES-Location + NES-Edit 双模型 | SFT+DAPO 两阶段训练，Qwen3-4B 底座 | 位置准确率 75.6%，端到端 <250ms · 04-18 · [原文](https://mp.weixin.qq.com/s/CsB_QU-nXurrUfvEuwiUUg)

- **OpenAI 重构 Codex，对标 Claude Code 加码桌面控制与企业插件生态。**
  关键词: 多 Agent 后台并行点 Mac 光标/操控 App | 内置浏览器 + 会话 Memory + 图像生成 | 111 个插件（CodeRabbit/GitLab/Slack/Calendar） | 企业版新增 pay-as-you-go 按量计费 · 04-17 · [原文](https://techcrunch.com/2026/04/16/openai-takes-aim-at-anthropic-with-beefed-up-codex-that-gives-it-more-power-over-your-desktop/)

---

## AI游戏


- **Roblox Assistant 升级为 agentic 游戏开发协作伙伴。**
  关键词: Planning Mode 对话澄清 + 可编辑动作计划 | Mesh/Procedural 生成带纹理 3D 模型 | 键鼠模拟 playtest 自检并修 bug | 后续开放 Claude/Cursor/Codex 接入 · 04-17 · [原文](https://techcrunch.com/2026/04/16/robloxs-ai-assistant-gets-new-agentic-tools-to-plan-build-and-test-games/)

---

## AI通用技术/模型

> **洞察**: 模型竞赛焦点从规模转向部署性价比：Qwen 本地小模型反超闭源旗舰、Google 让循环架构补齐召回短板，核心都在削推理成本。


- **Google 新论文 Memory Caching 让 RNN 拥有可生长长期记忆。**
  关键词: RNN 隐藏状态周期性缓存快照 | 三变体：门控残差/记忆汤/稀疏选择性 SSC | SSC 每 token 解码成本恒定 | 长上下文任务击败 SOTA 循环模型 · 04-17 · [原文](https://mp.weixin.qq.com/s/0rYYvTIqR4bRPNFgTSpJrg)

- **llm-anthropic 0.25 发布，CLI 即刻接入 Claude Opus 4.7。**
  关键词: 支持 thinking_effort=xhigh 超高思考档 | thinking_display/adaptive 两个新选项 | 默认 max_tokens 自动拉到各模型上限 | Simon Willison 维护的 llm CLI 插件 · 04-17 · [原文](https://simonwillison.net/2026/Apr/16/llm-anthropic/#atom-everything)

- **Qwen3.6-35B-A3B 本地跑赢同日发布的 Claude Opus 4.7。**
  关键词: MoE 架构激活 3B 参数 | MacBook Pro M5 + LM Studio 本地推理 | Q4_K_S 量化 20.9GB 可跑 | pelican/flamingo 两个 SVG 基准均胜出 · 04-17 · [原文](https://simonwillison.net/2026/Apr/16/qwen-beats-opus/#atom-everything)

---

## AI行业动态

> **洞察**: IPO 与融资压力把 AI 公司推上政商前台：OpenAI 内讧、Anthropic 赴白宫、DeepSeek 首轮融资，资本与政策成为新胜负手。


- **Anthropic CEO Amodei 将会见白宫幕僚长，为五角大楼 AI 合约争端灭火。（基于摘要生成）**
  关键词: Axios 首发、路透跟进 | 此前被 Trump 政府贴 RADICAL LEFT 标签 | Pentagon AI 合约分歧是导火索 | AI 巨头直接进白宫游说 · 04-17 · [原文](https://www.reuters.com/technology/anthropic-ceo-meet-white-house-chief-staff-amid-pentagon-ai-dispute-axios-2026-04-17/)

- **OpenAI 一天走三位高管，股东酝酿让 Bret Taylor 在 IPO 后取代 Altman。**
  关键词: Bill Peebles(Sora)/Kevin Weil/Narayanan 同日离职 | Sora 团队被关停、AI for Science 并入 Codex | Altman 私人投资 Helion/Merge/Stoke 利益冲突 | 8500 亿美元 IPO 估值在途 · 04-18 · [原文](https://mp.weixin.qq.com/s/oYLwdabWmbRGPBiCZfq5ig)

- **DeepSeek 正洽谈史上首次外部融资，估值约 100 亿美元。**
  关键词: 融资至少 3 亿美元、The Information/路透披露 | 此前从幻方体系输血、多次拒绝 VC | 内蒙古乌兰察布首次自建数据中心 | V4 即将发布、核心成员出走小米字节 · 04-18 · [原文](https://mp.weixin.qq.com/s/vdaIgZZ5E1gnIlseRs4hjg)

---

## 其他值得关注的产品

> **洞察**: 产品路线分化：Anthropic 把 Agent 做成替代研究员/设计师的一体化流水线，国产紫东太初用透明编排切入科研 B 端。


- **Anthropic 开源自主对齐研究 Agent (AAR)，5 天内成绩碾压人类研究员。**
  关键词: 9 个 Claude 驱动 AAR 并行独立沙箱 | weak-to-strong PGR 从 0.23 推至 0.97 | 800 AAR 小时、总成本 1.8 万美元 | GitHub safety-research/automated-w2s-research · 04-18 · [原文](https://alignment.anthropic.com/2026/automated-w2s-researcher/)

- **Anthropic 发 Claude Design 直捣设计软件腹地，Figma/Adobe 股价应声下跌。**
  关键词: Opus 4.7 驱动的 AI 原生设计平台 | 读代码库自动抽品牌系统/字体/组件 | handoff bundle 一键交 Claude Code 落地 | Datadog 案例：一周流程压至一次对话 · 04-18 · [原文](https://mp.weixin.qq.com/s/i9rEaID6g32IJRyuZ1eINA)

- **紫东太初发 ScienceClaw，做国产透明化版 Claude Managed Agents。**
  关键词: Lead/SubAgent 注册/子 Agent 工厂三层编排 | 内置 AlphaFold 等 3000+ 科研工具、覆盖 8 大学科 | SSE 协议任务全生命周期可回溯 | 飞书/微信机器人 + 紫东太初 4.0 多模态底座 · 04-17 · [原文](https://mp.weixin.qq.com/s/YbfHSyb1q5O7TWn7ZyExUg)

---

## 行业观点

> **洞察**: AI 平台叙事从「能力提升」转向「成本转嫁」：用户为订阅费拿到缩水算力，顶级模型被用来游说政府，信息差成新矛盾。


- **Simon Willison 拆一条短 prompt，讲清高效 Agent 编程的三要素。**
  关键词: 克隆参考仓库到 /tmp 避免污染提交 | 用 similar to X 指向现有实现省描述 | 给 Agent 可自检机制（uvx rodney 浏览器自动化） | 实战平台：Claude Code on the web · 04-18 · [原文](https://simonwillison.net/guides/agentic-engineering-patterns/adding-a-new-content-type/#atom-everything)

- **TechCrunch Equity：AI 内外信息鸿沟正在变成资本与政治的新词。**
  关键词: OpenAI 并购 Hiro 理财/TBPN 播客 | Allbirds 卖鞋转 AI 基建 | Anthropic 发「不敢公开」的 Mythos 却演示给鲍威尔 | Fluidstack 500 亿协议、Wayve 6000 万投资 · 04-17 · [原文](https://techcrunch.com/podcast/tokenmaxxing-openais-shopping-spree-and-the-ai-anxiety-gap/)

- **AMD 总监实测：Claude Code 降智+企业涨价，部分团队账单翻 3 倍。**
  关键词: 审计 6852 份会话/17871 思考块/23 万次工具调用 | BridgeBench 准确率 83.3%→68.3%、排名从 2 跌到 10 | 默认中等努力 85 分 + 缓存从 1 小时砍至 5 分钟 | 企业套餐拆为底薪+按量、OpenAI 趁机推 100 美元 Codex · 04-17 · [原文](https://mp.weixin.qq.com/s/fKQ48kxgRR-_q1jRg6iyZg)

---

## Twitter 热门

> **洞察**: 推特热议集中在模型层：Meta 回归一线、国产 Elephant 攻长尾、美众议院借国安名义重锤中国蒸馏。


- **美众议院报告首次把「系统性对抗性蒸馏」定性为工业间谍行为。**
  关键词: 报告题名《能买就买，买不到就偷》 | 点名 DeepSeek/Moonshot/MiniMax 用欺诈账户蒸馏 | 建议 DOJ 据经济间谍法 + CFAA 起诉 | 建议 BIS 将三家列入制裁/出口管制清单 · 04-18 · 🔁66 👁38,176 · [原文](https://x.com/1260553941714186241/status/2045306318651621432)

- **Meta Muse Spark 登上 ClawEval 第 3，碾压 GPT-5.4 和 Gemini 3.1 Pro。**
  关键词: ClawEval 第三方 Agent 任务基准 | 排名力压 GPT-5.4 / Gemini 3.1 Pro | 测试者评价 surprisingly agentic | Meta 重返一线模型竞赛 · 04-18 · 🔁16 👁20,007 · [原文](https://x.com/615818451/status/2045348588734066794)

- **神秘模型 Elephant Alpha 以极快推理速度切入代码与轻 Agent 场景。**
  关键词: 参数 100B、上下文 256K、输出上限 32K | 主打速度而非对标国外旗舰 | 定位代码补全/长文档处理/轻量 Agent | 已在 OpenRouter 与 Kilo 免费体验 · 04-17 · 🔁2 👁5,815 · [原文](https://x.com/50683/status/2045018432069148757)

---

## GitHub 热门趋势

> 今日 GitHub Trending 无新增 AI 相关项目（多数为昨日延续上榜）

> 可查阅昨日日报：`data/2026-04-17/daily.md`


---

---
