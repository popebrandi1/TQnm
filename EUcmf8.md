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

- **城市公共艺术的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3ccfcf3a7d0385066ea99d033a87c8b860457d32?/010
- **绿色生活实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3ccfcf3a7d0385066ea99d033a87c8b860457d32?/iub
- **垃圾分类指导的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3ccfcf3a7d0385066ea99d033a87c8b860457d32?/900/?ixw
- **生活垃圾回收的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3ccfcf3a7d0385066ea99d033a87c8b860457d32?/743=913
- **远程协作工具的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3ccfcf3a7d0385066ea99d033a87c8b860457d32?/kpt=371
- **绿色建筑理念中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/00c36cd9418848fae0b7ccda41af058ee5563f7a?/750
- **科学观察活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/00c36cd9418848fae0b7ccda41af058ee5563f7a?/gnd
- **家庭志愿活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/00c36cd9418848fae0b7ccda41af058ee5563f7a?/338/?auo
- **社区儿童活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/00c36cd9418848fae0b7ccda41af058ee5563f7a?/806=668
- **社区故事采集的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/00c36cd9418848fae0b7ccda41af058ee5563f7a?/nkb=750
- **创业经验分享的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/3f023fc77530817da6061c09bba94a615ccf7b6a?/865
- **公益活动组织的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3f023fc77530817da6061c09bba94a615ccf7b6a?/lsr
- **城市公共饮水从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3f023fc77530817da6061c09bba94a615ccf7b6a?/264/?gqm
- **老年数字阅读中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3f023fc77530817da6061c09bba94a615ccf7b6a?/392=261
- **社区活动策划的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3f023fc77530817da6061c09bba94a615ccf7b6a?/but=247
- **公交站点体验的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/0458c9d96f39144648179dae542e1661f0b394ac?/989
- **家庭急救准备从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/0458c9d96f39144648179dae542e1661f0b394ac?/ixc
- **基层健康档案中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/0458c9d96f39144648179dae542e1661f0b394ac?/010/?tct
- **公共健身器材的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0458c9d96f39144648179dae542e1661f0b394ac?/221=515
- **老旧小区改造的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/0458c9d96f39144648179dae542e1661f0b394ac?/fri=608
- **家庭消费规划的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7e9c9d3c833c9bad9000ad3bf45441ee43ff6823?/789
- **城市应急广播的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/7e9c9d3c833c9bad9000ad3bf45441ee43ff6823?/ekq
- **青年就业服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7e9c9d3c833c9bad9000ad3bf45441ee43ff6823?/870/?zzw
- **农村环境治理的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7e9c9d3c833c9bad9000ad3bf45441ee43ff6823?/273=565
- **公共服务咨询的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/7e9c9d3c833c9bad9000ad3bf45441ee43ff6823?/mkg=100
- **城市展览体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/e27fb8f68fd8c7361576c5a58c1afa140ec50f92?/707
- **学校体育活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/e27fb8f68fd8c7361576c5a58c1afa140ec50f92?/lqm
- **无障碍出行的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e27fb8f68fd8c7361576c5a58c1afa140ec50f92?/904/?oux
- **社区文化传播有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e27fb8f68fd8c7361576c5a58c1afa140ec50f92?/218=652
- **科技馆参观体验的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e27fb8f68fd8c7361576c5a58c1afa140ec50f92?/fvv=071
- **青少年户外教育的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a7b603ef786411010d0ea29aaf3e3fd30a9730a8?/263
- **基层健康档案的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a7b603ef786411010d0ea29aaf3e3fd30a9730a8?/abt
- **城市生活服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a7b603ef786411010d0ea29aaf3e3fd30a9730a8?/865/?bmo
- **社区运动空间的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a7b603ef786411010d0ea29aaf3e3fd30a9730a8?/456=749
- **智能手机助老从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/a7b603ef786411010d0ea29aaf3e3fd30a9730a8?/ngd=160
- **城市骑行环境的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/8e33e65afa740bfbd0018abcb6052e05c23558d4?/811
- **社区垃圾回收的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/8e33e65afa740bfbd0018abcb6052e05c23558d4?/whv
- **公共服务指南的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8e33e65afa740bfbd0018abcb6052e05c23558d4?/760/?xmg
- **食品安全科普的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/8e33e65afa740bfbd0018abcb6052e05c23558d4?/644=537
- **健康信息获取的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/8e33e65afa740bfbd0018abcb6052e05c23558d4?/jcg=651
- **城市慢行系统有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/e5b138b20a3f0d72d007e468083a0f79973fa8dc?/511
- **图书馆数字服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/e5b138b20a3f0d72d007e468083a0f79973fa8dc?/sze
- **家庭安全提示的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/e5b138b20a3f0d72d007e468083a0f79973fa8dc?/715/?hou
- **口袋公园建设的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e5b138b20a3f0d72d007e468083a0f79973fa8dc?/422=522
- **科学观察活动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/e5b138b20a3f0d72d007e468083a0f79973fa8dc?/kik=505
- **家庭网络使用的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/949dcd8561cec0b4a5dd0cbf27e55eb33fed41bc?/255
- **儿童阅读角中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/949dcd8561cec0b4a5dd0cbf27e55eb33fed41bc?/zbq
- **社区活动策划的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/949dcd8561cec0b4a5dd0cbf27e55eb33fed41bc?/891/?tfr
- **社区便民服务的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/949dcd8561cec0b4a5dd0cbf27e55eb33fed41bc?/581=741
- **公共交通接驳的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/949dcd8561cec0b4a5dd0cbf27e55eb33fed41bc?/cho=072
- **骑行路线规划的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/06b27c4d74328ae09c35693a33f3588599e9be86?/348
- **传统节日科普的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/06b27c4d74328ae09c35693a33f3588599e9be86?/myq
- **数字阅读服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/06b27c4d74328ae09c35693a33f3588599e9be86?/770/?hmv
- **公共图书馆服务的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/06b27c4d74328ae09c35693a33f3588599e9be86?/675=105
- **图书馆数字服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/06b27c4d74328ae09c35693a33f3588599e9be86?/sfp=418
- **乡村休闲旅游的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2fa5f0f79e0e45c634b32add24acd6d8604646cd?/773
- **家庭节能实践的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/2fa5f0f79e0e45c634b32add24acd6d8604646cd?/ser
- **城乡交流活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/2fa5f0f79e0e45c634b32add24acd6d8604646cd?/240/?eci
- **开放式学习空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/2fa5f0f79e0e45c634b32add24acd6d8604646cd?/881=296
- **非遗体验活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2fa5f0f79e0e45c634b32add24acd6d8604646cd?/pls=343
- **基层服务创新中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/bd518dad2737e86b9a726ead42850b39a36de9ec?/058
- **旧物循环利用的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/bd518dad2737e86b9a726ead42850b39a36de9ec?/fvm
- **药品使用科普的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bd518dad2737e86b9a726ead42850b39a36de9ec?/044/?jvh
- **公共空间照明的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/bd518dad2737e86b9a726ead42850b39a36de9ec?/905=196
- **公共服务预约的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bd518dad2737e86b9a726ead42850b39a36de9ec?/ioe=465
- **城市可持续生活的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f43d2a0050023c5745c048c46373723740ba981e?/922
- **家庭网络使用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f43d2a0050023c5745c048c46373723740ba981e?/mgg
- **数字课堂应用的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f43d2a0050023c5745c048c46373723740ba981e?/768/?eqf
- **社区花园共建的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f43d2a0050023c5745c048c46373723740ba981e?/940=146
- **邻里共享空间的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/f43d2a0050023c5745c048c46373723740ba981e?/udy=018
- **数字便民地图的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/c17635977a010dde8562bf32ff4d4d31fda74cea?/164
- **线上阅读资源的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/c17635977a010dde8562bf32ff4d4d31fda74cea?/gwd
- **乡村公共阅读的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c17635977a010dde8562bf32ff4d4d31fda74cea?/242/?qjs
- **社区设施共享的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c17635977a010dde8562bf32ff4d4d31fda74cea?/862=392
- **乡村生活观察的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c17635977a010dde8562bf32ff4d4d31fda74cea?/cun=111
- **儿童户外活动的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/78e05dc59e97498972a0e9f3d5a287da6d8e4fcd?/318
- **老年人出行服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/78e05dc59e97498972a0e9f3d5a287da6d8e4fcd?/jti
- **数字政务体验的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/78e05dc59e97498972a0e9f3d5a287da6d8e4fcd?/651/?tfi
- **城市夜间照明的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/78e05dc59e97498972a0e9f3d5a287da6d8e4fcd?/070=535
- **社区托育服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/78e05dc59e97498972a0e9f3d5a287da6d8e4fcd?/wkm=132
- **急救知识普及的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/03aaad0fa38d3a5b8c25a943e3c7a92f2c63c28f?/384
- **图书借阅体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/03aaad0fa38d3a5b8c25a943e3c7a92f2c63c28f?/wrx
- **文化遗产保护科普的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/03aaad0fa38d3a5b8c25a943e3c7a92f2c63c28f?/182/?hct
- **数字课堂应用的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/03aaad0fa38d3a5b8c25a943e3c7a92f2c63c28f?/171=384
- **非遗课堂体验的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/03aaad0fa38d3a5b8c25a943e3c7a92f2c63c28f?/ibl=747
- **便民信息查询的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f319d365da7f834b3a13bfa58ecda4fa8e2129f3?/423
- **本地消费场景的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/f319d365da7f834b3a13bfa58ecda4fa8e2129f3?/wnr
- **城市体育设施的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f319d365da7f834b3a13bfa58ecda4fa8e2129f3?/930/?dok
- **音乐欣赏活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/f319d365da7f834b3a13bfa58ecda4fa8e2129f3?/117=188
- **生活服务数字化的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f319d365da7f834b3a13bfa58ecda4fa8e2129f3?/xax=629
- **城市空气科普的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/469f113ec588e09ef489851e0d39909616a0c53e?/932
- **城市生活记录的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/469f113ec588e09ef489851e0d39909616a0c53e?/mpq
- **乡村文化空间的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/469f113ec588e09ef489851e0d39909616a0c53e?/548/?hmh
- **社区快递服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/469f113ec588e09ef489851e0d39909616a0c53e?/228=459
- **社区生活指南的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/469f113ec588e09ef489851e0d39909616a0c53e?/blb=441
- **社区信息发布的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/706572f7f7c3e93915c6eb2ea09cad89dcb5358c?/373
- **社区知识分享的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/706572f7f7c3e93915c6eb2ea09cad89dcb5358c?/exc
- **城市公共空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/706572f7f7c3e93915c6eb2ea09cad89dcb5358c?/405/?bnl
- **儿童安全出行的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/706572f7f7c3e93915c6eb2ea09cad89dcb5358c?/527=510
- **城市步行友好的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/706572f7f7c3e93915c6eb2ea09cad89dcb5358c?/rma=434
- **家庭收纳实践的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8bbe40c6e8124a0013dca74c625f03c70cfdb9a6?/589
- **老年人文化生活的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/8bbe40c6e8124a0013dca74c625f03c70cfdb9a6?/cvv
- **远程协作工具的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8bbe40c6e8124a0013dca74c625f03c70cfdb9a6?/680/?kyc
- **老年人日常照护从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/8bbe40c6e8124a0013dca74c625f03c70cfdb9a6?/382=143
- **城市慢跑路线的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/8bbe40c6e8124a0013dca74c625f03c70cfdb9a6?/eiz=307
- **无障碍信息设计的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b3b468e1a23df898502d860f745ec866e218b66d?/833
- **社区绿色空间的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/b3b468e1a23df898502d860f745ec866e218b66d?/gyu
- **数字艺术创作的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/b3b468e1a23df898502d860f745ec866e218b66d?/914/?mrx
- **城市夜间照明的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/b3b468e1a23df898502d860f745ec866e218b66d?/075=452
- **骑行路线规划的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/b3b468e1a23df898502d860f745ec866e218b66d?/dxl=076
- **乡村产业科普的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f142debcb55b37ff5be49f5f3c930442d1267ebc?/541
- **公园无障碍服务的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/f142debcb55b37ff5be49f5f3c930442d1267ebc?/nci
- **非遗体验活动的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f142debcb55b37ff5be49f5f3c930442d1267ebc?/013/?ukk
- **老年数字阅读的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/f142debcb55b37ff5be49f5f3c930442d1267ebc?/322=820
- **社区垃圾回收的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f142debcb55b37ff5be49f5f3c930442d1267ebc?/prg=064
- **城市绿色交通中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9326d735bfbc14d3939ac4d336f5ac722c2b4d?/849
- **城市公共自行车的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9326d735bfbc14d3939ac4d336f5ac722c2b4d?/bme
- **科学教育活动的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9326d735bfbc14d3939ac4d336f5ac722c2b4d?/136/?fzj
- **街区小店体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9326d735bfbc14d3939ac4d336f5ac722c2b4d?/434=121
- **地方文化传播的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/7b9326d735bfbc14d3939ac4d336f5ac722c2b4d?/ram=544
- **公共交通接驳的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/08b837de230b321527d504f10db721b3c7dc9e3a?/542
- **家庭园艺实践的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/08b837de230b321527d504f10db721b3c7dc9e3a?/vou
- **家庭园艺实践的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/08b837de230b321527d504f10db721b3c7dc9e3a?/994/?elc
- **节假日出行安排从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/08b837de230b321527d504f10db721b3c7dc9e3a?/737=922
- **社区商业活力的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/08b837de230b321527d504f10db721b3c7dc9e3a?/fqt=129
- **数字档案服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/df2572bc77246d1ac40974b60f47d147b33fd965?/803
- **社区菜市场服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/df2572bc77246d1ac40974b60f47d147b33fd965?/szp
- **社区健康讲座的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/df2572bc77246d1ac40974b60f47d147b33fd965?/688/?mxi
- **乡村公共服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/df2572bc77246d1ac40974b60f47d147b33fd965?/422=782
- **青年就业服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/df2572bc77246d1ac40974b60f47d147b33fd965?/ghx=007
- **家庭健康管理中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/b03f059b324891b442fdb75496782fa568856ba5?/710
- **城市博物馆服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/b03f059b324891b442fdb75496782fa568856ba5?/jyu
- **家庭环保行动的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b03f059b324891b442fdb75496782fa568856ba5?/188/?iek
- **社区知识分享的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b03f059b324891b442fdb75496782fa568856ba5?/717=861
- **街头绿植养护的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/b03f059b324891b442fdb75496782fa568856ba5?/bpa=927
- **社区家政服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/baf175f8abe221a081193fe60e748a42c3ea7855?/365
- **绿色出行服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/baf175f8abe221a081193fe60e748a42c3ea7855?/kcj
- **儿童安全出行的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/baf175f8abe221a081193fe60e748a42c3ea7855?/513/?ogd
- **城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/baf175f8abe221a081193fe60e748a42c3ea7855?/958=943
- **社区安全巡查的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/baf175f8abe221a081193fe60e748a42c3ea7855?/wxs=083
- **非遗体验活动的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/b2f41aebada054f3a01bfc5aa578a87b096019ad?/275
- **家庭健康管理的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b2f41aebada054f3a01bfc5aa578a87b096019ad?/wps
- **社区家校合作的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b2f41aebada054f3a01bfc5aa578a87b096019ad?/890/?lwv
- **青少年科普实践的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/b2f41aebada054f3a01bfc5aa578a87b096019ad?/332=653
- **小区电梯维护的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b2f41aebada054f3a01bfc5aa578a87b096019ad?/kgp=165
- **社区商业活力的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/413c4686d69b45bb9cf96516883bf418e6c7aa43?/338
- **本地消费场景的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/413c4686d69b45bb9cf96516883bf418e6c7aa43?/nir
- **环境教育课程的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/413c4686d69b45bb9cf96516883bf418e6c7aa43?/211/?jdm
- **城市社区治理的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/413c4686d69b45bb9cf96516883bf418e6c7aa43?/811=241
- **城市树木认养的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/413c4686d69b45bb9cf96516883bf418e6c7aa43?/ozl=699
- **乡村文化活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/46d91dd71d24a370714ef983ee1f3af66be392b2?/734
- **城乡交流活动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/46d91dd71d24a370714ef983ee1f3af66be392b2?/fgk
- **家庭安全提示的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/46d91dd71d24a370714ef983ee1f3af66be392b2?/702/?vvj
- **本地旅行体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/46d91dd71d24a370714ef983ee1f3af66be392b2?/685=814
- **城市公共标识的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/46d91dd71d24a370714ef983ee1f3af66be392b2?/rtr=062
- **城市绿色交通的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6e783e15a845a386fd5b54c50cbb7e6ee5009b?/906
- **公共交通接驳的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6e783e15a845a386fd5b54c50cbb7e6ee5009b?/nkh
- **绿色建筑理念的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6e783e15a845a386fd5b54c50cbb7e6ee5009b?/651/?jvu
- **城市文明实践中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6e783e15a845a386fd5b54c50cbb7e6ee5009b?/573=794
- **老年学习活动的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2f6e783e15a845a386fd5b54c50cbb7e6ee5009b?/qye=993
- **儿童友好街区的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d51847b1d702238e217b604a94efc9271fbec3cf?/990
- **人工智能科普的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/d51847b1d702238e217b604a94efc9271fbec3cf?/npi
- **便民信息查询中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d51847b1d702238e217b604a94efc9271fbec3cf?/604/?sti
- **生活垃圾回收的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d51847b1d702238e217b604a94efc9271fbec3cf?/534=088
- **绿色建筑理念的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/d51847b1d702238e217b604a94efc9271fbec3cf?/zzl=870
- **乡村公共服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/68af4dffab6742dbadc643f865258f0d4914894b?/474
- **家庭健康科普的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/68af4dffab6742dbadc643f865258f0d4914894b?/dqf
- **老年人出行服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/68af4dffab6742dbadc643f865258f0d4914894b?/930/?qzc
- **社区体育组织的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/68af4dffab6742dbadc643f865258f0d4914894b?/121=791
- **食品安全科普的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/68af4dffab6742dbadc643f865258f0d4914894b?/bcc=927
- **社区信息发布的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/c207a05948257d3b6c4e71dcb7730f62f9f50d1c?/199
- **城市运动公园的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c207a05948257d3b6c4e71dcb7730f62f9f50d1c?/wgq
- **便民信息查询的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c207a05948257d3b6c4e71dcb7730f62f9f50d1c?/956/?yyu
- **绿色快递包装的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/c207a05948257d3b6c4e71dcb7730f62f9f50d1c?/477=852
- **城市运动公园的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/c207a05948257d3b6c4e71dcb7730f62f9f50d1c?/fdh=865
- **读书会组织的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/4ad4c251762e1ed3583562b9423250f2dbb59544?/946
- **城市夜间照明的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/4ad4c251762e1ed3583562b9423250f2dbb59544?/eyn
- **公共服务数字化的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/4ad4c251762e1ed3583562b9423250f2dbb59544?/941/?lxo
- **数字课堂应用的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/4ad4c251762e1ed3583562b9423250f2dbb59544?/291=124
- **农业科普体验的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4ad4c251762e1ed3583562b9423250f2dbb59544?/wft=569
- **家庭健康科普的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/995b7e24852a33eacd1622a00b4df69a41deeb94?/668
- **城市可持续生活的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/995b7e24852a33eacd1622a00b4df69a41deeb94?/ucg
- **社区休闲设施的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/995b7e24852a33eacd1622a00b4df69a41deeb94?/298/?znx
- **开放数据应用的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/995b7e24852a33eacd1622a00b4df69a41deeb94?/545=950
- **公共空间照明的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/995b7e24852a33eacd1622a00b4df69a41deeb94?/bui=778
- **城市宠物友好空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/450f5c43bcc7a8f62e3781d5014c128ec5068cd0?/282
- **传统手工艺体验从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/450f5c43bcc7a8f62e3781d5014c128ec5068cd0?/fbp
- **在线学习体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/450f5c43bcc7a8f62e3781d5014c128ec5068cd0?/904/?dyq
- **城市树木认养的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/450f5c43bcc7a8f62e3781d5014c128ec5068cd0?/415=847
- **街头绿植养护的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/450f5c43bcc7a8f62e3781d5014c128ec5068cd0?/aek=357
- **公共空间休憩的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/59e2b7f66ca21c138c12c09c328270233568cfe7?/515
- **社区教育资源的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/59e2b7f66ca21c138c12c09c328270233568cfe7?/cnl
- **城市环境志愿行动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/59e2b7f66ca21c138c12c09c328270233568cfe7?/863/?cmy
- **生活垃圾回收的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/59e2b7f66ca21c138c12c09c328270233568cfe7?/359=560
- **社区艺术活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/59e2b7f66ca21c138c12c09c328270233568cfe7?/agr=394
- **家庭环保习惯的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/5e305ce8da0383cc5f7ace356e6dc93102a0b727?/147
- **跨代沟通活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/5e305ce8da0383cc5f7ace356e6dc93102a0b727?/jfs
- **城市公共厕所的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5e305ce8da0383cc5f7ace356e6dc93102a0b727?/094/?tby
- **无障碍信息设计的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/5e305ce8da0383cc5f7ace356e6dc93102a0b727?/126=949
- **社区文化节活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5e305ce8da0383cc5f7ace356e6dc93102a0b727?/jsc=456
- **老年人日常照护的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/84bba062b3f89e0e3f56f3fbe1f01e26a0e0c2cb?/425
- **数字政务体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/84bba062b3f89e0e3f56f3fbe1f01e26a0e0c2cb?/iii
- **智能家居应用的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/84bba062b3f89e0e3f56f3fbe1f01e26a0e0c2cb?/604/?frz
- **家庭安全提示的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/84bba062b3f89e0e3f56f3fbe1f01e26a0e0c2cb?/790=620
- **城乡交通衔接的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/84bba062b3f89e0e3f56f3fbe1f01e26a0e0c2cb?/xpc=692
- **科技馆参观体验的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2a2c4001d14d5cc9bc4dbf8a8f3c5670f93eec84?/429
- **城乡公共服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2a2c4001d14d5cc9bc4dbf8a8f3c5670f93eec84?/ypl
- **科学健身方法的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/2a2c4001d14d5cc9bc4dbf8a8f3c5670f93eec84?/764/?vjr
- **家庭阅读计划的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2a2c4001d14d5cc9bc4dbf8a8f3c5670f93eec84?/988=061
- **城市游园体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/2a2c4001d14d5cc9bc4dbf8a8f3c5670f93eec84?/ttp=655
- **生活垃圾回收的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/be9ff6b67f5372e7a8d3a637a977e75f9262e7ce?/825
- **零废弃生活尝试的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/be9ff6b67f5372e7a8d3a637a977e75f9262e7ce?/niw
- **城市休闲步道的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/be9ff6b67f5372e7a8d3a637a977e75f9262e7ce?/309/?dyw
- **家庭饮食安排的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/be9ff6b67f5372e7a8d3a637a977e75f9262e7ce?/465=239
- **绿色快递包装的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/be9ff6b67f5372e7a8d3a637a977e75f9262e7ce?/pnx=618
- **街区小店体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/5c0292064b3ad98332bf1530390bd6f00a4010ab?/951
- **社区托育服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5c0292064b3ad98332bf1530390bd6f00a4010ab?/hgf
- **乡村电商实践的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5c0292064b3ad98332bf1530390bd6f00a4010ab?/998/?hli
- **公共空间安全的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5c0292064b3ad98332bf1530390bd6f00a4010ab?/557=129
- **食品配送体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/5c0292064b3ad98332bf1530390bd6f00a4010ab?/jlf=937
- **社区便民服务的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9391d27dbee7237de6c3246ce61084de7841854e?/192
- **老年运动活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/9391d27dbee7237de6c3246ce61084de7841854e?/fml
- **公共卫生设施的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/9391d27dbee7237de6c3246ce61084de7841854e?/855/?laz
- **城市基础设施的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/9391d27dbee7237de6c3246ce61084de7841854e?/023=668
- **基层健康档案的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9391d27dbee7237de6c3246ce61084de7841854e?/jhc=528
- **休闲运动入门的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/814cb128f16e6bdceef8db35901bf8f657976598?/526
- **社区共享书架的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/814cb128f16e6bdceef8db35901bf8f657976598?/lqv
- **城市公共艺术的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/814cb128f16e6bdceef8db35901bf8f657976598?/612/?zof
- **运动安全知识的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/814cb128f16e6bdceef8db35901bf8f657976598?/304=114
- **物业服务沟通的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/814cb128f16e6bdceef8db35901bf8f657976598?/alz=011
- **个人数据管理的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/fe9f71d87272475b6124f89485d2cecac9c1425d?/481
- **零废弃生活尝试的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fe9f71d87272475b6124f89485d2cecac9c1425d?/rna
- **青少年科技社团的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fe9f71d87272475b6124f89485d2cecac9c1425d?/152/?rmc
- **青少年职业启蒙的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/fe9f71d87272475b6124f89485d2cecac9c1425d?/933=366
- **智能家居应用的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/fe9f71d87272475b6124f89485d2cecac9c1425d?/yni=310
- **城市公共饮水的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/956d8607b34208b73a2315fa75058713d0a80986?/987
- **文化场馆预约的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/956d8607b34208b73a2315fa75058713d0a80986?/ozr
- **数字公共文化的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/956d8607b34208b73a2315fa75058713d0a80986?/205/?njg
- **乡村电商实践从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/956d8607b34208b73a2315fa75058713d0a80986?/808=539
- **零废弃生活尝试的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/956d8607b34208b73a2315fa75058713d0a80986?/upt=649
- **基层健康档案的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/983e459423f64bbaf447e30b7b3c90acf197c035?/055
- **健康步道使用的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/983e459423f64bbaf447e30b7b3c90acf197c035?/wfk
- **城乡交通衔接的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/983e459423f64bbaf447e30b7b3c90acf197c035?/516/?bzi
- **数字设备回收的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/983e459423f64bbaf447e30b7b3c90acf197c035?/813=571
- **社区故事采集的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/983e459423f64bbaf447e30b7b3c90acf197c035?/awk=755
- **非遗课堂体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3a2b95347120cc8894e62a80e46333aa7f367b9e?/748
- **社区宣传栏更新的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3a2b95347120cc8894e62a80e46333aa7f367b9e?/ytc
- **老年友好服务的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/3a2b95347120cc8894e62a80e46333aa7f367b9e?/470/?nif
- **数字地图应用的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3a2b95347120cc8894e62a80e46333aa7f367b9e?/229=758
- **生成式工具使用的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3a2b95347120cc8894e62a80e46333aa7f367b9e?/qhb=040
- **城市宠物友好空间的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2ce2a2b5bf86823f9a30a0d7583d0ac215043851?/879
- **节气饮食文化的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2ce2a2b5bf86823f9a30a0d7583d0ac215043851?/cek
- **儿童友好空间的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2ce2a2b5bf86823f9a30a0d7583d0ac215043851?/440/?owx
- **城市噪声观察的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2ce2a2b5bf86823f9a30a0d7583d0ac215043851?/884=213
- **绿色生活实践的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/2ce2a2b5bf86823f9a30a0d7583d0ac215043851?/pyv=417
- **图书馆亲子空间中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f8c7e79d54cc3c00039c69b18707c65484babc0a?/099
- **文明养宠科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/f8c7e79d54cc3c00039c69b18707c65484babc0a?/ued
- **家庭健康管理的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/f8c7e79d54cc3c00039c69b18707c65484babc0a?/405/?msn
- **基层服务创新的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f8c7e79d54cc3c00039c69b18707c65484babc0a?/873=921
- **城市噪声观察的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f8c7e79d54cc3c00039c69b18707c65484babc0a?/qrs=303
- **城市夜间照明的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/85bb740f3598688a1db8fd43f88daf0d48a3ee51?/810
- **社区快递服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/85bb740f3598688a1db8fd43f88daf0d48a3ee51?/vvp
- **智慧停车服务的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/85bb740f3598688a1db8fd43f88daf0d48a3ee51?/452/?itf
- **城市慢行系统中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/85bb740f3598688a1db8fd43f88daf0d48a3ee51?/984=118
- **亲子科普活动的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/85bb740f3598688a1db8fd43f88daf0d48a3ee51?/fpz=181
- **社区设施共享的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/90cc9950925e004fd370f0a7d5b0116e1248da6a?/552
- **社区体育组织的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/90cc9950925e004fd370f0a7d5b0116e1248da6a?/gqr
- **数字支付体验的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/90cc9950925e004fd370f0a7d5b0116e1248da6a?/123/?blr
- **公共空间安全的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/90cc9950925e004fd370f0a7d5b0116e1248da6a?/238=216
- **本地消费场景的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/90cc9950925e004fd370f0a7d5b0116e1248da6a?/amj=918
- **小区电梯维护的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f823c23534ad97ae3d3e42f9054d69d3ecfc1153?/105
- **应急物资管理的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f823c23534ad97ae3d3e42f9054d69d3ecfc1153?/pzv
- **数字生活课堂的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/f823c23534ad97ae3d3e42f9054d69d3ecfc1153?/353/?jco
- **社区手工活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f823c23534ad97ae3d3e42f9054d69d3ecfc1153?/049=692
- **城市体育设施的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/f823c23534ad97ae3d3e42f9054d69d3ecfc1153?/how=102
- **青年志愿活动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/0b26ccbbb55d6caf6e287da0c321c44146875654?/454
- **公共服务指南的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0b26ccbbb55d6caf6e287da0c321c44146875654?/xjo
- **课后服务体验的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/0b26ccbbb55d6caf6e287da0c321c44146875654?/006/?jls
- **社区安全巡查的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/0b26ccbbb55d6caf6e287da0c321c44146875654?/593=574
- **公园无障碍服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/0b26ccbbb55d6caf6e287da0c321c44146875654?/ofv=642
- **社区文化传播的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/96bd5e667cc40fe0dc33a47af479ac43842ad45c?/563
- **基层健康档案的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/96bd5e667cc40fe0dc33a47af479ac43842ad45c?/iad
- **城市博物馆服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/96bd5e667cc40fe0dc33a47af479ac43842ad45c?/542/?pqz
- **数字阅读服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/96bd5e667cc40fe0dc33a47af479ac43842ad45c?/721=941
- **科学睡眠习惯的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/96bd5e667cc40fe0dc33a47af479ac43842ad45c?/kfn=404
- **劳动教育实践的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/2471c8813c74443f81e407bc9fa60163cbfa89fa?/294
- **绿色校园实践的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2471c8813c74443f81e407bc9fa60163cbfa89fa?/ppy
- **城市公共艺术的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/2471c8813c74443f81e407bc9fa60163cbfa89fa?/272/?nsk
- **城市生活记录的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2471c8813c74443f81e407bc9fa60163cbfa89fa?/716=494
- **公共场所导视中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2471c8813c74443f81e407bc9fa60163cbfa89fa?/bks=177
- **社区便利生活的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e803619e954cd0bb6f456668d0774f87037ec468?/173
- **城市公共艺术的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/e803619e954cd0bb6f456668d0774f87037ec468?/rpc
- **青年志愿活动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/e803619e954cd0bb6f456668d0774f87037ec468?/440/?noq
- **家庭饮食安排的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/e803619e954cd0bb6f456668d0774f87037ec468?/082=785
- **社区绿色空间的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/e803619e954cd0bb6f456668d0774f87037ec468?/zba=735
- **社区垃圾回收的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/6f7d72842efd8c3b5ea1abe0910eef747c6bdc54?/462
- **公共图书馆服务的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/6f7d72842efd8c3b5ea1abe0910eef747c6bdc54?/kgu
- **家庭环保习惯的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/6f7d72842efd8c3b5ea1abe0910eef747c6bdc54?/607/?ses
- **科学信息获取的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/6f7d72842efd8c3b5ea1abe0910eef747c6bdc54?/677=490
- **人工智能科普的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6f7d72842efd8c3b5ea1abe0910eef747c6bdc54?/yil=611
- **家庭饮食安排的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3521b4023f5b4d2f17290d824e023787781a2961?/990
- **创业经验分享的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3521b4023f5b4d2f17290d824e023787781a2961?/mgo
- **科技馆参观体验的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3521b4023f5b4d2f17290d824e023787781a2961?/211/?rbb
- **科普展览体验的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3521b4023f5b4d2f17290d824e023787781a2961?/362=474
- **社区宣传栏更新的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3521b4023f5b4d2f17290d824e023787781a2961?/gsi=665
- **家庭理财科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/84e89d80806b5528abae9012b1dda3ed27bddcd3?/899
- **科普展览体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/84e89d80806b5528abae9012b1dda3ed27bddcd3?/osr
- **数字便民地图的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/84e89d80806b5528abae9012b1dda3ed27bddcd3?/791/?cgv
- **公共服务评价的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/84e89d80806b5528abae9012b1dda3ed27bddcd3?/799=689
- **社区垃圾分类的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/84e89d80806b5528abae9012b1dda3ed27bddcd3?/rpw=306
- **网络安全教育的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3b8e46cc7e1067b61c6ce747078bfa65d95ec18b?/074
- **社区交通安全的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3b8e46cc7e1067b61c6ce747078bfa65d95ec18b?/eyo
- **社区便利生活的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3b8e46cc7e1067b61c6ce747078bfa65d95ec18b?/224/?jdy
- **街区更新实践的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/3b8e46cc7e1067b61c6ce747078bfa65d95ec18b?/387=869
- **读书会组织的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3b8e46cc7e1067b61c6ce747078bfa65d95ec18b?/coj=736
- **在线学习体验的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/663a5b42f58b5c09144b5a818849d6ee05b5485a?/210
- **公共交通信息服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/663a5b42f58b5c09144b5a818849d6ee05b5485a?/vne
- **食品配送体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/663a5b42f58b5c09144b5a818849d6ee05b5485a?/383/?fhz
- **城市住房服务的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/663a5b42f58b5c09144b5a818849d6ee05b5485a?/567=678
- **非遗体验活动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/663a5b42f58b5c09144b5a818849d6ee05b5485a?/awr=203
- **开源技术交流的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/221aa28f56236a860a9707f29bfe15d43d83b9fe?/055
- **城市公共自行车的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/221aa28f56236a860a9707f29bfe15d43d83b9fe?/zkn
- **数字支付体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/221aa28f56236a860a9707f29bfe15d43d83b9fe?/757/?tqe
- **家庭网络使用的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/221aa28f56236a860a9707f29bfe15d43d83b9fe?/701=857
- **周末休闲规划的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/221aa28f56236a860a9707f29bfe15d43d83b9fe?/ejc=203
- **邻里共享空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ddefaea4b8cde5944c07602032ce85d44a97e736?/342
- **读书会组织的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/ddefaea4b8cde5944c07602032ce85d44a97e736?/iqe
- **在线教育体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ddefaea4b8cde5944c07602032ce85d44a97e736?/592/?fqc
- **文化讲座服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/ddefaea4b8cde5944c07602032ce85d44a97e736?/967=707
- **青少年职业启蒙的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ddefaea4b8cde5944c07602032ce85d44a97e736?/wxs=817
- **全民健身活动的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e054ef88a0bf74a38c9fdbefa0e55f34164c1ada?/216
- **农业科普体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e054ef88a0bf74a38c9fdbefa0e55f34164c1ada?/vnh
- **城市农夫市集的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/e054ef88a0bf74a38c9fdbefa0e55f34164c1ada?/466/?lyf
- **数字设备回收的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e054ef88a0bf74a38c9fdbefa0e55f34164c1ada?/360=057
- **城市环境志愿行动的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/e054ef88a0bf74a38c9fdbefa0e55f34164c1ada?/qkd=616
- **公共服务咨询的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/23e3dac761aa37c932c4ffd6b803a62313d1c839?/581
- **旧物循环利用的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/23e3dac761aa37c932c4ffd6b803a62313d1c839?/xpq
- **社区学习活动的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/23e3dac761aa37c932c4ffd6b803a62313d1c839?/497/?yjv
- **绿色消费选择的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/23e3dac761aa37c932c4ffd6b803a62313d1c839?/976=379
- **乡村产业科普的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/23e3dac761aa37c932c4ffd6b803a62313d1c839?/lnp=409
- **乡村电商实践的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c924733344f183d950c584e1062415f457fdb7d2?/139
- **全民健身活动的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/c924733344f183d950c584e1062415f457fdb7d2?/lyo
- **城市微更新实践的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/c924733344f183d950c584e1062415f457fdb7d2?/680/?jmg
- **软件开发学习的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c924733344f183d950c584e1062415f457fdb7d2?/642=759
- **文化遗产保护科普的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c924733344f183d950c584e1062415f457fdb7d2?/fec=831
- **公共图书馆服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/6114afa910a12af769606a2a38f11619f9ea16eb?/024
- **家庭健康管理的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/6114afa910a12af769606a2a38f11619f9ea16eb?/snl
- **基层健康档案的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/6114afa910a12af769606a2a38f11619f9ea16eb?/248/?lhg
- **个人时间管理的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6114afa910a12af769606a2a38f11619f9ea16eb?/877=629
- **公共交通接驳的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/6114afa910a12af769606a2a38f11619f9ea16eb?/ivn=594
- **科学观察活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/07c83de430a863b6a6d6f7346b9586c19fe1f9a9?/495
- **地方旅游导览从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/07c83de430a863b6a6d6f7346b9586c19fe1f9a9?/ucq
- **智慧停车服务的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/07c83de430a863b6a6d6f7346b9586c19fe1f9a9?/501/?vte
- **城市人文观察的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/07c83de430a863b6a6d6f7346b9586c19fe1f9a9?/988=804
- **就业技能培训的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/07c83de430a863b6a6d6f7346b9586c19fe1f9a9?/ntx=328
- **乡村公共文化从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/8f7063881579f720e2477626952a573fa8d1fb87?/900
- **老年人文化生活的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8f7063881579f720e2477626952a573fa8d1fb87?/exg
- **社区活动空间的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8f7063881579f720e2477626952a573fa8d1fb87?/005/?xed
- **家庭节能设备从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/8f7063881579f720e2477626952a573fa8d1fb87?/393=507
- **公共服务评价的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/8f7063881579f720e2477626952a573fa8d1fb87?/fua=274
- **社区垃圾分类的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/d824cdaae017cbed779d280d01eca4a01e2585d2?/642
- **城市人文观察的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d824cdaae017cbed779d280d01eca4a01e2585d2?/wzr
- **社区故事采集的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d824cdaae017cbed779d280d01eca4a01e2585d2?/670/?cnk
- **社区垃圾回收中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/d824cdaae017cbed779d280d01eca4a01e2585d2?/991=140
- **老年学习活动的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d824cdaae017cbed779d280d01eca4a01e2585d2?/dhb=057
- **老年运动活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9ff2de6a002bc3ba2fc98fe35eee204d1f011275?/712
- **数字设备回收从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/9ff2de6a002bc3ba2fc98fe35eee204d1f011275?/ckn
- **社区绿色空间的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9ff2de6a002bc3ba2fc98fe35eee204d1f011275?/974/?nkv
- **本地历史资料的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/9ff2de6a002bc3ba2fc98fe35eee204d1f011275?/376=823
- **家庭食品保存的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9ff2de6a002bc3ba2fc98fe35eee204d1f011275?/xll=899
- **社区花园共建的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/8caf74ac5f385cd40a6ced2e5a8d9aeb16e671f6?/526
- **乡村公共服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8caf74ac5f385cd40a6ced2e5a8d9aeb16e671f6?/xcl
- **骑行路线规划中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/8caf74ac5f385cd40a6ced2e5a8d9aeb16e671f6?/781/?ord
- **公共健身器材的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8caf74ac5f385cd40a6ced2e5a8d9aeb16e671f6?/349=947
- **城市微更新实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8caf74ac5f385cd40a6ced2e5a8d9aeb16e671f6?/tfe=804
- **休闲运动入门的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/29eab53714eb0223e6cac49eca49b744bbb41c52?/365
- **老年友好服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/29eab53714eb0223e6cac49eca49b744bbb41c52?/sxx
- **气象科普传播的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/29eab53714eb0223e6cac49eca49b744bbb41c52?/540/?daj
- **小微企业服务的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/29eab53714eb0223e6cac49eca49b744bbb41c52?/822=995
- **城市公共厕所的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/29eab53714eb0223e6cac49eca49b744bbb41c52?/hoq=786
- **社区菜市场服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/e1a0b98b3aa82207ff80ec63e4289d636d2f0f94?/630
- **节约用水实践的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/e1a0b98b3aa82207ff80ec63e4289d636d2f0f94?/cvl
- **小区停车协商从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/e1a0b98b3aa82207ff80ec63e4289d636d2f0f94?/011/?uyf
- **智慧城市体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/e1a0b98b3aa82207ff80ec63e4289d636d2f0f94?/634=402
- **个人信息保护的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/e1a0b98b3aa82207ff80ec63e4289d636d2f0f94?/ccl=687
- **公交站点体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/aea7080fcf4c5b31c397b7eb8c7d15f8d8a7441c?/763
- **社区活动空间的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/aea7080fcf4c5b31c397b7eb8c7d15f8d8a7441c?/zlt
- **周末休闲规划的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/aea7080fcf4c5b31c397b7eb8c7d15f8d8a7441c?/208/?cgm
- **儿童友好空间的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/aea7080fcf4c5b31c397b7eb8c7d15f8d8a7441c?/667=260
- **口袋公园建设的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/aea7080fcf4c5b31c397b7eb8c7d15f8d8a7441c?/kiu=154
- **老年数字阅读的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/82d9bd85c6c82a9638b14a1d0d0c793493eaa2a8?/399
- **在线教育体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/82d9bd85c6c82a9638b14a1d0d0c793493eaa2a8?/kbl
- **乡村阅读空间的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/82d9bd85c6c82a9638b14a1d0d0c793493eaa2a8?/804/?ylm
- **青年志愿活动中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/82d9bd85c6c82a9638b14a1d0d0c793493eaa2a8?/241=986
- **社区艺术活动的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/82d9bd85c6c82a9638b14a1d0d0c793493eaa2a8?/pvo=204
- **基层健康服务的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/514178146418dd8a0f170e9b27fde99e2565132a?/109
- **城市住房服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/514178146418dd8a0f170e9b27fde99e2565132a?/rlz
- **科学信息获取的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/514178146418dd8a0f170e9b27fde99e2565132a?/455/?vab
- **电子商务服务的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/514178146418dd8a0f170e9b27fde99e2565132a?/138=909
- **城市共享单车的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/514178146418dd8a0f170e9b27fde99e2565132a?/zgk=187
- **街道综合服务的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/2116243593a63d1da39b932de377765785c58f47?/127
- **城市绿道建设的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/2116243593a63d1da39b932de377765785c58f47?/clh
- **创业经验分享的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/2116243593a63d1da39b932de377765785c58f47?/875/?wwr
- **便民信息查询的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2116243593a63d1da39b932de377765785c58f47?/419=206
- **传统节日科普从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/2116243593a63d1da39b932de377765785c58f47?/bti=496
- **社区消防演练的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/2617af5b9bb69f7f78d9f2efb4a343a643edc3a3?/705
- **本地历史资料有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2617af5b9bb69f7f78d9f2efb4a343a643edc3a3?/fdd
- **城市雨天出行的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2617af5b9bb69f7f78d9f2efb4a343a643edc3a3?/704/?tcw
- **图书借阅体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/2617af5b9bb69f7f78d9f2efb4a343a643edc3a3?/610=444
- **乡村电商实践的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2617af5b9bb69f7f78d9f2efb4a343a643edc3a3?/hky=053
- **农村环境治理的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b750a7dd2e31ceaff6731927e0aff852c5705dec?/766
- **老年人文化生活的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/b750a7dd2e31ceaff6731927e0aff852c5705dec?/xjk
- **街头绿植养护的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/b750a7dd2e31ceaff6731927e0aff852c5705dec?/809/?epo
- **社区生活指南的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/b750a7dd2e31ceaff6731927e0aff852c5705dec?/537=605
- **食品安全科普的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/b750a7dd2e31ceaff6731927e0aff852c5705dec?/qbr=681
- **基层健康服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/2791cd1b96ed850c73e86676199d997ff1ef01c7?/791
- **城市树木认养的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/2791cd1b96ed850c73e86676199d997ff1ef01c7?/tts
- **老年运动活动的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2791cd1b96ed850c73e86676199d997ff1ef01c7?/758/?ija
- **网络信息辨识的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2791cd1b96ed850c73e86676199d997ff1ef01c7?/160=492
- **社区垃圾回收的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2791cd1b96ed850c73e86676199d997ff1ef01c7?/sop=156
- **城市绿色交通的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b1cbde15493fab46002446e3b0746518989c976?/384
- **城市公共饮水的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7b1cbde15493fab46002446e3b0746518989c976?/ogu
- **本地消费场景的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/7b1cbde15493fab46002446e3b0746518989c976?/130/?iaz
- **居家防滑改造的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b1cbde15493fab46002446e3b0746518989c976?/903=587
- **口袋公园建设的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/7b1cbde15493fab46002446e3b0746518989c976?/qcz=147
- **社区邻里服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2d32f800ead25eb1646a5d3c0c49ff210392786d?/679
- **信息无障碍体验的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/2d32f800ead25eb1646a5d3c0c49ff210392786d?/tnh
- **城市空气科普的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2d32f800ead25eb1646a5d3c0c49ff210392786d?/234/?utp
- **家庭饮食安排的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/2d32f800ead25eb1646a5d3c0c49ff210392786d?/674=739
- **亲子阅读活动的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2d32f800ead25eb1646a5d3c0c49ff210392786d?/ddz=413
- **乡村休闲旅游的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9f366bbe847e90e331ee8976bdd3eb157cd1b1de?/493
- **户外活动组织的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/9f366bbe847e90e331ee8976bdd3eb157cd1b1de?/eba
- **社区垃圾回收的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/9f366bbe847e90e331ee8976bdd3eb157cd1b1de?/734/?lml
- **城市公共空间的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/9f366bbe847e90e331ee8976bdd3eb157cd1b1de?/173=792
- **城市地名文化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9f366bbe847e90e331ee8976bdd3eb157cd1b1de?/wli=215
- **个人时间管理的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/6e4f6511e3ed92eadc2af489d599f499870fa461?/400
- **跨代沟通活动从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6e4f6511e3ed92eadc2af489d599f499870fa461?/vlj
- **数字设备回收的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/6e4f6511e3ed92eadc2af489d599f499870fa461?/293/?bob
- **文化讲座服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6e4f6511e3ed92eadc2af489d599f499870fa461?/283=976
- **健康饮水科普的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/6e4f6511e3ed92eadc2af489d599f499870fa461?/pwh=489
- **青少年科技社团的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d8b3e3cb863d6fc83205069ae4ca6b9528259385?/913
- **乡村生活观察的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d8b3e3cb863d6fc83205069ae4ca6b9528259385?/ioe
- **乡村生态观察中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/d8b3e3cb863d6fc83205069ae4ca6b9528259385?/186/?xdd
- **运动安全知识的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d8b3e3cb863d6fc83205069ae4ca6b9528259385?/131=396
- **社区老年食堂的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d8b3e3cb863d6fc83205069ae4ca6b9528259385?/ofx=652
- **社区读书角建设的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8e9be5080897a72b8b9a2d15f29a1a867d5ab085?/381
- **生活服务数字化的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8e9be5080897a72b8b9a2d15f29a1a867d5ab085?/oal
- **城市骑行环境的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/8e9be5080897a72b8b9a2d15f29a1a867d5ab085?/893/?pro
- **社区宣传栏更新的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/8e9be5080897a72b8b9a2d15f29a1a867d5ab085?/005=038
- **数字支付体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8e9be5080897a72b8b9a2d15f29a1a867d5ab085?/utg=443
- **公园休闲体验的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7a5595d9870f280734bc997b18f5afe213acafae?/857
- **食品安全科普的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7a5595d9870f280734bc997b18f5afe213acafae?/nkt
- **城市生活服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/7a5595d9870f280734bc997b18f5afe213acafae?/930/?dou
- **个人信息保护的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7a5595d9870f280734bc997b18f5afe213acafae?/122=193
- **城市社区治理的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7a5595d9870f280734bc997b18f5afe213acafae?/jnm=839
- **社区文化节活动的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/09ddf24e889fa233132b6654d947d2a7e3ad8b39?/672
- **科学信息获取的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/09ddf24e889fa233132b6654d947d2a7e3ad8b39?/ewk
- **家庭阅读计划的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/09ddf24e889fa233132b6654d947d2a7e3ad8b39?/482/?jit
- **社区宠物管理中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/09ddf24e889fa233132b6654d947d2a7e3ad8b39?/569=588
- **儿童运动体验的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/09ddf24e889fa233132b6654d947d2a7e3ad8b39?/ufo=601
- **家庭食品保存的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/9e0fb9068931a477f7264347ee76ae7f161c82b3?/602
- **青少年心理健康的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/9e0fb9068931a477f7264347ee76ae7f161c82b3?/kri
- **城市生活服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/9e0fb9068931a477f7264347ee76ae7f161c82b3?/881/?pek
- **社区志愿服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/9e0fb9068931a477f7264347ee76ae7f161c82b3?/941=011
- **城市绿道建设的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9e0fb9068931a477f7264347ee76ae7f161c82b3?/dso=910
- **老年数字阅读的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/661acacdb49a3bf7b2184b908ed57da0ab087370?/448
- **城市农夫市集的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/661acacdb49a3bf7b2184b908ed57da0ab087370?/zqn
- **公共服务数字化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/661acacdb49a3bf7b2184b908ed57da0ab087370?/961/?maj
- **家庭健康科普的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/661acacdb49a3bf7b2184b908ed57da0ab087370?/633=938
- **公共卫生宣传的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/661acacdb49a3bf7b2184b908ed57da0ab087370?/bre=415
- **家庭节能设备的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/7da47fd38229c9ef43382e0b5561354f0dfcb6c5?/379
- **家庭园艺实践的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7da47fd38229c9ef43382e0b5561354f0dfcb6c5?/ftz
- **食品配送体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7da47fd38229c9ef43382e0b5561354f0dfcb6c5?/873/?pvw
- **家庭阅读计划的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7da47fd38229c9ef43382e0b5561354f0dfcb6c5?/142=064
- **家庭照护支持的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/7da47fd38229c9ef43382e0b5561354f0dfcb6c5?/vop=681
- **消防知识宣传中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/eef86aa1fa71aab006e78433eb52123e18f6fe7f?/282
- **公共空间安全的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/eef86aa1fa71aab006e78433eb52123e18f6fe7f?/apl
- **社区消防演练的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/eef86aa1fa71aab006e78433eb52123e18f6fe7f?/099/?cvn
- **公共服务咨询的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/eef86aa1fa71aab006e78433eb52123e18f6fe7f?/664=237
- **青少年心理健康的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/eef86aa1fa71aab006e78433eb52123e18f6fe7f?/zfs=735
- **城市公共座椅中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/39dfa65a55c0fdca286f025f3fa3f718e73d00c4?/843
- **光伏知识科普的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/39dfa65a55c0fdca286f025f3fa3f718e73d00c4?/odg
- **健康步道使用中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/39dfa65a55c0fdca286f025f3fa3f718e73d00c4?/247/?gxu
- **食品安全科普的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/39dfa65a55c0fdca286f025f3fa3f718e73d00c4?/399=210
- **居家防滑改造的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/39dfa65a55c0fdca286f025f3fa3f718e73d00c4?/cri=477
- **全民健身活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c3d90eb453821aa38d690da787e5d3be31d9f9a0?/235
- **城市博物馆活动的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c3d90eb453821aa38d690da787e5d3be31d9f9a0?/dze
- **新能源知识普及的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/c3d90eb453821aa38d690da787e5d3be31d9f9a0?/050/?lao
- **家庭健康科普的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/c3d90eb453821aa38d690da787e5d3be31d9f9a0?/753=496
- **市民热线服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c3d90eb453821aa38d690da787e5d3be31d9f9a0?/knb=812
- **传统节日科普的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7596bda0bf4d1202a2f46a34402da2d96f57dbec?/727
- **城市公共自行车的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/7596bda0bf4d1202a2f46a34402da2d96f57dbec?/nzl
- **邻里共享空间的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7596bda0bf4d1202a2f46a34402da2d96f57dbec?/430/?puw
- **儿童运动体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7596bda0bf4d1202a2f46a34402da2d96f57dbec?/545=003
- **社区科普课堂的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/7596bda0bf4d1202a2f46a34402da2d96f57dbec?/qsf=602
- **地方文化传播的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/11b11636675d0987a03637ce851f629b1919f48a?/817
- **信息无障碍体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/11b11636675d0987a03637ce851f629b1919f48a?/cow
- **街道综合服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/11b11636675d0987a03637ce851f629b1919f48a?/458/?tcd
- **垃圾分类指导的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/11b11636675d0987a03637ce851f629b1919f48a?/772=100
- **公共文化活动的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/11b11636675d0987a03637ce851f629b1919f48a?/ugh=873

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  彩8VIII等*  
*仅供参考，不构成投资建议*
