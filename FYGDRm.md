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

- **终身学习资源的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5c62025631f7a0687ab8e69393ad6e87800f27d9?/594
- **青少年编程学习中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5c62025631f7a0687ab8e69393ad6e87800f27d9?/jrh
- **城市生活记录的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5c62025631f7a0687ab8e69393ad6e87800f27d9?/487/?ctz
- **社区家校合作的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/5c62025631f7a0687ab8e69393ad6e87800f27d9?/901=613
- **本地旅行体验的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5c62025631f7a0687ab8e69393ad6e87800f27d9?/qkk=192
- **节能家电使用的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9e49724f8acaab20c51c2bca1e34cb2a39398a50?/414
- **节约用水实践的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9e49724f8acaab20c51c2bca1e34cb2a39398a50?/ijw
- **社区交通安全从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/9e49724f8acaab20c51c2bca1e34cb2a39398a50?/517/?vsf
- **电子商务服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/9e49724f8acaab20c51c2bca1e34cb2a39398a50?/508=210
- **节假日出行安排的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/9e49724f8acaab20c51c2bca1e34cb2a39398a50?/ydj=469
- **旧物循环利用的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/05c6bde055602fff91c41df870d85f3e0769dee0?/458
- **地方民俗记录的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/05c6bde055602fff91c41df870d85f3e0769dee0?/hej
- **乡村公共阅读的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/05c6bde055602fff91c41df870d85f3e0769dee0?/173/?iit
- **社区科普课堂的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/05c6bde055602fff91c41df870d85f3e0769dee0?/951=945
- **乡村公共服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/05c6bde055602fff91c41df870d85f3e0769dee0?/rvs=940
- **公共空间休憩的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/4d38e57b9fbcc4c3e543419e5d90500820d4dd7c?/234
- **社区学习活动的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/4d38e57b9fbcc4c3e543419e5d90500820d4dd7c?/mcv
- **科学观察活动的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/4d38e57b9fbcc4c3e543419e5d90500820d4dd7c?/842/?hyg
- **公共设施维护的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4d38e57b9fbcc4c3e543419e5d90500820d4dd7c?/070=532
- **科学运动指导中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/4d38e57b9fbcc4c3e543419e5d90500820d4dd7c?/lqv=257
- **小区电梯维护的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/3d43ce485efe9ff927b7a0b2e4938c724721837b?/452
- **学校食育活动的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3d43ce485efe9ff927b7a0b2e4938c724721837b?/vfj
- **青少年科普实践的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3d43ce485efe9ff927b7a0b2e4938c724721837b?/497/?lzq
- **社区托育服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3d43ce485efe9ff927b7a0b2e4938c724721837b?/372=808
- **社区老年食堂有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3d43ce485efe9ff927b7a0b2e4938c724721837b?/bzo=558
- **地方旅游导览的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9908eed08f98cdc8b039beaf808e65bd71e839e1?/771
- **社区邻里服务的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/9908eed08f98cdc8b039beaf808e65bd71e839e1?/nan
- **乡村阅读空间的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/9908eed08f98cdc8b039beaf808e65bd71e839e1?/545/?zbi
- **地方戏曲体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/9908eed08f98cdc8b039beaf808e65bd71e839e1?/591=482
- **社区健康讲座的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/9908eed08f98cdc8b039beaf808e65bd71e839e1?/ffr=617
- **户外活动组织的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3eeaec613ad94a5a5595b0ba4b692c3f5ba824f0?/412
- **社区便利生活的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3eeaec613ad94a5a5595b0ba4b692c3f5ba824f0?/uqc
- **无障碍出行的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3eeaec613ad94a5a5595b0ba4b692c3f5ba824f0?/688/?xwi
- **公共交通信息服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3eeaec613ad94a5a5595b0ba4b692c3f5ba824f0?/286=235
- **城市应急科普的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3eeaec613ad94a5a5595b0ba4b692c3f5ba824f0?/qug=742
- **科学观察活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1115ed1af1fe7c5dc3bbe5dca3dd15eea30cf076?/997
- **数字公共文化的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1115ed1af1fe7c5dc3bbe5dca3dd15eea30cf076?/edx
- **社区艺术活动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1115ed1af1fe7c5dc3bbe5dca3dd15eea30cf076?/870/?mtm
- **公共服务数字化的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/1115ed1af1fe7c5dc3bbe5dca3dd15eea30cf076?/147=370
- **药品使用科普的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1115ed1af1fe7c5dc3bbe5dca3dd15eea30cf076?/ebx=164
- **物业服务沟通的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/03a7321b51840b5322fc6f9a3230b7c0ae88c926?/874
- **老年人出行服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/03a7321b51840b5322fc6f9a3230b7c0ae88c926?/oto
- **城市慢跑路线的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/03a7321b51840b5322fc6f9a3230b7c0ae88c926?/951/?zhk
- **社区停车服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/03a7321b51840b5322fc6f9a3230b7c0ae88c926?/120=439
- **信息无障碍体验的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/03a7321b51840b5322fc6f9a3230b7c0ae88c926?/byb=459
- **农村环境治理的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/8298450bdfd0623e21ba30f4df0e874da1e22640?/273
- **青少年科普实践的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/8298450bdfd0623e21ba30f4df0e874da1e22640?/dwv
- **本地消费场景的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8298450bdfd0623e21ba30f4df0e874da1e22640?/280/?sye
- **社区慢性病防控的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8298450bdfd0623e21ba30f4df0e874da1e22640?/311=444
- **老年运动活动的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/8298450bdfd0623e21ba30f4df0e874da1e22640?/xsh=383
- **城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/2ddcf172ca4530727d22e46f8b5754f6657b3eff?/996
- **城市夜间生活的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2ddcf172ca4530727d22e46f8b5754f6657b3eff?/itp
- **城市人文观察的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2ddcf172ca4530727d22e46f8b5754f6657b3eff?/264/?xoe
- **开放式学习空间的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2ddcf172ca4530727d22e46f8b5754f6657b3eff?/714=997
- **家庭饮食安排的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/2ddcf172ca4530727d22e46f8b5754f6657b3eff?/zsj=895
- **生活技能分享的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/cac01484fcd02c0ba92d11dbd0d0159c0b6c5396?/902
- **城市休闲步道的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/cac01484fcd02c0ba92d11dbd0d0159c0b6c5396?/rot
- **新能源知识普及的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/cac01484fcd02c0ba92d11dbd0d0159c0b6c5396?/583/?ozd
- **新能源出行的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/cac01484fcd02c0ba92d11dbd0d0159c0b6c5396?/340=903
- **社区知识分享的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/cac01484fcd02c0ba92d11dbd0d0159c0b6c5396?/emi=738
- **地方文化传播的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/88c34fc35ccd96c9ffa1de737a8340c00899b366?/759
- **终身学习资源的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/88c34fc35ccd96c9ffa1de737a8340c00899b366?/ptx
- **文化场馆预约的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/88c34fc35ccd96c9ffa1de737a8340c00899b366?/395/?cch
- **城市休闲步道的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/88c34fc35ccd96c9ffa1de737a8340c00899b366?/154=242
- **生活垃圾减量的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/88c34fc35ccd96c9ffa1de737a8340c00899b366?/bhz=437
- **社区心理支持的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fee31383d0565c819d42adc0069ee04e555dde3c?/114
- **绿色办公实践的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/fee31383d0565c819d42adc0069ee04e555dde3c?/qkk
- **文化遗产保护科普的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fee31383d0565c819d42adc0069ee04e555dde3c?/094/?qjn
- **数字创意课程的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fee31383d0565c819d42adc0069ee04e555dde3c?/075=436
- **社区协商议事的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/fee31383d0565c819d42adc0069ee04e555dde3c?/mdn=853
- **家庭科学教育的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/4ee84d774b9b2f879238dfa070b0532c6c410d12?/607
- **儿童阅读角的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/4ee84d774b9b2f879238dfa070b0532c6c410d12?/yrn
- **公共空间导览的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/4ee84d774b9b2f879238dfa070b0532c6c410d12?/618/?nwm
- **青少年心理健康的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/4ee84d774b9b2f879238dfa070b0532c6c410d12?/555=588
- **公园无障碍服务的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/4ee84d774b9b2f879238dfa070b0532c6c410d12?/nkw=723
- **校园节能行动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/618b75e75167116f0cf6aa71343e3d770531083b?/429
- **城市社区治理的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/618b75e75167116f0cf6aa71343e3d770531083b?/jsn
- **社区宣传栏更新的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/618b75e75167116f0cf6aa71343e3d770531083b?/527/?rdz
- **线上阅读资源的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/618b75e75167116f0cf6aa71343e3d770531083b?/453=406
- **青少年科普实践的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/618b75e75167116f0cf6aa71343e3d770531083b?/alo=866
- **青少年科技社团的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/df9d56f470b9d6d7192a1316898511f1afc8ebd4?/233
- **街区更新实践的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/df9d56f470b9d6d7192a1316898511f1afc8ebd4?/dtz
- **健康步道使用的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/df9d56f470b9d6d7192a1316898511f1afc8ebd4?/223/?vtk
- **公共卫生宣传的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/df9d56f470b9d6d7192a1316898511f1afc8ebd4?/679=334
- **城市宠物友好空间的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/df9d56f470b9d6d7192a1316898511f1afc8ebd4?/ojp=138
- **公共空间安全的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a15731ac35a7f8165c1c8d3f870d6649dfea434a?/507
- **城市生活记录的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/a15731ac35a7f8165c1c8d3f870d6649dfea434a?/fsh
- **社区科普课堂的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/a15731ac35a7f8165c1c8d3f870d6649dfea434a?/117/?gyk
- **节日文化体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/a15731ac35a7f8165c1c8d3f870d6649dfea434a?/331=913
- **乡村产业科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/a15731ac35a7f8165c1c8d3f870d6649dfea434a?/mor=169
- **垃圾分类指导的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/49aa5935044c76027b15fd2ce88ea3cc1b69e9f8?/419
- **在线教育体验的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/49aa5935044c76027b15fd2ce88ea3cc1b69e9f8?/run
- **科学健身方法的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/49aa5935044c76027b15fd2ce88ea3cc1b69e9f8?/520/?cnn
- **家庭健康科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/49aa5935044c76027b15fd2ce88ea3cc1b69e9f8?/536=352
- **社区托育服务的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/49aa5935044c76027b15fd2ce88ea3cc1b69e9f8?/iev=929
- **科学运动指导的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/dc7af273d5f2e14af6644356cba405d0bcad3067?/792
- **儿童户外活动的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/dc7af273d5f2e14af6644356cba405d0bcad3067?/rem
- **公园亲子设施的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/dc7af273d5f2e14af6644356cba405d0bcad3067?/565/?bfb
- **儿童户外活动的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/dc7af273d5f2e14af6644356cba405d0bcad3067?/113=647
- **便民服务地图的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/dc7af273d5f2e14af6644356cba405d0bcad3067?/wls=625
- **公共空间导览的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0f7f3fa08169d29f60ae5a2f78b8eddf2117c29c?/559
- **城市慢行系统的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/0f7f3fa08169d29f60ae5a2f78b8eddf2117c29c?/ttx
- **公共场馆服务的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0f7f3fa08169d29f60ae5a2f78b8eddf2117c29c?/394/?jef
- **公共设施维护的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/0f7f3fa08169d29f60ae5a2f78b8eddf2117c29c?/483=272
- **基层健康服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/0f7f3fa08169d29f60ae5a2f78b8eddf2117c29c?/nwd=178
- **城市应急广播的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2e32304ed34e54f1053752fdd020749f1e40e379?/752
- **家庭园艺实践的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2e32304ed34e54f1053752fdd020749f1e40e379?/aii
- **青少年科普实践的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2e32304ed34e54f1053752fdd020749f1e40e379?/361/?myy
- **城市游园体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/2e32304ed34e54f1053752fdd020749f1e40e379?/401=705
- **城市噪声观察的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2e32304ed34e54f1053752fdd020749f1e40e379?/wdy=128
- **城市步行友好的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9f636debaf6b9758595f3b545968054859a22607?/972
- **旧物循环利用的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9f636debaf6b9758595f3b545968054859a22607?/ohq
- **青少年编程学习的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9f636debaf6b9758595f3b545968054859a22607?/751/?fiu
- **城市绿色交通的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/9f636debaf6b9758595f3b545968054859a22607?/247=632
- **城市树木认养的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9f636debaf6b9758595f3b545968054859a22607?/rtw=093
- **线上办事服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d73c5f284f409de8458971ad7acc7b7728041121?/722
- **公共服务数字化的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/d73c5f284f409de8458971ad7acc7b7728041121?/scu
- **校园安全教育的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/d73c5f284f409de8458971ad7acc7b7728041121?/979/?sxe
- **乡村文化空间的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/d73c5f284f409de8458971ad7acc7b7728041121?/654=166
- **城市博物馆活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/d73c5f284f409de8458971ad7acc7b7728041121?/wgl=342
- **儿童友好街区的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/e835257d08f1892ee0332d87e1d29c9e0600c0f8?/535
- **城市噪声观察的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/e835257d08f1892ee0332d87e1d29c9e0600c0f8?/pbw
- **居民健康教育的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/e835257d08f1892ee0332d87e1d29c9e0600c0f8?/862/?ner
- **社区宣传栏更新的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/e835257d08f1892ee0332d87e1d29c9e0600c0f8?/168=287
- **数字支付体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/e835257d08f1892ee0332d87e1d29c9e0600c0f8?/ahf=539
- **社区快递服务的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a183004c34d2c90712c9d5b635e04b6333ea332a?/795
- **开放式学习空间的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/a183004c34d2c90712c9d5b635e04b6333ea332a?/ume
- **社区艺术活动的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a183004c34d2c90712c9d5b635e04b6333ea332a?/069/?ylj
- **乡村公共文化的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a183004c34d2c90712c9d5b635e04b6333ea332a?/980=756
- **社区科普课堂有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/a183004c34d2c90712c9d5b635e04b6333ea332a?/oiz=624
- **节假日出行安排的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/3543c9cf1f21cfac41f243ae74279bc88c6bbbe8?/719
- **社会体育指导的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3543c9cf1f21cfac41f243ae74279bc88c6bbbe8?/ybs
- **校园社团活动的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3543c9cf1f21cfac41f243ae74279bc88c6bbbe8?/504/?mtk
- **社区教育资源的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3543c9cf1f21cfac41f243ae74279bc88c6bbbe8?/956=773
- **租房信息服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/3543c9cf1f21cfac41f243ae74279bc88c6bbbe8?/kmp=582
- **基层健康档案的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/cc6493e53bece23a34c18f8ed83a9ee4f0797417?/540
- **本地旅行体验的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/cc6493e53bece23a34c18f8ed83a9ee4f0797417?/pth
- **社区故事采集的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/cc6493e53bece23a34c18f8ed83a9ee4f0797417?/864/?scq
- **儿童安全出行的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/cc6493e53bece23a34c18f8ed83a9ee4f0797417?/002=315
- **基层健康档案的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/cc6493e53bece23a34c18f8ed83a9ee4f0797417?/buj=085
- **社区科普课堂的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5c4ffbcfec42d0079619d82aa1b6dab5bb9ee9?/114
- **科学教育活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5c4ffbcfec42d0079619d82aa1b6dab5bb9ee9?/bkp
- **药品使用科普的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5c4ffbcfec42d0079619d82aa1b6dab5bb9ee9?/438/?kqb
- **城市树木认养的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5c4ffbcfec42d0079619d82aa1b6dab5bb9ee9?/194=572
- **农贸市场环境的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5c4ffbcfec42d0079619d82aa1b6dab5bb9ee9?/ylw=382
- **电动汽车充电的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/fcbdcf14b440e0ffd88260d2fc632148f88ddbf6?/045
- **数字支付体验的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fcbdcf14b440e0ffd88260d2fc632148f88ddbf6?/fal
- **社区停车服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/fcbdcf14b440e0ffd88260d2fc632148f88ddbf6?/803/?kaw
- **城市宠物友好空间的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/fcbdcf14b440e0ffd88260d2fc632148f88ddbf6?/152=814
- **家庭防灾准备的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/fcbdcf14b440e0ffd88260d2fc632148f88ddbf6?/xdy=042
- **家庭饮食安排的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/96496dd8527e6cfcc94456fcfcba11657cbcb9f7?/363
- **信息无障碍体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/96496dd8527e6cfcc94456fcfcba11657cbcb9f7?/xqs
- **食品配送体验的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/96496dd8527e6cfcc94456fcfcba11657cbcb9f7?/161/?qgm
- **农业科普体验的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/96496dd8527e6cfcc94456fcfcba11657cbcb9f7?/811=691
- **公共服务咨询的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/96496dd8527e6cfcc94456fcfcba11657cbcb9f7?/rgp=490
- **城乡交流活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4e65a7f62cbe9259211a8cebd4968245893a5140?/955
- **青年就业服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/4e65a7f62cbe9259211a8cebd4968245893a5140?/oop
- **家庭健康管理的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/4e65a7f62cbe9259211a8cebd4968245893a5140?/133/?xbi
- **社区文化节活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/4e65a7f62cbe9259211a8cebd4968245893a5140?/244=814
- **社区共享书架的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/4e65a7f62cbe9259211a8cebd4968245893a5140?/dec=040
- **青少年职业启蒙的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ffb4606c8bb87dee1786713de1cc1633b7312243?/336
- **居家防滑改造的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ffb4606c8bb87dee1786713de1cc1633b7312243?/qvy
- **校园阅读活动的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/ffb4606c8bb87dee1786713de1cc1633b7312243?/048/?htc
- **老年人日常照护的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ffb4606c8bb87dee1786713de1cc1633b7312243?/580=055
- **家庭节能实践的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/ffb4606c8bb87dee1786713de1cc1633b7312243?/zdc=219
- **社区菜市场服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/7e548f0f270ca49a3e19953dff5d6fc97ca1e269?/873
- **市民热线服务的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/7e548f0f270ca49a3e19953dff5d6fc97ca1e269?/ley
- **城市绿色交通的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7e548f0f270ca49a3e19953dff5d6fc97ca1e269?/499/?yjt
- **地方戏曲体验中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/7e548f0f270ca49a3e19953dff5d6fc97ca1e269?/844=594
- **青少年科技社团的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7e548f0f270ca49a3e19953dff5d6fc97ca1e269?/tah=017
- **社区老年食堂的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/6db271c5d3c98a0e9acb8d411769440f1f017514?/392
- **城市文明出行的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/6db271c5d3c98a0e9acb8d411769440f1f017514?/rtr
- **城市步行环境的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/6db271c5d3c98a0e9acb8d411769440f1f017514?/015/?qaj
- **乡村文化活动的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/6db271c5d3c98a0e9acb8d411769440f1f017514?/773=872
- **乡村生态观察的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/6db271c5d3c98a0e9acb8d411769440f1f017514?/kwn=912
- **城市慢行系统的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/cf022730e430426a7e9e37c1b71b7145d01e4e8f?/843
- **社区便民服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/cf022730e430426a7e9e37c1b71b7145d01e4e8f?/lxf
- **公共交通信息服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/cf022730e430426a7e9e37c1b71b7145d01e4e8f?/756/?bwh
- **数字设备回收的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/cf022730e430426a7e9e37c1b71b7145d01e4e8f?/917=712
- **乡村阅读空间的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/cf022730e430426a7e9e37c1b71b7145d01e4e8f?/auv=078
- **校园社团活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/610db8bc630a64b6fffa9ea663f65880f3b49319?/729
- **儿童友好空间的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/610db8bc630a64b6fffa9ea663f65880f3b49319?/sux
- **城市农夫市集的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/610db8bc630a64b6fffa9ea663f65880f3b49319?/845/?irj
- **城市空气科普的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/610db8bc630a64b6fffa9ea663f65880f3b49319?/410=288
- **读书会组织的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/610db8bc630a64b6fffa9ea663f65880f3b49319?/suw=735
- **便民维修服务的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/14ed1b6e18b1b71797268b190eb9e77dfba9b6d9?/442
- **社区科普课堂的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/14ed1b6e18b1b71797268b190eb9e77dfba9b6d9?/jxj
- **药品使用科普的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/14ed1b6e18b1b71797268b190eb9e77dfba9b6d9?/917/?tgb
- **社区托育服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/14ed1b6e18b1b71797268b190eb9e77dfba9b6d9?/315=378
- **社区设施共享的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/14ed1b6e18b1b71797268b190eb9e77dfba9b6d9?/hnq=265
- **数字便民地图的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/14eb66de8a72c03a3f41e21e400a79a124364732?/349
- **城市水环境观察的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/14eb66de8a72c03a3f41e21e400a79a124364732?/hqs
- **城乡公共服务的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/14eb66de8a72c03a3f41e21e400a79a124364732?/374/?trd
- **数字便民地图的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/14eb66de8a72c03a3f41e21e400a79a124364732?/637=889
- **儿童安全出行的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/14eb66de8a72c03a3f41e21e400a79a124364732?/xpn=772
- **社区文化节活动的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/650114ec66d59e6c19f59b3da114db92d97eff44?/025
- **地方旅游导览的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/650114ec66d59e6c19f59b3da114db92d97eff44?/niu
- **健康饮水科普的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/650114ec66d59e6c19f59b3da114db92d97eff44?/950/?xte
- **家庭科学教育的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/650114ec66d59e6c19f59b3da114db92d97eff44?/216=066
- **机器人科普活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/650114ec66d59e6c19f59b3da114db92d97eff44?/utw=462
- **数字便民地图的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ffd8652b885110b8273d567cf432c2987c77717d?/330
- **城乡交通衔接中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/ffd8652b885110b8273d567cf432c2987c77717d?/mdd
- **社区儿童活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/ffd8652b885110b8273d567cf432c2987c77717d?/300/?eai
- **社区故事采集的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ffd8652b885110b8273d567cf432c2987c77717d?/731=670
- **本地消费场景的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/ffd8652b885110b8273d567cf432c2987c77717d?/typ=585
- **校园社团活动的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/d48a997cd8430842f534c41ef29ed61647e39c28?/665
- **个人信息保护的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/d48a997cd8430842f534c41ef29ed61647e39c28?/cnh
- **社区信息发布的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d48a997cd8430842f534c41ef29ed61647e39c28?/687/?trx
- **城市应急广播中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d48a997cd8430842f534c41ef29ed61647e39c28?/816=492
- **乡村电商实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/d48a997cd8430842f534c41ef29ed61647e39c28?/kwc=978
- **城市树木认养的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8f2ff6f49d5efe4d58d17c6fb2ea89a85a89d304?/884
- **城市适老服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/8f2ff6f49d5efe4d58d17c6fb2ea89a85a89d304?/hod
- **社区修缮行动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/8f2ff6f49d5efe4d58d17c6fb2ea89a85a89d304?/177/?dla
- **城市展览体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8f2ff6f49d5efe4d58d17c6fb2ea89a85a89d304?/804=876
- **街区更新实践的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/8f2ff6f49d5efe4d58d17c6fb2ea89a85a89d304?/lvr=943
- **市民热线服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/3aa97c577d3c31cc1846fc251ecc5b8f4c637fc5?/567
- **城市公共空间的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3aa97c577d3c31cc1846fc251ecc5b8f4c637fc5?/pol
- **志愿服务平台的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3aa97c577d3c31cc1846fc251ecc5b8f4c637fc5?/227/?qdq
- **课后服务体验的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/3aa97c577d3c31cc1846fc251ecc5b8f4c637fc5?/827=365
- **街道综合服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/3aa97c577d3c31cc1846fc251ecc5b8f4c637fc5?/yjl=256
- **家庭教育交流的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/81adfd3d57199c537279c9322e09ebaf8fea90cb?/068
- **光伏知识科普中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/81adfd3d57199c537279c9322e09ebaf8fea90cb?/emb
- **开放数据应用的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/81adfd3d57199c537279c9322e09ebaf8fea90cb?/321/?lgm
- **社区设施共享的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/81adfd3d57199c537279c9322e09ebaf8fea90cb?/022=150
- **社区知识分享的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/81adfd3d57199c537279c9322e09ebaf8fea90cb?/qfs=706
- **家庭照护支持的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/69d20dececee384d22ea5d1eeb70c9764c3db5b5?/709
- **电动汽车充电的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/69d20dececee384d22ea5d1eeb70c9764c3db5b5?/eso
- **健康饮水科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/69d20dececee384d22ea5d1eeb70c9764c3db5b5?/088/?yka
- **公共服务预约的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/69d20dececee384d22ea5d1eeb70c9764c3db5b5?/265=246
- **城市慢行系统的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/69d20dececee384d22ea5d1eeb70c9764c3db5b5?/dar=315
- **社区协商议事的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/78f0f9cb663fa709a00db73596fd34e84b7eebb9?/337
- **社区活动策划的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/78f0f9cb663fa709a00db73596fd34e84b7eebb9?/svy
- **读书会组织的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/78f0f9cb663fa709a00db73596fd34e84b7eebb9?/172/?dwp
- **应急物资管理的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/78f0f9cb663fa709a00db73596fd34e84b7eebb9?/126=020
- **地方戏曲体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/78f0f9cb663fa709a00db73596fd34e84b7eebb9?/gzp=093
- **生成式工具使用的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/088d3649c6fc6cf32edb6803a457d577be5b092e?/381
- **城市住房服务的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/088d3649c6fc6cf32edb6803a457d577be5b092e?/lbp
- **网络安全教育的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/088d3649c6fc6cf32edb6803a457d577be5b092e?/652/?iyl
- **家庭网络使用的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/088d3649c6fc6cf32edb6803a457d577be5b092e?/500=323
- **线上办事服务的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/088d3649c6fc6cf32edb6803a457d577be5b092e?/idr=586
- **生活服务数字化的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8a90825369003e1465040d12a3b530594cb5be23?/841
- **城市生活服务的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a90825369003e1465040d12a3b530594cb5be23?/pre
- **儿童运动体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a90825369003e1465040d12a3b530594cb5be23?/809/?rvh
- **城市绿色交通的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/8a90825369003e1465040d12a3b530594cb5be23?/876=608
- **社区健康讲座的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a90825369003e1465040d12a3b530594cb5be23?/kvz=688
- **创业经验分享的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1d5ea13d6a92b892a3aeee2d434c017b67cd9d71?/396
- **口袋公园建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/1d5ea13d6a92b892a3aeee2d434c017b67cd9d71?/jfj
- **公交站点体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1d5ea13d6a92b892a3aeee2d434c017b67cd9d71?/562/?gck
- **儿童阅读角中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/1d5ea13d6a92b892a3aeee2d434c017b67cd9d71?/983=894
- **社会体育指导的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1d5ea13d6a92b892a3aeee2d434c017b67cd9d71?/lcr=724
- **家庭节能设备的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a40af61ff968169fa6d55c908544d5ffe66e4e?/282
- **地方旅游导览的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a40af61ff968169fa6d55c908544d5ffe66e4e?/rlx
- **公共服务评价的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a40af61ff968169fa6d55c908544d5ffe66e4e?/180/?jmr
- **社区故事采集的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a40af61ff968169fa6d55c908544d5ffe66e4e?/093=070
- **生活垃圾回收的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/d4a40af61ff968169fa6d55c908544d5ffe66e4e?/jri=667
- **社区邻里服务从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/89fba11243c82fed6255a2fae66db838b856df1a?/239
- **青年职业探索的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/89fba11243c82fed6255a2fae66db838b856df1a?/poz
- **社区宣传栏更新的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/89fba11243c82fed6255a2fae66db838b856df1a?/484/?tnh
- **绿色办公实践的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/89fba11243c82fed6255a2fae66db838b856df1a?/994=570
- **生活服务数字化的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/89fba11243c82fed6255a2fae66db838b856df1a?/sio=350
- **绿色建筑理念的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/915b5447ec64e7bdebbcaf0f70a2c9af55f9bcf7?/515
- **数字生活课堂的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/915b5447ec64e7bdebbcaf0f70a2c9af55f9bcf7?/utz
- **家庭饮食安排的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/915b5447ec64e7bdebbcaf0f70a2c9af55f9bcf7?/609/?ycf
- **地方民俗记录的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/915b5447ec64e7bdebbcaf0f70a2c9af55f9bcf7?/458=482
- **地方旅游导览的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/915b5447ec64e7bdebbcaf0f70a2c9af55f9bcf7?/coa=661
- **节能家电使用的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/93c07520d13fafbd64d9a7c3b5d87dee7e98e5ce?/153
- **数字支付体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/93c07520d13fafbd64d9a7c3b5d87dee7e98e5ce?/ngy
- **城市共享单车的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/93c07520d13fafbd64d9a7c3b5d87dee7e98e5ce?/378/?szx
- **城市文化路线的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/93c07520d13fafbd64d9a7c3b5d87dee7e98e5ce?/392=800
- **社区志愿服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/93c07520d13fafbd64d9a7c3b5d87dee7e98e5ce?/txo=034
- **信息无障碍体验的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7b50493462fff8d237b81a5a6c476707fa95b845?/138
- **社区消防演练的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/7b50493462fff8d237b81a5a6c476707fa95b845?/yxp
- **科学观察活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/7b50493462fff8d237b81a5a6c476707fa95b845?/800/?hlh
- **电子商务服务的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7b50493462fff8d237b81a5a6c476707fa95b845?/907=707
- **社区健康讲座的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/7b50493462fff8d237b81a5a6c476707fa95b845?/aow=048
- **社区便民集市的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/391bbeb0376990912015f5111007ce114356d474?/859
- **数字设备回收的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/391bbeb0376990912015f5111007ce114356d474?/yfx
- **城市便民驿站的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/391bbeb0376990912015f5111007ce114356d474?/000/?mpj
- **文化遗产保护科普中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/391bbeb0376990912015f5111007ce114356d474?/208=716
- **生活垃圾回收的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/391bbeb0376990912015f5111007ce114356d474?/slj=272
- **开放数据应用的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ab7ac73c709d5b0d439c2128d9ea4b4e995b2b50?/643
- **公交无障碍服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ab7ac73c709d5b0d439c2128d9ea4b4e995b2b50?/vuu
- **生活服务数字化从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ab7ac73c709d5b0d439c2128d9ea4b4e995b2b50?/699/?xlz
- **地方戏曲体验中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ab7ac73c709d5b0d439c2128d9ea4b4e995b2b50?/084=268
- **社区协商议事的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/ab7ac73c709d5b0d439c2128d9ea4b4e995b2b50?/luu=318
- **科学健身方法的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c0ada3333c40fdca351b24158934ba7c0bbddc46?/681
- **小区停车协商的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/c0ada3333c40fdca351b24158934ba7c0bbddc46?/xkh
- **社区便民集市的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/c0ada3333c40fdca351b24158934ba7c0bbddc46?/447/?tai
- **绿色校园实践的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/c0ada3333c40fdca351b24158934ba7c0bbddc46?/653=135
- **小微企业服务的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/c0ada3333c40fdca351b24158934ba7c0bbddc46?/cij=061
- **社区家校合作的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/9eb8dffc6560c1cf7687640807227a57e6412bcb?/797
- **乡村阅读活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/9eb8dffc6560c1cf7687640807227a57e6412bcb?/sgd
- **科学信息获取的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9eb8dffc6560c1cf7687640807227a57e6412bcb?/247/?huu
- **农贸市场环境的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9eb8dffc6560c1cf7687640807227a57e6412bcb?/286=839
- **公共场馆服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9eb8dffc6560c1cf7687640807227a57e6412bcb?/vhs=289
- **居家防滑改造的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a0317edb2cdf184708f1e26b1cadcfde4236f310?/537
- **绿色消费选择的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a0317edb2cdf184708f1e26b1cadcfde4236f310?/wkv
- **乡村公共阅读的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a0317edb2cdf184708f1e26b1cadcfde4236f310?/604/?woy
- **城市微更新实践的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a0317edb2cdf184708f1e26b1cadcfde4236f310?/244=725
- **科学信息获取的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a0317edb2cdf184708f1e26b1cadcfde4236f310?/nqs=376
- **小区公共照明的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1bc7cce9bb1e8c0fb8a6857d260b60737c8982d6?/631
- **图书馆数字服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1bc7cce9bb1e8c0fb8a6857d260b60737c8982d6?/liw
- **城市基础设施中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1bc7cce9bb1e8c0fb8a6857d260b60737c8982d6?/571/?ymz
- **社区法律科普中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/1bc7cce9bb1e8c0fb8a6857d260b60737c8982d6?/480=614
- **图书馆数字服务的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1bc7cce9bb1e8c0fb8a6857d260b60737c8982d6?/yzr=163
- **家庭节能设备的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/5805f71ef590566685965ae2232db9c587f5ca27?/515
- **城市噪声观察的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/5805f71ef590566685965ae2232db9c587f5ca27?/bxw
- **网络信息辨识的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5805f71ef590566685965ae2232db9c587f5ca27?/037/?dxs
- **数字素养提升的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/5805f71ef590566685965ae2232db9c587f5ca27?/959=129
- **志愿者培训交流的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5805f71ef590566685965ae2232db9c587f5ca27?/ofq=720
- **街区更新实践的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/70cef0d5e1c98c6bf94149ab08bfdd56ac20b2cf?/887
- **乡村生活观察的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/70cef0d5e1c98c6bf94149ab08bfdd56ac20b2cf?/odr
- **乡村生活观察的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/70cef0d5e1c98c6bf94149ab08bfdd56ac20b2cf?/334/?yld
- **城市绿色交通的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/70cef0d5e1c98c6bf94149ab08bfdd56ac20b2cf?/958=232
- **数字政务体验的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/70cef0d5e1c98c6bf94149ab08bfdd56ac20b2cf?/xfy=911
- **环境教育课程从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/3daf381d8536c05e15ede8d69491676afaceaca7?/141
- **便民维修服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3daf381d8536c05e15ede8d69491676afaceaca7?/ohi
- **公共卫生宣传的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/3daf381d8536c05e15ede8d69491676afaceaca7?/889/?djt
- **城市环境志愿行动的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3daf381d8536c05e15ede8d69491676afaceaca7?/811=036
- **跨代沟通活动的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3daf381d8536c05e15ede8d69491676afaceaca7?/nic=910
- **社区便民服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8b6293fb6cf914c6f5e5997e75c9d5589371f1f1?/325
- **消防知识宣传的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8b6293fb6cf914c6f5e5997e75c9d5589371f1f1?/jlu
- **无障碍信息设计的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8b6293fb6cf914c6f5e5997e75c9d5589371f1f1?/394/?ece
- **社区运动空间的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/8b6293fb6cf914c6f5e5997e75c9d5589371f1f1?/430=946
- **公共场馆服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8b6293fb6cf914c6f5e5997e75c9d5589371f1f1?/vgg=316
- **社区宠物管理的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7bd3c1194760bd7359804f23a82a8b48daf8bd89?/656
- **公益活动组织的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7bd3c1194760bd7359804f23a82a8b48daf8bd89?/iqf
- **城市公共座椅的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7bd3c1194760bd7359804f23a82a8b48daf8bd89?/887/?hat
- **社区安全巡查的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/7bd3c1194760bd7359804f23a82a8b48daf8bd89?/813=998
- **城市水环境观察从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/7bd3c1194760bd7359804f23a82a8b48daf8bd89?/vgu=220
- **公共设施使用的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/5393dfaa60bced3fbaa0616a03cbdcef55929dfe?/034
- **青少年职业启蒙的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/5393dfaa60bced3fbaa0616a03cbdcef55929dfe?/rvr
- **城市建设科普的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/5393dfaa60bced3fbaa0616a03cbdcef55929dfe?/598/?veu
- **科学信息获取的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5393dfaa60bced3fbaa0616a03cbdcef55929dfe?/182=757
- **家庭运动计划的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5393dfaa60bced3fbaa0616a03cbdcef55929dfe?/xub=461
- **社区活动策划的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2dc4ba0b5a76a7f6526209a37768caa6d7d6f5e5?/741
- **社区活动策划的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/2dc4ba0b5a76a7f6526209a37768caa6d7d6f5e5?/bgq
- **乡村文化活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/2dc4ba0b5a76a7f6526209a37768caa6d7d6f5e5?/366/?kfz
- **城市微更新实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/2dc4ba0b5a76a7f6526209a37768caa6d7d6f5e5?/658=505
- **学校体育活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/2dc4ba0b5a76a7f6526209a37768caa6d7d6f5e5?/yix=444
- **城市绿色交通有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/4b351ed593c2aa5cefa508fb81dff70c59d53e80?/570
- **小微企业服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/4b351ed593c2aa5cefa508fb81dff70c59d53e80?/kus
- **科学健身方法的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/4b351ed593c2aa5cefa508fb81dff70c59d53e80?/912/?nbp
- **公共设施使用的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/4b351ed593c2aa5cefa508fb81dff70c59d53e80?/095=675
- **青少年科普实践的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/4b351ed593c2aa5cefa508fb81dff70c59d53e80?/smi=782
- **公共空间安全的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/7814b43a2ea41c326d1fa82f1e340cf167f3500b?/059
- **健康信息获取的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/7814b43a2ea41c326d1fa82f1e340cf167f3500b?/sqt
- **城市文化路线的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/7814b43a2ea41c326d1fa82f1e340cf167f3500b?/676/?bcr
- **家庭食品保存中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7814b43a2ea41c326d1fa82f1e340cf167f3500b?/754=675
- **家庭急救准备的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/7814b43a2ea41c326d1fa82f1e340cf167f3500b?/jtt=877
- **数字资源检索的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/852ae3da41a9f302eaa6da08bc22842133f411bd?/186
- **数字艺术创作从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/852ae3da41a9f302eaa6da08bc22842133f411bd?/bis
- **公园休闲体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/852ae3da41a9f302eaa6da08bc22842133f411bd?/191/?bog
- **校园社团活动的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/852ae3da41a9f302eaa6da08bc22842133f411bd?/747=784
- **数字档案服务的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/852ae3da41a9f302eaa6da08bc22842133f411bd?/ydw=485
- **城市空气科普的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5a564da850e8388ef03295f389387063953284dc?/744
- **城市应急广播的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/5a564da850e8388ef03295f389387063953284dc?/ouf
- **网络信息辨识的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/5a564da850e8388ef03295f389387063953284dc?/784/?gpy
- **传统节日科普的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/5a564da850e8388ef03295f389387063953284dc?/589=255
- **城市人文观察的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/5a564da850e8388ef03295f389387063953284dc?/dvf=618
- **绿色消费选择的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b78d3b4e6b1c8887310a10fc9e85a9140b64b496?/311
- **社区消防演练的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b78d3b4e6b1c8887310a10fc9e85a9140b64b496?/ecw
- **本地消费场景的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/b78d3b4e6b1c8887310a10fc9e85a9140b64b496?/285/?urp
- **便民服务窗口的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/b78d3b4e6b1c8887310a10fc9e85a9140b64b496?/367=168
- **社区庭院绿化的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/b78d3b4e6b1c8887310a10fc9e85a9140b64b496?/krm=294
- **科学睡眠习惯的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/db279a1b6c079a447a85907b33cdfe06240ca549?/763
- **社区防暑服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/db279a1b6c079a447a85907b33cdfe06240ca549?/neu
- **食品安全科普的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/db279a1b6c079a447a85907b33cdfe06240ca549?/096/?bpp
- **家庭园艺实践的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/db279a1b6c079a447a85907b33cdfe06240ca549?/194=107
- **城市文化路线的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/db279a1b6c079a447a85907b33cdfe06240ca549?/bhs=258
- **青年志愿活动的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/d1e6d396b8edf3040c5a8ea1460b642f80592751?/240
- **数字资源检索的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d1e6d396b8edf3040c5a8ea1460b642f80592751?/zkl
- **公园亲子设施的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/d1e6d396b8edf3040c5a8ea1460b642f80592751?/364/?vgu
- **社区互助网络的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/d1e6d396b8edf3040c5a8ea1460b642f80592751?/793=384
- **公共服务沟通的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/d1e6d396b8edf3040c5a8ea1460b642f80592751?/xrz=631
- **公共卫生设施的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/cc174bdd16c7b157e8e3dfcfe18bcf465d9568d9?/597
- **读书会组织的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/cc174bdd16c7b157e8e3dfcfe18bcf465d9568d9?/lhi
- **社区故事采集有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/cc174bdd16c7b157e8e3dfcfe18bcf465d9568d9?/473/?kci
- **家庭教育交流的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/cc174bdd16c7b157e8e3dfcfe18bcf465d9568d9?/461=514
- **家庭环保行动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/cc174bdd16c7b157e8e3dfcfe18bcf465d9568d9?/knz=894
- **城市噪声观察的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/49fde0cbd8e21ec1465fa2036b5b178ef36c68f4?/959
- **节能家电使用的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/49fde0cbd8e21ec1465fa2036b5b178ef36c68f4?/cxu
- **数字设备回收的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/49fde0cbd8e21ec1465fa2036b5b178ef36c68f4?/241/?vae
- **电动汽车充电的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/49fde0cbd8e21ec1465fa2036b5b178ef36c68f4?/842=912
- **社区庭院绿化的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/49fde0cbd8e21ec1465fa2036b5b178ef36c68f4?/gso=398
- **城乡交流活动的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/06179205b0b27e75e31ae30ba8e1dd1348d1cd4d?/378
- **全民阅读推广有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/06179205b0b27e75e31ae30ba8e1dd1348d1cd4d?/ser
- **社区手工活动的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/06179205b0b27e75e31ae30ba8e1dd1348d1cd4d?/472/?hex
- **城市公共艺术的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/06179205b0b27e75e31ae30ba8e1dd1348d1cd4d?/264=229
- **城市人文观察的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/06179205b0b27e75e31ae30ba8e1dd1348d1cd4d?/rqk=296
- **物业服务沟通的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/9cbe4470789c431564c3d8e9e7f33f57098a24c5?/462
- **公共设施维护的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/9cbe4470789c431564c3d8e9e7f33f57098a24c5?/ohp
- **社区安全巡查的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/9cbe4470789c431564c3d8e9e7f33f57098a24c5?/602/?tgn
- **街区道路维护的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/9cbe4470789c431564c3d8e9e7f33f57098a24c5?/420=947
- **数字生活课堂的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/9cbe4470789c431564c3d8e9e7f33f57098a24c5?/tli=834
- **城市水环境观察的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/689c3ae709a5420e2aec77a01a3e298358768e44?/199
- **城市运动公园的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/689c3ae709a5420e2aec77a01a3e298358768e44?/iwj
- **公共健身器材的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/689c3ae709a5420e2aec77a01a3e298358768e44?/881/?sqn
- **全民健身活动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/689c3ae709a5420e2aec77a01a3e298358768e44?/186=895
- **音乐欣赏活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/689c3ae709a5420e2aec77a01a3e298358768e44?/waa=416
- **社区家校合作的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/59516c1f9f4048615db386bf7909a773b4f49dc9?/319
- **日常摄影记录的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/59516c1f9f4048615db386bf7909a773b4f49dc9?/rlm
- **科普展览体验的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/59516c1f9f4048615db386bf7909a773b4f49dc9?/871/?dfs
- **气象科普传播的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/59516c1f9f4048615db386bf7909a773b4f49dc9?/619=637
- **城市公共艺术中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/59516c1f9f4048615db386bf7909a773b4f49dc9?/dup=271
- **街区道路维护的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/ce959874639986909929f6d1cdc18a8d477faa90?/617
- **城市社区治理的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/ce959874639986909929f6d1cdc18a8d477faa90?/brn
- **市民热线服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ce959874639986909929f6d1cdc18a8d477faa90?/296/?pwe
- **社区学习活动的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ce959874639986909929f6d1cdc18a8d477faa90?/351=901
- **城市应急广播的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/ce959874639986909929f6d1cdc18a8d477faa90?/nvp=155
- **数字生活课堂的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f0553d0df2e1939176de8e0676ac3b5d12d8fd5c?/854
- **环境监测科普的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/f0553d0df2e1939176de8e0676ac3b5d12d8fd5c?/orc
- **城市公共厕所的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/f0553d0df2e1939176de8e0676ac3b5d12d8fd5c?/058/?eze
- **青年就业服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f0553d0df2e1939176de8e0676ac3b5d12d8fd5c?/598=814
- **地方文化传播的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f0553d0df2e1939176de8e0676ac3b5d12d8fd5c?/fil=353
- **学校食育活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/41c6553597bcfb6fa9af2eab9947dd922011bf0a?/898
- **健康步道使用的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/41c6553597bcfb6fa9af2eab9947dd922011bf0a?/jys
- **家庭节能实践的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/41c6553597bcfb6fa9af2eab9947dd922011bf0a?/324/?fga
- **城市步行环境的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/41c6553597bcfb6fa9af2eab9947dd922011bf0a?/168=682
- **基层健康服务的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/41c6553597bcfb6fa9af2eab9947dd922011bf0a?/prv=554
- **便民服务窗口的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a3b6a607e028f9c7145f930bb371d99b8472f989?/952
- **数字档案服务的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a3b6a607e028f9c7145f930bb371d99b8472f989?/fpp
- **创业经验分享的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/a3b6a607e028f9c7145f930bb371d99b8472f989?/574/?lin
- **公园无障碍服务的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/a3b6a607e028f9c7145f930bb371d99b8472f989?/529=737
- **数字素养提升的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a3b6a607e028f9c7145f930bb371d99b8472f989?/iqf=347
- **老年人日常照护的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2a7cb721e65524ea070d19a2174e29ccbde11d61?/118
- **社区体育组织的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2a7cb721e65524ea070d19a2174e29ccbde11d61?/qna
- **便民信息查询的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2a7cb721e65524ea070d19a2174e29ccbde11d61?/960/?gsf
- **社区艺术活动有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/2a7cb721e65524ea070d19a2174e29ccbde11d61?/281=175
- **老旧小区改造的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2a7cb721e65524ea070d19a2174e29ccbde11d61?/kmk=552
- **街道综合服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/0f8034894ef3fb6f52784c9fd0ebc6920199e861?/804
- **城市空气科普的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0f8034894ef3fb6f52784c9fd0ebc6920199e861?/xpv
- **公共服务指南的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/0f8034894ef3fb6f52784c9fd0ebc6920199e861?/341/?prt
- **城乡公共服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0f8034894ef3fb6f52784c9fd0ebc6920199e861?/421=129
- **社区活动空间的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/0f8034894ef3fb6f52784c9fd0ebc6920199e861?/jhu=709
- **网络信息辨识的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a16c981461cb14d797d5a3a3abd3a5a4808e4cfc?/827
- **社区宣传栏更新的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a16c981461cb14d797d5a3a3abd3a5a4808e4cfc?/vnx
- **小区停车协商的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a16c981461cb14d797d5a3a3abd3a5a4808e4cfc?/360/?dcd
- **绿色办公实践的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/a16c981461cb14d797d5a3a3abd3a5a4808e4cfc?/657=276
- **节气饮食文化的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a16c981461cb14d797d5a3a3abd3a5a4808e4cfc?/mgw=900
- **城市宠物友好空间的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/70bd791cc72e8737554fcf94640d37b06cb7fde2?/536
- **老旧小区改造的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/70bd791cc72e8737554fcf94640d37b06cb7fde2?/vqy
- **城市建设科普的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/70bd791cc72e8737554fcf94640d37b06cb7fde2?/215/?kmf
- **节气饮食文化的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/70bd791cc72e8737554fcf94640d37b06cb7fde2?/789=749
- **学校体育活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/70bd791cc72e8737554fcf94640d37b06cb7fde2?/hoz=721
- **职业技能学习的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/9596bde8a6eb4ad0daba6a2eef3b7e40e03e3274?/153
- **城市宠物友好空间的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/9596bde8a6eb4ad0daba6a2eef3b7e40e03e3274?/rbk
- **光伏知识科普的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/9596bde8a6eb4ad0daba6a2eef3b7e40e03e3274?/337/?klp
- **信息无障碍体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9596bde8a6eb4ad0daba6a2eef3b7e40e03e3274?/335=061
- **骑行路线规划的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/9596bde8a6eb4ad0daba6a2eef3b7e40e03e3274?/bno=349
- **城市适老服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a69861efe0466fd0d5395dc1451db49fa9fe826e?/604
- **社区庭院绿化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a69861efe0466fd0d5395dc1451db49fa9fe826e?/hdj
- **基层健康服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/a69861efe0466fd0d5395dc1451db49fa9fe826e?/251/?wmn
- **居家适老化改造的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a69861efe0466fd0d5395dc1451db49fa9fe826e?/252=269
- **线上阅读资源的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a69861efe0466fd0d5395dc1451db49fa9fe826e?/qku=431
- **本地消费场景的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/044ed36e1eba00c93bb99aec8dc80861d5b2ec5b?/685
- **城市文明出行的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/044ed36e1eba00c93bb99aec8dc80861d5b2ec5b?/may
- **灵活就业交流的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/044ed36e1eba00c93bb99aec8dc80861d5b2ec5b?/382/?smr
- **城市社区治理的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/044ed36e1eba00c93bb99aec8dc80861d5b2ec5b?/114=835
- **地方戏曲体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/044ed36e1eba00c93bb99aec8dc80861d5b2ec5b?/zwi=193
- **小区停车协商的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/8e99272b9945a5fe9af7bbd312b2b81c1264e7ab?/057
- **社区志愿服务的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8e99272b9945a5fe9af7bbd312b2b81c1264e7ab?/ogg
- **城市树木认养的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/8e99272b9945a5fe9af7bbd312b2b81c1264e7ab?/091/?qzy
- **社区花园共建的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/8e99272b9945a5fe9af7bbd312b2b81c1264e7ab?/354=741
- **家庭陪伴活动的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/8e99272b9945a5fe9af7bbd312b2b81c1264e7ab?/mfx=782
- **街道综合服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a2d52772b7b0e158c6b800aac8f5560a6942a93?/765
- **城市基础设施的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/8a2d52772b7b0e158c6b800aac8f5560a6942a93?/mkg
- **街区道路维护的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/8a2d52772b7b0e158c6b800aac8f5560a6942a93?/429/?xzr
- **社区故事采集的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/8a2d52772b7b0e158c6b800aac8f5560a6942a93?/570=684
- **城市建设科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/8a2d52772b7b0e158c6b800aac8f5560a6942a93?/ksn=917
- **乡村电商实践的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3e9943ffc5a2c16908ac44698cddacb0e7ac863d?/475
- **老年学习活动的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3e9943ffc5a2c16908ac44698cddacb0e7ac863d?/mne
- **街区更新实践的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3e9943ffc5a2c16908ac44698cddacb0e7ac863d?/566/?njs
- **城市雨天出行的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/3e9943ffc5a2c16908ac44698cddacb0e7ac863d?/436=349
- **城市树木认养从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/3e9943ffc5a2c16908ac44698cddacb0e7ac863d?/oxu=025
- **基层服务创新的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6674ead75c7ce909931fc4d22db4e13d16ef5f08?/241
- **城市公共自行车的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6674ead75c7ce909931fc4d22db4e13d16ef5f08?/cus
- **小区公共照明的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6674ead75c7ce909931fc4d22db4e13d16ef5f08?/304/?chf
- **人工智能科普的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/6674ead75c7ce909931fc4d22db4e13d16ef5f08?/642=393
- **社区快递服务的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6674ead75c7ce909931fc4d22db4e13d16ef5f08?/irk=666
- **地方民俗记录的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/901e15fe959e83841838702e543ed17fbb4ae932?/286
- **城市骑行环境的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/901e15fe959e83841838702e543ed17fbb4ae932?/rnp
- **传统手工艺体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/901e15fe959e83841838702e543ed17fbb4ae932?/321/?aef
- **城市博物馆服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/901e15fe959e83841838702e543ed17fbb4ae932?/279=612
- **社区设施共享的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/901e15fe959e83841838702e543ed17fbb4ae932?/zpw=836
- **家庭节能实践的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/836328931a3ad9864d6de37ddac42c470eefd609?/524
- **社区家校合作的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/836328931a3ad9864d6de37ddac42c470eefd609?/txg
- **生活垃圾回收的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/836328931a3ad9864d6de37ddac42c470eefd609?/400/?sjw
- **智能手机助老的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/836328931a3ad9864d6de37ddac42c470eefd609?/102=228
- **城市步行友好中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/836328931a3ad9864d6de37ddac42c470eefd609?/tcw=900
- **青少年户外教育的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/86542441a7fd52765692bdd940a69b154ff2841c?/830
- **通勤路线规划的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/86542441a7fd52765692bdd940a69b154ff2841c?/bcv
- **城市共享单车的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/86542441a7fd52765692bdd940a69b154ff2841c?/769/?esd
- **公共服务预约的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/86542441a7fd52765692bdd940a69b154ff2841c?/131=114
- **公共健身器材的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/86542441a7fd52765692bdd940a69b154ff2841c?/qnu=083
- **数字素养提升的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/386362583a5c248c1268c95b74e80968d48ab83a?/603
- **校园社团活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/386362583a5c248c1268c95b74e80968d48ab83a?/ban
- **基层健康服务的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/386362583a5c248c1268c95b74e80968d48ab83a?/554/?vjy
- **街区更新实践的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/386362583a5c248c1268c95b74e80968d48ab83a?/698=843
- **乡村教育资源有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/386362583a5c248c1268c95b74e80968d48ab83a?/dvj=644

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  大发最高代理等*  
*仅供参考，不构成投资建议*
