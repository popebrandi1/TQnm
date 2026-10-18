# 🤖 AI领域每日焦点简报

**日期：2026年10月18日**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- **城市雨天出行的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/26a47a29980036ee23cb1d6df5280b7f357fc117?/363
- **在线教育体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/26a47a29980036ee23cb1d6df5280b7f357fc117?/wmz
- **城乡交流活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/26a47a29980036ee23cb1d6df5280b7f357fc117?/640/?amw
- **城市环境志愿行动的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/26a47a29980036ee23cb1d6df5280b7f357fc117?/620=085
- **城市可持续生活的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/26a47a29980036ee23cb1d6df5280b7f357fc117?/sgl=923
- **科技馆参观体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/17bf473b1b3d2a1173998d2b5738fb8f78a91e33?/891
- **开放式学习空间的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/17bf473b1b3d2a1173998d2b5738fb8f78a91e33?/azz
- **绿色消费选择的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/17bf473b1b3d2a1173998d2b5738fb8f78a91e33?/632/?pvp
- **社区设施共享的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/17bf473b1b3d2a1173998d2b5738fb8f78a91e33?/047=419
- **城市生活服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/17bf473b1b3d2a1173998d2b5738fb8f78a91e33?/mcy=006
- **文化场馆预约从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/08ad786c87e0884021dc4736ae41af24ed287dfd?/681
- **社区垃圾回收中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/08ad786c87e0884021dc4736ae41af24ed287dfd?/jlw
- **城市公共厕所的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/08ad786c87e0884021dc4736ae41af24ed287dfd?/911/?omc
- **城市博物馆活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/08ad786c87e0884021dc4736ae41af24ed287dfd?/335=872
- **公园休闲体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/08ad786c87e0884021dc4736ae41af24ed287dfd?/xji=717
- **社区文化传播的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/54faa778fd71a3c77d05a7dd25e932e8ebe46ba4?/957
- **绿色快递包装的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/54faa778fd71a3c77d05a7dd25e932e8ebe46ba4?/hgo
- **市民热线服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/54faa778fd71a3c77d05a7dd25e932e8ebe46ba4?/770/?zyy
- **社区宣传栏更新的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/54faa778fd71a3c77d05a7dd25e932e8ebe46ba4?/726=663
- **绿色出行服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/54faa778fd71a3c77d05a7dd25e932e8ebe46ba4?/alk=394
- **城市休闲步道的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/af2686c2a75dc7ae105a24cfefbd808ff696010d?/084
- **社区生活指南中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/af2686c2a75dc7ae105a24cfefbd808ff696010d?/uuq
- **线上办事服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/af2686c2a75dc7ae105a24cfefbd808ff696010d?/398/?hic
- **校园节能行动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/af2686c2a75dc7ae105a24cfefbd808ff696010d?/022=724
- **本地消费场景的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/af2686c2a75dc7ae105a24cfefbd808ff696010d?/aya=440
- **在线教育体验的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/853d97c1502583e80baa6f101949596b8e578d5a?/548
- **城市便民驿站的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/853d97c1502583e80baa6f101949596b8e578d5a?/tys
- **社区邻里服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/853d97c1502583e80baa6f101949596b8e578d5a?/638/?evn
- **个人信息保护中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/853d97c1502583e80baa6f101949596b8e578d5a?/695=968
- **社区运动空间的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/853d97c1502583e80baa6f101949596b8e578d5a?/dnp=941
- **城乡交流活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/85bdce857f7dfa1ff1311ac3e467f9d5e8b8e8cc?/436
- **城市噪声观察的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/85bdce857f7dfa1ff1311ac3e467f9d5e8b8e8cc?/lrz
- **农产品消费体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/85bdce857f7dfa1ff1311ac3e467f9d5e8b8e8cc?/553/?nuq
- **机器人科普活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/85bdce857f7dfa1ff1311ac3e467f9d5e8b8e8cc?/066=241
- **乡村产业科普的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/85bdce857f7dfa1ff1311ac3e467f9d5e8b8e8cc?/jwp=262
- **儿童友好空间的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8e3806cc753ddba1083f7b2c90c5ae976d2829af?/993
- **数字课堂应用中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8e3806cc753ddba1083f7b2c90c5ae976d2829af?/pgt
- **社区设施共享的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/8e3806cc753ddba1083f7b2c90c5ae976d2829af?/950/?fky
- **数字设备回收的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8e3806cc753ddba1083f7b2c90c5ae976d2829af?/568=010
- **数字素养提升的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/8e3806cc753ddba1083f7b2c90c5ae976d2829af?/bvh=326
- **志愿服务平台的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/1b34a42191c0cb3030686ce38e64d5a7a9838197?/961
- **城市展览体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1b34a42191c0cb3030686ce38e64d5a7a9838197?/rwz
- **街区更新实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1b34a42191c0cb3030686ce38e64d5a7a9838197?/345/?vus
- **数字阅读服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/1b34a42191c0cb3030686ce38e64d5a7a9838197?/650=052
- **城市适老服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/1b34a42191c0cb3030686ce38e64d5a7a9838197?/ttl=733
- **社区家政服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8859e551982cedc50cb973bdcd71f7a2291c1a0e?/793
- **社区应急准备的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8859e551982cedc50cb973bdcd71f7a2291c1a0e?/jif
- **节假日出行安排的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8859e551982cedc50cb973bdcd71f7a2291c1a0e?/538/?kki
- **文明养宠科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/8859e551982cedc50cb973bdcd71f7a2291c1a0e?/572=209
- **垃圾分类指导的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8859e551982cedc50cb973bdcd71f7a2291c1a0e?/ivv=747
- **安全出行教育有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3966d808681a856bfe3c946d6fef7d3024166ab6?/530
- **公共卫生设施的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3966d808681a856bfe3c946d6fef7d3024166ab6?/khb
- **青年职业探索的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3966d808681a856bfe3c946d6fef7d3024166ab6?/598/?wao
- **地方戏曲体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/3966d808681a856bfe3c946d6fef7d3024166ab6?/257=939
- **气象科普传播的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/3966d808681a856bfe3c946d6fef7d3024166ab6?/rnw=327
- **便民维修服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/fd868e91551ebce22c2691f88604a9f2409ead2b?/626
- **家庭教育交流的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/fd868e91551ebce22c2691f88604a9f2409ead2b?/mvz
- **科学信息获取的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/fd868e91551ebce22c2691f88604a9f2409ead2b?/841/?tqj
- **非遗课堂体验的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/fd868e91551ebce22c2691f88604a9f2409ead2b?/780=969
- **数字资源检索的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/fd868e91551ebce22c2691f88604a9f2409ead2b?/ysf=222
- **节假日出行安排的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c80ecc345a478005ecbb249e2ac0d8f2c7c3fc5a?/974
- **公交站点体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c80ecc345a478005ecbb249e2ac0d8f2c7c3fc5a?/vtc
- **家庭教育交流的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c80ecc345a478005ecbb249e2ac0d8f2c7c3fc5a?/201/?dtc
- **社区垃圾回收的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/c80ecc345a478005ecbb249e2ac0d8f2c7c3fc5a?/486=633
- **社区互助网络的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c80ecc345a478005ecbb249e2ac0d8f2c7c3fc5a?/isw=388
- **城市噪声观察的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/42da1aae6647d7e0c7b0792f49c88739d463f5e3?/364
- **城市地名文化的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/42da1aae6647d7e0c7b0792f49c88739d463f5e3?/eth
- **老年人日常照护的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/42da1aae6647d7e0c7b0792f49c88739d463f5e3?/095/?krl
- **读书会组织的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/42da1aae6647d7e0c7b0792f49c88739d463f5e3?/061=878
- **儿童户外活动的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/42da1aae6647d7e0c7b0792f49c88739d463f5e3?/uev=269
- **垃圾分类指导的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/dd2e309c9ccc28e08a7f5db232e22650d42f7f39?/049
- **城市休闲步道的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/dd2e309c9ccc28e08a7f5db232e22650d42f7f39?/zrv
- **节约用水实践的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/dd2e309c9ccc28e08a7f5db232e22650d42f7f39?/173/?uph
- **通勤路线规划的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/dd2e309c9ccc28e08a7f5db232e22650d42f7f39?/615=382
- **城市骑行环境的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/dd2e309c9ccc28e08a7f5db232e22650d42f7f39?/fat=883
- **城市住房服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/7395938f6707a585823f12cb56d77bcf7c207d9c?/754
- **城市雨天出行的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7395938f6707a585823f12cb56d77bcf7c207d9c?/ndv
- **骑行路线规划的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/7395938f6707a585823f12cb56d77bcf7c207d9c?/910/?nyb
- **城市宠物友好空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7395938f6707a585823f12cb56d77bcf7c207d9c?/627=853
- **便民服务窗口有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7395938f6707a585823f12cb56d77bcf7c207d9c?/iqm=721
- **社区活动策划的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/4ba5e9b3d259e8806cc0b1732192edf3fa25ad78?/441
- **数字便民地图从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/4ba5e9b3d259e8806cc0b1732192edf3fa25ad78?/djs
- **社区手工活动的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4ba5e9b3d259e8806cc0b1732192edf3fa25ad78?/488/?pwn
- **社区活动空间的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4ba5e9b3d259e8806cc0b1732192edf3fa25ad78?/521=186
- **社区便利生活的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/4ba5e9b3d259e8806cc0b1732192edf3fa25ad78?/xpu=664
- **城市博物馆活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/f3db9bfcf2e241d43efd5d3d011f9a45ef99cfac?/497
- **居家适老化改造的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f3db9bfcf2e241d43efd5d3d011f9a45ef99cfac?/yyw
- **公共设施维护的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f3db9bfcf2e241d43efd5d3d011f9a45ef99cfac?/485/?vzm
- **城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f3db9bfcf2e241d43efd5d3d011f9a45ef99cfac?/615=965
- **传统节日科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f3db9bfcf2e241d43efd5d3d011f9a45ef99cfac?/itx=965
- **儿童户外活动的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/70e490b07a57d59ae85ed60e11fc108380fe6d84?/990
- **小区停车协商的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/70e490b07a57d59ae85ed60e11fc108380fe6d84?/brr
- **城市生活记录的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/70e490b07a57d59ae85ed60e11fc108380fe6d84?/470/?ldk
- **社区公共卫生的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/70e490b07a57d59ae85ed60e11fc108380fe6d84?/304=109
- **便民维修服务的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/70e490b07a57d59ae85ed60e11fc108380fe6d84?/cuy=066
- **城市步行环境从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/004a7efa6a9f9f7491c441d2662545e189a8ae7b?/646
- **数字便民地图的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/004a7efa6a9f9f7491c441d2662545e189a8ae7b?/ria
- **城市共享单车的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/004a7efa6a9f9f7491c441d2662545e189a8ae7b?/588/?bqk
- **旧物循环利用的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/004a7efa6a9f9f7491c441d2662545e189a8ae7b?/945=852
- **智能手机助老的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/004a7efa6a9f9f7491c441d2662545e189a8ae7b?/gng=649
- **城市骑行环境的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f61833cb7ed2c05f1d743fdff1fc4532dbc635c8?/727
- **家庭饮食安排的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/f61833cb7ed2c05f1d743fdff1fc4532dbc635c8?/yzm
- **数字公共文化的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f61833cb7ed2c05f1d743fdff1fc4532dbc635c8?/774/?nwf
- **远程协作工具的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f61833cb7ed2c05f1d743fdff1fc4532dbc635c8?/974=197
- **基层服务创新的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f61833cb7ed2c05f1d743fdff1fc4532dbc635c8?/iuc=281
- **图书馆数字服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ad5c158d0a82c1149c6aa3e400c956c2bb5504bb?/099
- **开源技术交流的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/ad5c158d0a82c1149c6aa3e400c956c2bb5504bb?/zyg
- **机器人科普活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ad5c158d0a82c1149c6aa3e400c956c2bb5504bb?/474/?pfb
- **科学健身方法的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/ad5c158d0a82c1149c6aa3e400c956c2bb5504bb?/742=703
- **社区体育组织的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/ad5c158d0a82c1149c6aa3e400c956c2bb5504bb?/egj=904
- **社区垃圾分类的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4179d9379bfdf12767cebeb50b45f25cd07c0459?/258
- **志愿者培训交流中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4179d9379bfdf12767cebeb50b45f25cd07c0459?/ava
- **乡村生态观察的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/4179d9379bfdf12767cebeb50b45f25cd07c0459?/274/?ffu
- **气象科普传播的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/4179d9379bfdf12767cebeb50b45f25cd07c0459?/298=791
- **社区阅读服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4179d9379bfdf12767cebeb50b45f25cd07c0459?/vsx=585
- **街头绿植养护的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f88890af429bf7b02656ec5c027c80adfbd68bdf?/079
- **城市展览体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/f88890af429bf7b02656ec5c027c80adfbd68bdf?/lxy
- **数字档案服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f88890af429bf7b02656ec5c027c80adfbd68bdf?/764/?jkq
- **数字政务体验的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/f88890af429bf7b02656ec5c027c80adfbd68bdf?/707=924
- **城市绿道建设的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f88890af429bf7b02656ec5c027c80adfbd68bdf?/ppe=456
- **城市农夫市集的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d9ba90621b91a397050b3de5c74dbfdda5bdc1a5?/988
- **在线学习体验的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d9ba90621b91a397050b3de5c74dbfdda5bdc1a5?/cex
- **人工智能科普的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/d9ba90621b91a397050b3de5c74dbfdda5bdc1a5?/596/?cyt
- **家庭节能设备的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d9ba90621b91a397050b3de5c74dbfdda5bdc1a5?/379=672
- **老年人日常照护的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d9ba90621b91a397050b3de5c74dbfdda5bdc1a5?/njt=703
- **绿色生活实践的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/84d6899d50a6c63224b9ce15e6960e49efc7cbeb?/998
- **家庭用电安全的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/84d6899d50a6c63224b9ce15e6960e49efc7cbeb?/bqz
- **城市基础设施的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/84d6899d50a6c63224b9ce15e6960e49efc7cbeb?/217/?qjy
- **公共空间照明的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/84d6899d50a6c63224b9ce15e6960e49efc7cbeb?/951=886
- **公共服务沟通的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/84d6899d50a6c63224b9ce15e6960e49efc7cbeb?/qma=079
- **绿色出行服务的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/5ff1374b9c82da813bf9ad853947ed2183cec155?/051
- **公共卫生设施的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5ff1374b9c82da813bf9ad853947ed2183cec155?/cns
- **个人时间管理的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/5ff1374b9c82da813bf9ad853947ed2183cec155?/977/?ckr
- **社区生活指南的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5ff1374b9c82da813bf9ad853947ed2183cec155?/459=086
- **家庭环保习惯的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5ff1374b9c82da813bf9ad853947ed2183cec155?/knr=341
- **节能生活方式的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a97ac44e9d7d11041eb3e34d7b422ea789111ee7?/993
- **城市公共空间的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a97ac44e9d7d11041eb3e34d7b422ea789111ee7?/upw
- **社区环保活动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a97ac44e9d7d11041eb3e34d7b422ea789111ee7?/977/?pot
- **公共场馆服务的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/a97ac44e9d7d11041eb3e34d7b422ea789111ee7?/824=900
- **数字素养提升的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a97ac44e9d7d11041eb3e34d7b422ea789111ee7?/ppb=185
- **城市人文观察从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/20cf30bf145bfa5bf8e0b8a0f9180ef61474d01d?/783
- **城市农夫市集的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/20cf30bf145bfa5bf8e0b8a0f9180ef61474d01d?/ozc
- **社区交通安全的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/20cf30bf145bfa5bf8e0b8a0f9180ef61474d01d?/926/?yxv
- **食品安全科普的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/20cf30bf145bfa5bf8e0b8a0f9180ef61474d01d?/557=405
- **公园无障碍服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/20cf30bf145bfa5bf8e0b8a0f9180ef61474d01d?/gct=841
- **青少年职业启蒙的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/1ca78c6c869b16bfbec894e0ced8c33854a481b3?/706
- **农业科普体验的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/1ca78c6c869b16bfbec894e0ced8c33854a481b3?/hjg
- **低碳社区实践的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/1ca78c6c869b16bfbec894e0ced8c33854a481b3?/334/?pdi
- **社区设施共享有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1ca78c6c869b16bfbec894e0ced8c33854a481b3?/729=968
- **数字阅读服务的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1ca78c6c869b16bfbec894e0ced8c33854a481b3?/lhg=698
- **青年职业探索的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/d442c5cfab19696b0cb8d8eb3c5a3c6f40950c38?/523
- **社区交通安全的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d442c5cfab19696b0cb8d8eb3c5a3c6f40950c38?/olg
- **开源技术交流的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d442c5cfab19696b0cb8d8eb3c5a3c6f40950c38?/292/?dqm
- **机器人科普活动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d442c5cfab19696b0cb8d8eb3c5a3c6f40950c38?/115=249
- **学校体育活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/d442c5cfab19696b0cb8d8eb3c5a3c6f40950c38?/eiq=555
- **农业科普体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/d19e9b32bfad81f8e705312982396ab1ef5a87d5?/232
- **传统节日科普的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d19e9b32bfad81f8e705312982396ab1ef5a87d5?/fev
- **农业科普体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/d19e9b32bfad81f8e705312982396ab1ef5a87d5?/236/?exm
- **老年人日常照护的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d19e9b32bfad81f8e705312982396ab1ef5a87d5?/270=252
- **旧物循环利用的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d19e9b32bfad81f8e705312982396ab1ef5a87d5?/qek=125
- **居民健康教育的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/0f81824f3abdf3cccee40d1857a8982b14d37ad0?/644
- **家庭理财科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/0f81824f3abdf3cccee40d1857a8982b14d37ad0?/eml
- **社区家校合作的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/0f81824f3abdf3cccee40d1857a8982b14d37ad0?/984/?dex
- **城市应急广播的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/0f81824f3abdf3cccee40d1857a8982b14d37ad0?/587=654
- **乡村公共阅读的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/0f81824f3abdf3cccee40d1857a8982b14d37ad0?/anf=190
- **智慧停车服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0279f18a3a0a1a4fc19b9228f0527f9aca5836a5?/802
- **家庭饮食安排中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/0279f18a3a0a1a4fc19b9228f0527f9aca5836a5?/sbh
- **社区共享书架的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0279f18a3a0a1a4fc19b9228f0527f9aca5836a5?/031/?umh
- **社区学习活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/0279f18a3a0a1a4fc19b9228f0527f9aca5836a5?/900=887
- **乡村公共服务的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/0279f18a3a0a1a4fc19b9228f0527f9aca5836a5?/yfu=541
- **家庭环保行动的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e319e031fe6ecb7f6e3d29b49d7828bf5e7ab056?/763
- **线上办事服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/e319e031fe6ecb7f6e3d29b49d7828bf5e7ab056?/doi
- **社区垃圾回收的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e319e031fe6ecb7f6e3d29b49d7828bf5e7ab056?/444/?avl
- **生成式工具使用的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/e319e031fe6ecb7f6e3d29b49d7828bf5e7ab056?/846=948
- **乡村文化活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/e319e031fe6ecb7f6e3d29b49d7828bf5e7ab056?/bth=030
- **儿童安全出行的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2c9ae34a7934438981d3f3361292a077919e0017?/209
- **文化遗产保护科普的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/2c9ae34a7934438981d3f3361292a077919e0017?/dtw
- **电动汽车充电的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2c9ae34a7934438981d3f3361292a077919e0017?/014/?jas
- **青少年科普实践的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/2c9ae34a7934438981d3f3361292a077919e0017?/012=443
- **线上阅读资源的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2c9ae34a7934438981d3f3361292a077919e0017?/hun=393
- **社区读书角建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/72b8307c2318860d6d5574abee4c1521b1db423b?/008
- **家庭健康管理中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/72b8307c2318860d6d5574abee4c1521b1db423b?/uce
- **健康饮水科普从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/72b8307c2318860d6d5574abee4c1521b1db423b?/223/?zrs
- **绿色校园实践的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/72b8307c2318860d6d5574abee4c1521b1db423b?/074=161
- **绿色办公实践的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/72b8307c2318860d6d5574abee4c1521b1db423b?/myv=437
- **城市人文观察的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/f8e7ba4fffbb0ae278e3bf588e4c9ce1a87b4059?/417
- **图书馆活动策划的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f8e7ba4fffbb0ae278e3bf588e4c9ce1a87b4059?/wcx
- **城市公共艺术的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f8e7ba4fffbb0ae278e3bf588e4c9ce1a87b4059?/218/?knk
- **社区公共餐饮的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/f8e7ba4fffbb0ae278e3bf588e4c9ce1a87b4059?/379=381
- **图书馆亲子空间的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/f8e7ba4fffbb0ae278e3bf588e4c9ce1a87b4059?/teu=658
- **乡村生活观察的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ccc98376e42544bcc6ff55171db5c3d035ddc905?/786
- **地方戏曲体验的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/ccc98376e42544bcc6ff55171db5c3d035ddc905?/yka
- **社区文化传播的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ccc98376e42544bcc6ff55171db5c3d035ddc905?/893/?hoq
- **社区公共议事中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ccc98376e42544bcc6ff55171db5c3d035ddc905?/955=777
- **户外活动组织的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ccc98376e42544bcc6ff55171db5c3d035ddc905?/qvn=668
- **家庭健康科普的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/41bc5425c563d2274f86e4223462f15404472f91?/127
- **数字学习资源的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/41bc5425c563d2274f86e4223462f15404472f91?/ego
- **乡村生态旅游的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/41bc5425c563d2274f86e4223462f15404472f91?/763/?znq
- **城乡交流活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/41bc5425c563d2274f86e4223462f15404472f91?/366=539
- **数字档案服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/41bc5425c563d2274f86e4223462f15404472f91?/fag=275
- **社区活动报名的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3b1ff6c7db3ff3ad63c08a8959dfc6d09a31f1de?/500
- **家庭理财科普的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3b1ff6c7db3ff3ad63c08a8959dfc6d09a31f1de?/wtr
- **社会体育指导从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3b1ff6c7db3ff3ad63c08a8959dfc6d09a31f1de?/796/?oas
- **生活技能分享的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3b1ff6c7db3ff3ad63c08a8959dfc6d09a31f1de?/360=564
- **城市应急科普的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/3b1ff6c7db3ff3ad63c08a8959dfc6d09a31f1de?/tnc=782
- **青少年编程学习的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/a942fcc4b28c16f1506990649e6e62a769025f48?/718
- **市民热线服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a942fcc4b28c16f1506990649e6e62a769025f48?/bra
- **节能生活方式的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/a942fcc4b28c16f1506990649e6e62a769025f48?/178/?rze
- **街区更新实践的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/a942fcc4b28c16f1506990649e6e62a769025f48?/927=097
- **社区知识分享的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/a942fcc4b28c16f1506990649e6e62a769025f48?/gku=521
- **物业服务沟通的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/b33324ef3da33c4d4270410e44afac76c96edb58?/774
- **地方民俗记录从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/b33324ef3da33c4d4270410e44afac76c96edb58?/fdo
- **垃圾分类指导的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b33324ef3da33c4d4270410e44afac76c96edb58?/735/?lsg
- **社区宠物管理的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/b33324ef3da33c4d4270410e44afac76c96edb58?/104=585
- **社区花园共建的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/b33324ef3da33c4d4270410e44afac76c96edb58?/jub=951
- **电子商务服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/782dfd45bd2bc1b9fc1ff0f9a88d00ee943455fe?/548
- **远程协作工具的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/782dfd45bd2bc1b9fc1ff0f9a88d00ee943455fe?/gys
- **人工智能科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/782dfd45bd2bc1b9fc1ff0f9a88d00ee943455fe?/782/?xxo
- **社区共享书架的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/782dfd45bd2bc1b9fc1ff0f9a88d00ee943455fe?/916=951
- **社区养老服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/782dfd45bd2bc1b9fc1ff0f9a88d00ee943455fe?/cnb=667
- **社区防暑服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fc864d51ab8416d3f49c36ecc9e765189f013dd4?/910
- **城乡交流活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/fc864d51ab8416d3f49c36ecc9e765189f013dd4?/hml
- **青少年心理健康的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/fc864d51ab8416d3f49c36ecc9e765189f013dd4?/356/?eae
- **社区协商议事中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/fc864d51ab8416d3f49c36ecc9e765189f013dd4?/669=718
- **城市环境志愿行动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/fc864d51ab8416d3f49c36ecc9e765189f013dd4?/jcz=890
- **食品安全科普从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/ae26db441249f3465de8ce5978fbd1191be6b1e3?/334
- **乡村公共阅读的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/ae26db441249f3465de8ce5978fbd1191be6b1e3?/jjo
- **社区托育服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/ae26db441249f3465de8ce5978fbd1191be6b1e3?/367/?bsv
- **地方美食文化的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/ae26db441249f3465de8ce5978fbd1191be6b1e3?/796=301
- **绿色办公实践中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ae26db441249f3465de8ce5978fbd1191be6b1e3?/mvk=011
- **社区安全巡查的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/01066546d055387192bdd02ece92111417d57cbc?/371
- **公共健身器材的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/01066546d055387192bdd02ece92111417d57cbc?/jnu
- **信息无障碍体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/01066546d055387192bdd02ece92111417d57cbc?/434/?wda
- **公共卫生宣传的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/01066546d055387192bdd02ece92111417d57cbc?/485=001
- **城市应急广播中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/01066546d055387192bdd02ece92111417d57cbc?/mat=738
- **社区邻里服务的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/53e97dc459a49d889863322d8f1026483f72761b?/042
- **智能手机助老的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/53e97dc459a49d889863322d8f1026483f72761b?/vrv
- **社区手工活动的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/53e97dc459a49d889863322d8f1026483f72761b?/761/?bjh
- **节能家电使用的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/53e97dc459a49d889863322d8f1026483f72761b?/969=875
- **家庭防灾准备的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/53e97dc459a49d889863322d8f1026483f72761b?/pcg=698
- **公共服务咨询的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/608dd38a1c416d40525f438f1829a3eaad50198a?/471
- **数字阅读服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/608dd38a1c416d40525f438f1829a3eaad50198a?/noq
- **学校食育活动的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/608dd38a1c416d40525f438f1829a3eaad50198a?/348/?xgz
- **社会体育指导的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/608dd38a1c416d40525f438f1829a3eaad50198a?/427=263
- **社区公共卫生的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/608dd38a1c416d40525f438f1829a3eaad50198a?/suy=784
- **城市雨天出行的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb1a5fa98319af0ff0c7a32a34ba5c018b1eec5?/726
- **开放数据应用的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb1a5fa98319af0ff0c7a32a34ba5c018b1eec5?/zww
- **就业技能培训的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb1a5fa98319af0ff0c7a32a34ba5c018b1eec5?/847/?put
- **青少年职业启蒙的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb1a5fa98319af0ff0c7a32a34ba5c018b1eec5?/638=761
- **公共场馆服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb1a5fa98319af0ff0c7a32a34ba5c018b1eec5?/byl=493
- **乡村电商实践中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/f7e98d4f9b01e1761b3992e97659571325726d5a?/216
- **居家防滑改造的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f7e98d4f9b01e1761b3992e97659571325726d5a?/pur
- **乡村文化活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/f7e98d4f9b01e1761b3992e97659571325726d5a?/620/?oaa
- **节日文化体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/f7e98d4f9b01e1761b3992e97659571325726d5a?/564=151
- **食品安全科普的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/f7e98d4f9b01e1761b3992e97659571325726d5a?/zly=243
- **校园阅读活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/c81c861bc9c6b942087384ae35ffabb7ddfb4237?/724
- **节日文化体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/c81c861bc9c6b942087384ae35ffabb7ddfb4237?/yhy
- **公共交通接驳的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c81c861bc9c6b942087384ae35ffabb7ddfb4237?/730/?eze
- **社区邻里服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/c81c861bc9c6b942087384ae35ffabb7ddfb4237?/779=344
- **电动汽车充电的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/c81c861bc9c6b942087384ae35ffabb7ddfb4237?/yzo=643
- **城市公共标识的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c65fa9c8ad3778cab430385e3a81c793ad83407b?/489
- **科普展览体验的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c65fa9c8ad3778cab430385e3a81c793ad83407b?/vwv
- **家庭饮食安排的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c65fa9c8ad3778cab430385e3a81c793ad83407b?/424/?xxu
- **城市社区治理的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c65fa9c8ad3778cab430385e3a81c793ad83407b?/135=159
- **小区停车协商的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c65fa9c8ad3778cab430385e3a81c793ad83407b?/lxs=526
- **家庭运动计划的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/3ede9b13ccb87222fea245ee667fc1ebdd91c60b?/767
- **便民服务地图的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/3ede9b13ccb87222fea245ee667fc1ebdd91c60b?/xzu
- **城市公共艺术的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3ede9b13ccb87222fea245ee667fc1ebdd91c60b?/123/?quf
- **家庭网络使用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3ede9b13ccb87222fea245ee667fc1ebdd91c60b?/022=793
- **家庭食品保存的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/3ede9b13ccb87222fea245ee667fc1ebdd91c60b?/riw=676
- **儿童户外活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/79c581953c572edcc2e8bbcd4ef95779665a79ee?/114
- **科普展览体验的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/79c581953c572edcc2e8bbcd4ef95779665a79ee?/kxe
- **智能家居应用的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/79c581953c572edcc2e8bbcd4ef95779665a79ee?/778/?qtm
- **数字阅读服务的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/79c581953c572edcc2e8bbcd4ef95779665a79ee?/070=902
- **社区心理支持的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/79c581953c572edcc2e8bbcd4ef95779665a79ee?/sok=557
- **城市慢行系统的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/3c323aa70d91c0dfba98f9257bd12aac3bc980c1?/940
- **灵活就业交流的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3c323aa70d91c0dfba98f9257bd12aac3bc980c1?/zly
- **公共交通接驳的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3c323aa70d91c0dfba98f9257bd12aac3bc980c1?/864/?lkx
- **环境教育课程从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3c323aa70d91c0dfba98f9257bd12aac3bc980c1?/053=057
- **城市微更新实践的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3c323aa70d91c0dfba98f9257bd12aac3bc980c1?/wai=995
- **城市慢跑路线从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/9924915198aff6d2f6f7357d6835e331bfe32fa4?/366
- **社区垃圾回收的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/9924915198aff6d2f6f7357d6835e331bfe32fa4?/ijh
- **城市住房服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9924915198aff6d2f6f7357d6835e331bfe32fa4?/520/?ewi
- **公共空间导览的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9924915198aff6d2f6f7357d6835e331bfe32fa4?/078=526
- **老年智能设备的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/9924915198aff6d2f6f7357d6835e331bfe32fa4?/qeq=225
- **电动汽车充电的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/cc622675d996c04693fd392e345b1ebd052a7374?/991
- **文化讲座服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/cc622675d996c04693fd392e345b1ebd052a7374?/rxp
- **科技馆参观体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/cc622675d996c04693fd392e345b1ebd052a7374?/054/?ata
- **生活垃圾减量的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/cc622675d996c04693fd392e345b1ebd052a7374?/233=865
- **科学信息获取的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/cc622675d996c04693fd392e345b1ebd052a7374?/lbk=637
- **乡村阅读活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f655cc7de5a1eb5f5268779d5d134d8cc87633?/190
- **非遗课堂体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f655cc7de5a1eb5f5268779d5d134d8cc87633?/inz
- **社区消防演练的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f655cc7de5a1eb5f5268779d5d134d8cc87633?/963/?vsl
- **食品安全科普的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f655cc7de5a1eb5f5268779d5d134d8cc87633?/232=648
- **街区小店体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f655cc7de5a1eb5f5268779d5d134d8cc87633?/twl=787
- **城市适老服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/836c9fe143ce2416439119f23968e6c5bc658c10?/284
- **家庭食品保存的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/836c9fe143ce2416439119f23968e6c5bc658c10?/geb
- **城市文明出行的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/836c9fe143ce2416439119f23968e6c5bc658c10?/351/?qex
- **文明养宠科普的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/836c9fe143ce2416439119f23968e6c5bc658c10?/057=846
- **公共服务数字化的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/836c9fe143ce2416439119f23968e6c5bc658c10?/fij=542
- **线上阅读资源的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/0d0cabde48614ea2af108c610993fdcfc68bacf0?/160
- **软件开发学习的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/0d0cabde48614ea2af108c610993fdcfc68bacf0?/zzr
- **公共场所导视的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0d0cabde48614ea2af108c610993fdcfc68bacf0?/394/?ate
- **绿色消费选择的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/0d0cabde48614ea2af108c610993fdcfc68bacf0?/781=934
- **街道综合服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0d0cabde48614ea2af108c610993fdcfc68bacf0?/fgv=425
- **科学运动指导的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/dc3604025cb669fb2bf6b0f3f7e7918329aba1f2?/961
- **城市共享单车的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/dc3604025cb669fb2bf6b0f3f7e7918329aba1f2?/udi
- **零废弃生活尝试中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/dc3604025cb669fb2bf6b0f3f7e7918329aba1f2?/240/?onu
- **城市树木认养的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/dc3604025cb669fb2bf6b0f3f7e7918329aba1f2?/240=046
- **租房信息服务的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/dc3604025cb669fb2bf6b0f3f7e7918329aba1f2?/yfm=530
- **公共服务沟通的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ce5bc0ad0d757ffa277c397f259710049fe177c8?/646
- **生活技能分享从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/ce5bc0ad0d757ffa277c397f259710049fe177c8?/dxr
- **科学健身方法的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/ce5bc0ad0d757ffa277c397f259710049fe177c8?/713/?wlx
- **个人信息保护的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ce5bc0ad0d757ffa277c397f259710049fe177c8?/978=660
- **在线教育体验的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/ce5bc0ad0d757ffa277c397f259710049fe177c8?/ott=777
- **社区活动策划的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/49464dba18fae539d9481239df73c1b7c2df18fa?/865
- **公共设施使用的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/49464dba18fae539d9481239df73c1b7c2df18fa?/gxp
- **文化遗产保护科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/49464dba18fae539d9481239df73c1b7c2df18fa?/508/?abt
- **社区家校合作中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/49464dba18fae539d9481239df73c1b7c2df18fa?/403=451
- **社区信息发布的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/49464dba18fae539d9481239df73c1b7c2df18fa?/bis=924
- **公共场馆服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f1a5feb5e377dff80f2dc5050ec7c140f5e05b8f?/451
- **城市建设科普中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f1a5feb5e377dff80f2dc5050ec7c140f5e05b8f?/jma
- **青少年科普实践的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/f1a5feb5e377dff80f2dc5050ec7c140f5e05b8f?/864/?tnk
- **传统节日科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f1a5feb5e377dff80f2dc5050ec7c140f5e05b8f?/671=429
- **社区绿色空间的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f1a5feb5e377dff80f2dc5050ec7c140f5e05b8f?/jhw=597
- **社区科普课堂的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0b68b9447fe771b8f319e14d2a0a42ae279ac162?/146
- **社区教育资源的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0b68b9447fe771b8f319e14d2a0a42ae279ac162?/qyt
- **城市农夫市集的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/0b68b9447fe771b8f319e14d2a0a42ae279ac162?/724/?agk
- **低碳社区实践的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/0b68b9447fe771b8f319e14d2a0a42ae279ac162?/320=461
- **社区法律科普的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0b68b9447fe771b8f319e14d2a0a42ae279ac162?/iof=877
- **垃圾分类指导的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/043defb7e5885c58895ddb72008c78b1325718ce?/447
- **乡村生态观察的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/043defb7e5885c58895ddb72008c78b1325718ce?/bon
- **文化讲座服务的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/043defb7e5885c58895ddb72008c78b1325718ce?/951/?owq
- **零废弃生活尝试的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/043defb7e5885c58895ddb72008c78b1325718ce?/127=521
- **公共空间照明的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/043defb7e5885c58895ddb72008c78b1325718ce?/bel=107
- **社区公共卫生的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/264dff57d3c6db5422c755fc8b89aefbe788b691?/504
- **城市文化路线的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/264dff57d3c6db5422c755fc8b89aefbe788b691?/kjn
- **学校食育活动的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/264dff57d3c6db5422c755fc8b89aefbe788b691?/700/?fgh
- **城市博物馆服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/264dff57d3c6db5422c755fc8b89aefbe788b691?/184=198
- **家庭养老规划从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/264dff57d3c6db5422c755fc8b89aefbe788b691?/fqp=601
- **社区健康讲座中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/802276a8f4321513517878501be52832b7456d5e?/884
- **地方民俗记录的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/802276a8f4321513517878501be52832b7456d5e?/ifi
- **垃圾分类指导的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/802276a8f4321513517878501be52832b7456d5e?/829/?vnt
- **社区信息发布从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/802276a8f4321513517878501be52832b7456d5e?/115=519
- **社区垃圾回收的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/802276a8f4321513517878501be52832b7456d5e?/njy=600
- **社区故事采集的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/ea330c8704f2766660ad83e85b01a2be5642a6e3?/323
- **劳动教育实践从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ea330c8704f2766660ad83e85b01a2be5642a6e3?/lgb
- **基层健康服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ea330c8704f2766660ad83e85b01a2be5642a6e3?/143/?nlj
- **公共服务评价有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ea330c8704f2766660ad83e85b01a2be5642a6e3?/081=534
- **职业技能学习的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/ea330c8704f2766660ad83e85b01a2be5642a6e3?/iwv=119
- **个人数据管理的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/61dd1e113d24e9be1ccbf0345fb70f644be24a7b?/597
- **公共服务评价的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/61dd1e113d24e9be1ccbf0345fb70f644be24a7b?/tmb
- **旧物循环利用的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/61dd1e113d24e9be1ccbf0345fb70f644be24a7b?/745/?aqw
- **低碳社区实践的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/61dd1e113d24e9be1ccbf0345fb70f644be24a7b?/983=409
- **乡村生活观察的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/61dd1e113d24e9be1ccbf0345fb70f644be24a7b?/ojw=673
- **学校体育活动的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8bcb887dc4d8cc45712f6cdd66acb746b904c154?/787
- **社区心理支持的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/8bcb887dc4d8cc45712f6cdd66acb746b904c154?/hzl
- **社区科普课堂中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/8bcb887dc4d8cc45712f6cdd66acb746b904c154?/188/?hns
- **传统节日科普的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/8bcb887dc4d8cc45712f6cdd66acb746b904c154?/588=122
- **社区垃圾分类的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/8bcb887dc4d8cc45712f6cdd66acb746b904c154?/pny=190
- **家庭教育交流的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/599881626562a29701281164b8b79c7966ffc750?/139
- **家庭志愿活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/599881626562a29701281164b8b79c7966ffc750?/vkk
- **公共空间安全的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/599881626562a29701281164b8b79c7966ffc750?/494/?uau
- **社区公共卫生的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/599881626562a29701281164b8b79c7966ffc750?/447=300
- **网络安全教育的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/599881626562a29701281164b8b79c7966ffc750?/gfy=863
- **公共交通接驳的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/e7b5c39dde76d3eac4887aab8929ff114e5ee97c?/949
- **乡村文化活动的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e7b5c39dde76d3eac4887aab8929ff114e5ee97c?/fvh
- **医院导诊服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/e7b5c39dde76d3eac4887aab8929ff114e5ee97c?/902/?fke
- **绿色快递包装的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e7b5c39dde76d3eac4887aab8929ff114e5ee97c?/363=214
- **城市噪声观察的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e7b5c39dde76d3eac4887aab8929ff114e5ee97c?/ovv=830
- **数字公共文化的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/877ecc2758b354e9ea1aa25e9995b5ee00bf45f1?/137
- **智能手机助老的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/877ecc2758b354e9ea1aa25e9995b5ee00bf45f1?/law
- **社区便利生活的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/877ecc2758b354e9ea1aa25e9995b5ee00bf45f1?/057/?qmt
- **公交无障碍服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/877ecc2758b354e9ea1aa25e9995b5ee00bf45f1?/902=793
- **公共空间导览的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/877ecc2758b354e9ea1aa25e9995b5ee00bf45f1?/tnp=522
- **校园节能行动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9c76b9ac89a9b3b479a91c05ec601f26c48bc63e?/906
- **公共交通信息服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/9c76b9ac89a9b3b479a91c05ec601f26c48bc63e?/xrf
- **儿童友好空间的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/9c76b9ac89a9b3b479a91c05ec601f26c48bc63e?/280/?fnd
- **乡村产业科普有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9c76b9ac89a9b3b479a91c05ec601f26c48bc63e?/134=764
- **课后服务体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9c76b9ac89a9b3b479a91c05ec601f26c48bc63e?/owu=695
- **线上办事服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/6a2f69e93bf9839c4b4f0e8ac60189d91007bb38?/692
- **口袋公园建设中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6a2f69e93bf9839c4b4f0e8ac60189d91007bb38?/lpw
- **零废弃生活尝试的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/6a2f69e93bf9839c4b4f0e8ac60189d91007bb38?/385/?tab
- **城市环境志愿行动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/6a2f69e93bf9839c4b4f0e8ac60189d91007bb38?/692=215
- **公共服务指南的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/6a2f69e93bf9839c4b4f0e8ac60189d91007bb38?/waq=701
- **开放数据应用的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4a27b804d85f0fe8696900619ed82ef3b8c7c112?/405
- **社区阅读服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4a27b804d85f0fe8696900619ed82ef3b8c7c112?/xbp
- **开源技术交流的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/4a27b804d85f0fe8696900619ed82ef3b8c7c112?/969/?meu
- **数字学习资源的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/4a27b804d85f0fe8696900619ed82ef3b8c7c112?/833=360
- **信息无障碍体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4a27b804d85f0fe8696900619ed82ef3b8c7c112?/jor=603
- **数字档案服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c0760443fd8b6ee84520373bb9a3823730667fb7?/411
- **家庭阅读计划的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c0760443fd8b6ee84520373bb9a3823730667fb7?/aou
- **家庭科学教育的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c0760443fd8b6ee84520373bb9a3823730667fb7?/326/?ovu
- **信息无障碍体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c0760443fd8b6ee84520373bb9a3823730667fb7?/456=755
- **科技馆参观体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c0760443fd8b6ee84520373bb9a3823730667fb7?/llx=812
- **城市树木认养的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5e8a9c30002bca2df3abe970ee6b6735303d645b?/386
- **家庭急救准备有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5e8a9c30002bca2df3abe970ee6b6735303d645b?/eun
- **青年就业服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5e8a9c30002bca2df3abe970ee6b6735303d645b?/747/?dgy
- **便民服务窗口的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5e8a9c30002bca2df3abe970ee6b6735303d645b?/400=025
- **社区活动策划的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/5e8a9c30002bca2df3abe970ee6b6735303d645b?/sgl=820
- **便民维修服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/15b842caa604caa1941db7fab2a4f97b3718105c?/434
- **社区快递服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/15b842caa604caa1941db7fab2a4f97b3718105c?/fdx
- **儿童户外活动的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/15b842caa604caa1941db7fab2a4f97b3718105c?/450/?qzc
- **儿童友好空间的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/15b842caa604caa1941db7fab2a4f97b3718105c?/462=052
- **社区协商议事从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/15b842caa604caa1941db7fab2a4f97b3718105c?/gio=932
- **数字公共文化中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/1a2c68cf6ebee910a894407d5ac4b9c1f285d02a?/801
- **新能源出行中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/1a2c68cf6ebee910a894407d5ac4b9c1f285d02a?/duo
- **户外活动组织的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/1a2c68cf6ebee910a894407d5ac4b9c1f285d02a?/492/?mdy
- **家庭照护支持的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1a2c68cf6ebee910a894407d5ac4b9c1f285d02a?/627=988
- **城市公共自行车的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1a2c68cf6ebee910a894407d5ac4b9c1f285d02a?/bai=195
- **社区体育组织的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/919d2fdf984e7ebad4d4cd0f615f34a8ed8d3155?/538
- **公共卫生宣传的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/919d2fdf984e7ebad4d4cd0f615f34a8ed8d3155?/yfe
- **城市游园体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/919d2fdf984e7ebad4d4cd0f615f34a8ed8d3155?/601/?jin
- **便民信息查询的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/919d2fdf984e7ebad4d4cd0f615f34a8ed8d3155?/860=671
- **社区修缮行动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/919d2fdf984e7ebad4d4cd0f615f34a8ed8d3155?/lhn=286
- **社区慢性病防控的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/27692ef098349a2f7c8b13a5b734ead5a973c188?/870
- **青少年职业启蒙的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/27692ef098349a2f7c8b13a5b734ead5a973c188?/aus
- **社区信息发布中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/27692ef098349a2f7c8b13a5b734ead5a973c188?/464/?ioe
- **社区体育组织的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/27692ef098349a2f7c8b13a5b734ead5a973c188?/710=538
- **运动安全知识的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/27692ef098349a2f7c8b13a5b734ead5a973c188?/diu=590
- **青少年编程学习有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ec28f19767919b7ea39fac96301ee2023d5ff8b0?/046
- **地方文化传播的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ec28f19767919b7ea39fac96301ee2023d5ff8b0?/fqe
- **新能源知识普及的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ec28f19767919b7ea39fac96301ee2023d5ff8b0?/976/?xgv
- **电子商务服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/ec28f19767919b7ea39fac96301ee2023d5ff8b0?/620=479
- **数字生活课堂的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ec28f19767919b7ea39fac96301ee2023d5ff8b0?/aya=495
- **绿色建筑理念的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/eb074cae20510c8758ed8ad1b05d5665bad6a06c?/583
- **城市夜间照明的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/eb074cae20510c8758ed8ad1b05d5665bad6a06c?/atf
- **城乡公共服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/eb074cae20510c8758ed8ad1b05d5665bad6a06c?/107/?eng
- **城市文明出行的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/eb074cae20510c8758ed8ad1b05d5665bad6a06c?/732=454
- **城市公共厕所中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/eb074cae20510c8758ed8ad1b05d5665bad6a06c?/kup=167
- **街区更新实践的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7e61a0acf2d7548b6d5df05c8275e48dff9574f4?/679
- **居民健康教育的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/7e61a0acf2d7548b6d5df05c8275e48dff9574f4?/ikb
- **网络安全教育的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/7e61a0acf2d7548b6d5df05c8275e48dff9574f4?/972/?crf
- **家庭收纳实践的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7e61a0acf2d7548b6d5df05c8275e48dff9574f4?/834=582
- **数字课堂应用的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/7e61a0acf2d7548b6d5df05c8275e48dff9574f4?/qzf=930
- **便民维修服务的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2895d3e5d71279587ddb5e12eb566ce52846dadd?/542
- **乡村文化空间的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2895d3e5d71279587ddb5e12eb566ce52846dadd?/ney
- **家庭运动计划的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2895d3e5d71279587ddb5e12eb566ce52846dadd?/680/?bbs
- **城乡交通衔接的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2895d3e5d71279587ddb5e12eb566ce52846dadd?/522=529
- **社区便民集市的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2895d3e5d71279587ddb5e12eb566ce52846dadd?/caj=387
- **新能源知识普及的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/73cc60399a76a1b50c816758fa213d54c73a8af3?/072
- **健康步道使用中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/73cc60399a76a1b50c816758fa213d54c73a8af3?/njk
- **数字创作工具的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/73cc60399a76a1b50c816758fa213d54c73a8af3?/437/?qvu
- **居家适老化改造的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/73cc60399a76a1b50c816758fa213d54c73a8af3?/420=613
- **家庭健康管理从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/73cc60399a76a1b50c816758fa213d54c73a8af3?/frp=517
- **公共设施维护的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/55d4f591f15c896653896a029fc162d87c8a14f4?/068
- **智慧城市体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/55d4f591f15c896653896a029fc162d87c8a14f4?/pxm
- **城乡公共服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/55d4f591f15c896653896a029fc162d87c8a14f4?/423/?txe
- **安全出行教育的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/55d4f591f15c896653896a029fc162d87c8a14f4?/478=324
- **租房信息服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/55d4f591f15c896653896a029fc162d87c8a14f4?/pww=909
- **社区健康讲座的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0b81f6d9862cbe9dfbb62b4fb59d53de0365fca6?/030
- **职业技能学习的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0b81f6d9862cbe9dfbb62b4fb59d53de0365fca6?/iir
- **城市宠物友好空间的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/0b81f6d9862cbe9dfbb62b4fb59d53de0365fca6?/792/?ckf
- **社区故事采集的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/0b81f6d9862cbe9dfbb62b4fb59d53de0365fca6?/024=466
- **家庭健康管理的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0b81f6d9862cbe9dfbb62b4fb59d53de0365fca6?/wjt=206
- **公共空间安全的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ca633171be8d5b3e0449c9aabffba8e07c52daf9?/873
- **校园社团活动的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ca633171be8d5b3e0449c9aabffba8e07c52daf9?/ssu
- **数字创意课程的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ca633171be8d5b3e0449c9aabffba8e07c52daf9?/768/?ogo
- **亲子阅读活动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ca633171be8d5b3e0449c9aabffba8e07c52daf9?/283=624
- **网络信息辨识的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/ca633171be8d5b3e0449c9aabffba8e07c52daf9?/smu=047
- **休闲运动入门的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d86060ff7070333ac4f2c006ac53915d2ba72f87?/733
- **无障碍信息设计的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/d86060ff7070333ac4f2c006ac53915d2ba72f87?/wtj
- **乡村电商实践的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d86060ff7070333ac4f2c006ac53915d2ba72f87?/653/?vds
- **城市体育设施的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d86060ff7070333ac4f2c006ac53915d2ba72f87?/237=276
- **科技馆参观体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d86060ff7070333ac4f2c006ac53915d2ba72f87?/mcy=553
- **公交站点体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/674c4f3dd9b2704720366aaabe2ecad3f072be42?/440
- **公交无障碍服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/674c4f3dd9b2704720366aaabe2ecad3f072be42?/cof
- **街区更新实践的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/674c4f3dd9b2704720366aaabe2ecad3f072be42?/708/?jws
- **社区便利生活的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/674c4f3dd9b2704720366aaabe2ecad3f072be42?/006=863
- **个人时间管理从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/674c4f3dd9b2704720366aaabe2ecad3f072be42?/mgh=217
- **科学信息获取的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1a1d21ef4555711e2ac7532221bb327bc40998de?/247
- **城市公共标识的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1a1d21ef4555711e2ac7532221bb327bc40998de?/zeq
- **健康饮水科普的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/1a1d21ef4555711e2ac7532221bb327bc40998de?/191/?fnk
- **生活服务数字化的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1a1d21ef4555711e2ac7532221bb327bc40998de?/835=712
- **社区家校合作的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/1a1d21ef4555711e2ac7532221bb327bc40998de?/knf=781
- **网络安全教育的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/42bf4dce5792eda046077f560b2fdf81cc727188?/574
- **运动安全知识的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/42bf4dce5792eda046077f560b2fdf81cc727188?/cti
- **智能家居应用的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/42bf4dce5792eda046077f560b2fdf81cc727188?/975/?drc
- **公共空间导览的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/42bf4dce5792eda046077f560b2fdf81cc727188?/637=802
- **城市空气科普的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/42bf4dce5792eda046077f560b2fdf81cc727188?/jer=448
- **社区商业活力的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3f95a904d2fa539dd0e19107ac48a2e04ec15fa0?/497
- **环境教育课程的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/3f95a904d2fa539dd0e19107ac48a2e04ec15fa0?/sqo
- **家庭理财科普的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3f95a904d2fa539dd0e19107ac48a2e04ec15fa0?/052/?mvd
- **老年数字阅读的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3f95a904d2fa539dd0e19107ac48a2e04ec15fa0?/124=349
- **通勤路线规划的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/3f95a904d2fa539dd0e19107ac48a2e04ec15fa0?/gqn=222
- **城市步行友好的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/cd299f5a799c2b3a94cef0266ac9b08b3f86f40d?/410
- **公共场馆服务的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/cd299f5a799c2b3a94cef0266ac9b08b3f86f40d?/mgb
- **街道综合服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/cd299f5a799c2b3a94cef0266ac9b08b3f86f40d?/280/?hnl
- **开放数据应用的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/cd299f5a799c2b3a94cef0266ac9b08b3f86f40d?/144=263
- **社区休闲设施的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/cd299f5a799c2b3a94cef0266ac9b08b3f86f40d?/xob=570
- **信息无障碍体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c11daf5a77949853ff0b60fa04d186baa01cc44c?/102
- **农村环境治理的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c11daf5a77949853ff0b60fa04d186baa01cc44c?/zeo
- **社区生活指南的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/c11daf5a77949853ff0b60fa04d186baa01cc44c?/662/?phs
- **家庭健康科普的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/c11daf5a77949853ff0b60fa04d186baa01cc44c?/838=866
- **本地消费场景的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c11daf5a77949853ff0b60fa04d186baa01cc44c?/msq=924
- **便民维修服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/0ee0e1fecee69b96a7f53aa2435c980b6029c2c6?/703
- **城市夜间照明的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0ee0e1fecee69b96a7f53aa2435c980b6029c2c6?/fuk
- **租房信息服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0ee0e1fecee69b96a7f53aa2435c980b6029c2c6?/034/?efq
- **城市人文观察的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0ee0e1fecee69b96a7f53aa2435c980b6029c2c6?/452=201
- **城市文明出行的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0ee0e1fecee69b96a7f53aa2435c980b6029c2c6?/pry=337

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  网信彩票登录大厅等*  
*仅供参考，不构成投资建议*
