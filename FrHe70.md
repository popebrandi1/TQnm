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

- **城市文明实践的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/eb1fe3937142766b91ea3eab3181d71d1a288c32?/393
- **城市公共座椅的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/eb1fe3937142766b91ea3eab3181d71d1a288c32?/vyc
- **小区电梯维护的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/eb1fe3937142766b91ea3eab3181d71d1a288c32?/129/?pej
- **城市夜间照明的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/eb1fe3937142766b91ea3eab3181d71d1a288c32?/025=482
- **儿童阅读角的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/eb1fe3937142766b91ea3eab3181d71d1a288c32?/wkq=726
- **城市公共厕所的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b5bf1278180e05129619595dfb417dc1e93046d0?/080
- **社区信息发布的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b5bf1278180e05129619595dfb417dc1e93046d0?/myd
- **远程协作工具的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/b5bf1278180e05129619595dfb417dc1e93046d0?/964/?may
- **智慧城市体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/b5bf1278180e05129619595dfb417dc1e93046d0?/550=276
- **城市运动公园的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/b5bf1278180e05129619595dfb417dc1e93046d0?/urx=095
- **城市雨天出行的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/74533c27cde011961cad294ce15aa00f2dbda6da?/901
- **开放式学习空间的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/74533c27cde011961cad294ce15aa00f2dbda6da?/ome
- **社区垃圾回收的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/74533c27cde011961cad294ce15aa00f2dbda6da?/665/?syw
- **公共空间休憩的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/74533c27cde011961cad294ce15aa00f2dbda6da?/225=113
- **社区生活指南中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/74533c27cde011961cad294ce15aa00f2dbda6da?/zpt=755
- **社区协商议事的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8ad2e8fd2ec9b6bcee5b0b33f38afa6191bf5db6?/296
- **课后服务体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/8ad2e8fd2ec9b6bcee5b0b33f38afa6191bf5db6?/wqz
- **社区老年食堂的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/8ad2e8fd2ec9b6bcee5b0b33f38afa6191bf5db6?/092/?bkv
- **老年学习活动的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/8ad2e8fd2ec9b6bcee5b0b33f38afa6191bf5db6?/071=731
- **数字课堂应用的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8ad2e8fd2ec9b6bcee5b0b33f38afa6191bf5db6?/qpi=684
- **城市共享单车的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/87b1704ec8c967d07a0d3689d320cb0a96578112?/852
- **街区更新实践的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/87b1704ec8c967d07a0d3689d320cb0a96578112?/slm
- **城市游园体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/87b1704ec8c967d07a0d3689d320cb0a96578112?/933/?rja
- **社区家政服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/87b1704ec8c967d07a0d3689d320cb0a96578112?/220=471
- **基层医疗预约的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/87b1704ec8c967d07a0d3689d320cb0a96578112?/hsg=576
- **城市展览体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/671845d8cbae27d4f9a2e71af4d5e9e165714bca?/412
- **城乡交流活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/671845d8cbae27d4f9a2e71af4d5e9e165714bca?/upl
- **在线学习体验的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/671845d8cbae27d4f9a2e71af4d5e9e165714bca?/744/?qcm
- **社区法律科普的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/671845d8cbae27d4f9a2e71af4d5e9e165714bca?/317=941
- **文化讲座服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/671845d8cbae27d4f9a2e71af4d5e9e165714bca?/gnk=471
- **气象科普传播的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/ca059bd3c73b7cb550c717b5bf5038ed25087e22?/650
- **数字档案服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/ca059bd3c73b7cb550c717b5bf5038ed25087e22?/vjb
- **网络信息辨识的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/ca059bd3c73b7cb550c717b5bf5038ed25087e22?/445/?yjg
- **环境教育课程有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ca059bd3c73b7cb550c717b5bf5038ed25087e22?/446=954
- **农产品品牌传播的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/ca059bd3c73b7cb550c717b5bf5038ed25087e22?/txd=815
- **健康步道使用的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/2dbbdcd18e176b07cb4537939c7f4eba92b3edf1?/288
- **社区文化传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2dbbdcd18e176b07cb4537939c7f4eba92b3edf1?/wzn
- **居家防滑改造有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2dbbdcd18e176b07cb4537939c7f4eba92b3edf1?/286/?rtr
- **开放式学习空间的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/2dbbdcd18e176b07cb4537939c7f4eba92b3edf1?/906=508
- **全民健身活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2dbbdcd18e176b07cb4537939c7f4eba92b3edf1?/kjz=023
- **城市社区治理的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a2c12093aa6a3fd34fc5132bac9df933496d101a?/998
- **节能家电使用的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a2c12093aa6a3fd34fc5132bac9df933496d101a?/okp
- **小区公共照明的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a2c12093aa6a3fd34fc5132bac9df933496d101a?/773/?nis
- **科学教育活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a2c12093aa6a3fd34fc5132bac9df933496d101a?/880=289
- **个人时间管理的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/a2c12093aa6a3fd34fc5132bac9df933496d101a?/abc=438
- **网络信息辨识的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/8324066e86bde2d9ae4aaf97ad68c4336f25eb29?/661
- **新能源出行的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/8324066e86bde2d9ae4aaf97ad68c4336f25eb29?/vvg
- **市民意见收集的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/8324066e86bde2d9ae4aaf97ad68c4336f25eb29?/062/?aoy
- **街区更新实践的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/8324066e86bde2d9ae4aaf97ad68c4336f25eb29?/853=812
- **社区垃圾回收的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/8324066e86bde2d9ae4aaf97ad68c4336f25eb29?/vjr=918
- **社区垃圾回收的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/d03712331e13f0bc635166bc69d034c2ee808b21?/050
- **城市绿色交通的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/d03712331e13f0bc635166bc69d034c2ee808b21?/nlr
- **家庭用电安全的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/d03712331e13f0bc635166bc69d034c2ee808b21?/596/?chc
- **社区共享书架的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d03712331e13f0bc635166bc69d034c2ee808b21?/247=873
- **街区绿化养护的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d03712331e13f0bc635166bc69d034c2ee808b21?/itx=110
- **机器学习入门的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4490a05ee370cef66b86579aac4106ab77ba0fec?/545
- **亲子阅读活动的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/4490a05ee370cef66b86579aac4106ab77ba0fec?/lfq
- **数字资源检索的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/4490a05ee370cef66b86579aac4106ab77ba0fec?/039/?pba
- **儿童友好空间的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/4490a05ee370cef66b86579aac4106ab77ba0fec?/386=426
- **亲子阅读活动的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/4490a05ee370cef66b86579aac4106ab77ba0fec?/hjd=710
- **社区协商议事中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6db073cc5dda023817b63b994b1e1596cb1c0b49?/640
- **社区健康讲座的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6db073cc5dda023817b63b994b1e1596cb1c0b49?/mei
- **绿色出行服务的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6db073cc5dda023817b63b994b1e1596cb1c0b49?/449/?wkg
- **街区绿化养护的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6db073cc5dda023817b63b994b1e1596cb1c0b49?/247=514
- **运动安全知识的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/6db073cc5dda023817b63b994b1e1596cb1c0b49?/ryv=462
- **公共服务预约有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a3c03c529830ae20f81ab26a539523722a15d0e7?/925
- **社区活动策划的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a3c03c529830ae20f81ab26a539523722a15d0e7?/vvl
- **街区小店体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/a3c03c529830ae20f81ab26a539523722a15d0e7?/678/?ibj
- **垃圾分类指导的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a3c03c529830ae20f81ab26a539523722a15d0e7?/841=301
- **健康饮食教育的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/a3c03c529830ae20f81ab26a539523722a15d0e7?/wfd=958
- **城市运动公园的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/8a0da9ebd1bd186933e2848f26bd8c5f0ce8f3af?/623
- **乡村生活观察的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8a0da9ebd1bd186933e2848f26bd8c5f0ce8f3af?/kea
- **在线学习体验的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/8a0da9ebd1bd186933e2848f26bd8c5f0ce8f3af?/198/?cvp
- **城市应急广播的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a0da9ebd1bd186933e2848f26bd8c5f0ce8f3af?/827=075
- **亲子阅读活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8a0da9ebd1bd186933e2848f26bd8c5f0ce8f3af?/bwo=619
- **市民意见收集的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a75268326b94f9c532d3398be9aa399201bf7215?/054
- **家庭运动计划的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a75268326b94f9c532d3398be9aa399201bf7215?/rue
- **安全出行教育的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a75268326b94f9c532d3398be9aa399201bf7215?/373/?zyd
- **社区防暑服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a75268326b94f9c532d3398be9aa399201bf7215?/761=346
- **儿童友好街区的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a75268326b94f9c532d3398be9aa399201bf7215?/cyr=892
- **城市步行友好的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2fe912bdffce013273638faf0d71912ac2a4b8d8?/059
- **社区修缮行动的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/2fe912bdffce013273638faf0d71912ac2a4b8d8?/mro
- **科学运动指导的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2fe912bdffce013273638faf0d71912ac2a4b8d8?/924/?jim
- **家庭节能实践的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2fe912bdffce013273638faf0d71912ac2a4b8d8?/765=383
- **校园阅读活动的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/2fe912bdffce013273638faf0d71912ac2a4b8d8?/mzx=845
- **社区家校合作的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/6ef01960461dab4ee2b34a94c4ab42492210d7b2?/440
- **小微企业服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6ef01960461dab4ee2b34a94c4ab42492210d7b2?/eyd
- **城市社区治理的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/6ef01960461dab4ee2b34a94c4ab42492210d7b2?/089/?hhz
- **邻里共享空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/6ef01960461dab4ee2b34a94c4ab42492210d7b2?/530=806
- **生活技能分享的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6ef01960461dab4ee2b34a94c4ab42492210d7b2?/yoa=537
- **家庭环保行动的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/106384f6efba8f0b8e4e37ce4fcdd76c2913fec0?/694
- **社区防暑服务的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/106384f6efba8f0b8e4e37ce4fcdd76c2913fec0?/ibm
- **家庭养老规划的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/106384f6efba8f0b8e4e37ce4fcdd76c2913fec0?/325/?ohy
- **家庭教育交流的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/106384f6efba8f0b8e4e37ce4fcdd76c2913fec0?/351=281
- **数字公共文化的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/106384f6efba8f0b8e4e37ce4fcdd76c2913fec0?/kck=636
- **社区托育服务的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/39cad57d35382f6d91ac9d14fb0fe648d3301549?/594
- **家庭安全提示的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/39cad57d35382f6d91ac9d14fb0fe648d3301549?/ycb
- **绿色出行服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/39cad57d35382f6d91ac9d14fb0fe648d3301549?/836/?kbm
- **本地旅行体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/39cad57d35382f6d91ac9d14fb0fe648d3301549?/281=873
- **数字创作工具的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/39cad57d35382f6d91ac9d14fb0fe648d3301549?/opq=543
- **消防知识宣传的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/95d7ec43f7fd332e88ea41f75e59e8a6a4dd5774?/343
- **社区休闲设施的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/95d7ec43f7fd332e88ea41f75e59e8a6a4dd5774?/qai
- **数字便民地图的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/95d7ec43f7fd332e88ea41f75e59e8a6a4dd5774?/320/?rux
- **城乡交流活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/95d7ec43f7fd332e88ea41f75e59e8a6a4dd5774?/768=830
- **家庭陪伴活动的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/95d7ec43f7fd332e88ea41f75e59e8a6a4dd5774?/gvo=421
- **城市展览体验的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/675a054511befee262f6592dc8e085929c229223?/917
- **社区互助网络的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/675a054511befee262f6592dc8e085929c229223?/eqf
- **城市步行环境的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/675a054511befee262f6592dc8e085929c229223?/837/?drm
- **科学信息获取的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/675a054511befee262f6592dc8e085929c229223?/127=459
- **社区活动报名的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/675a054511befee262f6592dc8e085929c229223?/sja=267
- **药品使用科普的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/058356f1f4b0c75e37b4e889e52ed5dbc7eaf5d9?/931
- **城市可持续生活的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/058356f1f4b0c75e37b4e889e52ed5dbc7eaf5d9?/ket
- **图书借阅体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/058356f1f4b0c75e37b4e889e52ed5dbc7eaf5d9?/759/?yig
- **城市公共饮水的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/058356f1f4b0c75e37b4e889e52ed5dbc7eaf5d9?/287=649
- **社区便民集市的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/058356f1f4b0c75e37b4e889e52ed5dbc7eaf5d9?/vsj=635
- **乡村生态观察的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/cedfaabd0cdf43572534aeac3b177aa6bc4b092e?/743
- **食品配送体验的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/cedfaabd0cdf43572534aeac3b177aa6bc4b092e?/avg
- **社区科普课堂的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/cedfaabd0cdf43572534aeac3b177aa6bc4b092e?/985/?mha
- **社区修缮行动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/cedfaabd0cdf43572534aeac3b177aa6bc4b092e?/029=735
- **社区商业活力的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/cedfaabd0cdf43572534aeac3b177aa6bc4b092e?/eid=904
- **城市宠物友好空间的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6e1e293da998d5043c06996968b2ae82421cf60?/315
- **社会体育指导的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/f6e1e293da998d5043c06996968b2ae82421cf60?/mug
- **地方旅游导览的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f6e1e293da998d5043c06996968b2ae82421cf60?/300/?cny
- **药品使用科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6e1e293da998d5043c06996968b2ae82421cf60?/471=380
- **家庭理财科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6e1e293da998d5043c06996968b2ae82421cf60?/lgc=726
- **数字创意课程中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c5e7a0f17e90174b9f12e0e46af2e6d04c41ea26?/592
- **城市夜间照明的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c5e7a0f17e90174b9f12e0e46af2e6d04c41ea26?/ndf
- **城市骑行环境的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c5e7a0f17e90174b9f12e0e46af2e6d04c41ea26?/855/?fqj
- **街道综合服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c5e7a0f17e90174b9f12e0e46af2e6d04c41ea26?/794=849
- **城市游园体验的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c5e7a0f17e90174b9f12e0e46af2e6d04c41ea26?/bqh=152
- **公交无障碍服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/040658d90fc60bfc01774089d0bce335c08200f1?/279
- **无障碍信息设计的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/040658d90fc60bfc01774089d0bce335c08200f1?/ulr
- **社区商业活力的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/040658d90fc60bfc01774089d0bce335c08200f1?/791/?yva
- **线上阅读资源的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/040658d90fc60bfc01774089d0bce335c08200f1?/891=240
- **农业科普体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/040658d90fc60bfc01774089d0bce335c08200f1?/fgd=652
- **数字支付体验的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3254e7bac43402424cbf5c66c9c65e276bdb0299?/987
- **城市博物馆服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3254e7bac43402424cbf5c66c9c65e276bdb0299?/kbg
- **公共服务咨询的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3254e7bac43402424cbf5c66c9c65e276bdb0299?/721/?wpm
- **医院导诊服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3254e7bac43402424cbf5c66c9c65e276bdb0299?/918=505
- **乡村阅读活动的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3254e7bac43402424cbf5c66c9c65e276bdb0299?/rcv=224
- **乡村文化空间有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/46c8d4cf3023c63e217578e773b3e0ee9a79648e?/761
- **通勤路线规划的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/46c8d4cf3023c63e217578e773b3e0ee9a79648e?/stk
- **城市地名文化的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/46c8d4cf3023c63e217578e773b3e0ee9a79648e?/694/?sug
- **社区读书角建设的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/46c8d4cf3023c63e217578e773b3e0ee9a79648e?/303=570
- **日常摄影记录的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/46c8d4cf3023c63e217578e773b3e0ee9a79648e?/bul=111
- **城市公共空间的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/57f9416bcfd90566291835043010b62a303e76ff?/674
- **健康饮食教育的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/57f9416bcfd90566291835043010b62a303e76ff?/ndn
- **公共空间安全的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/57f9416bcfd90566291835043010b62a303e76ff?/689/?xtt
- **城市公共艺术中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/57f9416bcfd90566291835043010b62a303e76ff?/438=064
- **乡村文化空间的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/57f9416bcfd90566291835043010b62a303e76ff?/jbo=484
- **邻里互助活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/2e47b59b96080981ab42a3ad4635831d1914f8e3?/036
- **城市共享单车的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2e47b59b96080981ab42a3ad4635831d1914f8e3?/ltj
- **健康步道使用中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/2e47b59b96080981ab42a3ad4635831d1914f8e3?/195/?zlw
- **休闲运动入门的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/2e47b59b96080981ab42a3ad4635831d1914f8e3?/653=544
- **智能家居应用的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2e47b59b96080981ab42a3ad4635831d1914f8e3?/agn=609
- **就业技能培训的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/53cad1b619c2556a3c4c56db22f84c92f0c70120?/608
- **城市步行友好的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/53cad1b619c2556a3c4c56db22f84c92f0c70120?/ska
- **家庭节能设备的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/53cad1b619c2556a3c4c56db22f84c92f0c70120?/729/?lui
- **老旧小区改造的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/53cad1b619c2556a3c4c56db22f84c92f0c70120?/979=823
- **社区学习活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/53cad1b619c2556a3c4c56db22f84c92f0c70120?/kfl=157
- **社区便利生活的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/cf78418e4c4080759428450bd4efe0b6ac897c79?/974
- **公共卫生宣传的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/cf78418e4c4080759428450bd4efe0b6ac897c79?/rdg
- **生活技能分享中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/cf78418e4c4080759428450bd4efe0b6ac897c79?/557/?qyp
- **地方美食文化的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/cf78418e4c4080759428450bd4efe0b6ac897c79?/635=443
- **租房信息服务的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/cf78418e4c4080759428450bd4efe0b6ac897c79?/iyv=775
- **绿色快递包装的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/74b999e448e5d9ae70af145be5ac2da749bafd82?/040
- **居家适老化改造的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/74b999e448e5d9ae70af145be5ac2da749bafd82?/cdd
- **社区活动报名的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/74b999e448e5d9ae70af145be5ac2da749bafd82?/043/?uql
- **校园阅读活动的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/74b999e448e5d9ae70af145be5ac2da749bafd82?/398=732
- **儿童运动体验的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/74b999e448e5d9ae70af145be5ac2da749bafd82?/zow=924
- **城乡交流活动的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c70330332bea1bab6e8001fbfcc4f245992d2b9f?/347
- **数字便民地图的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c70330332bea1bab6e8001fbfcc4f245992d2b9f?/twc
- **公共卫生宣传的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c70330332bea1bab6e8001fbfcc4f245992d2b9f?/636/?cdr
- **无障碍出行的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c70330332bea1bab6e8001fbfcc4f245992d2b9f?/819=024
- **全民健身活动的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c70330332bea1bab6e8001fbfcc4f245992d2b9f?/aph=139
- **城市树木认养的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/18d0abbba211159fcc670a9282f612bfbc440a71?/446
- **老年人日常照护的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/18d0abbba211159fcc670a9282f612bfbc440a71?/xny
- **乡村产业科普的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/18d0abbba211159fcc670a9282f612bfbc440a71?/734/?pca
- **家庭养老规划的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/18d0abbba211159fcc670a9282f612bfbc440a71?/739=335
- **科学运动指导的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/18d0abbba211159fcc670a9282f612bfbc440a71?/rps=020
- **生活技能分享的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/21030faaa460266b6e651ff586d236f805016583?/143
- **文化遗产保护科普的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/21030faaa460266b6e651ff586d236f805016583?/lxd
- **农贸市场环境的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/21030faaa460266b6e651ff586d236f805016583?/389/?uoz
- **青年志愿活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/21030faaa460266b6e651ff586d236f805016583?/893=535
- **城市微更新实践的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/21030faaa460266b6e651ff586d236f805016583?/snj=609
- **科学观察活动的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/0e170a8ddaf1124b0e4be94908bc252c7075ef7b?/492
- **家庭防灾准备的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/0e170a8ddaf1124b0e4be94908bc252c7075ef7b?/uxb
- **文化场馆预约的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0e170a8ddaf1124b0e4be94908bc252c7075ef7b?/262/?rcz
- **社区活动空间的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/0e170a8ddaf1124b0e4be94908bc252c7075ef7b?/859=022
- **乡村生态观察的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0e170a8ddaf1124b0e4be94908bc252c7075ef7b?/eqi=706
- **图书馆数字服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/d0b72cb992a2f6ec3da3ecfeddd1ddfc2acda07b?/829
- **公园无障碍服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/d0b72cb992a2f6ec3da3ecfeddd1ddfc2acda07b?/djs
- **社区健康讲座的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d0b72cb992a2f6ec3da3ecfeddd1ddfc2acda07b?/065/?poh
- **社区生活指南的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/d0b72cb992a2f6ec3da3ecfeddd1ddfc2acda07b?/602=127
- **青少年户外教育的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d0b72cb992a2f6ec3da3ecfeddd1ddfc2acda07b?/wau=935
- **家庭健康管理的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a6bb52b392ce0c2589d71e1ac5d148345a6d5daf?/557
- **城乡交流活动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/a6bb52b392ce0c2589d71e1ac5d148345a6d5daf?/ylq
- **家庭养老规划的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/a6bb52b392ce0c2589d71e1ac5d148345a6d5daf?/003/?cmc
- **城乡公共服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/a6bb52b392ce0c2589d71e1ac5d148345a6d5daf?/654=685
- **物业服务沟通从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/a6bb52b392ce0c2589d71e1ac5d148345a6d5daf?/xgi=022
- **数字支付体验的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/187fa5d71a84a56062c07f233f4439c1378eae66?/353
- **青少年科普实践的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/187fa5d71a84a56062c07f233f4439c1378eae66?/gxq
- **乡村阅读空间的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/187fa5d71a84a56062c07f233f4439c1378eae66?/668/?bgh
- **科学信息获取的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/187fa5d71a84a56062c07f233f4439c1378eae66?/017=992
- **城市游园体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/187fa5d71a84a56062c07f233f4439c1378eae66?/ukb=590
- **乡村阅读空间的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/ca6d66c8ec8e609bd4b7118a1ee31e6f175a4ddb?/152
- **数字阅读服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ca6d66c8ec8e609bd4b7118a1ee31e6f175a4ddb?/kzo
- **公共空间安全的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/ca6d66c8ec8e609bd4b7118a1ee31e6f175a4ddb?/627/?jwe
- **数字便民地图的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/ca6d66c8ec8e609bd4b7118a1ee31e6f175a4ddb?/486=275
- **个人数据管理的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/ca6d66c8ec8e609bd4b7118a1ee31e6f175a4ddb?/tdg=103
- **乡村电商实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ee013ff8b95dd7a30ff29149065c50155936d891?/390
- **小区停车协商的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ee013ff8b95dd7a30ff29149065c50155936d891?/dis
- **家庭防灾准备的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ee013ff8b95dd7a30ff29149065c50155936d891?/425/?zzc
- **老年数字阅读的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ee013ff8b95dd7a30ff29149065c50155936d891?/677=678
- **乡村生态旅游的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/ee013ff8b95dd7a30ff29149065c50155936d891?/wrp=596
- **社区停车服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/99fb1560fd760d3ab376ba61250451a558072438?/482
- **社区家政服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/99fb1560fd760d3ab376ba61250451a558072438?/jmj
- **城市雨天出行的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/99fb1560fd760d3ab376ba61250451a558072438?/605/?kjn
- **社区公共餐饮的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/99fb1560fd760d3ab376ba61250451a558072438?/754=290
- **老年人文化生活的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/99fb1560fd760d3ab376ba61250451a558072438?/ryx=758
- **城市公共自行车的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8b88e5110a0853a712fda4ec4f05a01c72924162?/794
- **数字政务体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8b88e5110a0853a712fda4ec4f05a01c72924162?/boc
- **数字生活课堂的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8b88e5110a0853a712fda4ec4f05a01c72924162?/821/?blo
- **市民热线服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8b88e5110a0853a712fda4ec4f05a01c72924162?/596=136
- **家庭收纳实践的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/8b88e5110a0853a712fda4ec4f05a01c72924162?/wbf=912
- **非遗课堂体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/0a3ff8253fbf7b5e8a2195a92d22c16433acabd2?/635
- **公共空间休憩的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0a3ff8253fbf7b5e8a2195a92d22c16433acabd2?/oic
- **社区安全巡查的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/0a3ff8253fbf7b5e8a2195a92d22c16433acabd2?/495/?oeq
- **城市水环境观察的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/0a3ff8253fbf7b5e8a2195a92d22c16433acabd2?/472=980
- **城市公共自行车的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/0a3ff8253fbf7b5e8a2195a92d22c16433acabd2?/var=052
- **数字生活课堂的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2300a6c88a424ca36283ff1dbfa87555e6d67be3?/874
- **儿童运动体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2300a6c88a424ca36283ff1dbfa87555e6d67be3?/nzz
- **社区花园共建的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2300a6c88a424ca36283ff1dbfa87555e6d67be3?/233/?coj
- **城市人文观察的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/2300a6c88a424ca36283ff1dbfa87555e6d67be3?/940=634
- **公园亲子设施的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/2300a6c88a424ca36283ff1dbfa87555e6d67be3?/uvs=283
- **公交无障碍服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9f9f371a2310dfab379023d5d92209aa8916e0cb?/921
- **社区设施共享的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9f9f371a2310dfab379023d5d92209aa8916e0cb?/abw
- **城市公共自行车从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/9f9f371a2310dfab379023d5d92209aa8916e0cb?/617/?yvh
- **机器人科普活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9f9f371a2310dfab379023d5d92209aa8916e0cb?/468=581
- **邻里共享空间的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9f9f371a2310dfab379023d5d92209aa8916e0cb?/hfk=131
- **节约用水实践的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ae0ddc52bfb5694d02ea590f8692ffd4117b233a?/308
- **机器人科普活动的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ae0ddc52bfb5694d02ea590f8692ffd4117b233a?/uti
- **健康饮食教育的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ae0ddc52bfb5694d02ea590f8692ffd4117b233a?/277/?yfo
- **乡村文化活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ae0ddc52bfb5694d02ea590f8692ffd4117b233a?/861=019
- **社区阅读服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/ae0ddc52bfb5694d02ea590f8692ffd4117b233a?/svs=793
- **社区科普课堂的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/412ec5e31faa8500170829c950c2ef91ed8865ac?/229
- **老年运动活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/412ec5e31faa8500170829c950c2ef91ed8865ac?/ppj
- **家庭节能实践的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/412ec5e31faa8500170829c950c2ef91ed8865ac?/673/?kec
- **节假日出行安排的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/412ec5e31faa8500170829c950c2ef91ed8865ac?/367=517
- **劳动教育实践的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/412ec5e31faa8500170829c950c2ef91ed8865ac?/nkk=991
- **城市生活服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f66bf7ce3bc5dd73c51c106f55c33fc152a34eff?/679
- **社区快递服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f66bf7ce3bc5dd73c51c106f55c33fc152a34eff?/yop
- **家庭志愿活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f66bf7ce3bc5dd73c51c106f55c33fc152a34eff?/578/?nlc
- **城市博物馆服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f66bf7ce3bc5dd73c51c106f55c33fc152a34eff?/733=928
- **劳动教育实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f66bf7ce3bc5dd73c51c106f55c33fc152a34eff?/swb=427
- **社区环保活动的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/9e01928e3b93c13dd3380039380c6a2573be1b67?/847
- **科技馆参观体验的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/9e01928e3b93c13dd3380039380c6a2573be1b67?/zxj
- **居家防滑改造从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/9e01928e3b93c13dd3380039380c6a2573be1b67?/045/?zla
- **公共设施维护的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/9e01928e3b93c13dd3380039380c6a2573be1b67?/750=260
- **城市休闲步道的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9e01928e3b93c13dd3380039380c6a2573be1b67?/gzu=912
- **城市空气科普的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1849ef56c5e345d58d9d6d7949cfdddb8f1d56c6?/132
- **市民热线服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/1849ef56c5e345d58d9d6d7949cfdddb8f1d56c6?/pye
- **老年学习活动的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1849ef56c5e345d58d9d6d7949cfdddb8f1d56c6?/720/?bor
- **家庭阅读计划的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1849ef56c5e345d58d9d6d7949cfdddb8f1d56c6?/764=827
- **城市体育设施的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1849ef56c5e345d58d9d6d7949cfdddb8f1d56c6?/arg=251
- **数字地图应用的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a0dcc7049bf3e8e099126966234b4b7f98de52fe?/469
- **数字素养提升的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/a0dcc7049bf3e8e099126966234b4b7f98de52fe?/dlz
- **文化讲座服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a0dcc7049bf3e8e099126966234b4b7f98de52fe?/177/?dkf
- **开源技术交流的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a0dcc7049bf3e8e099126966234b4b7f98de52fe?/622=769
- **城市社区治理的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a0dcc7049bf3e8e099126966234b4b7f98de52fe?/dhu=000
- **城市树木认养的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/270cc5a3c3177f2d1b0d4da79160aa69fedc5235?/933
- **家庭饮食安排中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/270cc5a3c3177f2d1b0d4da79160aa69fedc5235?/mbw
- **数字便民地图的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/270cc5a3c3177f2d1b0d4da79160aa69fedc5235?/148/?inn
- **社区法律科普的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/270cc5a3c3177f2d1b0d4da79160aa69fedc5235?/465=096
- **社区运动空间的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/270cc5a3c3177f2d1b0d4da79160aa69fedc5235?/oqt=645
- **社区商业活力的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/858328684fc2d02aa243fc981b90900e3fee54aa?/060
- **城市公共标识的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/858328684fc2d02aa243fc981b90900e3fee54aa?/shk
- **社区艺术活动的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/858328684fc2d02aa243fc981b90900e3fee54aa?/597/?ewp
- **公共服务评价的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/858328684fc2d02aa243fc981b90900e3fee54aa?/569=705
- **城市生活服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/858328684fc2d02aa243fc981b90900e3fee54aa?/mij=217
- **城市适老服务的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/6efa5a906708059dc833867b1a931a24f9745fb3?/288
- **数据分析入门有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6efa5a906708059dc833867b1a931a24f9745fb3?/ano
- **社区家校合作的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6efa5a906708059dc833867b1a931a24f9745fb3?/328/?mkw
- **公共服务数字化的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/6efa5a906708059dc833867b1a931a24f9745fb3?/391=797
- **公共服务数字化的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6efa5a906708059dc833867b1a931a24f9745fb3?/ldv=001
- **地方旅游导览的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/c3c927b142be4a04552d1828eeb5829c6eb17722?/491
- **社区便民集市的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3c927b142be4a04552d1828eeb5829c6eb17722?/npo
- **地方旅游导览的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c3c927b142be4a04552d1828eeb5829c6eb17722?/295/?nlq
- **非遗体验活动的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c3c927b142be4a04552d1828eeb5829c6eb17722?/828=330
- **家庭健康管理的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c3c927b142be4a04552d1828eeb5829c6eb17722?/ziw=277
- **城市步行友好的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/466587d8ffe208e8eda5083c34e9471adf0dc34f?/872
- **儿童友好空间的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/466587d8ffe208e8eda5083c34e9471adf0dc34f?/mbc
- **社区科普课堂的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/466587d8ffe208e8eda5083c34e9471adf0dc34f?/469/?vcb
- **城市人文观察的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/466587d8ffe208e8eda5083c34e9471adf0dc34f?/899=289
- **节日文化体验的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/466587d8ffe208e8eda5083c34e9471adf0dc34f?/bxt=010
- **社区知识分享的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c72e60dfe29e5c8e81177182ce11e9d86aaa2f52?/043
- **绿色办公实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c72e60dfe29e5c8e81177182ce11e9d86aaa2f52?/ikr
- **绿色出行服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/c72e60dfe29e5c8e81177182ce11e9d86aaa2f52?/720/?bei
- **乡村文化空间的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c72e60dfe29e5c8e81177182ce11e9d86aaa2f52?/838=347
- **绿色消费选择的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c72e60dfe29e5c8e81177182ce11e9d86aaa2f52?/eyb=751
- **健康步道使用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/5c1f3d7e08433a12202177a25e46502ad668a4ae?/527
- **社区宣传栏更新的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5c1f3d7e08433a12202177a25e46502ad668a4ae?/gsd
- **数字档案服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5c1f3d7e08433a12202177a25e46502ad668a4ae?/668/?rbu
- **城市文明出行的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5c1f3d7e08433a12202177a25e46502ad668a4ae?/556=112
- **课后服务体验的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/5c1f3d7e08433a12202177a25e46502ad668a4ae?/aab=811
- **网络安全教育从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/38b96aa2e9de2f0e1c441185d7c6d58bc8c134ac?/251
- **数字创意课程的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/38b96aa2e9de2f0e1c441185d7c6d58bc8c134ac?/iyw
- **家庭科学教育的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/38b96aa2e9de2f0e1c441185d7c6d58bc8c134ac?/206/?ghj
- **农产品品牌传播中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/38b96aa2e9de2f0e1c441185d7c6d58bc8c134ac?/126=761
- **科学健身方法的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/38b96aa2e9de2f0e1c441185d7c6d58bc8c134ac?/arr=624
- **农产品品牌传播的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/d65a3b2a0bed0ddd96fa94b2ba4993715b5e3614?/181
- **社区便民服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d65a3b2a0bed0ddd96fa94b2ba4993715b5e3614?/vmq
- **气象科普传播的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d65a3b2a0bed0ddd96fa94b2ba4993715b5e3614?/245/?gdj
- **基层服务创新的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d65a3b2a0bed0ddd96fa94b2ba4993715b5e3614?/376=243
- **城市文明出行的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d65a3b2a0bed0ddd96fa94b2ba4993715b5e3614?/mqs=326
- **城市应急科普的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/2086294560dc127a88197039282c19876d6bde91?/209
- **绿色生活实践的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/2086294560dc127a88197039282c19876d6bde91?/kvi
- **社区家政服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2086294560dc127a88197039282c19876d6bde91?/048/?zmz
- **传统手工艺体验的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2086294560dc127a88197039282c19876d6bde91?/755=630
- **青少年编程学习的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/2086294560dc127a88197039282c19876d6bde91?/gjf=095
- **社区宠物管理的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/8ee4d93fa6a96a128fb5552c3e3c81b857f4ffd8?/609
- **社区信息发布有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8ee4d93fa6a96a128fb5552c3e3c81b857f4ffd8?/ejt
- **市民意见收集的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/8ee4d93fa6a96a128fb5552c3e3c81b857f4ffd8?/475/?pdw
- **社区便利生活的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8ee4d93fa6a96a128fb5552c3e3c81b857f4ffd8?/334=567
- **智能手机助老的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8ee4d93fa6a96a128fb5552c3e3c81b857f4ffd8?/hrh=796
- **青少年科技社团的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/bcc1fc7037652b3ca7a9c36c2e8048784c0a50b3?/711
- **乡村文化活动的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/bcc1fc7037652b3ca7a9c36c2e8048784c0a50b3?/wdr
- **租房信息服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/bcc1fc7037652b3ca7a9c36c2e8048784c0a50b3?/775/?dth
- **校园节能行动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/bcc1fc7037652b3ca7a9c36c2e8048784c0a50b3?/753=169
- **城市公共标识的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/bcc1fc7037652b3ca7a9c36c2e8048784c0a50b3?/gdm=138
- **城市展览体验的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/16b24babfb3b35ebf3e0671b04b9999207c149f8?/206
- **家庭健康管理从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/16b24babfb3b35ebf3e0671b04b9999207c149f8?/rlb
- **家庭节能实践的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/16b24babfb3b35ebf3e0671b04b9999207c149f8?/291/?gvu
- **社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/16b24babfb3b35ebf3e0671b04b9999207c149f8?/549=283
- **城市空气科普的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/16b24babfb3b35ebf3e0671b04b9999207c149f8?/eui=778
- **周末休闲规划的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/4a5731ef8feeb6f1c0ec0bcbe852ce13dfe2c0bc?/323
- **城市博物馆活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/4a5731ef8feeb6f1c0ec0bcbe852ce13dfe2c0bc?/gpz
- **基层健康档案的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/4a5731ef8feeb6f1c0ec0bcbe852ce13dfe2c0bc?/422/?ynu
- **跨代沟通活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/4a5731ef8feeb6f1c0ec0bcbe852ce13dfe2c0bc?/011=740
- **绿色出行服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4a5731ef8feeb6f1c0ec0bcbe852ce13dfe2c0bc?/ptf=249
- **节气饮食文化的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b2a1d01288238a2d87f29515615a2368c2e023d3?/236
- **图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b2a1d01288238a2d87f29515615a2368c2e023d3?/nps
- **休闲运动入门的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b2a1d01288238a2d87f29515615a2368c2e023d3?/032/?vqf
- **城市文化路线的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b2a1d01288238a2d87f29515615a2368c2e023d3?/445=686
- **社区故事采集的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/b2a1d01288238a2d87f29515615a2368c2e023d3?/ksg=114
- **家庭食品保存的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e504495027a3c2c96a7584f591fb5f55163ac0d9?/806
- **社区手工活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/e504495027a3c2c96a7584f591fb5f55163ac0d9?/xql
- **家庭安全提示的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/e504495027a3c2c96a7584f591fb5f55163ac0d9?/450/?yhl
- **科学信息获取的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/e504495027a3c2c96a7584f591fb5f55163ac0d9?/652=811
- **家庭网络使用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e504495027a3c2c96a7584f591fb5f55163ac0d9?/bgk=066
- **乡村生态旅游的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/900c9d7bea7f60ae56ee955093086bc64852a361?/672
- **节日文化体验的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/900c9d7bea7f60ae56ee955093086bc64852a361?/npg
- **社区故事采集的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/900c9d7bea7f60ae56ee955093086bc64852a361?/445/?tcb
- **街道综合服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/900c9d7bea7f60ae56ee955093086bc64852a361?/593=181
- **环境教育课程的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/900c9d7bea7f60ae56ee955093086bc64852a361?/rxz=440
- **家庭急救准备的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6f45fc7dbb690ed0f2d1dffa676e20286dccf51?/383
- **城市雨天出行的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f6f45fc7dbb690ed0f2d1dffa676e20286dccf51?/xmo
- **科技馆参观体验的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/f6f45fc7dbb690ed0f2d1dffa676e20286dccf51?/706/?xpk
- **地方文化传播的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6f45fc7dbb690ed0f2d1dffa676e20286dccf51?/767=869
- **城市噪声观察的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6f45fc7dbb690ed0f2d1dffa676e20286dccf51?/xui=835
- **社区菜市场服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f709f438696335700b73cde5408b93335443baf5?/600
- **非遗体验活动的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f709f438696335700b73cde5408b93335443baf5?/kvj
- **乡村文化活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/f709f438696335700b73cde5408b93335443baf5?/955/?jup
- **社区运动空间的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f709f438696335700b73cde5408b93335443baf5?/139=392
- **科学运动指导的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f709f438696335700b73cde5408b93335443baf5?/tsx=465
- **基层服务创新的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/dc59f0f37371fc8e5c3e5c4f2f1cb8c59b6fc0e0?/923
- **生活技能分享的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/dc59f0f37371fc8e5c3e5c4f2f1cb8c59b6fc0e0?/hwm
- **乡村生活观察的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/dc59f0f37371fc8e5c3e5c4f2f1cb8c59b6fc0e0?/033/?iyx
- **街道综合服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/dc59f0f37371fc8e5c3e5c4f2f1cb8c59b6fc0e0?/044=361
- **公共空间照明的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/dc59f0f37371fc8e5c3e5c4f2f1cb8c59b6fc0e0?/eje=875
- **城市文明出行的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/961a273ccfb849a8e8d99d275f43f7a16efa2fb1?/155
- **小微企业服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/961a273ccfb849a8e8d99d275f43f7a16efa2fb1?/hrk
- **家庭运动计划的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/961a273ccfb849a8e8d99d275f43f7a16efa2fb1?/947/?efh
- **城市公共标识的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/961a273ccfb849a8e8d99d275f43f7a16efa2fb1?/316=716
- **家庭科学教育的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/961a273ccfb849a8e8d99d275f43f7a16efa2fb1?/dtl=739
- **城市慢跑路线从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/a21db914866b58275191cb82258a718adb6e55f6?/582
- **社区宣传栏更新的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a21db914866b58275191cb82258a718adb6e55f6?/tga
- **公共服务咨询的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/a21db914866b58275191cb82258a718adb6e55f6?/565/?cxq
- **全民健身活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a21db914866b58275191cb82258a718adb6e55f6?/183=287
- **公共服务评价的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/a21db914866b58275191cb82258a718adb6e55f6?/lho=735
- **消防知识宣传的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/cc1fd3f73619beca983fe8a126d8789a1faa391d?/974
- **绿色消费选择的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/cc1fd3f73619beca983fe8a126d8789a1faa391d?/blt
- **地方文化传播的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/cc1fd3f73619beca983fe8a126d8789a1faa391d?/925/?yxr
- **急救知识普及的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/cc1fd3f73619beca983fe8a126d8789a1faa391d?/646=538
- **社区老年食堂的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/cc1fd3f73619beca983fe8a126d8789a1faa391d?/gmm=637
- **通勤路线规划的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/e3a5ac7e6a60b487dde9bc72e8d98c11b11441af?/847
- **周末休闲规划的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e3a5ac7e6a60b487dde9bc72e8d98c11b11441af?/pex
- **校园节能行动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e3a5ac7e6a60b487dde9bc72e8d98c11b11441af?/803/?sxy
- **公共文化活动中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/e3a5ac7e6a60b487dde9bc72e8d98c11b11441af?/901=699
- **城市绿道建设的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/e3a5ac7e6a60b487dde9bc72e8d98c11b11441af?/dnr=227
- **社区知识分享的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/aee8fe93cb0650d66021e34015f48c017c7ee971?/548
- **社区公共议事的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/aee8fe93cb0650d66021e34015f48c017c7ee971?/gvb
- **家庭消费规划的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/aee8fe93cb0650d66021e34015f48c017c7ee971?/793/?ryh
- **城市公共饮水从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/aee8fe93cb0650d66021e34015f48c017c7ee971?/308=080
- **社区消防演练的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/aee8fe93cb0650d66021e34015f48c017c7ee971?/ats=630
- **就业技能培训有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/89b783325976f3cdf4816087a52a55b025aabac8?/333
- **乡村文化活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/89b783325976f3cdf4816087a52a55b025aabac8?/eqr
- **开源技术交流的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/89b783325976f3cdf4816087a52a55b025aabac8?/451/?dxa
- **城市公共艺术的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/89b783325976f3cdf4816087a52a55b025aabac8?/925=229
- **街道综合服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/89b783325976f3cdf4816087a52a55b025aabac8?/ftn=828
- **乡村公共阅读的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c2cf3790fc99e80060a397eb5f8b88817bca6e7f?/460
- **城市空气科普的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c2cf3790fc99e80060a397eb5f8b88817bca6e7f?/lvb
- **城市环境志愿行动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/c2cf3790fc99e80060a397eb5f8b88817bca6e7f?/470/?lud
- **节约用水实践的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c2cf3790fc99e80060a397eb5f8b88817bca6e7f?/509=664
- **乡村教育资源的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/c2cf3790fc99e80060a397eb5f8b88817bca6e7f?/zth=502
- **非遗体验活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/7c79aee30371c3620ebd59d9809e83328c003331?/746
- **老年人文化生活的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/7c79aee30371c3620ebd59d9809e83328c003331?/php
- **公共服务评价的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/7c79aee30371c3620ebd59d9809e83328c003331?/969/?zic
- **绿色校园实践的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7c79aee30371c3620ebd59d9809e83328c003331?/991=295
- **社区邻里服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7c79aee30371c3620ebd59d9809e83328c003331?/eic=469
- **科技馆参观体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ea0c40b8301c2a2c64a44b3f087c409574d89253?/379
- **周末休闲规划的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ea0c40b8301c2a2c64a44b3f087c409574d89253?/wte
- **消防知识宣传的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ea0c40b8301c2a2c64a44b3f087c409574d89253?/467/?cue
- **社区体育组织的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ea0c40b8301c2a2c64a44b3f087c409574d89253?/805=034
- **数据分析入门的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/ea0c40b8301c2a2c64a44b3f087c409574d89253?/fik=127
- **街区绿化养护的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ba513ad99070900a7283a87ce3ef2bd99e537a02?/774
- **公共交通信息服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ba513ad99070900a7283a87ce3ef2bd99e537a02?/ivc
- **社区消防演练的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/ba513ad99070900a7283a87ce3ef2bd99e537a02?/791/?qpi
- **创业经验分享的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ba513ad99070900a7283a87ce3ef2bd99e537a02?/801=123
- **安全出行教育的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/ba513ad99070900a7283a87ce3ef2bd99e537a02?/ckm=662
- **数字便民地图的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/14ac7652c907ce07057408af73e4de05c6948651?/908
- **社区阅读服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/14ac7652c907ce07057408af73e4de05c6948651?/kzu
- **城市慢行系统的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/14ac7652c907ce07057408af73e4de05c6948651?/309/?nwm
- **基层健康档案从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/14ac7652c907ce07057408af73e4de05c6948651?/530=163
- **小微企业服务的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/14ac7652c907ce07057408af73e4de05c6948651?/fzj=242
- **便民服务地图的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/f6083f99dcacd164e1a21b85fb5395201c6adcd0?/617
- **乡村休闲旅游的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f6083f99dcacd164e1a21b85fb5395201c6adcd0?/bff
- **基层健康档案的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f6083f99dcacd164e1a21b85fb5395201c6adcd0?/709/?roa
- **街区道路维护的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/f6083f99dcacd164e1a21b85fb5395201c6adcd0?/277=390
- **本地历史资料的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f6083f99dcacd164e1a21b85fb5395201c6adcd0?/qzj=867
- **电动汽车充电的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5fbc7d17e1781d48f56448f1e74918f21f03beb9?/647
- **社区快递服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5fbc7d17e1781d48f56448f1e74918f21f03beb9?/sgg
- **社区活动报名的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/5fbc7d17e1781d48f56448f1e74918f21f03beb9?/714/?nox
- **城市慢行系统的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5fbc7d17e1781d48f56448f1e74918f21f03beb9?/166=462
- **周末休闲规划的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/5fbc7d17e1781d48f56448f1e74918f21f03beb9?/efr=385
- **家庭节能设备的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8c59df6f6944334343fdec7328bc236920667ad9?/159
- **科学信息获取的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/8c59df6f6944334343fdec7328bc236920667ad9?/ung
- **数字创意课程的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8c59df6f6944334343fdec7328bc236920667ad9?/234/?beo
- **社区修缮行动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8c59df6f6944334343fdec7328bc236920667ad9?/752=973
- **城市水环境观察的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8c59df6f6944334343fdec7328bc236920667ad9?/kfw=929
- **志愿者培训交流的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8848fa2cf35629616e1e975193bd90f78b55da4f?/321
- **社区文化节活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8848fa2cf35629616e1e975193bd90f78b55da4f?/cxp
- **生活垃圾回收的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/8848fa2cf35629616e1e975193bd90f78b55da4f?/940/?dcw
- **街区道路维护的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/8848fa2cf35629616e1e975193bd90f78b55da4f?/493=082
- **社区家校合作的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/8848fa2cf35629616e1e975193bd90f78b55da4f?/ksz=049
- **环境监测科普的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/1031708055547f8ce52e61d8a892293d22dbf7b5?/412
- **社区文化节活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/1031708055547f8ce52e61d8a892293d22dbf7b5?/uhu
- **社会体育指导的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/1031708055547f8ce52e61d8a892293d22dbf7b5?/406/?ill
- **社区垃圾回收的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/1031708055547f8ce52e61d8a892293d22dbf7b5?/750=543
- **学校体育活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/1031708055547f8ce52e61d8a892293d22dbf7b5?/qvq=338
- **城市人文观察的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f08b54893bec8aa275f8b17e31d564150fe97376?/326
- **图书馆亲子空间的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/f08b54893bec8aa275f8b17e31d564150fe97376?/woy
- **数字阅读服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/f08b54893bec8aa275f8b17e31d564150fe97376?/633/?cfa
- **公共服务指南的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f08b54893bec8aa275f8b17e31d564150fe97376?/108=866
- **数字支付体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f08b54893bec8aa275f8b17e31d564150fe97376?/ytt=789
- **乡村阅读活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/5cf09b2e62a2302c128fb259d04feb4bd1799cf9?/064
- **家庭教育交流的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/5cf09b2e62a2302c128fb259d04feb4bd1799cf9?/hct
- **灵活就业交流的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5cf09b2e62a2302c128fb259d04feb4bd1799cf9?/810/?vxr
- **公共服务咨询的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5cf09b2e62a2302c128fb259d04feb4bd1799cf9?/426=541
- **街道综合服务的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/5cf09b2e62a2302c128fb259d04feb4bd1799cf9?/oln=244
- **农产品品牌传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/919c0aef4875c81e9f943f54622262b1d4ccab58?/823
- **安全出行教育的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/919c0aef4875c81e9f943f54622262b1d4ccab58?/ddl
- **城市农夫市集的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/919c0aef4875c81e9f943f54622262b1d4ccab58?/311/?gyh
- **街区小店体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/919c0aef4875c81e9f943f54622262b1d4ccab58?/670=545
- **节日文化体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/919c0aef4875c81e9f943f54622262b1d4ccab58?/czy=133
- **社区公共卫生的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c28234adb61e8ca5e13a18818b2ee8663d2c0f8d?/357
- **学校体育活动的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c28234adb61e8ca5e13a18818b2ee8663d2c0f8d?/ogm
- **城市文明实践的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/c28234adb61e8ca5e13a18818b2ee8663d2c0f8d?/672/?vwb
- **数字支付体验的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c28234adb61e8ca5e13a18818b2ee8663d2c0f8d?/425=594
- **社区活动空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/c28234adb61e8ca5e13a18818b2ee8663d2c0f8d?/ysw=323
- **邻里互助活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/69978689aa31f66051d9bebc79d6d0d330c3bd73?/720
- **社区菜市场服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/69978689aa31f66051d9bebc79d6d0d330c3bd73?/sve
- **社区宠物管理中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/69978689aa31f66051d9bebc79d6d0d330c3bd73?/448/?hej
- **儿童户外活动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/69978689aa31f66051d9bebc79d6d0d330c3bd73?/800=318
- **开源技术交流的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/69978689aa31f66051d9bebc79d6d0d330c3bd73?/itn=514
- **社区共享书架的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/fa91967a5254404b6ab29b76a826660e026faec1?/093
- **智能手机助老中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/fa91967a5254404b6ab29b76a826660e026faec1?/jub
- **地方美食文化的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fa91967a5254404b6ab29b76a826660e026faec1?/977/?jvf
- **社区停车服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fa91967a5254404b6ab29b76a826660e026faec1?/472=659
- **无障碍出行的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/fa91967a5254404b6ab29b76a826660e026faec1?/not=420
- **城市便民驿站有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c1370c63813122d4945881fc4c3617753bcc1e1e?/412
- **环境监测科普的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c1370c63813122d4945881fc4c3617753bcc1e1e?/ggf
- **生成式工具使用的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/c1370c63813122d4945881fc4c3617753bcc1e1e?/793/?vml
- **志愿服务平台的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c1370c63813122d4945881fc4c3617753bcc1e1e?/218=616
- **城市绿道建设的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c1370c63813122d4945881fc4c3617753bcc1e1e?/ewf=014
- **公共空间导览的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ab6ee63bf5a2c7500a8dd9faeea33c08a2c4c297?/844
- **公园休闲体验的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ab6ee63bf5a2c7500a8dd9faeea33c08a2c4c297?/eln
- **城市骑行环境的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ab6ee63bf5a2c7500a8dd9faeea33c08a2c4c297?/562/?qsz
- **乡村休闲旅游的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/ab6ee63bf5a2c7500a8dd9faeea33c08a2c4c297?/595=357
- **儿童友好空间的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ab6ee63bf5a2c7500a8dd9faeea33c08a2c4c297?/qsy=881
- **城市基础设施的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/394007654b379b209e062e64c9d1b7a0eb17692a?/470
- **绿色办公实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/394007654b379b209e062e64c9d1b7a0eb17692a?/vfh
- **青少年科普实践的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/394007654b379b209e062e64c9d1b7a0eb17692a?/867/?syh
- **家庭收纳实践的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/394007654b379b209e062e64c9d1b7a0eb17692a?/080=545
- **社会体育指导的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/394007654b379b209e062e64c9d1b7a0eb17692a?/yxu=442
- **急救知识普及的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/42237afaa02a84359b36be5aa8d4cfec7d5d1716?/118
- **城市文化路线的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/42237afaa02a84359b36be5aa8d4cfec7d5d1716?/qdn
- **数字政务体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/42237afaa02a84359b36be5aa8d4cfec7d5d1716?/873/?wgc
- **运动安全知识的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/42237afaa02a84359b36be5aa8d4cfec7d5d1716?/093=482
- **便民信息查询的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/42237afaa02a84359b36be5aa8d4cfec7d5d1716?/rcn=896

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  财源滚滚app官方下载等*  
*仅供参考，不构成投资建议*
