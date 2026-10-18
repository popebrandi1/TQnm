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

- **骑行路线规划的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/620
- **志愿者培训交流的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/mmm
- **科技馆参观体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/925/?zkf
- **城市文化路线的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/418=399
- **社区商业活力的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/03ce4b14160218f4f33e67c140527eb55e7a07d9?/ikx=961
- **家庭环保行动的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/322
- **青年志愿活动的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/ujt
- **社区庭院绿化的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/669/?aup
- **公共空间照明的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/855=274
- **社会体育指导的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a9bcd513e6b1345e6d2727ca6248438c91ca898a?/hog=465
- **公益活动组织的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/360
- **城市微更新实践的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/fqi
- **城市骑行环境的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/091/?xek
- **家庭陪伴活动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/366=216
- **青少年职业启蒙的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9ae2d951a1d35044d5aaf6ef6ab0378dcd94d667?/hud=806
- **城市雨天出行的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/598
- **城市公共艺术的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/zqi
- **课后服务体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/883/?eja
- **城市公共自行车有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/481=298
- **数字支付体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a8d597e204211f30f6e2894eb8b0a79ecd01d789?/voy=478
- **城市生活记录的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/672
- **家庭健康科普的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/opr
- **线上阅读资源的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/593/?zcc
- **绿色生活实践的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/525=991
- **城乡公共服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/069d30ee253e3339ec32bd20e6ea85fd1cfd9b18?/gnj=425
- **科学教育活动的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/628
- **远程协作工具的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/tov
- **旧物循环利用的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/192/?efw
- **数字资源检索的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/152=985
- **家庭消费规划的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/6d06dd56a9f7df8ac9300f0d86fd014bb6576107?/yca=900
- **家庭网络使用的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/033
- **科学运动指导的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/rbh
- **绿色出行服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/532/?cem
- **通勤路线规划的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/918=804
- **数字地图应用中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/b2af5c3f1b498dbc3761a15a9ea1a0cb2b687270?/hqe=268
- **社区活动报名的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/346
- **环境监测科普的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/kwe
- **城市文化路线的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/686/?nip
- **数字阅读服务的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/432=353
- **社区协商议事的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a711d9fbd408ae0ad90e93b9bd258fa11253c59c?/qtq=345
- **青年职业探索的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/950
- **社区阅读服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/svs
- **健康饮食教育的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/116/?hmi
- **节能家电使用的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/694=873
- **社区便民集市的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/f7d42871f553c50e69e4ca97e80bea04a5fe7351?/gca=081
- **数字素养提升的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/744
- **开放式学习空间的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/kju
- **家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/468/?plv
- **数字创意课程有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/028=269
- **跨代沟通活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/ff39cccca515381467f2c844bee30d5833517e9f?/xiq=194
- **乡村公共服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/344
- **小区停车协商的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/tgv
- **地方旅游导览的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/992/?ckz
- **数字课堂应用的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/123=961
- **文化场馆预约的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0d65a00634e2a79cc838121df158abf13657cbd8?/bsx=373
- **电动汽车充电的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/416
- **社区菜市场服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/ulp
- **社区环保活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/413/?vuc
- **数字便民地图的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/239=064
- **全民健身活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f33a658f16b1cbdc6420a47903a3b03cae62ada8?/wwx=088
- **志愿服务平台的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/662
- **无障碍信息设计的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/pyy
- **家庭园艺实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/170/?rcg
- **社区读书角建设的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/671=637
- **儿童友好街区的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b6713d5f62e25e79f0493b23efa6a80bc70ce764?/ibl=296
- **街区道路维护的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/627
- **绿色出行服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/ycu
- **数字政务体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/951/?lvw
- **社会体育指导的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/790=847
- **社区学习活动的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a998eb39b5b7ee574431fd5157f187022c0520e4?/feg=698
- **城市慢跑路线的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/779
- **乡村公共阅读的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/wmv
- **社区活动报名的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/927/?mdk
- **家庭饮食安排的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/234=957
- **家庭养老规划的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c574e99b6da21551d7c8acf0e939383a54f0f166?/kia=399
- **个人时间管理的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/999
- **图书馆亲子空间的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/bki
- **生活垃圾回收的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/434/?unl
- **城市文明出行的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/058=586
- **基层健康服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/12f8f0c92bb7b72b36c91efc6b903a815b85eb2f?/qad=298
- **地方文化传播的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/036
- **线上阅读资源的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/ypo
- **公共交通信息服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/859/?akq
- **城市社区治理的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/792=846
- **城市游园体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b8d8067d28b7eb101c4794391e96491b4eb86e06?/dzs=504
- **校园安全教育的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/751
- **社区停车服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/wrj
- **科学信息获取的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/965/?ieb
- **公共空间休憩的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/453=887
- **创业经验分享的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/c74c570724223965c52308a7a3127620757a9fdd?/aaw=015
- **城市生活服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/260
- **社区公共卫生的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/tvx
- **数字设备回收的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/272/?bza
- **图书借阅体验的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/244=692
- **家庭阅读计划的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/bf63d495d75ac63f4aff5f687fa75712b6194dca?/ezh=677
- **基层健康服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/953
- **社区健康讲座的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/ocl
- **公共服务评价的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/348/?msi
- **城市生活服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/734=173
- **公共文化活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7e8ba85a1426d57987092b6fb1d635ddd320b991?/tzn=729
- **城市文明实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/787
- **街区绿化养护的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/vpm
- **学校食育活动的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/826/?yfy
- **城市地名文化的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/582=530
- **无障碍出行的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e721a0cb0d67c005015436897430c1b44448afd2?/wvq=047
- **数字创意课程中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/792
- **家庭阅读计划的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/giw
- **社区便利生活的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/377/?izb
- **口袋公园建设的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/848=117
- **公共服务数字化中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7d37bafa9a6eb1b9c5930413d6d939a408a31196?/vwr=140
- **本地消费场景中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/909
- **社区邻里服务的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/ffe
- **文化讲座服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/481/?pxj
- **城市基础设施的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/027=716
- **地方旅游导览的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/52a50b22ecad2d583f0c187b23488f09e0165eb5?/jud=811
- **线上阅读资源的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/388
- **城市共享单车有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/ndk
- **街区道路维护的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/869/?bpf
- **社会体育指导的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/383=044
- **远程协作工具的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7a150ef70131cb148e08a2cca15683a7768457de?/mco=474
- **通勤路线规划的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/379
- **垃圾分类指导的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/scy
- **城市文化路线的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/589/?pax
- **公共图书馆服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/091=020
- **社区便民服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2ef4c571c300f382b407e5704e40373ce99969ab?/jov=879
- **公共设施维护的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/362
- **市民意见收集的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/nxf
- **社区托育服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/957/?hhc
- **志愿服务平台的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/778=347
- **校园安全教育的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9155b240e66566b563e418b5073f8a1e4048e7?/drd=286
- **科技馆参观体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/234
- **城乡交流活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/evv
- **个人时间管理的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/640/?lmq
- **公共交通信息服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/818=820
- **科普展览体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3a3406d8a5efced8963f4755e1a33981162b47e8?/lxb=752
- **租房信息服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/952
- **城市环境志愿行动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/bsw
- **劳动教育实践的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/460/?tib
- **机器人科普活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/523=524
- **数字艺术创作的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9afb3e90c0cb6a7140a902342af2f8f7abead036?/gkf=772
- **乡村产业科普的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/800
- **城市公共标识中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/qnr
- **社区慢性病防控的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/083/?kku
- **药品使用科普的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/375=972
- **乡村阅读空间的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d470915735864f51bef3adb112e05255a88ec241?/nqa=069
- **老年友好服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/477
- **口袋公园建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/fdp
- **电动汽车充电中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/838/?vwp
- **家庭照护支持的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/015=246
- **家庭健康科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/7cbc71d7bb5a63bff1fef9db6e4fb4fe25b3a194?/nuc=640
- **数字生活课堂的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/835
- **社区宠物管理的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/oxg
- **居家防滑改造的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/093/?unf
- **社区邻里服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/235=777
- **健康饮水科普的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/39598aa7c2b2cfa4c860d5938e6f828e64a9b0cf?/aim=534
- **网络安全教育的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/206
- **儿童友好空间的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/iyn
- **公交站点体验的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/320/?jec
- **儿童运动体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/969=879
- **儿童户外活动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/76d347dd3029fec3073cd4487d3773174e5fcbdb?/rhs=533
- **城市应急科普的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/540
- **城市人文观察的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/cxo
- **数字阅读服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/115/?vub
- **全民阅读推广中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/272=750
- **家庭节能实践的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a30394e020aeae91c4ea67cad3bfdd276a64d926?/alg=876
- **线上办事服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/502
- **城市人文观察的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/fpp
- **居家适老化改造的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/168/?ybe
- **城市住房服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/952=724
- **药品使用科普的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f5fbfd2d822b314340354aa685274f073979c23d?/hxy=069
- **新能源出行的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/770
- **青年就业服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/wno
- **节日文化体验的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/982/?nwz
- **农产品消费体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/082=892
- **社区故事采集从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ecd50263ce31e95d68a35cbba4ac9fb21391bb82?/xih=502
- **小区停车协商有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/729
- **老年人日常照护的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/mpp
- **家庭节能实践中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/204/?dii
- **健康饮食教育的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/078=367
- **社区艺术活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/ee8c17df4856a79a92c0f464472881417b1ad074?/dnf=933
- **城市地名文化的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/137
- **青少年编程学习的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/lxv
- **老年友好服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/590/?nfl
- **邻里互助活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/355=201
- **就业技能培训的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8ca65854af1bb86962314dfabebc3f8284e49637?/dme=975
- **食品安全科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/015
- **城市住房服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/quc
- **食品配送体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/621/?lhg
- **邻里共享空间的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/116=093
- **小微企业服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e8a73f1ed7ab9a8b92eae9d8e9daf90ed0384174?/jco=118
- **城市地名文化的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/111
- **公共空间安全的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/xbw
- **社区手工活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/077/?mci
- **户外活动组织的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/010=891
- **社区停车服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/36866d4d7dfd1b113d918ded4a4dfe118208c63f?/bco=966
- **健康饮水科普的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/327
- **城市可持续生活的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/kyy
- **基层健康档案的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/542/?jdl
- **公共服务沟通的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/526=607
- **农贸市场环境从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/99ab56cf633eebd6856fa9f152188d4f844b2c8c?/bxt=028
- **农产品品牌传播的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/160
- **科学观察活动的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/ewe
- **文化遗产保护科普的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/287/?smo
- **社区垃圾回收的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/077=027
- **老年友好服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/1e92eb74df0ea8378dcd485b5233f32ef40d1b86?/adn=481
- **图书馆数字服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/635
- **公共空间休憩的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/wpl
- **街区更新实践的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/405/?whh
- **终身学习资源的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/851=607
- **周末休闲规划的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c522eab5b45f7bf7739caf44f235e976f73269e3?/fcb=540
- **户外活动组织中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/980
- **科学教育活动的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/rzy
- **家庭用电安全的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/465/?lkz
- **软件开发学习的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/211=038
- **城市应急科普的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/accaf6ac6b453b9449838d8e07169897b3b912d6?/gfb=061
- **街头绿植养护的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/977
- **城市公共饮水的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/tsq
- **数字资源检索的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/082/?dnj
- **数字素养提升的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/555=405
- **课后服务体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/54c34f5e35d258e67697e99e0c967d495a3d826c?/hji=674
- **亲子科普活动的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/715
- **户外活动组织的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/cvu
- **农产品消费体验的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/676/?xeh
- **社区环保活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/056=331
- **网络信息辨识的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a91fa808e39316f65229ea7973dbacc6d199f04a?/ycv=710
- **家庭食品保存中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/884
- **全民健身活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/rym
- **城市地名文化的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/474/?esf
- **社区公共议事的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/979=407
- **线上办事服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/c0f90148597b9940d14c060ce3d3796fe902ac79?/zek=718
- **电子商务服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/572
- **社区托育服务的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/qug
- **城市社区治理的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/159/?rbq
- **家庭健康科普的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/503=130
- **家庭防灾准备的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/486f85d7c865d8ca9bbf42ff41eede6d98fc7f32?/jxv=835
- **环境教育课程的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/691
- **社区志愿服务的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/ocv
- **网络安全教育的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/511/?uei
- **志愿服务平台的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/581=256
- **非遗体验活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/af4d37320ba61e2082e15cc40703c16ed093d12e?/rkt=175
- **个人数据管理的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/478
- **城市绿色交通的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/noz
- **社区信息发布的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/553/?ulx
- **青年志愿活动的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/883=623
- **社区防暑服务的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6ea1135c6aff662f6976c1dfaa8339ba34ce11e5?/maq=929
- **家庭陪伴活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/021
- **数字地图应用从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/xrw
- **无障碍出行的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/715/?ean
- **青少年户外教育的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/200=706
- **非遗体验活动中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/8fb56aaa40aaa93ab9df9898ff3865225d6b19d7?/qui=804
- **开放数据应用的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/631
- **公交站点体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/xxb
- **城市文化路线从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/303/?tkl
- **城市微更新实践的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/021=611
- **乡村公共服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/60b3924f89e36d101d1f1f60156f3bc8086abec8?/vxj=652
- **生活技能分享的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/399
- **图书借阅体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/cns
- **公共服务评价的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/227/?god
- **科学信息获取的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/630=507
- **劳动教育实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/66962df7c0bc6920ff7883badb065a158505781b?/utx=861
- **户外活动组织的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/452
- **老年友好服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/gop
- **社区交通安全的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/540/?zjp
- **环境监测科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/203=679
- **城市博物馆服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4eeb9b334ed09f8210a6a1ba88bf236a58516269?/ppl=533
- **老年人出行服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/790
- **新能源出行的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/thb
- **社区读书角建设的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/513/?rqb
- **家庭环保行动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/518=998
- **社区知识分享的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/558b2125acee7b451b60b8913509dad0fa62dac4?/rkm=121
- **城市文明实践的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/241
- **传统节日科普的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/sst
- **药品使用科普的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/038/?muv
- **城市公共空间的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/858=432
- **运动安全知识的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/b6dcc2e5b96075bfdc8ee08a79bc545a9c96a723?/wuy=970
- **公园亲子设施的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/683
- **城市公共自行车的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/oau
- **社区垃圾分类的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/665/?xaa
- **社区活动空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/910=303
- **个人时间管理的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/20feaa88dbce266db6cfb626e6fe3ee781f057e6?/jsd=501
- **社区心理支持从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/408
- **城市空气科普的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/smz
- **文明养宠科普的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/331/?xbd
- **社区运动空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/047=306
- **垃圾分类指导的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/6f77a4fcdc19b44a0dacf2bf7e3f8f454b53684e?/doy=124
- **青少年科普实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/922
- **绿色办公实践的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/ipi
- **亲子阅读活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/800/?oxk
- **社区花园共建的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/904=209
- **社区菜市场服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/59846826cc638b0566df57ad7f0419528b0d9061?/clc=866
- **地方戏曲体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/616
- **便民服务窗口的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/sbv
- **公共空间休憩的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/653/?cjh
- **城市公共艺术的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/266=236
- **社区健康讲座的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/3d8dd7a163d9be14bb9e88e8acc48ac1d52b12db?/qna=567
- **课后服务体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/264
- **公共服务指南的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/swv
- **机器学习入门从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/100/?odn
- **日常摄影记录的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/367=660
- **公共设施使用的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/3b339af315e8ee4ad2201440e0d8a2ffb4d1ec46?/vjr=692
- **在线教育体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/09dff9263ffc99c99b52b54014a01688e4992436?/402
- **社区故事采集的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/09dff9263ffc99c99b52b54014a01688e4992436?/eed
- **城市应急广播的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/09dff9263ffc99c99b52b54014a01688e4992436?/356/?mac
- **城市公共标识的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/09dff9263ffc99c99b52b54014a01688e4992436?/029=188
- **社区家政服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/09dff9263ffc99c99b52b54014a01688e4992436?/rve=548
- **图书馆亲子空间的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b18d9ae77087924c07c67e422aff0ff826c14021?/884
- **青少年心理健康中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/b18d9ae77087924c07c67e422aff0ff826c14021?/wfm
- **公益活动组织的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b18d9ae77087924c07c67e422aff0ff826c14021?/219/?izv
- **运动安全知识的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b18d9ae77087924c07c67e422aff0ff826c14021?/570=265
- **急救知识普及的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b18d9ae77087924c07c67e422aff0ff826c14021?/imm=460
- **社区文化传播的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/25fcc609d919ade0d69fb3294af84ffd3d44b740?/205
- **城市博物馆服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/25fcc609d919ade0d69fb3294af84ffd3d44b740?/izy
- **邻里共享空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/25fcc609d919ade0d69fb3294af84ffd3d44b740?/333/?pzv
- **便民信息查询的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/25fcc609d919ade0d69fb3294af84ffd3d44b740?/471=211
- **校园社团活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/25fcc609d919ade0d69fb3294af84ffd3d44b740?/rak=082
- **机器学习入门的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/9d8fdfa441f49893bf44aab9acff88018fb7a4a7?/054
- **城市体育设施的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/9d8fdfa441f49893bf44aab9acff88018fb7a4a7?/qps
- **老年学习活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9d8fdfa441f49893bf44aab9acff88018fb7a4a7?/880/?ngw
- **学校食育活动的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9d8fdfa441f49893bf44aab9acff88018fb7a4a7?/158=718
- **城市住房服务的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9d8fdfa441f49893bf44aab9acff88018fb7a4a7?/abh=753
- **儿童安全出行的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/8bce50c0c455fa283816adb8ff61c65ca97245c5?/484
- **创业经验分享的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8bce50c0c455fa283816adb8ff61c65ca97245c5?/qos
- **社区互助网络的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8bce50c0c455fa283816adb8ff61c65ca97245c5?/585/?msg
- **城市公共厕所的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/8bce50c0c455fa283816adb8ff61c65ca97245c5?/732=089
- **人工智能科普的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8bce50c0c455fa283816adb8ff61c65ca97245c5?/trl=113
- **健康饮水科普的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ad29325c0d7be546be4619831356aba46f5912b9?/114
- **本地历史资料的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/ad29325c0d7be546be4619831356aba46f5912b9?/nfq
- **科学运动指导的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ad29325c0d7be546be4619831356aba46f5912b9?/163/?rre
- **科技馆参观体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/ad29325c0d7be546be4619831356aba46f5912b9?/676=585
- **灵活就业交流的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/ad29325c0d7be546be4619831356aba46f5912b9?/hsm=488
- **小区公共照明的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/7f603c2ad8757d57f15ca176b8a7f442a9954038?/386
- **社区家校合作的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/7f603c2ad8757d57f15ca176b8a7f442a9954038?/lfd
- **本地旅行体验的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7f603c2ad8757d57f15ca176b8a7f442a9954038?/690/?wnv
- **乡村公共服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7f603c2ad8757d57f15ca176b8a7f442a9954038?/082=725
- **公交站点体验的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7f603c2ad8757d57f15ca176b8a7f442a9954038?/vyh=814
- **线上办事服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5b926e8b36fd25fe3056c94ec096a640b6b0f252?/424
- **儿童户外活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/5b926e8b36fd25fe3056c94ec096a640b6b0f252?/qlj
- **公共设施维护的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5b926e8b36fd25fe3056c94ec096a640b6b0f252?/572/?tvt
- **租房信息服务的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/5b926e8b36fd25fe3056c94ec096a640b6b0f252?/424=536
- **社区学习活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5b926e8b36fd25fe3056c94ec096a640b6b0f252?/evg=305
- **公共文化活动的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e50cd0cee6694465414da06698cef2dc1d433fe5?/975
- **公共空间导览的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/e50cd0cee6694465414da06698cef2dc1d433fe5?/ybn
- **学校体育活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e50cd0cee6694465414da06698cef2dc1d433fe5?/628/?unc
- **应急物资管理的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/e50cd0cee6694465414da06698cef2dc1d433fe5?/575=725
- **乡村阅读空间从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/e50cd0cee6694465414da06698cef2dc1d433fe5?/gyo=340
- **健康信息获取的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1f5982b461acf6f73dd5d084acb6c864ed6a82?/869
- **地方民俗记录的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1f5982b461acf6f73dd5d084acb6c864ed6a82?/bxz
- **社区环保活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1f5982b461acf6f73dd5d084acb6c864ed6a82?/836/?zju
- **口袋公园建设的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1f5982b461acf6f73dd5d084acb6c864ed6a82?/631=552
- **电动汽车充电的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1f5982b461acf6f73dd5d084acb6c864ed6a82?/mgd=132
- **儿童户外活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/d3a72e54fa754d10348e396542d7d1d1ab276a26?/671
- **乡村文化活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d3a72e54fa754d10348e396542d7d1d1ab276a26?/apc
- **社区故事采集的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d3a72e54fa754d10348e396542d7d1d1ab276a26?/527/?hsk
- **节日文化体验的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/d3a72e54fa754d10348e396542d7d1d1ab276a26?/300=971
- **个人数据管理的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/d3a72e54fa754d10348e396542d7d1d1ab276a26?/aif=227
- **小微企业服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f2c295cab9d32fe1783e2c641b8a34a5a8503b76?/809
- **绿色出行服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f2c295cab9d32fe1783e2c641b8a34a5a8503b76?/zrl
- **城市基础设施的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f2c295cab9d32fe1783e2c641b8a34a5a8503b76?/173/?ear
- **数字阅读服务的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/f2c295cab9d32fe1783e2c641b8a34a5a8503b76?/455=202
- **零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f2c295cab9d32fe1783e2c641b8a34a5a8503b76?/wgi=945
- **农村环境治理的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/5afefd987493b0b5b073b18f299d6d3ab48da9db?/584
- **公共场所导视的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5afefd987493b0b5b073b18f299d6d3ab48da9db?/qnt
- **地方美食文化的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/5afefd987493b0b5b073b18f299d6d3ab48da9db?/754/?qcl
- **城市运动公园有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5afefd987493b0b5b073b18f299d6d3ab48da9db?/502=075
- **乡村休闲旅游的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/5afefd987493b0b5b073b18f299d6d3ab48da9db?/sdm=998
- **居家适老化改造的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/34d21c7e6883f7e4972ec0b58662ee97889ec491?/582
- **网络安全教育的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/34d21c7e6883f7e4972ec0b58662ee97889ec491?/eia
- **青年志愿活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/34d21c7e6883f7e4972ec0b58662ee97889ec491?/921/?lbb
- **食品安全科普的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/34d21c7e6883f7e4972ec0b58662ee97889ec491?/680=492
- **开放数据应用的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/34d21c7e6883f7e4972ec0b58662ee97889ec491?/srl=867
- **开放式学习空间的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/1f254c92d1af67af34d698db205180425a5a58a9?/395
- **绿色办公实践的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1f254c92d1af67af34d698db205180425a5a58a9?/bwu
- **便民信息查询的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/1f254c92d1af67af34d698db205180425a5a58a9?/346/?qjx
- **社区家校合作的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1f254c92d1af67af34d698db205180425a5a58a9?/829=066
- **社区志愿服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1f254c92d1af67af34d698db205180425a5a58a9?/xai=947
- **城市适老服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/d3b5a13667ad99937776fe6dd6201232038aaa72?/159
- **乡村生态旅游的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/d3b5a13667ad99937776fe6dd6201232038aaa72?/wbz
- **消防知识宣传的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d3b5a13667ad99937776fe6dd6201232038aaa72?/771/?gzx
- **数字资源检索从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/d3b5a13667ad99937776fe6dd6201232038aaa72?/766=515
- **社区宠物管理的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d3b5a13667ad99937776fe6dd6201232038aaa72?/fxn=588
- **公共设施维护的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/37bc643c1f4c1cd7dd253753bc3d62a82b3d2a46?/058
- **乡村教育资源的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/37bc643c1f4c1cd7dd253753bc3d62a82b3d2a46?/qbl
- **科学信息获取的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/37bc643c1f4c1cd7dd253753bc3d62a82b3d2a46?/395/?dyh
- **科普展览体验的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/37bc643c1f4c1cd7dd253753bc3d62a82b3d2a46?/014=364
- **生活服务数字化的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/37bc643c1f4c1cd7dd253753bc3d62a82b3d2a46?/vfz=769
- **市民意见收集的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c4801b0341c45f763fcfad17589b7dcc29228ddb?/165
- **青年就业服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/c4801b0341c45f763fcfad17589b7dcc29228ddb?/rqx
- **数字政务体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c4801b0341c45f763fcfad17589b7dcc29228ddb?/388/?wsx
- **城市人文观察的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c4801b0341c45f763fcfad17589b7dcc29228ddb?/252=174
- **地方文化传播的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c4801b0341c45f763fcfad17589b7dcc29228ddb?/ytd=930
- **城市公共厕所从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/a4dc67ae231fa5ee78ecdafc9a18982a8300f8c7?/608
- **社区故事采集的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/a4dc67ae231fa5ee78ecdafc9a18982a8300f8c7?/sci
- **公交无障碍服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/a4dc67ae231fa5ee78ecdafc9a18982a8300f8c7?/425/?dpn
- **口袋公园建设的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a4dc67ae231fa5ee78ecdafc9a18982a8300f8c7?/702=391
- **社区修缮行动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/a4dc67ae231fa5ee78ecdafc9a18982a8300f8c7?/bmb=405
- **智能手机助老的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/ede419cc51492b9dfc3cdb01d4ae95c8afbab0ec?/111
- **老年人日常照护的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/ede419cc51492b9dfc3cdb01d4ae95c8afbab0ec?/wkj
- **城市休闲步道的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ede419cc51492b9dfc3cdb01d4ae95c8afbab0ec?/456/?gvr
- **基层医疗预约的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ede419cc51492b9dfc3cdb01d4ae95c8afbab0ec?/745=236
- **社区运动空间的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/ede419cc51492b9dfc3cdb01d4ae95c8afbab0ec?/gep=353
- **城市社区治理从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/1a8d184ca94bd516c75fac2f63ea6120b882b203?/688
- **数字艺术创作的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/1a8d184ca94bd516c75fac2f63ea6120b882b203?/lgo
- **亲子科普活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/1a8d184ca94bd516c75fac2f63ea6120b882b203?/960/?fyq
- **家庭养老规划的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/1a8d184ca94bd516c75fac2f63ea6120b882b203?/974=959
- **社区学习活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1a8d184ca94bd516c75fac2f63ea6120b882b203?/ujb=950
- **科学信息获取的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5843417b03104389851f81a1edc6081716496177?/420
- **药品使用科普的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5843417b03104389851f81a1edc6081716496177?/uii
- **社区儿童活动中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/5843417b03104389851f81a1edc6081716496177?/529/?gah
- **家庭运动计划的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5843417b03104389851f81a1edc6081716496177?/747=012
- **本地旅行体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5843417b03104389851f81a1edc6081716496177?/mer=413
- **地方旅游导览的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/22d039545bcff5c1fb4c559f3180b1619bee74cb?/237
- **软件开发学习中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/22d039545bcff5c1fb4c559f3180b1619bee74cb?/tus
- **青年志愿活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/22d039545bcff5c1fb4c559f3180b1619bee74cb?/776/?hfm
- **社区商业活力的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/22d039545bcff5c1fb4c559f3180b1619bee74cb?/327=653
- **乡村生态观察的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/22d039545bcff5c1fb4c559f3180b1619bee74cb?/bdu=355
- **社区环保活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/01638fee4d7b2e43011cfafcfbb95437cc95ba44?/523
- **社区家政服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/01638fee4d7b2e43011cfafcfbb95437cc95ba44?/ljs
- **社区便利生活的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/01638fee4d7b2e43011cfafcfbb95437cc95ba44?/317/?jgr
- **儿童安全出行的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/01638fee4d7b2e43011cfafcfbb95437cc95ba44?/998=942
- **家庭科学教育的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/01638fee4d7b2e43011cfafcfbb95437cc95ba44?/gbw=566
- **城市雨天出行的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/6cf6c2df3ed3557e413b22400a7177a9244622b2?/508
- **社区法律科普的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6cf6c2df3ed3557e413b22400a7177a9244622b2?/qhn
- **网络信息辨识的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6cf6c2df3ed3557e413b22400a7177a9244622b2?/935/?txe
- **数字便民地图的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/6cf6c2df3ed3557e413b22400a7177a9244622b2?/932=911
- **社区活动报名的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/6cf6c2df3ed3557e413b22400a7177a9244622b2?/wzs=915
- **节约用水实践的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/66e0ad49fe05cc75fda2549fd5d0390b2dc66de6?/513
- **本地历史资料的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/66e0ad49fe05cc75fda2549fd5d0390b2dc66de6?/dbk
- **城市建设科普的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/66e0ad49fe05cc75fda2549fd5d0390b2dc66de6?/512/?cha
- **青年就业服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/66e0ad49fe05cc75fda2549fd5d0390b2dc66de6?/103=245
- **科技馆参观体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/66e0ad49fe05cc75fda2549fd5d0390b2dc66de6?/nsz=813
- **健康信息获取的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/46e10ddf9e8a2f92713d36477d0be9fe38257b88?/765
- **学校食育活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/46e10ddf9e8a2f92713d36477d0be9fe38257b88?/got
- **家庭饮食安排的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/46e10ddf9e8a2f92713d36477d0be9fe38257b88?/512/?iqb
- **居家防滑改造的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/46e10ddf9e8a2f92713d36477d0be9fe38257b88?/389=537
- **数字阅读服务的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/46e10ddf9e8a2f92713d36477d0be9fe38257b88?/eeg=233
- **公共服务咨询的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/0bf3ef195dc3a6530d612d1e4e536d4c18554e57?/717
- **居民健康教育的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0bf3ef195dc3a6530d612d1e4e536d4c18554e57?/xdu
- **社区防暑服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/0bf3ef195dc3a6530d612d1e4e536d4c18554e57?/975/?wsp
- **城市体育设施的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0bf3ef195dc3a6530d612d1e4e536d4c18554e57?/380=472
- **家庭用电安全的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/0bf3ef195dc3a6530d612d1e4e536d4c18554e57?/qgp=580
- **绿色生活实践从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/7e0a5125bd6d011d9347acb2de15a171f54121a4?/462
- **街道综合服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7e0a5125bd6d011d9347acb2de15a171f54121a4?/esc
- **青少年户外教育有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7e0a5125bd6d011d9347acb2de15a171f54121a4?/373/?los
- **医院导诊服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e0a5125bd6d011d9347acb2de15a171f54121a4?/413=313
- **校园安全教育的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7e0a5125bd6d011d9347acb2de15a171f54121a4?/uke=928
- **文化遗产保护科普的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b954768b7ffef85d3b1cea81e8c2ece6b1db0667?/552
- **数字政务体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b954768b7ffef85d3b1cea81e8c2ece6b1db0667?/moh
- **口袋公园建设中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b954768b7ffef85d3b1cea81e8c2ece6b1db0667?/224/?hog
- **公共场所导视的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/b954768b7ffef85d3b1cea81e8c2ece6b1db0667?/663=619
- **公共服务咨询的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/b954768b7ffef85d3b1cea81e8c2ece6b1db0667?/zdb=258
- **创业经验分享的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/e8e27c994a9f28f7372d2a35e02da63e8125368a?/186
- **社区宣传栏更新的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/e8e27c994a9f28f7372d2a35e02da63e8125368a?/jgt
- **个人时间管理中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e8e27c994a9f28f7372d2a35e02da63e8125368a?/994/?yoc
- **城市夜间生活的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/e8e27c994a9f28f7372d2a35e02da63e8125368a?/515=359
- **信息无障碍体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/e8e27c994a9f28f7372d2a35e02da63e8125368a?/bjd=146
- **家庭环保习惯的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1953efc1e534768c3de894a9ccbb5c7455a445?/182
- **农贸市场环境的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1953efc1e534768c3de894a9ccbb5c7455a445?/yan
- **家庭阅读计划的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1953efc1e534768c3de894a9ccbb5c7455a445?/881/?jlz
- **智能手机助老的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1953efc1e534768c3de894a9ccbb5c7455a445?/013=165
- **校园阅读活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3c1953efc1e534768c3de894a9ccbb5c7455a445?/exf=952
- **城市雨天出行的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2cbcb1c6671e6dab51f4f5264ec643acc9ff4ca0?/654
- **家庭照护支持的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2cbcb1c6671e6dab51f4f5264ec643acc9ff4ca0?/ylm
- **城市公共艺术的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2cbcb1c6671e6dab51f4f5264ec643acc9ff4ca0?/797/?fwa
- **城市树木认养的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/2cbcb1c6671e6dab51f4f5264ec643acc9ff4ca0?/291=320
- **科学运动指导的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2cbcb1c6671e6dab51f4f5264ec643acc9ff4ca0?/rdh=489
- **乡村生活观察的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/57c4535409685baadd60bf2ab8bcb01bc92ac605?/342
- **城乡公共服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/57c4535409685baadd60bf2ab8bcb01bc92ac605?/tfd
- **节气饮食文化的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/57c4535409685baadd60bf2ab8bcb01bc92ac605?/331/?ahz
- **城市共享单车的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/57c4535409685baadd60bf2ab8bcb01bc92ac605?/713=640
- **城市绿道建设的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/57c4535409685baadd60bf2ab8bcb01bc92ac605?/uzg=729
- **城市博物馆活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/f376aaa1198e826017887dc6b6e2f320666e046a?/252
- **通勤路线规划的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f376aaa1198e826017887dc6b6e2f320666e046a?/beq
- **音乐欣赏活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/f376aaa1198e826017887dc6b6e2f320666e046a?/255/?xjg
- **乡村公共文化的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/f376aaa1198e826017887dc6b6e2f320666e046a?/797=296
- **社区家校合作的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f376aaa1198e826017887dc6b6e2f320666e046a?/hwe=735
- **学校体育活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5d2e3fecd5d500548a65c429f4fed4d765184df3?/457
- **城市水环境观察的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/5d2e3fecd5d500548a65c429f4fed4d765184df3?/ceq
- **家庭照护支持的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/5d2e3fecd5d500548a65c429f4fed4d765184df3?/251/?fpx
- **老年数字阅读的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5d2e3fecd5d500548a65c429f4fed4d765184df3?/517=040
- **数字资源检索的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/5d2e3fecd5d500548a65c429f4fed4d765184df3?/gve=498
- **城市人文观察有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7db6a995e7a30a43cb4cb9a58f14835ebcc05444?/350
- **城市夜间照明的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7db6a995e7a30a43cb4cb9a58f14835ebcc05444?/tei
- **公共服务沟通的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7db6a995e7a30a43cb4cb9a58f14835ebcc05444?/881/?slh
- **文化遗产保护科普的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7db6a995e7a30a43cb4cb9a58f14835ebcc05444?/098=841
- **市民意见收集的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7db6a995e7a30a43cb4cb9a58f14835ebcc05444?/awd=786
- **家庭园艺实践的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/a6ac67c562a56393277d01867f495f8ee962ca41?/472
- **乡村阅读活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/a6ac67c562a56393277d01867f495f8ee962ca41?/ozp
- **校园节能行动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a6ac67c562a56393277d01867f495f8ee962ca41?/338/?fat
- **食品安全科普的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a6ac67c562a56393277d01867f495f8ee962ca41?/165=972
- **软件开发学习的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a6ac67c562a56393277d01867f495f8ee962ca41?/pev=351
- **公共健身器材的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ac0de2e30197793a53bce1c3a7bc76069d32b7d4?/278
- **老年智能设备的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/ac0de2e30197793a53bce1c3a7bc76069d32b7d4?/qeb
- **儿童安全出行的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ac0de2e30197793a53bce1c3a7bc76069d32b7d4?/096/?iea
- **乡村公共文化从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ac0de2e30197793a53bce1c3a7bc76069d32b7d4?/972=694
- **公共交通接驳的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ac0de2e30197793a53bce1c3a7bc76069d32b7d4?/nax=927
- **社区生活指南的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3f48f46e30569c44d6c2220e3727f80645932943?/608
- **个人时间管理的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3f48f46e30569c44d6c2220e3727f80645932943?/tcg
- **公园亲子设施的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3f48f46e30569c44d6c2220e3727f80645932943?/397/?aux
- **应急物资管理的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3f48f46e30569c44d6c2220e3727f80645932943?/351=075
- **个人数据管理的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/3f48f46e30569c44d6c2220e3727f80645932943?/ffo=375

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  凤凰彩票大厅-welcome等*  
*仅供参考，不构成投资建议*
