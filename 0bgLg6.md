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

- **社区邻里服务的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/4392482ddb03fc78d856693264e4151eb1a66c74?/iyr
- **城市建设科普的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/4392482ddb03fc78d856693264e4151eb1a66c74?/130/?zmw
- **社区便民集市的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/4392482ddb03fc78d856693264e4151eb1a66c74?/812=873
- **社区宣传栏更新的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/4392482ddb03fc78d856693264e4151eb1a66c74?/cov=578
- **消防知识宣传的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/WIhRHv.md?/282
- **非遗课堂体验的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/WIhRHv.md?/ylz
- **就业技能培训从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/WIhRHv.md?/500/?weo
- **科技馆参观体验的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/WIhRHv.md?/676=626
- **非遗体验活动的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/WIhRHv.md?/iyd=581
- **乡村生态旅游的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md
- **城市慢行系统的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/6795d964261efd76bed7a8c8ec7978e9f06a6a9a?/825
- **儿童户外活动的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/6795d964261efd76bed7a8c8ec7978e9f06a6a9a?/ngu
- **家庭环保习惯的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/6795d964261efd76bed7a8c8ec7978e9f06a6a9a?/890/?fnk
- **社区信息发布的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/6795d964261efd76bed7a8c8ec7978e9f06a6a9a?/741=408
- **城市夜间生活的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/6795d964261efd76bed7a8c8ec7978e9f06a6a9a?/dcj=349
- **街区更新实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md?/167
- **社区健康讲座的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md?/kmt
- **食品安全科普的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md?/237/?kza
- **城市应急科普的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md?/503=605
- **社区花园共建的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tnbx4g.md?/lxa=652
- **社区老年食堂的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md
- **科学运动指导的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/9a08c09a6ca4a47cd64d7bcb91ca5b2ac69582e8?/840
- **公共空间照明的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/9a08c09a6ca4a47cd64d7bcb91ca5b2ac69582e8?/prp
- **社区老年食堂的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/9a08c09a6ca4a47cd64d7bcb91ca5b2ac69582e8?/310/?bfp
- **社区故事采集的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/9a08c09a6ca4a47cd64d7bcb91ca5b2ac69582e8?/752=772
- **社区便民服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/9a08c09a6ca4a47cd64d7bcb91ca5b2ac69582e8?/ypr=483
- **乡村生活观察的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md?/887
- **数据分析入门的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md?/gbf
- **儿童安全出行的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md?/996/?wyb
- **终身学习资源的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md?/972=535
- **家庭消费规划的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HgndIU.md?/smq=914
- **本地历史资料的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md
- **劳动教育实践的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/7bf92ed13e142336c0818843e7e6168afb098c29?/182
- **社区养老服务的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/7bf92ed13e142336c0818843e7e6168afb098c29?/vbi
- **城市树木认养的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/7bf92ed13e142336c0818843e7e6168afb098c29?/107/?uct
- **社区读书角建设的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/7bf92ed13e142336c0818843e7e6168afb098c29?/718=798
- **农业科普体验的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/7bf92ed13e142336c0818843e7e6168afb098c29?/bhx=179
- **食品配送体验有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md?/031
- **通勤路线规划的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md?/gtn
- **社区教育资源的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md?/635/?ked
- **公共服务评价中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md?/438=274
- **节能家电使用的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/qWKig6.md?/czk=863
- **城市展览体验的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md
- **社区庭院绿化的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/7425eaa5b2ce1689738ef40f3b7be485b198e301?/568
- **非遗课堂体验的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/7425eaa5b2ce1689738ef40f3b7be485b198e301?/fal
- **智能家居应用的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/7425eaa5b2ce1689738ef40f3b7be485b198e301?/722/?zad
- **社区公共餐饮的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/7425eaa5b2ce1689738ef40f3b7be485b198e301?/266=017
- **节日文化体验的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/7425eaa5b2ce1689738ef40f3b7be485b198e301?/prb=344
- **环境监测科普的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md?/260
- **社区运动空间的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md?/yna
- **图书馆活动策划的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md?/262/?ibr
- **社区修缮行动的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md?/092=541
- **软件开发学习的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/IWje5T.md?/tpw=930
- **志愿服务平台的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md
- **灵活就业交流的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/79e8978a87623fa88bfd52584951f4a27cbcb1a3?/388
- **社区公共议事的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/79e8978a87623fa88bfd52584951f4a27cbcb1a3?/tpc
- **城市文明实践的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/79e8978a87623fa88bfd52584951f4a27cbcb1a3?/461/?alg
- **青少年科普实践的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/79e8978a87623fa88bfd52584951f4a27cbcb1a3?/722=705
- **数字档案服务的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/79e8978a87623fa88bfd52584951f4a27cbcb1a3?/fdx=573
- **机器学习入门的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md?/564
- **公共设施使用的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md?/slb
- **家庭健康管理的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md?/353/?nbz
- **城市便民驿站的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md?/131=568
- **生活垃圾回收的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Sa7be0.md?/jze=498
- **城市展览体验的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md
- **科技馆参观体验的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/2ab0884773e4d155ca73536b15301b23628edc98?/205
- **乡村电商实践的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/2ab0884773e4d155ca73536b15301b23628edc98?/zku
- **生活技能分享的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/2ab0884773e4d155ca73536b15301b23628edc98?/114/?nqu
- **图书馆亲子空间的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/2ab0884773e4d155ca73536b15301b23628edc98?/164=222
- **科学教育活动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/2ab0884773e4d155ca73536b15301b23628edc98?/hht=494
- **亲子科普活动的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md?/421
- **读书会组织的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md?/jmt
- **城市文明出行的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md?/032/?tyl
- **城市生活服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md?/014=159
- **城市基础设施的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/sX8dp5.md?/wtb=323
- **节气饮食文化的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md
- **青少年心理健康的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/6319a77cd97897c8d7177c08d4ba41c712edcd01?/180
- **食品安全科普从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/6319a77cd97897c8d7177c08d4ba41c712edcd01?/slw
- **家庭食品保存的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/6319a77cd97897c8d7177c08d4ba41c712edcd01?/558/?dxv
- **基层健康服务的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/6319a77cd97897c8d7177c08d4ba41c712edcd01?/231=068
- **城市空气科普的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/6319a77cd97897c8d7177c08d4ba41c712edcd01?/wyq=635
- **社区知识分享的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md?/138
- **街区小店体验的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md?/mtd
- **公园休闲体验的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md?/855/?ido
- **社区交通安全的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md?/705=372
- **家庭急救准备的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/OKPVrC.md?/sbo=797
- **城市基础设施的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md
- **城市慢跑路线的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/29da3c4fac777eafce6853472caaad884e35f396?/687
- **老旧小区改造的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/29da3c4fac777eafce6853472caaad884e35f396?/xcg
- **家庭急救准备的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/29da3c4fac777eafce6853472caaad884e35f396?/397/?lnw
- **科普展览体验的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/29da3c4fac777eafce6853472caaad884e35f396?/507=902
- **老年人出行服务的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/29da3c4fac777eafce6853472caaad884e35f396?/lci=141
- **社区环保活动从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md?/714
- **社区安全巡查的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md?/wzy
- **日常摄影记录的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md?/220/?bhd
- **绿色快递包装的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md?/339=737
- **街道综合服务的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/4dDIrY.md?/nmu=644
- **城市社区治理的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md
- **在线学习体验的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/4713cbe1c129fb07971348ebe6ce3d065d8fb158?/054
- **青少年户外教育的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/4713cbe1c129fb07971348ebe6ce3d065d8fb158?/qex
- **老年学习活动的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/4713cbe1c129fb07971348ebe6ce3d065d8fb158?/230/?kpt
- **社会体育指导的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/4713cbe1c129fb07971348ebe6ce3d065d8fb158?/579=973
- **生活技能分享的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/4713cbe1c129fb07971348ebe6ce3d065d8fb158?/ujy=781
- **城市步行环境的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md?/692
- **社区生活指南的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md?/hkt
- **城市微更新实践的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md?/425/?gcb
- **个人信息保护的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md?/614=904
- **科学运动指导的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/0IlkdU.md?/ips=903
- **跨代沟通活动的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md
- **城市可持续生活的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/ee9c1b776beb824ce0142c725905f337119e1161?/851
- **校园安全教育的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/ee9c1b776beb824ce0142c725905f337119e1161?/niu
- **城市生活服务的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/ee9c1b776beb824ce0142c725905f337119e1161?/941/?rqm
- **社区文化节活动的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/ee9c1b776beb824ce0142c725905f337119e1161?/070=102
- **新能源知识普及的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/ee9c1b776beb824ce0142c725905f337119e1161?/tho=610
- **生成式工具使用的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md?/889
- **开放数据应用的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md?/pua
- **儿童友好空间的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md?/083/?uqe
- **城市水环境观察的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md?/569=477
- **绿色办公实践的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/DwIqDa.md?/qjl=440
- **零废弃生活尝试的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md
- **图书借阅体验的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/08f8b9163aa68ba148f36d3c1ab32b3fac5bb4d9?/674
- **城市步行友好的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/08f8b9163aa68ba148f36d3c1ab32b3fac5bb4d9?/uha
- **社区教育资源的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/08f8b9163aa68ba148f36d3c1ab32b3fac5bb4d9?/542/?zoa
- **地方旅游导览的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/08f8b9163aa68ba148f36d3c1ab32b3fac5bb4d9?/481=497
- **社区运动空间的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/08f8b9163aa68ba148f36d3c1ab32b3fac5bb4d9?/cng=906
- **生活技能分享的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md?/774
- **食品安全科普的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md?/cyi
- **城市应急广播的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md?/645/?psp
- **本地消费场景的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md?/972=833
- **食品配送体验从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/X8ezIc.md?/taf=879
- **科学健身方法的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md
- **科技馆参观体验的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/85507d994c0759afb053114fca20f748ebf8aac9?/495
- **乡村阅读活动中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/85507d994c0759afb053114fca20f748ebf8aac9?/oot
- **数字公共文化的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/85507d994c0759afb053114fca20f748ebf8aac9?/369/?smr
- **气象科普传播有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/85507d994c0759afb053114fca20f748ebf8aac9?/999=419
- **乡村阅读空间的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/85507d994c0759afb053114fca20f748ebf8aac9?/eza=950
- **数字政务体验的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md?/803
- **校园阅读活动的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md?/vrw
- **校园社团活动的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md?/566/?onw
- **网络安全教育的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md?/026=865
- **亲子阅读活动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/dXmEu4.md?/osy=814
- **青少年职业启蒙的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md
- **家庭节能实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/6cfb3338ca7f06f870f1381d0480d58cd588440b?/573
- **社区便民服务的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/6cfb3338ca7f06f870f1381d0480d58cd588440b?/ysi
- **数字课堂应用的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/6cfb3338ca7f06f870f1381d0480d58cd588440b?/380/?pgc
- **数字艺术创作中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/6cfb3338ca7f06f870f1381d0480d58cd588440b?/143=368
- **社区家校合作的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/6cfb3338ca7f06f870f1381d0480d58cd588440b?/xbn=950
- **社区活动空间的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md?/486
- **家庭陪伴活动的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md?/udg
- **小区电梯维护的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md?/414/?lfy
- **科普展览体验的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md?/298=046
- **公共场所导视的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/qPdWup.md?/bnl=979
- **老年运动活动的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md
- **小区公共照明的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/c10fe1353f348effe703f804152c155f6cbbd676?/936
- **医院导诊服务的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/c10fe1353f348effe703f804152c155f6cbbd676?/vkh
- **老旧小区改造的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/c10fe1353f348effe703f804152c155f6cbbd676?/545/?vlt
- **城市空气科普的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/c10fe1353f348effe703f804152c155f6cbbd676?/796=082
- **家庭网络使用的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/c10fe1353f348effe703f804152c155f6cbbd676?/htk=915
- **城乡交通衔接的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md?/863
- **绿色快递包装的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md?/yul
- **青少年职业启蒙的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md?/485/?hpv
- **居家防滑改造的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md?/230=573
- **无障碍信息设计的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/BnkO3p.md?/lyt=160
- **科学信息获取的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md
- **青年职业探索的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/99fec866118a990a5c7afbd7538fcdb0ba55d4e5?/961
- **老年人出行服务的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/99fec866118a990a5c7afbd7538fcdb0ba55d4e5?/cwt
- **城市步行环境的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/99fec866118a990a5c7afbd7538fcdb0ba55d4e5?/373/?qrx
- **公共服务咨询的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/99fec866118a990a5c7afbd7538fcdb0ba55d4e5?/050=942
- **居家适老化改造的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/99fec866118a990a5c7afbd7538fcdb0ba55d4e5?/qyo=117
- **城市博物馆服务的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md?/108
- **老年人日常照护的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md?/lbz
- **日常摄影记录的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md?/599/?enj
- **信息无障碍体验的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md?/657=550
- **社区协商议事的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/F37MGj.md?/tjv=048
- **智慧停车服务的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md
- **科技馆参观体验的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/fabb831dda360eae1e8d6693b20e2558c2f9a8ee?/199
- **劳动教育实践的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/fabb831dda360eae1e8d6693b20e2558c2f9a8ee?/zzc
- **社区老年食堂的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/fabb831dda360eae1e8d6693b20e2558c2f9a8ee?/356/?ynx
- **公共空间休憩的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/fabb831dda360eae1e8d6693b20e2558c2f9a8ee?/155=747
- **远程协作工具的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/fabb831dda360eae1e8d6693b20e2558c2f9a8ee?/bef=131
- **全民健身活动的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md?/721
- **节假日出行安排的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md?/krr
- **无障碍信息设计的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md?/223/?ufc
- **租房信息服务的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md?/403=017
- **社区商业活力的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/q5lHgj.md?/yrk=756
- **文化讲座服务的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md
- **非遗体验活动的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/e1c1b50d1cf9f6339aefdcdbd640889b972eaa12?/420
- **社区托育服务的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/e1c1b50d1cf9f6339aefdcdbd640889b972eaa12?/aom
- **图书馆活动策划的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/e1c1b50d1cf9f6339aefdcdbd640889b972eaa12?/242/?bau
- **在线教育体验的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/e1c1b50d1cf9f6339aefdcdbd640889b972eaa12?/800=025
- **电动汽车充电的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/e1c1b50d1cf9f6339aefdcdbd640889b972eaa12?/cvt=283
- **校园社团活动的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md?/776
- **食品配送体验的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md?/rth
- **社区宣传栏更新的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md?/084/?vyb
- **环境监测科普的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md?/719=729
- **老年人文化生活的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/1RjnoT.md?/ppm=045
- **健康饮水科普的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md
- **音乐欣赏活动的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/f8d72fd5b1eebecb198db81a03106a8672f92c53?/038
- **公园无障碍服务的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/f8d72fd5b1eebecb198db81a03106a8672f92c53?/gxu
- **城市噪声观察的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/f8d72fd5b1eebecb198db81a03106a8672f92c53?/694/?tch
- **电动汽车充电的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/f8d72fd5b1eebecb198db81a03106a8672f92c53?/013=016
- **社区共享书架的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/f8d72fd5b1eebecb198db81a03106a8672f92c53?/dsi=999
- **本地旅行体验的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md?/779
- **新能源出行的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md?/wvr
- **社区菜市场服务的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md?/185/?zat
- **数字生活课堂的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md?/540=999
- **就业技能培训的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/tNWnza.md?/vuh=425
- **数字学习资源的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md
- **乡村阅读空间的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/4b375b111e79163c566bbd95010890d30a9acc3f?/082
- **零废弃生活尝试的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/4b375b111e79163c566bbd95010890d30a9acc3f?/wrw
- **社区垃圾回收的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/4b375b111e79163c566bbd95010890d30a9acc3f?/729/?tss
- **社区教育资源的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/4b375b111e79163c566bbd95010890d30a9acc3f?/108=345
- **城市步行友好的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/4b375b111e79163c566bbd95010890d30a9acc3f?/ygf=546
- **数字创意课程的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md?/218
- **公交站点体验的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md?/tps
- **环境监测科普的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md?/117/?ppb
- **传统节日科普的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md?/107=136
- **急救知识普及从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/1qr7fO.md?/dkd=221
- **居家防滑改造的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md
- **社区共享书架的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/bd44df98c7529afacdd7a1ae2a029e69b42f705a?/927
- **口袋公园建设的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/bd44df98c7529afacdd7a1ae2a029e69b42f705a?/qfm
- **家庭消费规划的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/bd44df98c7529afacdd7a1ae2a029e69b42f705a?/010/?ogt
- **城市人文观察的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/bd44df98c7529afacdd7a1ae2a029e69b42f705a?/524=815
- **公共服务咨询的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/bd44df98c7529afacdd7a1ae2a029e69b42f705a?/phg=384
- **绿色建筑理念的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md?/924
- **智慧停车服务的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md?/ntp
- **图书馆数字服务的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md?/203/?gim
- **环境监测科普的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md?/887=892
- **城市步行友好有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/JW0kEn.md?/mzp=239
- **社区知识分享的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md
- **老年人日常照护的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/01ad0cf84e695bcf105502ddc2f025389681a5da?/636
- **数字创意课程的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/01ad0cf84e695bcf105502ddc2f025389681a5da?/phm
- **城市环境志愿行动的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/01ad0cf84e695bcf105502ddc2f025389681a5da?/173/?ngx
- **数字创意课程的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/01ad0cf84e695bcf105502ddc2f025389681a5da?/553=421
- **读书会组织的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/01ad0cf84e695bcf105502ddc2f025389681a5da?/qas=545
- **家庭健康科普的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md?/897
- **数字阅读服务的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md?/qed
- **社区庭院绿化的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md?/340/?skl
- **绿色生活实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md?/817=803
- **电动汽车充电的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wnc4Tg.md?/lmt=752
- **家庭节能实践的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md
- **科学运动指导的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/05a7789c2fdb516b67f2e5caa872cd69f472dc27?/616
- **社区运动空间的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/05a7789c2fdb516b67f2e5caa872cd69f472dc27?/kzo
- **绿色建筑理念的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/05a7789c2fdb516b67f2e5caa872cd69f472dc27?/313/?fku
- **街区小店体验的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/05a7789c2fdb516b67f2e5caa872cd69f472dc27?/852=350
- **数字创作工具的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/05a7789c2fdb516b67f2e5caa872cd69f472dc27?/hys=087
- **公共空间照明从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md?/879
- **绿色校园实践的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md?/hbh
- **生活垃圾回收的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md?/305/?rcj
- **城市体育设施中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md?/938=292
- **乡村生活观察的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/xE52eJ.md?/qln=153
- **志愿者培训交流的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md
- **公共服务沟通的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/83a6d26145e00b44a993b021d21d344c30cbdddd?/940
- **社区环保活动的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/83a6d26145e00b44a993b021d21d344c30cbdddd?/ueb
- **休闲运动入门的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/83a6d26145e00b44a993b021d21d344c30cbdddd?/131/?vsz
- **街道综合服务的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/83a6d26145e00b44a993b021d21d344c30cbdddd?/878=561
- **开放式学习空间的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/83a6d26145e00b44a993b021d21d344c30cbdddd?/hdv=395
- **城市博物馆活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md?/829
- **公共卫生设施的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md?/tad
- **社区老年食堂的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md?/442/?wlg
- **老年智能设备有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md?/368=151
- **社区慢性病防控的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/2EqyYZ.md?/mjj=870
- **个人信息保护从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md
- **社区公共议事的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/b734226a1af29899a32718dfec10891d50408564?/431
- **公交无障碍服务的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/b734226a1af29899a32718dfec10891d50408564?/wtk
- **家庭园艺实践的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/b734226a1af29899a32718dfec10891d50408564?/176/?ihx
- **社区宠物管理中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/b734226a1af29899a32718dfec10891d50408564?/558=169
- **数字设备回收中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/b734226a1af29899a32718dfec10891d50408564?/xsj=020
- **城市人文观察的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md?/947
- **社区花园共建的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md?/fhn
- **图书借阅体验的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md?/282/?wdu
- **社区老年食堂的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md?/914=774
- **青少年科普实践的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/MDV5Hk.md?/byt=449
- **公共服务指南的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md
- **个人时间管理的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/d10fd3d34790dc31c39f43c6f50616a94ac5e4c8?/087
- **城市公共厕所的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/d10fd3d34790dc31c39f43c6f50616a94ac5e4c8?/xuy
- **社区老年食堂的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/d10fd3d34790dc31c39f43c6f50616a94ac5e4c8?/859/?umw
- **社区活动报名的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/d10fd3d34790dc31c39f43c6f50616a94ac5e4c8?/924=247
- **社区知识分享的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/d10fd3d34790dc31c39f43c6f50616a94ac5e4c8?/ujn=010
- **社区商业活力的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md?/156
- **城市微更新实践有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md?/ahs
- **城市便民驿站的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md?/957/?ejd
- **社区宠物管理有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md?/368=415
- **社区设施共享的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/VUL4qW.md?/orf=219
- **非遗课堂体验的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md
- **校园社团活动的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/f23bbe4ad362a825e06c84d6b0b913d33a65a018?/794
- **绿色出行服务的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/f23bbe4ad362a825e06c84d6b0b913d33a65a018?/jwn
- **基层医疗预约的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/f23bbe4ad362a825e06c84d6b0b913d33a65a018?/549/?que
- **社区阅读服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/f23bbe4ad362a825e06c84d6b0b913d33a65a018?/604=912
- **科学信息获取的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/f23bbe4ad362a825e06c84d6b0b913d33a65a018?/mgw=819
- **亲子科普活动的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md?/468
- **数字地图应用从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md?/dqf
- **公共服务评价的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md?/721/?ybq
- **光伏知识科普的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md?/604=295
- **家庭教育交流的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/xlAP42.md?/dbs=201
- **社区共享书架的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md
- **家庭教育交流的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/b89481c57a2f1b11d561b526264191eb5b94d7b1?/680
- **安全出行教育的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/b89481c57a2f1b11d561b526264191eb5b94d7b1?/rdr
- **老年人出行服务的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/b89481c57a2f1b11d561b526264191eb5b94d7b1?/853/?ksw
- **街区更新实践的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/b89481c57a2f1b11d561b526264191eb5b94d7b1?/858=822
- **在线学习体验的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/b89481c57a2f1b11d561b526264191eb5b94d7b1?/per=827
- **社区商业活力的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md?/602
- **电动汽车充电的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md?/aga
- **食品配送体验的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md?/247/?fuk
- **社区设施共享的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md?/485=597
- **邻里互助活动的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/4JzkEV.md?/wzf=403
- **城市树木认养的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md
- **远程协作工具的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/77892b9fdd740669d9657319db746441daa0e319?/749
- **城市共享单车的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/77892b9fdd740669d9657319db746441daa0e319?/bky
- **居民健康教育的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/77892b9fdd740669d9657319db746441daa0e319?/895/?mph
- **校园节能行动的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/77892b9fdd740669d9657319db746441daa0e319?/503=692
- **生活技能分享中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/77892b9fdd740669d9657319db746441daa0e319?/rya=712
- **数字支付体验中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md?/446
- **地方戏曲体验的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md?/yhv
- **农产品品牌传播的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md?/296/?top
- **小微企业服务的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md?/509=331
- **线上办事服务的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Tz4qzl.md?/uvv=627
- **环境教育课程的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md
- **社区宠物管理的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/71a6853ee2f543896fb3bdfa0b20b4aa87417b75?/962
- **软件开发学习的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/71a6853ee2f543896fb3bdfa0b20b4aa87417b75?/hqf
- **社区安全巡查的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/71a6853ee2f543896fb3bdfa0b20b4aa87417b75?/427/?ncn
- **基层服务创新的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/71a6853ee2f543896fb3bdfa0b20b4aa87417b75?/893=043
- **绿色快递包装的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/71a6853ee2f543896fb3bdfa0b20b4aa87417b75?/pyg=792
- **智能手机助老的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md?/568
- **社区文化传播的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md?/gos
- **家庭教育交流的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md?/083/?yvl
- **家庭教育交流中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md?/512=881
- **生活垃圾减量从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/DuMYBE.md?/zxx=748
- **绿色校园实践的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md
- **家庭志愿活动的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/611909becb3ce0f0df0deb0ff9ff5ab1cec98891?/481
- **药品使用科普的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/611909becb3ce0f0df0deb0ff9ff5ab1cec98891?/qcb
- **终身学习资源的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/611909becb3ce0f0df0deb0ff9ff5ab1cec98891?/794/?tqb
- **安全出行教育的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/611909becb3ce0f0df0deb0ff9ff5ab1cec98891?/973=613
- **居民健康教育的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/611909becb3ce0f0df0deb0ff9ff5ab1cec98891?/zpx=546
- **生成式工具使用的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md?/081
- **传统手工艺体验的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md?/nwo
- **环境监测科普的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md?/699/?uql
- **街区绿化养护的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md?/643=395
- **公共服务预约的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/011tyF.md?/gsu=005
- **社区活动报名的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md
- **数字艺术创作的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/4db0e540b9cb0749ba5016d382baa70a10d4ab58?/481
- **公共空间休憩的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/4db0e540b9cb0749ba5016d382baa70a10d4ab58?/scg
- **社区学习活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/4db0e540b9cb0749ba5016d382baa70a10d4ab58?/335/?rht
- **公共设施维护的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/4db0e540b9cb0749ba5016d382baa70a10d4ab58?/655=999
- **公共文化活动的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/4db0e540b9cb0749ba5016d382baa70a10d4ab58?/ntf=873
- **无障碍出行的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md?/641
- **城市休闲步道的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md?/grj
- **地方戏曲体验的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md?/992/?hwu
- **居家适老化改造的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md?/921=533
- **公园亲子设施的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/N5IYdJ.md?/vxm=345
- **城市便民驿站的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md
- **城市运动公园的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/56873037af9188eed184caccd202e7ee2d3687e7?/126
- **运动安全知识的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/56873037af9188eed184caccd202e7ee2d3687e7?/uhr
- **消防知识宣传的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/56873037af9188eed184caccd202e7ee2d3687e7?/282/?rtm
- **文化讲座服务的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/56873037af9188eed184caccd202e7ee2d3687e7?/176=699
- **城市社区治理的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/56873037af9188eed184caccd202e7ee2d3687e7?/wdr=504
- **地方旅游导览的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md?/849
- **青少年编程学习中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md?/jwv
- **数字生活课堂的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md?/548/?pgt
- **气象科普传播的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md?/895=443
- **远程协作工具的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/pLTjfY.md?/jws=661
- **社区应急准备的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md
- **青少年科普实践的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/ca5480300161ce327846617d9981079c0badd550?/863
- **新能源知识普及的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/ca5480300161ce327846617d9981079c0badd550?/eiw
- **乡村公共文化的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/ca5480300161ce327846617d9981079c0badd550?/193/?jgz
- **物业服务沟通的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/ca5480300161ce327846617d9981079c0badd550?/029=370
- **儿童友好空间的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/ca5480300161ce327846617d9981079c0badd550?/jow=663
- **城市树木认养的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md?/639
- **数字设备回收的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md?/dvr
- **数字学习资源的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md?/438/?qfz
- **城乡交通衔接的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md?/356=601
- **社区便民集市中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/ChLVdY.md?/nbm=497
- **城市公共饮水的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md
- **数字创作工具有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/fa6c883530046a49327ce3bc5a247f758cf94bdc?/793
- **绿色出行服务从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/fa6c883530046a49327ce3bc5a247f758cf94bdc?/gzt
- **社区共享书架的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/fa6c883530046a49327ce3bc5a247f758cf94bdc?/623/?zzc
- **社区家校合作的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/fa6c883530046a49327ce3bc5a247f758cf94bdc?/562=909
- **社区停车服务的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/fa6c883530046a49327ce3bc5a247f758cf94bdc?/dkv=696
- **农村环境治理的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md?/317
- **生活垃圾减量中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md?/msk
- **机器学习入门的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md?/697/?frr
- **家庭运动计划的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md?/221=514
- **社区设施共享的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZXnLgc.md?/jnb=807
- **数字创作工具的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md
- **城市骑行环境的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/db8ac642bc8d6c6a1c43789ff351b12dcd98b3f6?/480
- **邻里共享空间中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/db8ac642bc8d6c6a1c43789ff351b12dcd98b3f6?/clz
- **生活服务数字化的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/db8ac642bc8d6c6a1c43789ff351b12dcd98b3f6?/070/?jcm
- **公共服务咨询的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/db8ac642bc8d6c6a1c43789ff351b12dcd98b3f6?/506=800
- **数字公共文化的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/db8ac642bc8d6c6a1c43789ff351b12dcd98b3f6?/xip=177
- **健康信息获取的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md?/128
- **社区活动策划的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md?/oqq
- **课后服务体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md?/397/?qpa
- **物业服务沟通的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md?/005=831
- **城市空气科普的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/HFNKNw.md?/egx=993
- **城市应急科普的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md
- **租房信息服务的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/2a17888f5a3bb0132f38abcd0caf1ec2089be08c?/838
- **健康步道使用的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/2a17888f5a3bb0132f38abcd0caf1ec2089be08c?/nga
- **居民健康教育的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/2a17888f5a3bb0132f38abcd0caf1ec2089be08c?/440/?sqw
- **地方旅游导览的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/2a17888f5a3bb0132f38abcd0caf1ec2089be08c?/551=260
- **公共服务评价的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/2a17888f5a3bb0132f38abcd0caf1ec2089be08c?/vuc=564
- **公共空间导览的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md?/560
- **生活垃圾减量的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md?/aal
- **数字学习资源的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md?/278/?sbi
- **街道综合服务的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md?/548=594
- **科学睡眠习惯的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/NU0I3m.md?/fws=146
- **城市应急科普的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md
- **科学信息获取的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/52dc8a4a14ef8884716878d1feb6c11cbb6cb45a?/859
- **物业服务沟通的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/52dc8a4a14ef8884716878d1feb6c11cbb6cb45a?/hgg
- **数字创意课程的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/52dc8a4a14ef8884716878d1feb6c11cbb6cb45a?/837/?bct
- **社区应急准备的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/52dc8a4a14ef8884716878d1feb6c11cbb6cb45a?/211=241
- **老年运动活动的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/52dc8a4a14ef8884716878d1feb6c11cbb6cb45a?/kqa=866
- **数字创意课程的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md?/733
- **邻里互助活动的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md?/djm
- **家庭网络使用的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md?/590/?prf
- **无障碍出行从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md?/045=849
- **文明养宠科普的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/Wc8HIk.md?/rkw=616
- **家庭饮食安排的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md
- **便民维修服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/004c6e05d5468519d6f3b517474572eb99f30199?/736
- **老年数字阅读的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/004c6e05d5468519d6f3b517474572eb99f30199?/xop
- **城市公共标识的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/004c6e05d5468519d6f3b517474572eb99f30199?/563/?aju
- **城市公共厕所的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/004c6e05d5468519d6f3b517474572eb99f30199?/402=513
- **数字便民地图中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/004c6e05d5468519d6f3b517474572eb99f30199?/kjk=403
- **城市宠物友好空间的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md?/301
- **本地旅行体验的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md?/xxp
- **家庭园艺实践的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md?/510/?gwl
- **儿童友好空间的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md?/660=444
- **家庭网络使用的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/QRXq7c.md?/mrg=067
- **公共设施使用的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md
- **乡村休闲旅游的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/bf70977dd1dd757784c3883ed0d4429c88f45044?/304
- **绿色消费选择的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/bf70977dd1dd757784c3883ed0d4429c88f45044?/ryw
- **软件开发学习的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/bf70977dd1dd757784c3883ed0d4429c88f45044?/475/?sol
- **乡村生活观察的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/bf70977dd1dd757784c3883ed0d4429c88f45044?/024=405
- **社区学习活动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/bf70977dd1dd757784c3883ed0d4429c88f45044?/mlt=462
- **个人数据管理的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md?/747
- **社区邻里服务中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md?/ikl
- **农产品消费体验的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md?/184/?wod
- **本地旅行体验的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md?/235=714
- **城市公共自行车的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/bgqUvQ.md?/vlx=378
- **家庭健康管理的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md
- **社区读书角建设的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/86d17b349ac90a65096b1b01c500c63968ec70af?/317
- **家庭节能实践的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/86d17b349ac90a65096b1b01c500c63968ec70af?/tac
- **学校食育活动的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/86d17b349ac90a65096b1b01c500c63968ec70af?/371/?rec
- **数字支付体验的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/86d17b349ac90a65096b1b01c500c63968ec70af?/111=712
- **图书馆亲子空间的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/86d17b349ac90a65096b1b01c500c63968ec70af?/xon=292
- **家庭急救准备的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md?/003
- **农村环境治理的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md?/qxh
- **街区道路维护中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md?/276/?gsr
- **家庭阅读计划的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md?/503=301
- **社区生活指南的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/YIvHux.md?/ean=614
- **城乡公共服务的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md
- **城市环境志愿行动的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/855b1b8ae5e31152a78581f44b55af29cb5ccbfe?/523
- **基层健康服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/855b1b8ae5e31152a78581f44b55af29cb5ccbfe?/sps
- **家庭安全提示的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/855b1b8ae5e31152a78581f44b55af29cb5ccbfe?/605/?bob
- **亲子科普活动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/855b1b8ae5e31152a78581f44b55af29cb5ccbfe?/910=714
- **乡村阅读活动的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/855b1b8ae5e31152a78581f44b55af29cb5ccbfe?/ncx=442
- **终身学习资源的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md?/221
- **健康饮食教育的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md?/pde
- **垃圾分类指导从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md?/154/?oya
- **急救知识普及的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md?/654=106
- **社区公共卫生的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4ILTHk.md?/rnj=868
- **图书馆亲子空间的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md
- **家庭网络使用的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/20f37ff48f785b9479a6c6c1373806b94f28eb32?/663
- **公共空间照明的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/20f37ff48f785b9479a6c6c1373806b94f28eb32?/mpd
- **社区家校合作的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/20f37ff48f785b9479a6c6c1373806b94f28eb32?/751/?wfw
- **数字创作工具的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/20f37ff48f785b9479a6c6c1373806b94f28eb32?/536=168
- **社区垃圾回收的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/20f37ff48f785b9479a6c6c1373806b94f28eb32?/vop=611
- **社区法律科普的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md?/785
- **城市体育设施的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md?/kdn
- **家庭阅读计划的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md?/024/?jka
- **小区停车协商从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md?/053=816
- **城市空气科普有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/JQh01A.md?/wyq=135
- **公共服务咨询有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md
- **低碳社区实践中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/c3772c4d51a266de9878a3f422a61904f9a17d2b?/531
- **公共卫生宣传的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/c3772c4d51a266de9878a3f422a61904f9a17d2b?/lzn
- **校园节能行动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/c3772c4d51a266de9878a3f422a61904f9a17d2b?/006/?lfi
- **小微企业服务的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/c3772c4d51a266de9878a3f422a61904f9a17d2b?/856=494
- **城市文化路线的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/c3772c4d51a266de9878a3f422a61904f9a17d2b?/qkh=191
- **在线学习体验的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md?/275
- **绿色生活实践从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md?/mbv
- **社区读书角建设的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md?/996/?iox
- **家庭理财科普的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md?/143=717
- **家庭教育交流从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/FOEPeb.md?/qay=426
- **公共卫生宣传的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md
- **街头绿植养护的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/14f76bdec24b2dc518e2f3d637b258589b1350cf?/032
- **家庭健康科普的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/14f76bdec24b2dc518e2f3d637b258589b1350cf?/pih
- **地方戏曲体验的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/14f76bdec24b2dc518e2f3d637b258589b1350cf?/472/?dfa
- **小区停车协商的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/14f76bdec24b2dc518e2f3d637b258589b1350cf?/874=585
- **社区花园共建的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/14f76bdec24b2dc518e2f3d637b258589b1350cf?/fvs=456
- **文明养宠科普的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md?/221
- **节能家电使用的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md?/xvx
- **家庭用电安全的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md?/648/?mbl
- **家庭运动计划的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md?/313=207
- **家庭节能实践从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/LFZo8a.md?/nmh=376
- **城市便民驿站的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/7Oisjp.md
- **消防知识宣传的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/5a55e0ae49a4b6ea692c06dcea4882ea049f8d8a?/157
- **城市基础设施中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/5a55e0ae49a4b6ea692c06dcea4882ea049f8d8a?/pcw
- **电动汽车充电从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/5a55e0ae49a4b6ea692c06dcea4882ea049f8d8a?/789/?pov
- **城市文明出行中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/5a55e0ae49a4b6ea692c06dcea4882ea049f8d8a?/559=010
- **健康饮食教育的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/5a55e0ae49a4b6ea692c06dcea4882ea049f8d8a?/lzl=628
- **社区教育资源的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/7Oisjp.md?/856

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  精准计划导师微信等*  
*仅供参考，不构成投资建议*
