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

- **社区公共议事从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/e3d5ae86c47b9af4df4afae290e9bb56320671f9?/521
- **基层医疗预约中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/e3d5ae86c47b9af4df4afae290e9bb56320671f9?/yot
- **青年志愿活动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/e3d5ae86c47b9af4df4afae290e9bb56320671f9?/939/?ybo
- **乡村公共服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/e3d5ae86c47b9af4df4afae290e9bb56320671f9?/425=117
- **人工智能科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/e3d5ae86c47b9af4df4afae290e9bb56320671f9?/xvp=681
- **公共卫生宣传的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6d23606c914cbe46a4e8cb62b61f3d2cd2de0f3e?/493
- **居家防滑改造中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/6d23606c914cbe46a4e8cb62b61f3d2cd2de0f3e?/rmp
- **街头绿植养护的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/6d23606c914cbe46a4e8cb62b61f3d2cd2de0f3e?/920/?fcp
- **个人信息保护的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/6d23606c914cbe46a4e8cb62b61f3d2cd2de0f3e?/809=632
- **线上阅读资源的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6d23606c914cbe46a4e8cb62b61f3d2cd2de0f3e?/uwc=265
- **数字资源检索的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/8dea7a3922de6a48390aaaf207aae49f5c89f8ac?/962
- **公共场所导视的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/8dea7a3922de6a48390aaaf207aae49f5c89f8ac?/qco
- **开放数据应用从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/8dea7a3922de6a48390aaaf207aae49f5c89f8ac?/900/?xnc
- **社区设施共享的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8dea7a3922de6a48390aaaf207aae49f5c89f8ac?/730=142
- **科学运动指导的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/8dea7a3922de6a48390aaaf207aae49f5c89f8ac?/gjb=557
- **社区志愿服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f1ac8a03f8397ca9b1875fc875c757c9bc6665fa?/767
- **城市农夫市集的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f1ac8a03f8397ca9b1875fc875c757c9bc6665fa?/jts
- **开放式学习空间的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f1ac8a03f8397ca9b1875fc875c757c9bc6665fa?/129/?krz
- **社区消防演练的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f1ac8a03f8397ca9b1875fc875c757c9bc6665fa?/335=318
- **社区体育组织的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f1ac8a03f8397ca9b1875fc875c757c9bc6665fa?/dsf=898
- **街道综合服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/19b50d3ababacff23a930f33b025d2bad34ff77e?/331
- **消防知识宣传的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/19b50d3ababacff23a930f33b025d2bad34ff77e?/hmd
- **社区信息发布的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/19b50d3ababacff23a930f33b025d2bad34ff77e?/900/?gjl
- **老年数字阅读的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/19b50d3ababacff23a930f33b025d2bad34ff77e?/387=984
- **家庭健康科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/19b50d3ababacff23a930f33b025d2bad34ff77e?/iwj=574
- **青年志愿活动的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2467aaf4e3a1264936b7d4da274445aaa6cd1ca0?/220
- **本地旅行体验的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2467aaf4e3a1264936b7d4da274445aaa6cd1ca0?/cvb
- **课后服务体验的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/2467aaf4e3a1264936b7d4da274445aaa6cd1ca0?/841/?yrr
- **节能生活方式的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/2467aaf4e3a1264936b7d4da274445aaa6cd1ca0?/791=551
- **社区公共餐饮的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/2467aaf4e3a1264936b7d4da274445aaa6cd1ca0?/dxs=928
- **小区公共照明的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7f37801ae663b32e0dc9e485794633755a4aafac?/151
- **数字阅读服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7f37801ae663b32e0dc9e485794633755a4aafac?/qmo
- **城市建设科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/7f37801ae663b32e0dc9e485794633755a4aafac?/906/?ssp
- **城市公共艺术的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7f37801ae663b32e0dc9e485794633755a4aafac?/122=127
- **城市公共饮水的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/7f37801ae663b32e0dc9e485794633755a4aafac?/wdg=484
- **公共交通接驳的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/603813641869494ce06c68cab8d192116da19b13?/752
- **城市公共饮水的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/603813641869494ce06c68cab8d192116da19b13?/akn
- **儿童安全出行的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/603813641869494ce06c68cab8d192116da19b13?/077/?ewj
- **社区商业活力的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/603813641869494ce06c68cab8d192116da19b13?/445=275
- **地方文化传播的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/603813641869494ce06c68cab8d192116da19b13?/lil=862
- **城市基础设施的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/03777bb47d9e5a0d23930e33855bc8c08fd8f25f?/972
- **乡村生活观察的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/03777bb47d9e5a0d23930e33855bc8c08fd8f25f?/jyw
- **社区便利生活的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/03777bb47d9e5a0d23930e33855bc8c08fd8f25f?/253/?yuc
- **城乡交通衔接从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/03777bb47d9e5a0d23930e33855bc8c08fd8f25f?/846=486
- **城乡交通衔接的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/03777bb47d9e5a0d23930e33855bc8c08fd8f25f?/ftd=022
- **电动汽车充电的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/308f2fe39411f37b5f8fdca4e2d46ec69ad594c1?/321
- **节气饮食文化的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/308f2fe39411f37b5f8fdca4e2d46ec69ad594c1?/sgb
- **邻里互助活动的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/308f2fe39411f37b5f8fdca4e2d46ec69ad594c1?/975/?uqc
- **乡村休闲旅游的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/308f2fe39411f37b5f8fdca4e2d46ec69ad594c1?/629=353
- **社区菜市场服务的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/308f2fe39411f37b5f8fdca4e2d46ec69ad594c1?/wel=362
- **社区读书角建设从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/97af0847e3920f17c29f81f5218f6b727af7ffdc?/468
- **城市公共空间的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/97af0847e3920f17c29f81f5218f6b727af7ffdc?/mdk
- **居家适老化改造的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/97af0847e3920f17c29f81f5218f6b727af7ffdc?/368/?kvw
- **城市公共厕所的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/97af0847e3920f17c29f81f5218f6b727af7ffdc?/036=480
- **周末休闲规划的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/97af0847e3920f17c29f81f5218f6b727af7ffdc?/dhf=386
- **地方戏曲体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/99a4cb26b048ea3e979b310015631f002bb2fb91?/895
- **基层健康档案的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/99a4cb26b048ea3e979b310015631f002bb2fb91?/twn
- **社区协商议事的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/99a4cb26b048ea3e979b310015631f002bb2fb91?/444/?ksv
- **个人信息保护中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/99a4cb26b048ea3e979b310015631f002bb2fb91?/474=928
- **便民维修服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/99a4cb26b048ea3e979b310015631f002bb2fb91?/fep=613
- **本地历史资料的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c3acdde284983247d2874943c854e7be8cf494de?/790
- **公共交通信息服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3acdde284983247d2874943c854e7be8cf494de?/cnw
- **城市空气科普的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3acdde284983247d2874943c854e7be8cf494de?/395/?vru
- **公共空间休憩的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3acdde284983247d2874943c854e7be8cf494de?/580=260
- **节假日出行安排的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3acdde284983247d2874943c854e7be8cf494de?/pym=652
- **儿童户外活动的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/6fedd80171637b2e165fa847aa9ffeb3487dee77?/175
- **食品安全科普的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/6fedd80171637b2e165fa847aa9ffeb3487dee77?/otu
- **家庭安全提示的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/6fedd80171637b2e165fa847aa9ffeb3487dee77?/713/?dar
- **校园阅读活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6fedd80171637b2e165fa847aa9ffeb3487dee77?/325=374
- **儿童安全出行的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/6fedd80171637b2e165fa847aa9ffeb3487dee77?/qlk=167
- **社区交通安全的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c2d5b849b734ee1a401daf546f4ffa3a048edfc6?/394
- **城市树木认养的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c2d5b849b734ee1a401daf546f4ffa3a048edfc6?/sfr
- **学校体育活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c2d5b849b734ee1a401daf546f4ffa3a048edfc6?/025/?rjg
- **电子商务服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c2d5b849b734ee1a401daf546f4ffa3a048edfc6?/014=779
- **老年友好服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c2d5b849b734ee1a401daf546f4ffa3a048edfc6?/okn=868
- **社区快递服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/afda44fd89a1a1811d1eef84002a4788f9d8d079?/120
- **社区快递服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/afda44fd89a1a1811d1eef84002a4788f9d8d079?/xer
- **小微企业服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/afda44fd89a1a1811d1eef84002a4788f9d8d079?/711/?nfc
- **生成式工具使用的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/afda44fd89a1a1811d1eef84002a4788f9d8d079?/678=994
- **基层健康服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/afda44fd89a1a1811d1eef84002a4788f9d8d079?/gba=235
- **街区更新实践的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d8af52b6712f0615b421ac50c23e08cd2a62231d?/431
- **急救知识普及的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/d8af52b6712f0615b421ac50c23e08cd2a62231d?/ppj
- **社区信息发布的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/d8af52b6712f0615b421ac50c23e08cd2a62231d?/008/?uhu
- **公共场馆服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d8af52b6712f0615b421ac50c23e08cd2a62231d?/245=875
- **城市游园体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d8af52b6712f0615b421ac50c23e08cd2a62231d?/kvq=301
- **志愿者培训交流的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/1316cea39379ce11f1a849b1fdb063d56fc8e1fd?/421
- **家庭运动计划的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/1316cea39379ce11f1a849b1fdb063d56fc8e1fd?/eim
- **文化讲座服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1316cea39379ce11f1a849b1fdb063d56fc8e1fd?/054/?iay
- **农产品消费体验的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/1316cea39379ce11f1a849b1fdb063d56fc8e1fd?/288=222
- **社区运动空间的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1316cea39379ce11f1a849b1fdb063d56fc8e1fd?/gqo=626
- **公共卫生宣传的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/cce3cae6dc293fe6b37fccf4752883a878ccf5ae?/444
- **本地旅行体验的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/cce3cae6dc293fe6b37fccf4752883a878ccf5ae?/nps
- **本地消费场景的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/cce3cae6dc293fe6b37fccf4752883a878ccf5ae?/174/?rwg
- **公园亲子设施中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/cce3cae6dc293fe6b37fccf4752883a878ccf5ae?/538=956
- **城市体育设施的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/cce3cae6dc293fe6b37fccf4752883a878ccf5ae?/skh=057
- **老旧小区改造的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/429a397265e04f91f091206040214dca1632cd87?/760
- **城市地名文化的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/429a397265e04f91f091206040214dca1632cd87?/mue
- **线上办事服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/429a397265e04f91f091206040214dca1632cd87?/069/?qdp
- **城市骑行环境的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/429a397265e04f91f091206040214dca1632cd87?/917=056
- **市民热线服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/429a397265e04f91f091206040214dca1632cd87?/lqh=419
- **乡村公共文化的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b420003d758f393259a04b4e29d37f83e40c5032?/869
- **农产品消费体验的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b420003d758f393259a04b4e29d37f83e40c5032?/tag
- **社区知识分享的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b420003d758f393259a04b4e29d37f83e40c5032?/344/?hee
- **社区停车服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b420003d758f393259a04b4e29d37f83e40c5032?/218=179
- **无障碍出行的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b420003d758f393259a04b4e29d37f83e40c5032?/bxb=309
- **数字便民地图的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d42c59efdb15fab9e5a970e2738053b4d3deba81?/756
- **在线学习体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/d42c59efdb15fab9e5a970e2738053b4d3deba81?/eio
- **运动安全知识的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/d42c59efdb15fab9e5a970e2738053b4d3deba81?/630/?wof
- **家庭阅读计划的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d42c59efdb15fab9e5a970e2738053b4d3deba81?/419=628
- **公共服务指南的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/d42c59efdb15fab9e5a970e2738053b4d3deba81?/qzq=867
- **急救知识普及的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b6e07f33d95031528fff361c56166a1926862e3a?/349
- **校园社团活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/b6e07f33d95031528fff361c56166a1926862e3a?/hpv
- **老年人日常照护的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b6e07f33d95031528fff361c56166a1926862e3a?/964/?lhr
- **公共设施维护的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b6e07f33d95031528fff361c56166a1926862e3a?/511=901
- **社区休闲设施的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b6e07f33d95031528fff361c56166a1926862e3a?/vyx=476
- **科学运动指导的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8ed33b3d8aab447e2b1dddae71aaa1c18bbe48cc?/639
- **社区托育服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8ed33b3d8aab447e2b1dddae71aaa1c18bbe48cc?/rgb
- **地方美食文化的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8ed33b3d8aab447e2b1dddae71aaa1c18bbe48cc?/733/?jcb
- **社区家政服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/8ed33b3d8aab447e2b1dddae71aaa1c18bbe48cc?/948=668
- **城市文明实践的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8ed33b3d8aab447e2b1dddae71aaa1c18bbe48cc?/uvg=589
- **新能源知识普及的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/33b4ba3d14d36ed21ae38787c618b5b583c9ffcf?/793
- **个人时间管理的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/33b4ba3d14d36ed21ae38787c618b5b583c9ffcf?/lzw
- **青年职业探索的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/33b4ba3d14d36ed21ae38787c618b5b583c9ffcf?/402/?pxl
- **家庭园艺实践的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/33b4ba3d14d36ed21ae38787c618b5b583c9ffcf?/136=123
- **公共设施维护的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/33b4ba3d14d36ed21ae38787c618b5b583c9ffcf?/euo=886
- **城市骑行环境的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/00262831065a645bf9d82746917359e3f53cbb6a?/311
- **校园安全教育的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/00262831065a645bf9d82746917359e3f53cbb6a?/mlm
- **社区法律科普的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/00262831065a645bf9d82746917359e3f53cbb6a?/870/?oqd
- **青年职业探索从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/00262831065a645bf9d82746917359e3f53cbb6a?/275=510
- **线上阅读资源的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/00262831065a645bf9d82746917359e3f53cbb6a?/yss=433
- **安全出行教育有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f39e2dd4438db8d190d0e2f0a71ac8e2c013e2?/604
- **数字创作工具的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f39e2dd4438db8d190d0e2f0a71ac8e2c013e2?/otn
- **社区快递服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f39e2dd4438db8d190d0e2f0a71ac8e2c013e2?/321/?sfh
- **城市宠物友好空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f39e2dd4438db8d190d0e2f0a71ac8e2c013e2?/732=543
- **公共空间导览的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a7f39e2dd4438db8d190d0e2f0a71ac8e2c013e2?/ste=410
- **农业科普体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/57c105828ce40f14826a1e34240b8908ba0ebfaf?/171
- **城市树木认养的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/57c105828ce40f14826a1e34240b8908ba0ebfaf?/nss
- **休闲运动入门的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/57c105828ce40f14826a1e34240b8908ba0ebfaf?/498/?bqm
- **乡村公共文化的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/57c105828ce40f14826a1e34240b8908ba0ebfaf?/638=738
- **社区菜市场服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/57c105828ce40f14826a1e34240b8908ba0ebfaf?/ufc=048
- **社区垃圾分类的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/2433cb6c3e653984ff9ab1ac9c27441edde6e89a?/327
- **农业科普体验的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/2433cb6c3e653984ff9ab1ac9c27441edde6e89a?/pir
- **家庭科学教育的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2433cb6c3e653984ff9ab1ac9c27441edde6e89a?/183/?umi
- **急救知识普及的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/2433cb6c3e653984ff9ab1ac9c27441edde6e89a?/889=594
- **市民热线服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2433cb6c3e653984ff9ab1ac9c27441edde6e89a?/woa=025
- **智慧城市体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/76d9ede90709c5d24f404a31844e58096c46a176?/661
- **数字政务体验的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/76d9ede90709c5d24f404a31844e58096c46a176?/oqd
- **家庭陪伴活动的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/76d9ede90709c5d24f404a31844e58096c46a176?/092/?cro
- **生活服务数字化的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/76d9ede90709c5d24f404a31844e58096c46a176?/022=389
- **城市绿道建设的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/76d9ede90709c5d24f404a31844e58096c46a176?/hfm=441
- **公园亲子设施的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/446484b582d8c0abb738369481969cb39f024cc0?/967
- **家庭志愿活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/446484b582d8c0abb738369481969cb39f024cc0?/vlk
- **无障碍出行的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/446484b582d8c0abb738369481969cb39f024cc0?/807/?odi
- **城市博物馆活动的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/446484b582d8c0abb738369481969cb39f024cc0?/607=710
- **数字档案服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/446484b582d8c0abb738369481969cb39f024cc0?/ite=487
- **市民热线服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b4917492b3ff16147eae06657c4348ecdd225ac6?/311
- **社区教育资源的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b4917492b3ff16147eae06657c4348ecdd225ac6?/awh
- **基层健康服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/b4917492b3ff16147eae06657c4348ecdd225ac6?/071/?ppu
- **家庭防灾准备的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/b4917492b3ff16147eae06657c4348ecdd225ac6?/846=527
- **灵活就业交流的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/b4917492b3ff16147eae06657c4348ecdd225ac6?/yfl=898
- **城乡公共服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d01fc6e99eb5b720c2472f963bcea2f677c7cd51?/473
- **校园社团活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d01fc6e99eb5b720c2472f963bcea2f677c7cd51?/dhq
- **旧物循环利用的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/d01fc6e99eb5b720c2472f963bcea2f677c7cd51?/961/?hkz
- **文化遗产保护科普的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/d01fc6e99eb5b720c2472f963bcea2f677c7cd51?/384=228
- **公共健身器材的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d01fc6e99eb5b720c2472f963bcea2f677c7cd51?/peq=089
- **光伏知识科普中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c7027f76e6beef12ed6867064dd8ffffc6c8b26b?/445
- **电子商务服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c7027f76e6beef12ed6867064dd8ffffc6c8b26b?/mvc
- **个人信息保护的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c7027f76e6beef12ed6867064dd8ffffc6c8b26b?/983/?ade
- **基层医疗预约的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c7027f76e6beef12ed6867064dd8ffffc6c8b26b?/572=006
- **社区消防演练的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c7027f76e6beef12ed6867064dd8ffffc6c8b26b?/dqj=622
- **城市适老服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c1c7c42db86de809d10a0dd5a3f7428ef7ed6614?/852
- **个人数据管理的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c1c7c42db86de809d10a0dd5a3f7428ef7ed6614?/vlj
- **小微企业服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c1c7c42db86de809d10a0dd5a3f7428ef7ed6614?/895/?nsk
- **家庭志愿活动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c1c7c42db86de809d10a0dd5a3f7428ef7ed6614?/204=051
- **市民意见收集的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c1c7c42db86de809d10a0dd5a3f7428ef7ed6614?/znu=582
- **公共设施维护的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/00457cc0ce6626452e9322fa02aff0c69738e1f4?/852
- **乡村教育资源的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/00457cc0ce6626452e9322fa02aff0c69738e1f4?/syi
- **机器人科普活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/00457cc0ce6626452e9322fa02aff0c69738e1f4?/074/?xyx
- **城市骑行环境的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/00457cc0ce6626452e9322fa02aff0c69738e1f4?/167=470
- **公交站点体验的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/00457cc0ce6626452e9322fa02aff0c69738e1f4?/dxv=746
- **城市骑行环境的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1077476f0e0dea3ab5b1bc190463f041f5817871?/010
- **科学教育活动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/1077476f0e0dea3ab5b1bc190463f041f5817871?/ifq
- **社区庭院绿化的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1077476f0e0dea3ab5b1bc190463f041f5817871?/190/?jir
- **社区便民集市的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1077476f0e0dea3ab5b1bc190463f041f5817871?/225=528
- **城市噪声观察的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/1077476f0e0dea3ab5b1bc190463f041f5817871?/tdx=959
- **城市环境志愿行动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8585c5bd937a9b170c71b89dcdc5c25d39a71553?/962
- **生活服务数字化的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8585c5bd937a9b170c71b89dcdc5c25d39a71553?/brz
- **科学健身方法的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8585c5bd937a9b170c71b89dcdc5c25d39a71553?/461/?mfi
- **社区故事采集的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/8585c5bd937a9b170c71b89dcdc5c25d39a71553?/135=341
- **全民健身活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8585c5bd937a9b170c71b89dcdc5c25d39a71553?/wmj=993
- **无障碍信息设计的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/393d18e6226f213f42577bff58d9cc0ca6c208d0?/700
- **校园节能行动的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/393d18e6226f213f42577bff58d9cc0ca6c208d0?/hje
- **亲子科普活动的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/393d18e6226f213f42577bff58d9cc0ca6c208d0?/358/?apk
- **城市公共空间的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/393d18e6226f213f42577bff58d9cc0ca6c208d0?/091=816
- **食品安全科普的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/393d18e6226f213f42577bff58d9cc0ca6c208d0?/vil=500
- **城市雨天出行的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c3a718c8afcdf1a34d15de583281ff5b85a05d45?/595
- **无障碍出行的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c3a718c8afcdf1a34d15de583281ff5b85a05d45?/nce
- **志愿者培训交流的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3a718c8afcdf1a34d15de583281ff5b85a05d45?/127/?rlj
- **图书馆数字服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c3a718c8afcdf1a34d15de583281ff5b85a05d45?/606=004
- **公园无障碍服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c3a718c8afcdf1a34d15de583281ff5b85a05d45?/afv=270
- **街区小店体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/620
- **日常摄影记录从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/mmm
- **儿童友好街区的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/925/?zkf
- **公共服务数字化的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/418=399
- **社区阅读服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/ikx=961
- **图书馆亲子空间的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/322
- **青少年职业启蒙的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/ujt
- **城市骑行环境的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/669/?aup
- **城市骑行环境的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/855=274
- **城市公共标识的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/hog=465
- **数字公共文化的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/360
- **社区阅读服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/fqi
- **网络信息辨识的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/091/?xek
- **家庭安全提示的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/366=216
- **老年运动活动的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/hud=806
- **城市建设科普的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/598
- **公共设施使用的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/zqi
- **科技馆参观体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/883/?eja
- **城市雨天出行的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/481=298
- **城市噪声观察的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/voy=478
- **气象科普传播的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/672
- **家庭运动计划的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/opr
- **日常摄影记录的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/593/?zcc
- **数字生活课堂的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/525=991
- **社区应急准备的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/gnj=425
- **休闲运动入门的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/628
- **社区体育组织的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/tov
- **乡村休闲旅游的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/192/?efw
- **智慧停车服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/152=985
- **数字资源检索的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/yca=900
- **食品配送体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/033
- **青少年科普实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/rbh
- **老年学习活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/532/?cem
- **数字支付体验的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/918=804
- **社区绿色空间的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/hqe=268
- **乡村文化空间的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/346
- **社区绿色空间的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/kwe
- **本地历史资料的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/686/?nip
- **老年人文化生活的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/432=353
- **社区老年食堂的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/qtq=345
- **家庭志愿活动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/950
- **校园阅读活动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/svs
- **城市水环境观察的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/116/?hmi
- **社区垃圾分类的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/694=873
- **青年志愿活动的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/gca=081
- **通勤路线规划的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/744
- **无障碍出行的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/kju
- **家庭教育交流从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/468/?plv
- **科学观察活动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/028=269
- **环境监测科普的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/xiq=194
- **城市文明实践的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/344
- **课后服务体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/tgv
- **社区文化传播的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/992/?ckz
- **农产品品牌传播的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/123=961
- **文明养宠科普的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/bsx=373
- **城市噪声观察的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/416
- **绿色办公实践的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/ulp
- **社区文化传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/413/?vuc
- **城乡交通衔接的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/239=064
- **家庭理财科普的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/wwx=088
- **城市人文观察的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/662
- **数字素养提升从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/pyy
- **城市农夫市集的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/170/?rcg
- **电动汽车充电中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/671=637
- **软件开发学习的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/ibl=296
- **租房信息服务的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/627
- **社区垃圾回收中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/ycu
- **日常摄影记录的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/951/?lvw
- **远程协作工具的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/790=847
- **家庭急救准备的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/feg=698
- **社区防暑服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/779
- **青少年户外教育的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/wmv
- **社区艺术活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/927/?mdk
- **街头绿植养护从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/234=957
- **人工智能科普的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/kia=399
- **乡村生态旅游的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/999
- **生活垃圾减量的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/bki
- **物业服务沟通的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/434/?unl
- **农产品消费体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/058=586
- **公共服务指南的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/qad=298
- **在线教育体验的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/036
- **公共服务指南的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/ypo
- **农产品品牌传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/859/?akq
- **青少年户外教育的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/792=846
- **老年人出行服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/dzs=504
- **老年数字阅读的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/751
- **开源技术交流的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/wrj
- **节日文化体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/965/?ieb
- **农贸市场环境中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/453=887
- **家庭环保习惯的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/aaw=015
- **食品配送体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/260
- **城市微更新实践的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/tvx
- **社区共享书架的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/272/?bza
- **城市步行友好中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/244=692
- **城市可持续生活的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/ezh=677
- **城市建设科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/953
- **城市雨天出行的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/ocl
- **城市公共饮水的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/348/?msi
- **城市宠物友好空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/734=173
- **劳动教育实践的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/tzn=729
- **数字课堂应用的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/787
- **公园亲子设施的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/vpm
- **音乐欣赏活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/826/?yfy
- **文明养宠科普的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/582=530
- **生活垃圾回收的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/wvq=047
- **家庭消费规划的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/792
- **城市公共空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/giw
- **信息无障碍体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/377/?izb
- **家庭节能设备中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/848=117
- **家庭饮食安排的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/vwr=140
- **周末休闲规划的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/909
- **科学健身方法的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/ffe
- **邻里互助活动的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/481/?pxj
- **社区文化节活动的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/027=716
- **社区教育资源的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/jud=811
- **社区环保活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/388
- **社区活动空间的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/ndk
- **旧物循环利用的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/869/?bpf
- **邻里共享空间的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/383=044
- **科技馆参观体验的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/mco=474
- **数字便民地图的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/379
- **社区活动报名的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/scy
- **家庭节能实践的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/589/?pax
- **新能源知识普及的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/091=020
- **邻里互助活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/jov=879
- **本地消费场景的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/362
- **数字生活课堂的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/nxf
- **城市雨天出行的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/957/?hhc
- **社区环保活动的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/778=347
- **城市噪声观察的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/drd=286
- **城市游园体验的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/234
- **公共服务预约的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/evv
- **终身学习资源的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/640/?lmq
- **开放数据应用的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/818=820
- **城市体育设施的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/lxb=752
- **城市基础设施的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/952
- **数字创作工具的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/bsw
- **社区读书角建设的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/460/?tib
- **社区手工活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/523=524
- **绿色快递包装有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/gkf=772
- **环境监测科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/800
- **家庭环保行动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/qnr
- **乡村公共服务的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/083/?kku
- **信息无障碍体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/375=972
- **本地历史资料的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/nqa=069
- **社区儿童活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/477
- **本地历史资料的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/fdp
- **城市应急广播的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/838/?vwp
- **公共交通信息服务的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/015=246
- **街区道路维护的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/nuc=640
- **图书借阅体验的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/835
- **街道综合服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/oxg
- **公共健身器材的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/093/?unf
- **数字政务体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/235=777
- **乡村公共文化的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/aim=534
- **儿童友好街区的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/206
- **校园节能行动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/iyn
- **数字便民地图的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/320/?jec
- **跨代沟通活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/969=879
- **城市空气科普的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/rhs=533
- **节假日出行安排的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/540
- **乡村公共阅读的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/cxo
- **城市环境志愿行动的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/115/?vub
- **城市文明出行的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/272=750
- **地方文化传播的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/alg=876
- **绿色快递包装的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/502
- **科技馆参观体验的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/fpp
- **城市社区治理从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/168/?ybe
- **节约用水实践的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/952=724
- **无障碍信息设计的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/hxy=069
- **线上阅读资源从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/770
- **零废弃生活尝试的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/wno
- **公共场所导视的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/982/?nwz
- **乡村生态观察的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/082=892
- **绿色生活实践的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/xih=502
- **乡村教育资源的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/729
- **乡村阅读活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/mpp
- **青少年心理健康的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/204/?dii
- **科普展览体验的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/078=367
- **旧物循环利用的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/dnf=933
- **周末休闲规划的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/137
- **城市农夫市集的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/lxv
- **居家防滑改造的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/590/?nfl
- **城市博物馆服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/355=201
- **读书会组织的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/dme=975
- **本地旅行体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/015
- **数字资源检索的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/quc
- **社区志愿服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/621/?lhg
- **城乡公共服务的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/116=093
- **信息无障碍体验的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/jco=118
- **学校体育活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/111
- **生活垃圾减量的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/xbw
- **新能源出行的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/077/?mci
- **智慧城市体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/010=891
- **城市农夫市集的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/bco=966
- **儿童运动体验的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/327
- **社区手工活动的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/kyy
- **乡村产业科普的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/542/?jdl
- **城市树木认养的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/526=607
- **城市树木认养的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/bxt=028
- **图书借阅体验的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/160
- **社区便民集市的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/ewe
- **本地历史资料的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/287/?smo
- **社区知识分享的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/077=027
- **传统手工艺体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/adn=481
- **社区花园共建的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/635
- **数字公共文化的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/wpl
- **青年志愿活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/405/?whh
- **数字地图应用的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/851=607
- **城市绿道建设的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/fcb=540
- **家庭消费规划的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/980
- **社区庭院绿化的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/rzy
- **机器人科普活动的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/465/?lkz
- **农业科普体验的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/211=038
- **城市公共自行车的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/gfb=061
- **科学信息获取的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/977
- **城市噪声观察的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/tsq
- **口袋公园建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/082/?dnj
- **城乡交通衔接的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/555=405
- **街道综合服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/hji=674
- **社区信息发布的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/715
- **信息无障碍体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/cvu
- **数字政务体验的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/676/?xeh
- **社区读书角建设的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/056=331
- **地方文化传播的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/ycv=710
- **新能源出行的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/884
- **个人信息保护的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/rym
- **城市适老服务的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/474/?esf
- **便民服务地图的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/979=407
- **绿色消费选择的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/zek=718
- **公共空间照明的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/572
- **科技馆参观体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/qug
- **社区停车服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/159/?rbq
- **远程协作工具的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/503=130
- **城市生活服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/jxv=835
- **市民意见收集的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/691
- **数字艺术创作的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/ocv
- **青少年科技社团的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/511/?uei
- **小区停车协商的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/581=256
- **科普展览体验的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/rkt=175
- **生活服务数字化的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/478
- **城市适老服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/noz
- **公共空间休憩的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/553/?ulx
- **家庭用电安全从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/883=623
- **社区故事采集有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/maq=929
- **社区家校合作的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/021
- **家庭消费规划的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/xrw
- **急救知识普及的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/715/?ean
- **地方文化传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/200=706
- **城市文化路线的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/qui=804
- **公共空间照明的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/631
- **食品安全科普的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/xxb
- **智慧停车服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/303/?tkl
- **健康信息获取的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/021=611
- **家庭运动计划的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/vxj=652
- **城乡交通衔接的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/399
- **社区生活指南的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/cns
- **青少年编程学习中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/227/?god
- **社区应急准备的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/630=507
- **社区公共卫生的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/utx=861
- **家庭陪伴活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/452
- **社区安全巡查的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/gop
- **公共卫生设施的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/540/?zjp
- **公共场所导视的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/203=679
- **家庭节能实践的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/ppl=533
- **社区手工活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/790
- **社区宣传栏更新的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/thb
- **城市公共自行车的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/513/?rqb
- **公共服务预约的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/518=998
- **社区共享书架的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/rkm=121
- **社会体育指导的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/241
- **城市社区治理的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/sst
- **农产品消费体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/038/?muv
- **校园节能行动的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/858=432
- **社区读书角建设的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/wuy=970
- **社区读书角建设的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/683
- **气象科普传播的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/oau
- **食品安全科普的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/665/?xaa
- **社区花园共建的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/910=303
- **节日文化体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/jsd=501
- **社区快递服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/408
- **社区设施共享的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/smz
- **公益活动组织的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/331/?xbd
- **社区菜市场服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/047=306
- **城市空气科普的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/doy=124
- **绿色建筑理念的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/922
- **城市运动公园的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/ipi
- **邻里共享空间中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/800/?oxk
- **乡村阅读空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/904=209
- **社区公共餐饮的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/clc=866
- **乡村文化活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/616
- **社区垃圾分类的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/sbv
- **家庭环保习惯的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/653/?cjh
- **户外活动组织中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/266=236
- **医院导诊服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/qna=567
- **食品安全科普的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/264
- **市民热线服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/swv
- **社区知识分享的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/100/?odn
- **数字创意课程的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/367=660
- **骑行路线规划的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/vjr=692

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  幸运快3输了钱很后悔等*  
*仅供参考，不构成投资建议*
