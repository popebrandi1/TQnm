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

- **社区活动报名的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/659cc908a53fd4b059dda0f2b214765355836946?/178
- **智慧停车服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/659cc908a53fd4b059dda0f2b214765355836946?/yga
- **传统手工艺体验的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/659cc908a53fd4b059dda0f2b214765355836946?/365/?zcj
- **软件开发学习的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/659cc908a53fd4b059dda0f2b214765355836946?/748=251
- **数字档案服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/659cc908a53fd4b059dda0f2b214765355836946?/vdy=983
- **无障碍出行的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/da7fc95952278054423b5e1548ebb27bedc16dd6?/423
- **数字阅读服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/da7fc95952278054423b5e1548ebb27bedc16dd6?/bre
- **社区商业活力的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/da7fc95952278054423b5e1548ebb27bedc16dd6?/529/?dmk
- **城市环境志愿行动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/da7fc95952278054423b5e1548ebb27bedc16dd6?/627=736
- **城市步行友好的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/da7fc95952278054423b5e1548ebb27bedc16dd6?/uzx=206
- **校园安全教育的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/00cf86b293212a293b68c9538bcf053cf7020996?/049
- **公共设施维护的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/00cf86b293212a293b68c9538bcf053cf7020996?/cxy
- **老年友好服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/00cf86b293212a293b68c9538bcf053cf7020996?/741/?jfw
- **数字创意课程的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/00cf86b293212a293b68c9538bcf053cf7020996?/779=754
- **节能生活方式的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/00cf86b293212a293b68c9538bcf053cf7020996?/iit=971
- **学校体育活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/1ed758e51ba69ae8d0282f0b00186a4a93e500e9?/998
- **文化讲座服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/1ed758e51ba69ae8d0282f0b00186a4a93e500e9?/lyl
- **社区托育服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1ed758e51ba69ae8d0282f0b00186a4a93e500e9?/551/?wyw
- **城市微更新实践的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/1ed758e51ba69ae8d0282f0b00186a4a93e500e9?/276=897
- **生活垃圾减量的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1ed758e51ba69ae8d0282f0b00186a4a93e500e9?/pmm=632
- **本地旅行体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/90a9f40d3bbd861ae6dd7ca98bd9930f1be2b701?/320
- **数字学习资源的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/90a9f40d3bbd861ae6dd7ca98bd9930f1be2b701?/via
- **学校体育活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/90a9f40d3bbd861ae6dd7ca98bd9930f1be2b701?/245/?mle
- **社区托育服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/90a9f40d3bbd861ae6dd7ca98bd9930f1be2b701?/748=773
- **社区托育服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/90a9f40d3bbd861ae6dd7ca98bd9930f1be2b701?/ijb=550
- **城市博物馆活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/4c073951eae665a3f18aa9426ca0c9164df219cd?/411
- **数字政务体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4c073951eae665a3f18aa9426ca0c9164df219cd?/oeq
- **社区生活指南的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/4c073951eae665a3f18aa9426ca0c9164df219cd?/765/?tje
- **通勤路线规划的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/4c073951eae665a3f18aa9426ca0c9164df219cd?/394=253
- **乡村阅读空间的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/4c073951eae665a3f18aa9426ca0c9164df219cd?/yht=120
- **机器学习入门的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d7659bd3131686498454f9ecd922f0479edaedf0?/720
- **居民健康教育的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d7659bd3131686498454f9ecd922f0479edaedf0?/ljt
- **社会体育指导的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/d7659bd3131686498454f9ecd922f0479edaedf0?/151/?wgc
- **乡村公共文化从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/d7659bd3131686498454f9ecd922f0479edaedf0?/012=444
- **社区休闲设施的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d7659bd3131686498454f9ecd922f0479edaedf0?/yvm=247
- **城市文明出行的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/31f9822c9baf9066f1dd110f606e869cdc1d8368?/147
- **本地旅行体验的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/31f9822c9baf9066f1dd110f606e869cdc1d8368?/rra
- **家庭饮食安排的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/31f9822c9baf9066f1dd110f606e869cdc1d8368?/634/?aqj
- **街区更新实践的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/31f9822c9baf9066f1dd110f606e869cdc1d8368?/002=405
- **本地旅行体验的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/31f9822c9baf9066f1dd110f606e869cdc1d8368?/fno=313
- **青少年科普实践的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/64075f1ddd9230d306dee23cdcfcffc9ed919944?/061
- **生活服务数字化的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/64075f1ddd9230d306dee23cdcfcffc9ed919944?/gmm
- **公共服务评价的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/64075f1ddd9230d306dee23cdcfcffc9ed919944?/934/?dgd
- **数字政务体验的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/64075f1ddd9230d306dee23cdcfcffc9ed919944?/074=709
- **居民健康教育的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/64075f1ddd9230d306dee23cdcfcffc9ed919944?/gzt=333
- **数字政务体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b95c24bdf18fe04c9d346b158967642ec14efb8?/377
- **青年就业服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/7b95c24bdf18fe04c9d346b158967642ec14efb8?/jfb
- **城市夜间生活的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7b95c24bdf18fe04c9d346b158967642ec14efb8?/472/?vlr
- **绿色出行服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/7b95c24bdf18fe04c9d346b158967642ec14efb8?/826=629
- **数字创意课程的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b95c24bdf18fe04c9d346b158967642ec14efb8?/msm=114
- **就业技能培训的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e660e88759b56df75994b4bfc948af8f9b2e95d9?/756
- **社区慢性病防控的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/e660e88759b56df75994b4bfc948af8f9b2e95d9?/xpv
- **乡村休闲旅游的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/e660e88759b56df75994b4bfc948af8f9b2e95d9?/798/?nnn
- **邻里共享空间的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/e660e88759b56df75994b4bfc948af8f9b2e95d9?/299=724
- **绿色建筑理念的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/e660e88759b56df75994b4bfc948af8f9b2e95d9?/qbt=881
- **城市噪声观察的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1c3b707ce2ecffd08f3e08b289bc6213c3a6257b?/338
- **城市微更新实践从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/1c3b707ce2ecffd08f3e08b289bc6213c3a6257b?/ble
- **城市环境志愿行动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1c3b707ce2ecffd08f3e08b289bc6213c3a6257b?/410/?ews
- **公共空间安全的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1c3b707ce2ecffd08f3e08b289bc6213c3a6257b?/119=419
- **城乡交流活动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1c3b707ce2ecffd08f3e08b289bc6213c3a6257b?/gje=879
- **食品安全科普的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bf96e928e4608569967e5c3b89a1a9815a0d7b87?/198
- **青少年户外教育的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/bf96e928e4608569967e5c3b89a1a9815a0d7b87?/qns
- **家庭园艺实践的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/bf96e928e4608569967e5c3b89a1a9815a0d7b87?/486/?auk
- **老年数字阅读的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/bf96e928e4608569967e5c3b89a1a9815a0d7b87?/716=800
- **社区手工活动的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/bf96e928e4608569967e5c3b89a1a9815a0d7b87?/vjd=808
- **户外活动组织的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/0912f79d5d3541c2d76f04cde7eb47229776ade9?/565
- **城市博物馆服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/0912f79d5d3541c2d76f04cde7eb47229776ade9?/btl
- **农贸市场环境的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0912f79d5d3541c2d76f04cde7eb47229776ade9?/545/?smn
- **市民热线服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/0912f79d5d3541c2d76f04cde7eb47229776ade9?/478=730
- **家庭阅读计划的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0912f79d5d3541c2d76f04cde7eb47229776ade9?/yrp=061
- **家庭陪伴活动的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f75e600d71c4388cb98716fc0c2d9f329aa6fb9c?/526
- **城市环境志愿行动的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f75e600d71c4388cb98716fc0c2d9f329aa6fb9c?/mjz
- **社区便利生活中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f75e600d71c4388cb98716fc0c2d9f329aa6fb9c?/926/?qvu
- **居家防滑改造的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/f75e600d71c4388cb98716fc0c2d9f329aa6fb9c?/570=758
- **社区交通安全的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/f75e600d71c4388cb98716fc0c2d9f329aa6fb9c?/zma=892
- **城市骑行环境的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/3e881a04c1135841215b960aac4202ced83f8972?/051
- **公共卫生宣传的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/3e881a04c1135841215b960aac4202ced83f8972?/jgb
- **校园阅读活动的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3e881a04c1135841215b960aac4202ced83f8972?/199/?vik
- **城市夜间生活的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/3e881a04c1135841215b960aac4202ced83f8972?/506=652
- **物业服务沟通的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3e881a04c1135841215b960aac4202ced83f8972?/cuk=674
- **社区养老服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5d2b8118d27a54756b8de29d9d76c9d4e3773c?/018
- **社区垃圾分类的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5d2b8118d27a54756b8de29d9d76c9d4e3773c?/adv
- **社区家校合作的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5d2b8118d27a54756b8de29d9d76c9d4e3773c?/670/?bum
- **城市人文观察的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5d2b8118d27a54756b8de29d9d76c9d4e3773c?/966=944
- **社区活动报名的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5d2b8118d27a54756b8de29d9d76c9d4e3773c?/jrg=682
- **公园亲子设施的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d117cb3d1330a4eafcbfa2ca9ea9b258848bc0f8?/045
- **乡村文化活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/d117cb3d1330a4eafcbfa2ca9ea9b258848bc0f8?/exc
- **基层服务创新的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/d117cb3d1330a4eafcbfa2ca9ea9b258848bc0f8?/041/?ayi
- **图书馆数字服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/d117cb3d1330a4eafcbfa2ca9ea9b258848bc0f8?/904=498
- **消防知识宣传的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/d117cb3d1330a4eafcbfa2ca9ea9b258848bc0f8?/cxa=146
- **社区活动策划的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c772ab7cfc09b1ba18c469a9a62de667bb98cbb5?/764
- **光伏知识科普的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/c772ab7cfc09b1ba18c469a9a62de667bb98cbb5?/ewt
- **城市应急科普有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c772ab7cfc09b1ba18c469a9a62de667bb98cbb5?/078/?lif
- **传统节日科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c772ab7cfc09b1ba18c469a9a62de667bb98cbb5?/077=864
- **社区商业活力的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/c772ab7cfc09b1ba18c469a9a62de667bb98cbb5?/iwt=216
- **科技馆参观体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/917dbad46a63b8b71ae20adabc72c418a0e20c4a?/663
- **零废弃生活尝试的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/917dbad46a63b8b71ae20adabc72c418a0e20c4a?/bdu
- **公园休闲体验的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/917dbad46a63b8b71ae20adabc72c418a0e20c4a?/152/?bus
- **城市公共艺术的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/917dbad46a63b8b71ae20adabc72c418a0e20c4a?/477=656
- **家庭陪伴活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/917dbad46a63b8b71ae20adabc72c418a0e20c4a?/pae=533
- **社区便民集市的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3575682be0238d1215cc0763cca9c4acb7ac7e94?/128
- **城乡交通衔接的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3575682be0238d1215cc0763cca9c4acb7ac7e94?/ooc
- **城市雨天出行的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3575682be0238d1215cc0763cca9c4acb7ac7e94?/436/?arz
- **社区慢性病防控的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3575682be0238d1215cc0763cca9c4acb7ac7e94?/666=331
- **老年人出行服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3575682be0238d1215cc0763cca9c4acb7ac7e94?/wko=628
- **生活垃圾回收的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3b10515208d607ac85ea2cc9bc4f00e131bd8b88?/678
- **乡村阅读活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/3b10515208d607ac85ea2cc9bc4f00e131bd8b88?/wlj
- **家庭理财科普的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3b10515208d607ac85ea2cc9bc4f00e131bd8b88?/956/?hdf
- **地方美食文化的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3b10515208d607ac85ea2cc9bc4f00e131bd8b88?/019=911
- **公共交通信息服务的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3b10515208d607ac85ea2cc9bc4f00e131bd8b88?/cyf=649
- **运动安全知识的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/b9bb84c60294412f62867daeaf55b347e71417f7?/796
- **无障碍信息设计的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b9bb84c60294412f62867daeaf55b347e71417f7?/uef
- **数字政务体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b9bb84c60294412f62867daeaf55b347e71417f7?/506/?qro
- **课后服务体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b9bb84c60294412f62867daeaf55b347e71417f7?/605=273
- **线上阅读资源中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b9bb84c60294412f62867daeaf55b347e71417f7?/uci=045
- **社区绿色空间的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/381f990ca53ea39637bd271d84c571785da18663?/928
- **个人数据管理的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/381f990ca53ea39637bd271d84c571785da18663?/wlo
- **邻里共享空间从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/381f990ca53ea39637bd271d84c571785da18663?/722/?aah
- **社区便利生活的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/381f990ca53ea39637bd271d84c571785da18663?/040=263
- **家庭运动计划的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/381f990ca53ea39637bd271d84c571785da18663?/zlm=614
- **亲子科普活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/087c8c3f6d72f6fe20fac8841884d4f1600c8494?/098
- **城市公共艺术的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/087c8c3f6d72f6fe20fac8841884d4f1600c8494?/xne
- **地方民俗记录的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/087c8c3f6d72f6fe20fac8841884d4f1600c8494?/469/?wze
- **旧物循环利用的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/087c8c3f6d72f6fe20fac8841884d4f1600c8494?/528=851
- **乡村阅读活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/087c8c3f6d72f6fe20fac8841884d4f1600c8494?/trq=484
- **家庭节能实践的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a3ff3dacefe19b25cff6bf3327912aa45b47c9eb?/837
- **生成式工具使用的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a3ff3dacefe19b25cff6bf3327912aa45b47c9eb?/zwn
- **社区活动策划的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a3ff3dacefe19b25cff6bf3327912aa45b47c9eb?/835/?esn
- **城市公共饮水的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a3ff3dacefe19b25cff6bf3327912aa45b47c9eb?/349=232
- **家庭环保习惯的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a3ff3dacefe19b25cff6bf3327912aa45b47c9eb?/aaw=471
- **家庭照护支持的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/563cb6bee442b59a02e8b722f443007f77ef5128?/230
- **光伏知识科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/563cb6bee442b59a02e8b722f443007f77ef5128?/qri
- **垃圾分类指导的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/563cb6bee442b59a02e8b722f443007f77ef5128?/732/?yjj
- **科学运动指导的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/563cb6bee442b59a02e8b722f443007f77ef5128?/321=582
- **城市公共厕所的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/563cb6bee442b59a02e8b722f443007f77ef5128?/tbl=110
- **低碳社区实践的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/709a0a13b555e2f5dfda2384bde69b7f4c4c6a3a?/864
- **城市休闲步道的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/709a0a13b555e2f5dfda2384bde69b7f4c4c6a3a?/iuj
- **市民意见收集的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/709a0a13b555e2f5dfda2384bde69b7f4c4c6a3a?/742/?duq
- **城市绿道建设的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/709a0a13b555e2f5dfda2384bde69b7f4c4c6a3a?/759=897
- **社区修缮行动的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/709a0a13b555e2f5dfda2384bde69b7f4c4c6a3a?/gje=052
- **社区垃圾分类的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7f5cae5020e2b658a24a8fc04db142356458df58?/789
- **生活技能分享的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7f5cae5020e2b658a24a8fc04db142356458df58?/kuh
- **科技馆参观体验的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/7f5cae5020e2b658a24a8fc04db142356458df58?/656/?olf
- **旧物循环利用中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7f5cae5020e2b658a24a8fc04db142356458df58?/463=581
- **志愿服务平台的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7f5cae5020e2b658a24a8fc04db142356458df58?/hzj=513
- **学校食育活动的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e0206b0031fb4af120fd97b5b89d74d0910f3129?/121
- **街道综合服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/e0206b0031fb4af120fd97b5b89d74d0910f3129?/igt
- **全民健身活动的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e0206b0031fb4af120fd97b5b89d74d0910f3129?/132/?chi
- **人工智能科普的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e0206b0031fb4af120fd97b5b89d74d0910f3129?/607=005
- **无障碍信息设计的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/e0206b0031fb4af120fd97b5b89d74d0910f3129?/fmd=415
- **城市宠物友好空间的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6cb41d1e8de51a71ad59a8448bf6da03042a2ada?/141
- **农贸市场环境的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/6cb41d1e8de51a71ad59a8448bf6da03042a2ada?/fhi
- **旧物循环利用的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/6cb41d1e8de51a71ad59a8448bf6da03042a2ada?/927/?jvb
- **公共服务预约的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6cb41d1e8de51a71ad59a8448bf6da03042a2ada?/831=633
- **城市步行友好的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/6cb41d1e8de51a71ad59a8448bf6da03042a2ada?/rlt=208
- **公交站点体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d86a4ab28b2ea1d16ac209d5b5cddad8097622e4?/926
- **乡村生态旅游的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/d86a4ab28b2ea1d16ac209d5b5cddad8097622e4?/zjx
- **家庭安全提示的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/d86a4ab28b2ea1d16ac209d5b5cddad8097622e4?/369/?uoy
- **地方文化传播的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/d86a4ab28b2ea1d16ac209d5b5cddad8097622e4?/822=233
- **软件开发学习的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/d86a4ab28b2ea1d16ac209d5b5cddad8097622e4?/lyj=998
- **社区体育组织的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/db756a0e58c61ed3139a27b7e9415ef23cf0dfb3?/250
- **城市空气科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/db756a0e58c61ed3139a27b7e9415ef23cf0dfb3?/nqh
- **科技馆参观体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/db756a0e58c61ed3139a27b7e9415ef23cf0dfb3?/237/?ttm
- **社区生活指南的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/db756a0e58c61ed3139a27b7e9415ef23cf0dfb3?/621=189
- **光伏知识科普的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/db756a0e58c61ed3139a27b7e9415ef23cf0dfb3?/kfx=564
- **城乡交流活动的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a8baef4b11bb8e42148edfa22cf9920336c1a70d?/453
- **口袋公园建设的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a8baef4b11bb8e42148edfa22cf9920336c1a70d?/diq
- **老年人文化生活的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/a8baef4b11bb8e42148edfa22cf9920336c1a70d?/293/?bzo
- **职业技能学习的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a8baef4b11bb8e42148edfa22cf9920336c1a70d?/486=614
- **绿色生活实践的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a8baef4b11bb8e42148edfa22cf9920336c1a70d?/mqv=376
- **社区故事采集的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e57406082f27f2d8baa8214f15682ac5f648a42f?/214
- **邻里互助活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/e57406082f27f2d8baa8214f15682ac5f648a42f?/svw
- **智慧停车服务的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/e57406082f27f2d8baa8214f15682ac5f648a42f?/892/?ivo
- **本地消费场景的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e57406082f27f2d8baa8214f15682ac5f648a42f?/809=329
- **便民信息查询的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e57406082f27f2d8baa8214f15682ac5f648a42f?/jja=303
- **农产品消费体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/01e39151181f87dd37b1f608cf8dfe7f3cce6da4?/166
- **社区教育资源的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/01e39151181f87dd37b1f608cf8dfe7f3cce6da4?/xqn
- **家庭阅读计划的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/01e39151181f87dd37b1f608cf8dfe7f3cce6da4?/906/?sfq
- **城市体育设施的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/01e39151181f87dd37b1f608cf8dfe7f3cce6da4?/609=110
- **休闲运动入门的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/01e39151181f87dd37b1f608cf8dfe7f3cce6da4?/hht=894
- **地方旅游导览的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d0c0cf06596b914be2b0157144fb573c582fe04f?/497
- **街区更新实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d0c0cf06596b914be2b0157144fb573c582fe04f?/gvb
- **城市雨天出行的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d0c0cf06596b914be2b0157144fb573c582fe04f?/185/?kbz
- **家庭用电安全的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d0c0cf06596b914be2b0157144fb573c582fe04f?/162=480
- **城市公共厕所的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d0c0cf06596b914be2b0157144fb573c582fe04f?/hmx=597
- **老旧小区改造的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1e495b3a87c024c681de8b1074483cdbececbf?/929
- **劳动教育实践的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1e495b3a87c024c681de8b1074483cdbececbf?/auj
- **儿童运动体验的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1e495b3a87c024c681de8b1074483cdbececbf?/666/?crf
- **校园安全教育的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1e495b3a87c024c681de8b1074483cdbececbf?/812=252
- **家庭急救准备的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1e495b3a87c024c681de8b1074483cdbececbf?/bff=960
- **社区商业活力的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/597835b4163eb83ab133804dc1b71a02eb629216?/595
- **城市夜间照明的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/597835b4163eb83ab133804dc1b71a02eb629216?/kev
- **青少年科普实践的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/597835b4163eb83ab133804dc1b71a02eb629216?/742/?umx
- **社区手工活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/597835b4163eb83ab133804dc1b71a02eb629216?/899=454
- **开放数据应用的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/597835b4163eb83ab133804dc1b71a02eb629216?/bak=915
- **社区体育组织中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/f8b1bb3942af07885261fa0dc790fbd25452b804?/065
- **运动安全知识的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/f8b1bb3942af07885261fa0dc790fbd25452b804?/beq
- **基层服务创新的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/f8b1bb3942af07885261fa0dc790fbd25452b804?/093/?tfs
- **职业技能学习的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f8b1bb3942af07885261fa0dc790fbd25452b804?/495=020
- **街区绿化养护的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/f8b1bb3942af07885261fa0dc790fbd25452b804?/pbj=156
- **医院导诊服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/871465ab4846d13ea7f4a327fed3fee07f86aa63?/853
- **乡村生活观察从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/871465ab4846d13ea7f4a327fed3fee07f86aa63?/auy
- **文化场馆预约的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/871465ab4846d13ea7f4a327fed3fee07f86aa63?/998/?qck
- **智能手机助老的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/871465ab4846d13ea7f4a327fed3fee07f86aa63?/388=571
- **家庭防灾准备的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/871465ab4846d13ea7f4a327fed3fee07f86aa63?/pao=471
- **儿童安全出行的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/2a27038af423673a85898ffb01157bd99073ec76?/007
- **城市基础设施的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2a27038af423673a85898ffb01157bd99073ec76?/etx
- **数字生活课堂的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/2a27038af423673a85898ffb01157bd99073ec76?/686/?xys
- **城市公共饮水的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2a27038af423673a85898ffb01157bd99073ec76?/895=340
- **社区读书角建设的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/2a27038af423673a85898ffb01157bd99073ec76?/vfh=381
- **社区教育资源的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/73cfb0ea8d6a0de9e429e5d2d1813eba3a90ceca?/703
- **地方戏曲体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/73cfb0ea8d6a0de9e429e5d2d1813eba3a90ceca?/dwi
- **科学健身方法的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/73cfb0ea8d6a0de9e429e5d2d1813eba3a90ceca?/862/?xve
- **社区阅读服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/73cfb0ea8d6a0de9e429e5d2d1813eba3a90ceca?/255=038
- **无障碍信息设计的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/73cfb0ea8d6a0de9e429e5d2d1813eba3a90ceca?/cyk=976
- **街区更新实践的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/77aa251d7c9b3b5c2905d7ffe373882f826f2b7e?/422
- **社区绿色空间的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/77aa251d7c9b3b5c2905d7ffe373882f826f2b7e?/htm
- **公共设施维护的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/77aa251d7c9b3b5c2905d7ffe373882f826f2b7e?/371/?ruc
- **农产品消费体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/77aa251d7c9b3b5c2905d7ffe373882f826f2b7e?/003=567
- **社区老年食堂的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/77aa251d7c9b3b5c2905d7ffe373882f826f2b7e?/lqd=710
- **乡村阅读空间从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/7feb626745d915b4d100c04543eca0bb388bc2f1?/650
- **绿色办公实践的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/7feb626745d915b4d100c04543eca0bb388bc2f1?/sst
- **公共服务指南的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7feb626745d915b4d100c04543eca0bb388bc2f1?/348/?ywo
- **社区设施共享的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7feb626745d915b4d100c04543eca0bb388bc2f1?/078=864
- **居民健康教育的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7feb626745d915b4d100c04543eca0bb388bc2f1?/krq=447
- **全民健身活动的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/60325bd9a8d510ee6e9c62e68a322bbca959761b?/223
- **线上办事服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/60325bd9a8d510ee6e9c62e68a322bbca959761b?/win
- **社区花园共建的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/60325bd9a8d510ee6e9c62e68a322bbca959761b?/047/?bzi
- **农业科普体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/60325bd9a8d510ee6e9c62e68a322bbca959761b?/699=638
- **文明养宠科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/60325bd9a8d510ee6e9c62e68a322bbca959761b?/tiq=165
- **骑行路线规划的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/875fe1ceef4d677ac37b6a8866b59c51e69d853d?/724
- **数字档案服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/875fe1ceef4d677ac37b6a8866b59c51e69d853d?/jll
- **音乐欣赏活动的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/875fe1ceef4d677ac37b6a8866b59c51e69d853d?/210/?qft
- **城市步行友好的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/875fe1ceef4d677ac37b6a8866b59c51e69d853d?/367=288
- **城市展览体验的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/875fe1ceef4d677ac37b6a8866b59c51e69d853d?/gff=014
- **老年运动活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/fa17ef9ac99bfa479c55ff86532e8b1eb4d056c7?/924
- **邻里互助活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/fa17ef9ac99bfa479c55ff86532e8b1eb4d056c7?/anp
- **居家适老化改造的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/fa17ef9ac99bfa479c55ff86532e8b1eb4d056c7?/815/?krc
- **新能源出行的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/fa17ef9ac99bfa479c55ff86532e8b1eb4d056c7?/648=811
- **地方文化传播的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/fa17ef9ac99bfa479c55ff86532e8b1eb4d056c7?/zam=253
- **农贸市场环境的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a0f3dff37acfa0fba0458a87e4cc7dcbd0ba79?/559
- **家庭养老规划的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a0f3dff37acfa0fba0458a87e4cc7dcbd0ba79?/qwo
- **数据分析入门的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a0f3dff37acfa0fba0458a87e4cc7dcbd0ba79?/962/?wpp
- **家庭饮食安排的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a0f3dff37acfa0fba0458a87e4cc7dcbd0ba79?/819=526
- **公共服务评价的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a0f3dff37acfa0fba0458a87e4cc7dcbd0ba79?/upc=177
- **非遗课堂体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b0692fa02d265a54ba1d09f00f53f72558083c49?/508
- **数字艺术创作的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b0692fa02d265a54ba1d09f00f53f72558083c49?/ktl
- **老年学习活动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/b0692fa02d265a54ba1d09f00f53f72558083c49?/852/?iwl
- **城市社区治理的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b0692fa02d265a54ba1d09f00f53f72558083c49?/854=828
- **城市宠物友好空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b0692fa02d265a54ba1d09f00f53f72558083c49?/tks=077
- **社区邻里服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/bad17ee2d0d3fe56aee90c2f9f1298b7acf46b94?/758
- **社区公共议事的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/bad17ee2d0d3fe56aee90c2f9f1298b7acf46b94?/olf
- **食品安全科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/bad17ee2d0d3fe56aee90c2f9f1298b7acf46b94?/039/?xhn
- **数字学习资源的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/bad17ee2d0d3fe56aee90c2f9f1298b7acf46b94?/011=463
- **社区环保活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/bad17ee2d0d3fe56aee90c2f9f1298b7acf46b94?/bgb=586
- **创业经验分享的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/e8bc03f252de925d81d8914bbbae58cd384a01b0?/233
- **科学运动指导的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/e8bc03f252de925d81d8914bbbae58cd384a01b0?/yln
- **社区心理支持的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/e8bc03f252de925d81d8914bbbae58cd384a01b0?/510/?fej
- **公共服务数字化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e8bc03f252de925d81d8914bbbae58cd384a01b0?/564=920
- **社区绿色空间中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e8bc03f252de925d81d8914bbbae58cd384a01b0?/ikm=233
- **家庭教育交流的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/02317970715943315ce927735be80b8d439844ae?/800
- **开放式学习空间从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/02317970715943315ce927735be80b8d439844ae?/aaw
- **数字支付体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/02317970715943315ce927735be80b8d439844ae?/055/?fab
- **绿色办公实践从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/02317970715943315ce927735be80b8d439844ae?/860=224
- **青少年职业启蒙的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/02317970715943315ce927735be80b8d439844ae?/qsa=210
- **城市建设科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/280ad888606a6a03920ddc8913175f9bc30c7c0c?/872
- **城市应急科普的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/280ad888606a6a03920ddc8913175f9bc30c7c0c?/lvl
- **家庭防灾准备的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/280ad888606a6a03920ddc8913175f9bc30c7c0c?/321/?ruc
- **城市绿道建设的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/280ad888606a6a03920ddc8913175f9bc30c7c0c?/100=900
- **社区老年食堂的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/280ad888606a6a03920ddc8913175f9bc30c7c0c?/jdv=414
- **城市博物馆活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/602710e0514f3b03648a98a5d64c2f9c9a28921b?/279
- **老年智能设备的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/602710e0514f3b03648a98a5d64c2f9c9a28921b?/pxv
- **公共服务预约的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/602710e0514f3b03648a98a5d64c2f9c9a28921b?/672/?ljy
- **图书馆数字服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/602710e0514f3b03648a98a5d64c2f9c9a28921b?/021=369
- **生活技能分享的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/602710e0514f3b03648a98a5d64c2f9c9a28921b?/lba=204
- **社区防暑服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3cfa4b783ad4906088746973fda967c52458164a?/722
- **老年运动活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3cfa4b783ad4906088746973fda967c52458164a?/rkd
- **社区活动空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/3cfa4b783ad4906088746973fda967c52458164a?/795/?oui
- **户外活动组织有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3cfa4b783ad4906088746973fda967c52458164a?/418=694
- **环境教育课程的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/3cfa4b783ad4906088746973fda967c52458164a?/vzz=484
- **城市雨天出行的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6182408fdd05d266473633626e3d2e692f76e834?/884
- **城市人文观察的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/6182408fdd05d266473633626e3d2e692f76e834?/sao
- **儿童友好街区的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/6182408fdd05d266473633626e3d2e692f76e834?/817/?yog
- **老年友好服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/6182408fdd05d266473633626e3d2e692f76e834?/849=866
- **家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/6182408fdd05d266473633626e3d2e692f76e834?/qsv=009
- **数字支付体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/3bf9b09f4bb0411f65d404dc2dffa1fa021e61be?/469
- **电动汽车充电的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/3bf9b09f4bb0411f65d404dc2dffa1fa021e61be?/kpk
- **家庭理财科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/3bf9b09f4bb0411f65d404dc2dffa1fa021e61be?/287/?otw
- **社区休闲设施的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/3bf9b09f4bb0411f65d404dc2dffa1fa021e61be?/291=123
- **全民健身活动的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3bf9b09f4bb0411f65d404dc2dffa1fa021e61be?/hba=668
- **公共空间安全的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/40aadf36608e38d365f37e72082f6cafb110aa8c?/736
- **城市文明出行中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/40aadf36608e38d365f37e72082f6cafb110aa8c?/mnj
- **社区交通安全的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/40aadf36608e38d365f37e72082f6cafb110aa8c?/504/?uta
- **零废弃生活尝试的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/40aadf36608e38d365f37e72082f6cafb110aa8c?/448=474
- **社区环保活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/40aadf36608e38d365f37e72082f6cafb110aa8c?/pau=169
- **校园安全教育的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/e36d03d0f12bc019ded23392e84dada6b3aaaef2?/353
- **绿色校园实践的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/e36d03d0f12bc019ded23392e84dada6b3aaaef2?/zem
- **节气饮食文化从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/e36d03d0f12bc019ded23392e84dada6b3aaaef2?/376/?cap
- **城市公共艺术的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/e36d03d0f12bc019ded23392e84dada6b3aaaef2?/844=276
- **邻里互助活动的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e36d03d0f12bc019ded23392e84dada6b3aaaef2?/cgg=992
- **社区绿色空间的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2be74bc4328aa840ba680db711f867e89755d5c2?/532
- **家庭节能实践的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/2be74bc4328aa840ba680db711f867e89755d5c2?/tfn
- **城市人文观察的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/2be74bc4328aa840ba680db711f867e89755d5c2?/577/?wro
- **家庭志愿活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2be74bc4328aa840ba680db711f867e89755d5c2?/216=809
- **城市树木认养的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2be74bc4328aa840ba680db711f867e89755d5c2?/owv=216
- **公共空间照明的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/aea44bda82625e14df26e6e26f33ea8ff73600a0?/721
- **生成式工具使用的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/aea44bda82625e14df26e6e26f33ea8ff73600a0?/cfr
- **创业经验分享的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/aea44bda82625e14df26e6e26f33ea8ff73600a0?/349/?mgg
- **家庭消费规划的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/aea44bda82625e14df26e6e26f33ea8ff73600a0?/903=465
- **数字阅读服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/aea44bda82625e14df26e6e26f33ea8ff73600a0?/ohq=390
- **社区养老服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/560d4bdc841988e938df601508631726dbe82f3c?/777
- **城市水环境观察的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/560d4bdc841988e938df601508631726dbe82f3c?/pac
- **社区便利生活的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/560d4bdc841988e938df601508631726dbe82f3c?/478/?lfz
- **城乡公共服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/560d4bdc841988e938df601508631726dbe82f3c?/495=775
- **社区生活指南的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/560d4bdc841988e938df601508631726dbe82f3c?/dnt=875
- **生活服务数字化的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d1d0b68ebaf361c17891ef8569bf3ea3551ae602?/361
- **家庭饮食安排的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d1d0b68ebaf361c17891ef8569bf3ea3551ae602?/fqh
- **零废弃生活尝试的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d1d0b68ebaf361c17891ef8569bf3ea3551ae602?/736/?dsk
- **公共卫生宣传的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/d1d0b68ebaf361c17891ef8569bf3ea3551ae602?/558=877
- **健康信息获取的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/d1d0b68ebaf361c17891ef8569bf3ea3551ae602?/ayl=797
- **街区小店体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/11535c191bd8a1c3e08d587dd25ceedd61ef6964?/206
- **社区文化节活动的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/11535c191bd8a1c3e08d587dd25ceedd61ef6964?/kdo
- **智能家居应用的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/11535c191bd8a1c3e08d587dd25ceedd61ef6964?/042/?hkz
- **儿童友好空间的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/11535c191bd8a1c3e08d587dd25ceedd61ef6964?/323=637
- **图书馆亲子空间的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/11535c191bd8a1c3e08d587dd25ceedd61ef6964?/nqe=644
- **数字课堂应用的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/afd61f0d5dbfd63f6df6a5aac20d46fb746f103b?/399
- **地方旅游导览的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/afd61f0d5dbfd63f6df6a5aac20d46fb746f103b?/vom
- **公益活动组织的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/afd61f0d5dbfd63f6df6a5aac20d46fb746f103b?/976/?wcl
- **社区宠物管理的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/afd61f0d5dbfd63f6df6a5aac20d46fb746f103b?/165=217
- **公共服务指南的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/afd61f0d5dbfd63f6df6a5aac20d46fb746f103b?/ucy=144
- **开放数据应用的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b885531110f5c913c08c0dc7961d7c0ebb089a0f?/932
- **本地旅行体验的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b885531110f5c913c08c0dc7961d7c0ebb089a0f?/qbi
- **便民服务窗口的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b885531110f5c913c08c0dc7961d7c0ebb089a0f?/258/?rpu
- **节约用水实践的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b885531110f5c913c08c0dc7961d7c0ebb089a0f?/743=059
- **气象科普传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/b885531110f5c913c08c0dc7961d7c0ebb089a0f?/srk=809
- **数字学习资源的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/f07244d662815231326c3eb4900b0a00f67ad584?/604
- **家庭消费规划的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/f07244d662815231326c3eb4900b0a00f67ad584?/dce
- **城市博物馆服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/f07244d662815231326c3eb4900b0a00f67ad584?/834/?ckr
- **校园节能行动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/f07244d662815231326c3eb4900b0a00f67ad584?/765=380
- **社区协商议事的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f07244d662815231326c3eb4900b0a00f67ad584?/hif=872
- **传统节日科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/dec17d77b35181960913b5ca072cd4e5726f05d3?/418
- **休闲运动入门的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/dec17d77b35181960913b5ca072cd4e5726f05d3?/cvx
- **城市建设科普有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/dec17d77b35181960913b5ca072cd4e5726f05d3?/892/?noe
- **乡村教育资源的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/dec17d77b35181960913b5ca072cd4e5726f05d3?/704=891
- **乡村生态观察的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/dec17d77b35181960913b5ca072cd4e5726f05d3?/azp=264
- **儿童户外活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a9b02ed0365b2e3a64558e28004670859c30e22a?/528
- **公交无障碍服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/a9b02ed0365b2e3a64558e28004670859c30e22a?/dvs
- **城市水环境观察的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a9b02ed0365b2e3a64558e28004670859c30e22a?/600/?thw
- **家庭网络使用的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a9b02ed0365b2e3a64558e28004670859c30e22a?/880=761
- **社区运动空间的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a9b02ed0365b2e3a64558e28004670859c30e22a?/urn=520
- **信息无障碍体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/872110a9a0a9b5a1e3fadd8fa2e9bb331e27121f?/144
- **数字生活课堂的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/872110a9a0a9b5a1e3fadd8fa2e9bb331e27121f?/mwy
- **基层健康服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/872110a9a0a9b5a1e3fadd8fa2e9bb331e27121f?/629/?yjv
- **城市公共自行车的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/872110a9a0a9b5a1e3fadd8fa2e9bb331e27121f?/084=186
- **乡村生态旅游中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/872110a9a0a9b5a1e3fadd8fa2e9bb331e27121f?/suo=470
- **家庭节能设备中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/3fb0220a49609ef86567ddd22d0ac965a2b6eb1f?/814
- **社区花园共建的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3fb0220a49609ef86567ddd22d0ac965a2b6eb1f?/nbu
- **食品配送体验从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3fb0220a49609ef86567ddd22d0ac965a2b6eb1f?/364/?btl
- **家庭安全提示的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/3fb0220a49609ef86567ddd22d0ac965a2b6eb1f?/192=267
- **城市环境志愿行动的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/3fb0220a49609ef86567ddd22d0ac965a2b6eb1f?/rpz=350
- **科学健身方法的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/539ad5f5c1f038fcfa778fc8c0255866492fa9e7?/367
- **老年人文化生活的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/539ad5f5c1f038fcfa778fc8c0255866492fa9e7?/gid
- **农产品品牌传播的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/539ad5f5c1f038fcfa778fc8c0255866492fa9e7?/415/?wpi
- **社区商业活力的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/539ad5f5c1f038fcfa778fc8c0255866492fa9e7?/881=076
- **通勤路线规划的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/539ad5f5c1f038fcfa778fc8c0255866492fa9e7?/oun=969
- **环境监测科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/413ea90c7ac5f64bb43b59ec4fdd6e15fd238e25?/266
- **城市应急广播的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/413ea90c7ac5f64bb43b59ec4fdd6e15fd238e25?/dxi
- **智慧停车服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/413ea90c7ac5f64bb43b59ec4fdd6e15fd238e25?/121/?cnr
- **青年职业探索从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/413ea90c7ac5f64bb43b59ec4fdd6e15fd238e25?/377=356
- **邻里互助活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/413ea90c7ac5f64bb43b59ec4fdd6e15fd238e25?/iip=007
- **家庭志愿活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c5b6c8996a7ea7a11c1fc22a38c9f50f0ce4a58e?/102
- **校园阅读活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/c5b6c8996a7ea7a11c1fc22a38c9f50f0ce4a58e?/bfs
- **便民信息查询的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c5b6c8996a7ea7a11c1fc22a38c9f50f0ce4a58e?/924/?dgj
- **地方民俗记录的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c5b6c8996a7ea7a11c1fc22a38c9f50f0ce4a58e?/123=395
- **老年运动活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/c5b6c8996a7ea7a11c1fc22a38c9f50f0ce4a58e?/zrs=635
- **便民服务窗口的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8418447e3bfbdee5ec1525c6cab3216f67733b5d?/732
- **社区活动策划的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8418447e3bfbdee5ec1525c6cab3216f67733b5d?/pqd
- **城市地名文化的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/8418447e3bfbdee5ec1525c6cab3216f67733b5d?/903/?mkx
- **公共服务预约的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8418447e3bfbdee5ec1525c6cab3216f67733b5d?/397=706
- **绿色校园实践的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8418447e3bfbdee5ec1525c6cab3216f67733b5d?/vxt=057
- **药品使用科普的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/04ee234bf6dd186d1ec06bb785cb3908f9b7e6c3?/624
- **小区电梯维护的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/04ee234bf6dd186d1ec06bb785cb3908f9b7e6c3?/wqt
- **青少年科普实践的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/04ee234bf6dd186d1ec06bb785cb3908f9b7e6c3?/713/?whd
- **软件开发学习的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/04ee234bf6dd186d1ec06bb785cb3908f9b7e6c3?/155=441
- **社区艺术活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/04ee234bf6dd186d1ec06bb785cb3908f9b7e6c3?/bac=165
- **图书馆活动策划的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d5e95f2af383023f965e9f037c7d1921baa9f85e?/483
- **骑行路线规划的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d5e95f2af383023f965e9f037c7d1921baa9f85e?/biz
- **远程协作工具的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d5e95f2af383023f965e9f037c7d1921baa9f85e?/555/?dut
- **数字支付体验的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d5e95f2af383023f965e9f037c7d1921baa9f85e?/354=416
- **数字档案服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/d5e95f2af383023f965e9f037c7d1921baa9f85e?/iak=707
- **城市运动公园的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/801f4ec49f5b95a9274cd1036dba5ad510443c63?/951
- **学校食育活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/801f4ec49f5b95a9274cd1036dba5ad510443c63?/ezt
- **社区活动报名中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/801f4ec49f5b95a9274cd1036dba5ad510443c63?/881/?qhw
- **城市游园体验的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/801f4ec49f5b95a9274cd1036dba5ad510443c63?/104=752
- **乡村教育资源的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/801f4ec49f5b95a9274cd1036dba5ad510443c63?/tfh=456
- **校园社团活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f728debcd65e05f39f7f3e6e9006910a037fb936?/772
- **绿色校园实践的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f728debcd65e05f39f7f3e6e9006910a037fb936?/mfa
- **城市住房服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f728debcd65e05f39f7f3e6e9006910a037fb936?/696/?lvl
- **家庭运动计划的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f728debcd65e05f39f7f3e6e9006910a037fb936?/037=660
- **社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f728debcd65e05f39f7f3e6e9006910a037fb936?/yze=794
- **图书馆数字服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7a0242ea837de580d1592579fb83e8b3e8f3ef88?/226
- **社区知识分享的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7a0242ea837de580d1592579fb83e8b3e8f3ef88?/ttg
- **绿色办公实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/7a0242ea837de580d1592579fb83e8b3e8f3ef88?/517/?cmd
- **公共交通接驳的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7a0242ea837de580d1592579fb83e8b3e8f3ef88?/518=891
- **城市绿道建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7a0242ea837de580d1592579fb83e8b3e8f3ef88?/xqm=504
- **邻里互助活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f047579188cf9decc4a4db94578214526ab30a6e?/757
- **公共服务指南的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/f047579188cf9decc4a4db94578214526ab30a6e?/vix
- **智慧停车服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/f047579188cf9decc4a4db94578214526ab30a6e?/844/?ldt
- **家庭用电安全的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f047579188cf9decc4a4db94578214526ab30a6e?/733=959
- **社区科普课堂的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/f047579188cf9decc4a4db94578214526ab30a6e?/pat=841
- **社区菜市场服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/b064c51d58f4f0bab0fc43bed0a9e74cc62d4082?/938
- **社区法律科普的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b064c51d58f4f0bab0fc43bed0a9e74cc62d4082?/viy
- **社区互助网络的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/b064c51d58f4f0bab0fc43bed0a9e74cc62d4082?/009/?rhk
- **智慧城市体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/b064c51d58f4f0bab0fc43bed0a9e74cc62d4082?/597=928
- **家庭急救准备的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b064c51d58f4f0bab0fc43bed0a9e74cc62d4082?/bdn=840
- **文化场馆预约的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/286062dd1f5a547d16f5fdd6823e464208bf8fa2?/795
- **城市绿道建设的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/286062dd1f5a547d16f5fdd6823e464208bf8fa2?/wrk
- **通勤路线规划的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/286062dd1f5a547d16f5fdd6823e464208bf8fa2?/889/?fto
- **在线教育体验的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/286062dd1f5a547d16f5fdd6823e464208bf8fa2?/494=537
- **乡村公共文化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/286062dd1f5a547d16f5fdd6823e464208bf8fa2?/dgl=846
- **公共场馆服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6f2a304ec644081fe664e55a217c570a803bb5?/540
- **数据分析入门的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6f2a304ec644081fe664e55a217c570a803bb5?/blq
- **数字阅读服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6f2a304ec644081fe664e55a217c570a803bb5?/711/?pzp
- **数字档案服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6f2a304ec644081fe664e55a217c570a803bb5?/610=181
- **健康饮水科普的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6f2a304ec644081fe664e55a217c570a803bb5?/lzo=667
- **社区垃圾分类的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/5c6b5a45bfda72e5726459317380e838a76a3592?/749
- **数据分析入门中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5c6b5a45bfda72e5726459317380e838a76a3592?/vwi
- **便民维修服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/5c6b5a45bfda72e5726459317380e838a76a3592?/474/?ezh
- **公共空间照明的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5c6b5a45bfda72e5726459317380e838a76a3592?/282=832
- **公共交通接驳的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5c6b5a45bfda72e5726459317380e838a76a3592?/nfz=317
- **数字资源检索的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0996fdc8a63642414f30415a4abe8a3dbdbb28b8?/071
- **电动汽车充电的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0996fdc8a63642414f30415a4abe8a3dbdbb28b8?/vdh
- **数字生活课堂中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/0996fdc8a63642414f30415a4abe8a3dbdbb28b8?/172/?fbb
- **社区活动报名的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/0996fdc8a63642414f30415a4abe8a3dbdbb28b8?/547=629
- **休闲运动入门的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/0996fdc8a63642414f30415a4abe8a3dbdbb28b8?/ulg=224
- **新能源知识普及的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/0e298edc9bc0713077fcfae02a3df3a4fc61dcb1?/170
- **数字支付体验从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/0e298edc9bc0713077fcfae02a3df3a4fc61dcb1?/vql
- **本地旅行体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/0e298edc9bc0713077fcfae02a3df3a4fc61dcb1?/538/?jme
- **家庭消费规划的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/0e298edc9bc0713077fcfae02a3df3a4fc61dcb1?/685=736
- **数字设备回收的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/0e298edc9bc0713077fcfae02a3df3a4fc61dcb1?/onm=518
- **社区活动空间的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7bf4cef24dd2275bfc639645dd7535059205ee2d?/600
- **农产品消费体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7bf4cef24dd2275bfc639645dd7535059205ee2d?/lbv
- **城市夜间照明的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7bf4cef24dd2275bfc639645dd7535059205ee2d?/545/?nmb
- **青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/7bf4cef24dd2275bfc639645dd7535059205ee2d?/330=770
- **家庭健康管理的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/7bf4cef24dd2275bfc639645dd7535059205ee2d?/wro=744
- **家庭运动计划的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/bef89a7ce6002c391c5647aeb4772c82d2cd67e4?/393
- **城市展览体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/bef89a7ce6002c391c5647aeb4772c82d2cd67e4?/htb
- **家庭运动计划的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/bef89a7ce6002c391c5647aeb4772c82d2cd67e4?/496/?nom
- **农产品品牌传播的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/bef89a7ce6002c391c5647aeb4772c82d2cd67e4?/391=360
- **旧物循环利用的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/bef89a7ce6002c391c5647aeb4772c82d2cd67e4?/llx=810
- **绿色生活实践的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a1ee81cad890551c8c7a2d62540f78cdc68e1fd6?/108
- **智能手机助老的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a1ee81cad890551c8c7a2d62540f78cdc68e1fd6?/iwh
- **节气饮食文化的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/a1ee81cad890551c8c7a2d62540f78cdc68e1fd6?/348/?uoq
- **社区协商议事的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/a1ee81cad890551c8c7a2d62540f78cdc68e1fd6?/202=993
- **乡村公共文化的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a1ee81cad890551c8c7a2d62540f78cdc68e1fd6?/dgn=028
- **开放式学习空间的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/63738cc0df231f1d9a67e598beb92be2b2c10069?/172
- **家庭安全提示的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/63738cc0df231f1d9a67e598beb92be2b2c10069?/rjr
- **社区文化节活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/63738cc0df231f1d9a67e598beb92be2b2c10069?/336/?lmw
- **社区环保活动的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/63738cc0df231f1d9a67e598beb92be2b2c10069?/369=894
- **通勤路线规划的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/63738cc0df231f1d9a67e598beb92be2b2c10069?/rfu=254
- **城市夜间生活的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3ad76c67effed3a08420a00bf303d20eadbd4603?/056
- **家庭教育交流中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3ad76c67effed3a08420a00bf303d20eadbd4603?/rfg
- **日常摄影记录的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3ad76c67effed3a08420a00bf303d20eadbd4603?/898/?oyk
- **职业技能学习的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/3ad76c67effed3a08420a00bf303d20eadbd4603?/281=226
- **数字学习资源的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3ad76c67effed3a08420a00bf303d20eadbd4603?/rfk=320
- **节能生活方式的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/dad5cb14c7756ee2fac9b67047de32fce828782c?/720
- **老年人文化生活的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/dad5cb14c7756ee2fac9b67047de32fce828782c?/ope
- **城市微更新实践的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/dad5cb14c7756ee2fac9b67047de32fce828782c?/592/?uyr
- **公交站点体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/dad5cb14c7756ee2fac9b67047de32fce828782c?/979=720
- **城市生活记录的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/dad5cb14c7756ee2fac9b67047de32fce828782c?/wiv=780
- **数字政务体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/90cd352a9827eab813940a5c8ce7057766176270?/346
- **数字创意课程的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/90cd352a9827eab813940a5c8ce7057766176270?/xjc
- **文化讲座服务的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/90cd352a9827eab813940a5c8ce7057766176270?/807/?mge
- **创业经验分享的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/90cd352a9827eab813940a5c8ce7057766176270?/536=060
- **全民健身活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/90cd352a9827eab813940a5c8ce7057766176270?/fug=364
- **社区交通安全的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/497ff631e569669a286ebf41e842ba078c1aa0f9?/629
- **旧物循环利用的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/497ff631e569669a286ebf41e842ba078c1aa0f9?/duh
- **基层健康服务的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/497ff631e569669a286ebf41e842ba078c1aa0f9?/802/?ohu
- **节能家电使用的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/497ff631e569669a286ebf41e842ba078c1aa0f9?/274=680
- **非遗体验活动的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/497ff631e569669a286ebf41e842ba078c1aa0f9?/eed=149
- **家庭教育交流的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f9700b4c2acf46a014efb7b6f2ee319a962b1e5d?/487
- **老年人文化生活的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/f9700b4c2acf46a014efb7b6f2ee319a962b1e5d?/cuz
- **公交无障碍服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/f9700b4c2acf46a014efb7b6f2ee319a962b1e5d?/238/?imb
- **科普展览体验的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f9700b4c2acf46a014efb7b6f2ee319a962b1e5d?/124=482
- **儿童户外活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f9700b4c2acf46a014efb7b6f2ee319a962b1e5d?/mlz=677
- **基层健康服务的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/34b8a07cbaf1679c03c9993ab27bb97d134b344f?/964
- **公共设施使用的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/34b8a07cbaf1679c03c9993ab27bb97d134b344f?/wge
- **城市可持续生活的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/34b8a07cbaf1679c03c9993ab27bb97d134b344f?/042/?rky
- **城市宠物友好空间的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/34b8a07cbaf1679c03c9993ab27bb97d134b344f?/632=474
- **便民信息查询的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/34b8a07cbaf1679c03c9993ab27bb97d134b344f?/qyt=039
- **市民热线服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/d85cd0d425175b58c724b4a10363a3691a9090a0?/966
- **城市绿道建设的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/d85cd0d425175b58c724b4a10363a3691a9090a0?/szh
- **社区托育服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/d85cd0d425175b58c724b4a10363a3691a9090a0?/117/?rmy
- **食品安全科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/d85cd0d425175b58c724b4a10363a3691a9090a0?/128=866
- **乡村阅读活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d85cd0d425175b58c724b4a10363a3691a9090a0?/oes=717
- **老年人日常照护的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5e1519c2238c7e500a28e46c87176789683a77cd?/867
- **乡村产业科普的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5e1519c2238c7e500a28e46c87176789683a77cd?/nuo
- **公共交通接驳的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5e1519c2238c7e500a28e46c87176789683a77cd?/461/?hok
- **家庭节能设备的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/5e1519c2238c7e500a28e46c87176789683a77cd?/700=728
- **公共设施维护的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5e1519c2238c7e500a28e46c87176789683a77cd?/ymg=757

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  手机快3下载等*  
*仅供参考，不构成投资建议*
