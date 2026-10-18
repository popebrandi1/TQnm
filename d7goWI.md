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

- **居民健康教育的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a025cf86f647714899de0eb3fab585e8cdeade70?/899
- **地方民俗记录的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a025cf86f647714899de0eb3fab585e8cdeade70?/mbx
- **跨代沟通活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a025cf86f647714899de0eb3fab585e8cdeade70?/853/?eli
- **公共场所导视的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a025cf86f647714899de0eb3fab585e8cdeade70?/761=223
- **社区设施共享的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a025cf86f647714899de0eb3fab585e8cdeade70?/inr=087
- **乡村文化空间的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d13fe9ebbd63d4fd8cf2c16b08a27e5de35b76dd?/518
- **社区读书角建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d13fe9ebbd63d4fd8cf2c16b08a27e5de35b76dd?/dnr
- **城市社区治理的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d13fe9ebbd63d4fd8cf2c16b08a27e5de35b76dd?/589/?lez
- **旧物循环利用的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d13fe9ebbd63d4fd8cf2c16b08a27e5de35b76dd?/222=074
- **家庭园艺实践的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d13fe9ebbd63d4fd8cf2c16b08a27e5de35b76dd?/qxj=785
- **城市绿色交通的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/ca3adb25756c4dcd417fe35efa5e168675a6a997?/159
- **城市雨天出行的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/ca3adb25756c4dcd417fe35efa5e168675a6a997?/dsy
- **社区文化传播的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ca3adb25756c4dcd417fe35efa5e168675a6a997?/090/?lqy
- **图书借阅体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/ca3adb25756c4dcd417fe35efa5e168675a6a997?/101=623
- **社区公共议事的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ca3adb25756c4dcd417fe35efa5e168675a6a997?/uel=929
- **生成式工具使用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fc46fea6560a7cf0b875fe0126b8b5b2c16565d3?/054
- **线上阅读资源的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/fc46fea6560a7cf0b875fe0126b8b5b2c16565d3?/dtb
- **老年学习活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/fc46fea6560a7cf0b875fe0126b8b5b2c16565d3?/639/?los
- **公共服务数字化的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/fc46fea6560a7cf0b875fe0126b8b5b2c16565d3?/623=254
- **电动汽车充电的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/fc46fea6560a7cf0b875fe0126b8b5b2c16565d3?/tog=386
- **本地历史资料的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/86c90573fe0e721825b358c8f9968ecbb4836821?/691
- **邻里共享空间的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/86c90573fe0e721825b358c8f9968ecbb4836821?/xdu
- **老年智能设备的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/86c90573fe0e721825b358c8f9968ecbb4836821?/167/?fjw
- **机器人科普活动的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/86c90573fe0e721825b358c8f9968ecbb4836821?/817=404
- **科普展览体验的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/86c90573fe0e721825b358c8f9968ecbb4836821?/rnb=017
- **基层医疗预约的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/2de95d461a168dbef0f29f28b4acd1d183da37ef?/260
- **城市运动公园的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2de95d461a168dbef0f29f28b4acd1d183da37ef?/ltm
- **家庭急救准备的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2de95d461a168dbef0f29f28b4acd1d183da37ef?/828/?yit
- **家庭食品保存的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/2de95d461a168dbef0f29f28b4acd1d183da37ef?/616=132
- **儿童户外活动的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2de95d461a168dbef0f29f28b4acd1d183da37ef?/szn=423
- **市民意见收集的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/d0786b3ad1a72540f90ab27092981f774a4cac72?/787
- **城市人文观察从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/d0786b3ad1a72540f90ab27092981f774a4cac72?/piw
- **数字政务体验的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/d0786b3ad1a72540f90ab27092981f774a4cac72?/305/?ilg
- **社区法律科普的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/d0786b3ad1a72540f90ab27092981f774a4cac72?/977=990
- **安全出行教育的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/d0786b3ad1a72540f90ab27092981f774a4cac72?/tuo=831
- **公益活动组织的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/464f69de9784aad4b103fe6846ef8ae99fd576a5?/990
- **儿童运动体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/464f69de9784aad4b103fe6846ef8ae99fd576a5?/wcl
- **社区便民集市的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/464f69de9784aad4b103fe6846ef8ae99fd576a5?/463/?nrs
- **农村环境治理的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/464f69de9784aad4b103fe6846ef8ae99fd576a5?/782=137
- **机器学习入门的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/464f69de9784aad4b103fe6846ef8ae99fd576a5?/zko=734
- **音乐欣赏活动的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/a945b31c9ad53e8f7b54d83fb6620cf8b93035ea?/868
- **气象科普传播的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a945b31c9ad53e8f7b54d83fb6620cf8b93035ea?/iwo
- **社区故事采集的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/a945b31c9ad53e8f7b54d83fb6620cf8b93035ea?/177/?ojm
- **社区环保活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a945b31c9ad53e8f7b54d83fb6620cf8b93035ea?/788=776
- **科普展览体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/a945b31c9ad53e8f7b54d83fb6620cf8b93035ea?/gbf=800
- **家庭运动计划的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/32a488020fd6dc63d7121134e119dcac5793524d?/458
- **家庭消费规划的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/32a488020fd6dc63d7121134e119dcac5793524d?/jnd
- **城市体育设施的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/32a488020fd6dc63d7121134e119dcac5793524d?/411/?ply
- **家庭急救准备从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/32a488020fd6dc63d7121134e119dcac5793524d?/384=181
- **城市文明实践的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/32a488020fd6dc63d7121134e119dcac5793524d?/sst=184
- **骑行路线规划的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/828e10a00b824770087290e3563a7939362a14b9?/737
- **数字艺术创作的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/828e10a00b824770087290e3563a7939362a14b9?/uuf
- **图书馆亲子空间的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/828e10a00b824770087290e3563a7939362a14b9?/295/?kpc
- **生成式工具使用的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/828e10a00b824770087290e3563a7939362a14b9?/334=713
- **乡村文化活动的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/828e10a00b824770087290e3563a7939362a14b9?/imv=189
- **小区公共照明的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/5d7c84cc5a9d27a2da6ef4a5758a39b6db7f612d?/889
- **校园安全教育的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5d7c84cc5a9d27a2da6ef4a5758a39b6db7f612d?/opi
- **社区学习活动的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/5d7c84cc5a9d27a2da6ef4a5758a39b6db7f612d?/079/?jbi
- **课后服务体验的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/5d7c84cc5a9d27a2da6ef4a5758a39b6db7f612d?/042=718
- **家庭收纳实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/5d7c84cc5a9d27a2da6ef4a5758a39b6db7f612d?/eko=439
- **居家防滑改造的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/293b2d03fa1eb728c306c5961a47d564a3a33f94?/522
- **社区家政服务的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/293b2d03fa1eb728c306c5961a47d564a3a33f94?/lko
- **公益活动组织的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/293b2d03fa1eb728c306c5961a47d564a3a33f94?/230/?hwi
- **公共交通信息服务的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/293b2d03fa1eb728c306c5961a47d564a3a33f94?/306=201
- **节能家电使用的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/293b2d03fa1eb728c306c5961a47d564a3a33f94?/cxb=509
- **灵活就业交流的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/202af490b850fe3b3900a526b3f2bc6412c6b2ac?/324
- **居家适老化改造的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/202af490b850fe3b3900a526b3f2bc6412c6b2ac?/ymo
- **家庭消费规划的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/202af490b850fe3b3900a526b3f2bc6412c6b2ac?/135/?xdk
- **社区公共议事的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/202af490b850fe3b3900a526b3f2bc6412c6b2ac?/326=464
- **智能家居应用的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/202af490b850fe3b3900a526b3f2bc6412c6b2ac?/cls=585
- **社区快递服务的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/31e2ef77256eb842b16790c1b639e76a5e1460d8?/022
- **乡村阅读空间的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/31e2ef77256eb842b16790c1b639e76a5e1460d8?/mbe
- **城市应急广播的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/31e2ef77256eb842b16790c1b639e76a5e1460d8?/931/?bqt
- **城市夜间照明中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/31e2ef77256eb842b16790c1b639e76a5e1460d8?/887=895
- **城市适老服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/31e2ef77256eb842b16790c1b639e76a5e1460d8?/avu=493
- **城乡交通衔接的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/99632923429aef0b28ab7be8aff2e8e9985c19ab?/925
- **街区道路维护的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/99632923429aef0b28ab7be8aff2e8e9985c19ab?/vai
- **生活垃圾回收的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/99632923429aef0b28ab7be8aff2e8e9985c19ab?/278/?gfy
- **邻里互助活动的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/99632923429aef0b28ab7be8aff2e8e9985c19ab?/442=155
- **科学运动指导的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/99632923429aef0b28ab7be8aff2e8e9985c19ab?/vsq=546
- **节能生活方式的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/6c7226e558ffae75f6cd22b62fb8dd314fdfd039?/307
- **非遗课堂体验的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/6c7226e558ffae75f6cd22b62fb8dd314fdfd039?/ycm
- **城乡公共服务的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/6c7226e558ffae75f6cd22b62fb8dd314fdfd039?/984/?wjq
- **社区艺术活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/6c7226e558ffae75f6cd22b62fb8dd314fdfd039?/482=698
- **城市文明实践的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/6c7226e558ffae75f6cd22b62fb8dd314fdfd039?/axq=733
- **生活垃圾减量的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/034933d2e6ec748d6c080c1e5ac26bd26eed536b?/948
- **城市游园体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/034933d2e6ec748d6c080c1e5ac26bd26eed536b?/evh
- **文化遗产保护科普的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/034933d2e6ec748d6c080c1e5ac26bd26eed536b?/972/?jqu
- **社区活动空间的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/034933d2e6ec748d6c080c1e5ac26bd26eed536b?/736=273
- **城市人文观察有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/034933d2e6ec748d6c080c1e5ac26bd26eed536b?/qwn=911
- **城市宠物友好空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/330e3d219031e3f7345aa4cf65b4c1a7dfcf992b?/371
- **生活垃圾回收的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/330e3d219031e3f7345aa4cf65b4c1a7dfcf992b?/hsz
- **儿童运动体验的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/330e3d219031e3f7345aa4cf65b4c1a7dfcf992b?/708/?ybr
- **青少年心理健康的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/330e3d219031e3f7345aa4cf65b4c1a7dfcf992b?/746=905
- **青年就业服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/330e3d219031e3f7345aa4cf65b4c1a7dfcf992b?/jqi=380
- **数字创作工具的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/0e3f3af39844d05cd3e3867dff21e5b290df01d3?/792
- **城市噪声观察的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/0e3f3af39844d05cd3e3867dff21e5b290df01d3?/qle
- **家庭健康管理的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/0e3f3af39844d05cd3e3867dff21e5b290df01d3?/084/?txd
- **电子商务服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/0e3f3af39844d05cd3e3867dff21e5b290df01d3?/048=739
- **骑行路线规划的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/0e3f3af39844d05cd3e3867dff21e5b290df01d3?/zri=278
- **公共服务沟通的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/3a22d536e59cf301c923080c665cae1890b72faf?/720
- **青年志愿活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/3a22d536e59cf301c923080c665cae1890b72faf?/srk
- **公共空间休憩的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3a22d536e59cf301c923080c665cae1890b72faf?/582/?enh
- **文化讲座服务的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/3a22d536e59cf301c923080c665cae1890b72faf?/304=443
- **家庭陪伴活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/3a22d536e59cf301c923080c665cae1890b72faf?/edi=546
- **便民服务地图的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/827702e60c8e2d7cada57fb84b6ee88196b3ed31?/197
- **社区法律科普的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/827702e60c8e2d7cada57fb84b6ee88196b3ed31?/evd
- **小微企业服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/827702e60c8e2d7cada57fb84b6ee88196b3ed31?/153/?ngr
- **居家适老化改造的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/827702e60c8e2d7cada57fb84b6ee88196b3ed31?/854=338
- **户外活动组织的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/827702e60c8e2d7cada57fb84b6ee88196b3ed31?/owt=419
- **户外活动组织的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/1f1abe617b9e20bd0ad0b09364264741ce5597b3?/597
- **街道综合服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/1f1abe617b9e20bd0ad0b09364264741ce5597b3?/dvn
- **图书馆活动策划的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1f1abe617b9e20bd0ad0b09364264741ce5597b3?/301/?thd
- **公园休闲体验的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1f1abe617b9e20bd0ad0b09364264741ce5597b3?/834=370
- **社区商业活力的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1f1abe617b9e20bd0ad0b09364264741ce5597b3?/oib=575
- **社区商业活力的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/3eb21abd435dd64305c78ec7c6a523837bad5111?/906
- **基层健康档案的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3eb21abd435dd64305c78ec7c6a523837bad5111?/csd
- **非遗课堂体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/3eb21abd435dd64305c78ec7c6a523837bad5111?/581/?vph
- **环境教育课程的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/3eb21abd435dd64305c78ec7c6a523837bad5111?/482=013
- **家庭网络使用的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/3eb21abd435dd64305c78ec7c6a523837bad5111?/yrp=296
- **社区公共餐饮的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/9b3f4a83bd30c61bf6c05c5a4a1441bbc56995cb?/699
- **社区快递服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/9b3f4a83bd30c61bf6c05c5a4a1441bbc56995cb?/mny
- **社区儿童活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/9b3f4a83bd30c61bf6c05c5a4a1441bbc56995cb?/678/?mxs
- **图书借阅体验的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/9b3f4a83bd30c61bf6c05c5a4a1441bbc56995cb?/561=052
- **数字设备回收的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/9b3f4a83bd30c61bf6c05c5a4a1441bbc56995cb?/qax=155
- **城市公共空间的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/26a913b263f976e0fc0d12f239b6bb24a5c10dd9?/689
- **城市公共标识的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/26a913b263f976e0fc0d12f239b6bb24a5c10dd9?/lhq
- **小区电梯维护的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/26a913b263f976e0fc0d12f239b6bb24a5c10dd9?/727/?kyh
- **城市体育设施的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/26a913b263f976e0fc0d12f239b6bb24a5c10dd9?/321=974
- **信息无障碍体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/26a913b263f976e0fc0d12f239b6bb24a5c10dd9?/fyl=409
- **社区体育组织的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/1a156cdc023279e29aeae9f8a9db445af8e6c2a6?/110
- **家庭理财科普的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1a156cdc023279e29aeae9f8a9db445af8e6c2a6?/pju
- **青少年科普实践的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/1a156cdc023279e29aeae9f8a9db445af8e6c2a6?/468/?gvs
- **邻里互助活动的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1a156cdc023279e29aeae9f8a9db445af8e6c2a6?/446=372
- **绿色消费选择的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/1a156cdc023279e29aeae9f8a9db445af8e6c2a6?/ipg=675
- **老年人文化生活从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/5a68d090e05b9346aef43c82028e43572f1564d1?/899
- **公共服务评价的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/5a68d090e05b9346aef43c82028e43572f1564d1?/hch
- **乡村生态旅游的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/5a68d090e05b9346aef43c82028e43572f1564d1?/009/?ndz
- **公共服务沟通的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/5a68d090e05b9346aef43c82028e43572f1564d1?/571=250
- **城市应急科普的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/5a68d090e05b9346aef43c82028e43572f1564d1?/rae=847
- **数字设备回收的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/99309476dfe7e5ea1d2639ca2bb506c8c0eea044?/449
- **公园无障碍服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/99309476dfe7e5ea1d2639ca2bb506c8c0eea044?/zyu
- **绿色消费选择的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/99309476dfe7e5ea1d2639ca2bb506c8c0eea044?/503/?ajl
- **地方戏曲体验的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/99309476dfe7e5ea1d2639ca2bb506c8c0eea044?/862=520
- **信息无障碍体验的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/99309476dfe7e5ea1d2639ca2bb506c8c0eea044?/tgb=202
- **社区活动空间的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/ae85a01221d85db58e5c2e8d5892f19dc0ece77f?/971
- **社区应急准备的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/ae85a01221d85db58e5c2e8d5892f19dc0ece77f?/iky
- **城市环境志愿行动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ae85a01221d85db58e5c2e8d5892f19dc0ece77f?/925/?gkr
- **城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ae85a01221d85db58e5c2e8d5892f19dc0ece77f?/070=084
- **家庭消费规划的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ae85a01221d85db58e5c2e8d5892f19dc0ece77f?/qlk=501
- **节约用水实践的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb9c4ca30a629bad4d5438a64da6d49dc8880df?/598
- **城市公共座椅的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb9c4ca30a629bad4d5438a64da6d49dc8880df?/afp
- **文化遗产保护科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb9c4ca30a629bad4d5438a64da6d49dc8880df?/965/?sbt
- **城市公共自行车的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb9c4ca30a629bad4d5438a64da6d49dc8880df?/215=723
- **家庭健康科普的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/bfb9c4ca30a629bad4d5438a64da6d49dc8880df?/xsm=828
- **社区公共议事的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/f620260fea9b775eeb5be1f291ef6210e6665a3a?/800
- **公共交通信息服务的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/f620260fea9b775eeb5be1f291ef6210e6665a3a?/ldg
- **城市慢行系统的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/f620260fea9b775eeb5be1f291ef6210e6665a3a?/524/?czx
- **全民阅读推广的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/f620260fea9b775eeb5be1f291ef6210e6665a3a?/509=221
- **数字艺术创作的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/f620260fea9b775eeb5be1f291ef6210e6665a3a?/iey=712
- **公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/58e9cd395dcd48cb9078a75a98b4cdf66039e7a7?/743
- **城市宠物友好空间的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/58e9cd395dcd48cb9078a75a98b4cdf66039e7a7?/utr
- **家庭环保习惯的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/58e9cd395dcd48cb9078a75a98b4cdf66039e7a7?/495/?ezg
- **家庭教育交流的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/58e9cd395dcd48cb9078a75a98b4cdf66039e7a7?/231=667
- **邻里共享空间的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/58e9cd395dcd48cb9078a75a98b4cdf66039e7a7?/mfz=226
- **口袋公园建设的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/3aae7cf8249988ae2141a3d083c92e57e8cb274c?/641
- **图书馆数字服务中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/3aae7cf8249988ae2141a3d083c92e57e8cb274c?/ndj
- **网络安全教育的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/3aae7cf8249988ae2141a3d083c92e57e8cb274c?/626/?fvk
- **基层健康档案的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/3aae7cf8249988ae2141a3d083c92e57e8cb274c?/144=026
- **个人信息保护的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/3aae7cf8249988ae2141a3d083c92e57e8cb274c?/vpa=274
- **社区手工活动的空间使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/eb54baf624649ba21c65819085affea60eaa661a?/781
- **数字课堂应用的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/eb54baf624649ba21c65819085affea60eaa661a?/rru
- **家庭防灾准备的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/eb54baf624649ba21c65819085affea60eaa661a?/856/?nae
- **药品使用科普的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/eb54baf624649ba21c65819085affea60eaa661a?/960=946
- **职业技能学习的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/eb54baf624649ba21c65819085affea60eaa661a?/lsa=492
- **家庭网络使用的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d033d665b08ba262c70325bc5689d91ecbeddd1d?/112
- **城市体育设施的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d033d665b08ba262c70325bc5689d91ecbeddd1d?/ttr
- **社区阅读服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/d033d665b08ba262c70325bc5689d91ecbeddd1d?/244/?vfm
- **城市慢行系统的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d033d665b08ba262c70325bc5689d91ecbeddd1d?/464=240
- **生活技能分享有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d033d665b08ba262c70325bc5689d91ecbeddd1d?/lao=601
- **科普展览体验的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5fc5ee751fbe9c939f80d1d21aba2576b6980e?/186
- **城市社区治理的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5fc5ee751fbe9c939f80d1d21aba2576b6980e?/odp
- **地方戏曲体验中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5fc5ee751fbe9c939f80d1d21aba2576b6980e?/647/?xua
- **社区互助网络的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5fc5ee751fbe9c939f80d1d21aba2576b6980e?/060=409
- **公共服务预约的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/1b5fc5ee751fbe9c939f80d1d21aba2576b6980e?/jbx=056
- **科学健身方法的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/959ea1b04b03dbadfd2ee6b95d68f9e9dacc7b72?/663
- **非遗体验活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/959ea1b04b03dbadfd2ee6b95d68f9e9dacc7b72?/qlz
- **社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/959ea1b04b03dbadfd2ee6b95d68f9e9dacc7b72?/681/?hdu
- **城市公共厕所的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/959ea1b04b03dbadfd2ee6b95d68f9e9dacc7b72?/532=811
- **乡村公共阅读的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/959ea1b04b03dbadfd2ee6b95d68f9e9dacc7b72?/jaf=494
- **口袋公园建设中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/da8f9f3d23fcf66dddfa33ecd7019f54e5d79f85?/007
- **城市步行友好中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/da8f9f3d23fcf66dddfa33ecd7019f54e5d79f85?/ddc
- **图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/da8f9f3d23fcf66dddfa33ecd7019f54e5d79f85?/219/?evi
- **公园亲子设施的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/da8f9f3d23fcf66dddfa33ecd7019f54e5d79f85?/067=446
- **家庭科学教育的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/da8f9f3d23fcf66dddfa33ecd7019f54e5d79f85?/mgy=284
- **社区老年食堂的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/25df785f605c83b80471efa95cea2f5acd1f7e5b?/749
- **在线学习体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/25df785f605c83b80471efa95cea2f5acd1f7e5b?/inv
- **数字创意课程的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/25df785f605c83b80471efa95cea2f5acd1f7e5b?/806/?ivm
- **城市噪声观察的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/25df785f605c83b80471efa95cea2f5acd1f7e5b?/733=170
- **家庭用电安全从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/25df785f605c83b80471efa95cea2f5acd1f7e5b?/bls=257
- **社区邻里服务的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/db54b5e7c07f4bb2396d8d9e3b727cc0e6043ce7?/208
- **青少年科普实践的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/db54b5e7c07f4bb2396d8d9e3b727cc0e6043ce7?/qhk
- **城市文化路线的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/db54b5e7c07f4bb2396d8d9e3b727cc0e6043ce7?/286/?iow
- **就业技能培训的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/db54b5e7c07f4bb2396d8d9e3b727cc0e6043ce7?/272=638
- **公共空间导览的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/db54b5e7c07f4bb2396d8d9e3b727cc0e6043ce7?/ykq=112
- **周末休闲规划的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/9816236e20ac125f0b2116010b941ea280cfa048?/542
- **城市宠物友好空间的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/9816236e20ac125f0b2116010b941ea280cfa048?/rth
- **社区互助网络的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/9816236e20ac125f0b2116010b941ea280cfa048?/671/?qtv
- **城市噪声观察的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/9816236e20ac125f0b2116010b941ea280cfa048?/991=949
- **社区体育组织的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/9816236e20ac125f0b2116010b941ea280cfa048?/wvr=545
- **创业经验分享的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/529d2f95fcda80b838559f67f6acf83b1cac1612?/996
- **乡村公共阅读的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/529d2f95fcda80b838559f67f6acf83b1cac1612?/fxc
- **老年数字阅读的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/529d2f95fcda80b838559f67f6acf83b1cac1612?/990/?vsu
- **社区学习活动的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/529d2f95fcda80b838559f67f6acf83b1cac1612?/947=306
- **公共卫生宣传的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/529d2f95fcda80b838559f67f6acf83b1cac1612?/hnd=983
- **社区菜市场服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/15e23a29468791f4a46c8931d0392d3feb63b856?/956
- **社区宣传栏更新的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/15e23a29468791f4a46c8931d0392d3feb63b856?/gur
- **生活垃圾减量的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/15e23a29468791f4a46c8931d0392d3feb63b856?/725/?nqx
- **读书会组织的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/15e23a29468791f4a46c8931d0392d3feb63b856?/564=251
- **社区志愿服务的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/15e23a29468791f4a46c8931d0392d3feb63b856?/iim=646
- **城市生活服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/dd697fff6ffe47a85567247326de8156f89fdfc5?/152
- **智能家居应用的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/dd697fff6ffe47a85567247326de8156f89fdfc5?/hjk
- **社区艺术活动的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/dd697fff6ffe47a85567247326de8156f89fdfc5?/522/?wbg
- **青少年科技社团的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/dd697fff6ffe47a85567247326de8156f89fdfc5?/428=090
- **科学观察活动的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/dd697fff6ffe47a85567247326de8156f89fdfc5?/hlk=939
- **青少年科技社团的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1411d08b9be77c0474a141d9f8d14d56590f8f?/676
- **急救知识普及的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1411d08b9be77c0474a141d9f8d14d56590f8f?/twk
- **城市便民驿站的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1411d08b9be77c0474a141d9f8d14d56590f8f?/808/?ihh
- **青年就业服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1411d08b9be77c0474a141d9f8d14d56590f8f?/400=909
- **社区手工活动的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/7e1411d08b9be77c0474a141d9f8d14d56590f8f?/css=647
- **城市农夫市集的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/365126c93b685c33d66ef7ff199ac851d03dfe9a?/213
- **学校食育活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/365126c93b685c33d66ef7ff199ac851d03dfe9a?/aqs
- **文化讲座服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/365126c93b685c33d66ef7ff199ac851d03dfe9a?/084/?uwg
- **农业科普体验的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/365126c93b685c33d66ef7ff199ac851d03dfe9a?/322=917
- **社区公共餐饮的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/365126c93b685c33d66ef7ff199ac851d03dfe9a?/qpv=731
- **城市水环境观察的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/c13e3d7ae361d0a3d6ef6aa0f21e832435420ac3?/014
- **城市文明实践的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c13e3d7ae361d0a3d6ef6aa0f21e832435420ac3?/ilm
- **公交站点体验的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c13e3d7ae361d0a3d6ef6aa0f21e832435420ac3?/692/?mga
- **地方戏曲体验的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/c13e3d7ae361d0a3d6ef6aa0f21e832435420ac3?/754=805
- **社区快递服务的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c13e3d7ae361d0a3d6ef6aa0f21e832435420ac3?/vlo=959
- **公共服务咨询的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/c1a427ffee762f2e159f07b1f8c2c183237beb0d?/928
- **公共服务数字化的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/c1a427ffee762f2e159f07b1f8c2c183237beb0d?/twl
- **公共场馆服务从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/c1a427ffee762f2e159f07b1f8c2c183237beb0d?/537/?dwl
- **城市展览体验的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/c1a427ffee762f2e159f07b1f8c2c183237beb0d?/251=576
- **家庭照护支持的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/c1a427ffee762f2e159f07b1f8c2c183237beb0d?/tya=398
- **社区健康讲座的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3b23c485350fb44c53f6df69ba9ddfefefc827a3?/894
- **数字创意课程的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3b23c485350fb44c53f6df69ba9ddfefefc827a3?/bsm
- **无障碍出行的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/3b23c485350fb44c53f6df69ba9ddfefefc827a3?/817/?och
- **绿色校园实践的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3b23c485350fb44c53f6df69ba9ddfefefc827a3?/511=732
- **青年志愿活动的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/3b23c485350fb44c53f6df69ba9ddfefefc827a3?/ces=063
- **学校食育活动的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/334e1ca8a0a52345617f0ba259a07925c02b2466?/125
- **城市公共饮水的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/334e1ca8a0a52345617f0ba259a07925c02b2466?/eea
- **城市公共自行车的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/334e1ca8a0a52345617f0ba259a07925c02b2466?/297/?mgf
- **城市住房服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/334e1ca8a0a52345617f0ba259a07925c02b2466?/569=769
- **数字支付体验的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/334e1ca8a0a52345617f0ba259a07925c02b2466?/myh=057
- **青少年科技社团的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/54685551a28e4f5de46a54743f416500eeb67e0b?/966
- **城市应急科普的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/54685551a28e4f5de46a54743f416500eeb67e0b?/ssm
- **社区学习活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/54685551a28e4f5de46a54743f416500eeb67e0b?/539/?lej
- **开放数据应用的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/54685551a28e4f5de46a54743f416500eeb67e0b?/455=472
- **市民意见收集的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/54685551a28e4f5de46a54743f416500eeb67e0b?/lsg=911
- **城市慢行系统的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/42467a6ffb7f3de47c637460f1d31e7230db5f31?/297
- **社区活动报名的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/42467a6ffb7f3de47c637460f1d31e7230db5f31?/itc
- **家庭用电安全的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/42467a6ffb7f3de47c637460f1d31e7230db5f31?/657/?pma
- **数据分析入门的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/42467a6ffb7f3de47c637460f1d31e7230db5f31?/309=762
- **网络安全教育的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/42467a6ffb7f3de47c637460f1d31e7230db5f31?/ehq=631
- **健康饮水科普的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/bed56c839b9dc4d54abe754ea145d2084e705c46?/181
- **城市夜间照明的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bed56c839b9dc4d54abe754ea145d2084e705c46?/yhh
- **城市适老服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/bed56c839b9dc4d54abe754ea145d2084e705c46?/715/?aor
- **城市适老服务的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/bed56c839b9dc4d54abe754ea145d2084e705c46?/806=611
- **社区家校合作的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/bed56c839b9dc4d54abe754ea145d2084e705c46?/nqq=809
- **机器人科普活动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/be3b7c28120f376bd8f138b787f471fd13d4fa21?/184
- **城市文化路线的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/be3b7c28120f376bd8f138b787f471fd13d4fa21?/sxl
- **家庭理财科普的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/be3b7c28120f376bd8f138b787f471fd13d4fa21?/333/?rcg
- **社区文化节活动的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/be3b7c28120f376bd8f138b787f471fd13d4fa21?/035=702
- **数据分析入门的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/be3b7c28120f376bd8f138b787f471fd13d4fa21?/emr=282
- **科学教育活动的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/ae8af9f8f7026117fc174cce0f34526d7786ed58?/701
- **数字艺术创作的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/ae8af9f8f7026117fc174cce0f34526d7786ed58?/lwn
- **便民维修服务的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/ae8af9f8f7026117fc174cce0f34526d7786ed58?/658/?ypr
- **街区小店体验从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/ae8af9f8f7026117fc174cce0f34526d7786ed58?/682=952
- **青年志愿活动中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/ae8af9f8f7026117fc174cce0f34526d7786ed58?/hjn=936
- **口袋公园建设的公共信息获取方式 |来源：https://github.com/whitakertraci6/lPLm/commit/6186cf54da70e42b7cd5fe63de0454ac11b3d6b4?/248
- **社区防暑服务的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/6186cf54da70e42b7cd5fe63de0454ac11b3d6b4?/fkv
- **数字政务体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/6186cf54da70e42b7cd5fe63de0454ac11b3d6b4?/284/?yez
- **城市水环境观察的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/6186cf54da70e42b7cd5fe63de0454ac11b3d6b4?/727=469
- **城市微更新实践有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/6186cf54da70e42b7cd5fe63de0454ac11b3d6b4?/oly=913
- **旧物循环利用的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/2d4c37c29e7043bf5ad9abfccf7c66fedf9e8e53?/313
- **家庭消费规划的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/2d4c37c29e7043bf5ad9abfccf7c66fedf9e8e53?/atr
- **儿童户外活动中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/2d4c37c29e7043bf5ad9abfccf7c66fedf9e8e53?/598/?bgn
- **社区协商议事的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/2d4c37c29e7043bf5ad9abfccf7c66fedf9e8e53?/525=479
- **城市生活记录的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/2d4c37c29e7043bf5ad9abfccf7c66fedf9e8e53?/yhc=965
- **智慧停车服务有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/923a5dbb1bcca2785404a8e63be7f8b8cb3226eb?/058
- **医院导诊服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/923a5dbb1bcca2785404a8e63be7f8b8cb3226eb?/hzq
- **科学信息获取的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/923a5dbb1bcca2785404a8e63be7f8b8cb3226eb?/739/?agm
- **公共交通接驳的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/923a5dbb1bcca2785404a8e63be7f8b8cb3226eb?/019=683
- **基层服务创新的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/923a5dbb1bcca2785404a8e63be7f8b8cb3226eb?/wer=577
- **社区家校合作的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b6f6019fa60f6850bcdc8ee84961c42928e5ae08?/957
- **生活垃圾回收的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/b6f6019fa60f6850bcdc8ee84961c42928e5ae08?/raw
- **线上阅读资源的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/b6f6019fa60f6850bcdc8ee84961c42928e5ae08?/367/?fpk
- **城市适老服务的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/b6f6019fa60f6850bcdc8ee84961c42928e5ae08?/723=083
- **社区便利生活的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/b6f6019fa60f6850bcdc8ee84961c42928e5ae08?/lcl=266
- **儿童友好空间的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fe77d8685c7e53df46ef80a1a4883b4e76b9afd1?/093
- **绿色出行服务的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/fe77d8685c7e53df46ef80a1a4883b4e76b9afd1?/frc
- **城市展览体验的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/fe77d8685c7e53df46ef80a1a4883b4e76b9afd1?/514/?ypr
- **家庭健康科普的实用信息清单 |来源：https://github.com/whitakertraci6/lPLm/commit/fe77d8685c7e53df46ef80a1a4883b4e76b9afd1?/156=595
- **低碳社区实践的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/fe77d8685c7e53df46ef80a1a4883b4e76b9afd1?/ydv=462
- **公共设施维护的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5e9e3bd551b118bd214f909ee210536a5b80bd?/011
- **儿童友好空间的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5e9e3bd551b118bd214f909ee210536a5b80bd?/yfc
- **智慧城市体验的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5e9e3bd551b118bd214f909ee210536a5b80bd?/023/?iik
- **电子商务服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5e9e3bd551b118bd214f909ee210536a5b80bd?/653=920
- **亲子科普活动的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/aa5e9e3bd551b118bd214f909ee210536a5b80bd?/wdd=123
- **城市夜间照明的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/fdd2474aa4284288254988ba6c798eab2e397e8d?/936
- **城市夜间照明的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/fdd2474aa4284288254988ba6c798eab2e397e8d?/ter
- **社区体育组织的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/fdd2474aa4284288254988ba6c798eab2e397e8d?/957/?eky
- **家庭急救准备的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/fdd2474aa4284288254988ba6c798eab2e397e8d?/263=231
- **社区交通安全的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/fdd2474aa4284288254988ba6c798eab2e397e8d?/epy=692
- **在线教育体验中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/84f794798869932136cedb9fe5a63e6666f44d46?/249
- **街道综合服务的便民做法梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/84f794798869932136cedb9fe5a63e6666f44d46?/uok
- **便民维修服务的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/84f794798869932136cedb9fe5a63e6666f44d46?/055/?obf
- **公共交通信息服务的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/84f794798869932136cedb9fe5a63e6666f44d46?/086=308
- **家庭园艺实践中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/84f794798869932136cedb9fe5a63e6666f44d46?/xup=813
- **城市公共标识的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/30fcd919e476da35af6214dec16bb2bd0361b558?/492
- **乡村阅读活动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/30fcd919e476da35af6214dec16bb2bd0361b558?/dea
- **智能手机助老的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/30fcd919e476da35af6214dec16bb2bd0361b558?/977/?ynb
- **生活垃圾回收的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/30fcd919e476da35af6214dec16bb2bd0361b558?/980=461
- **居家防滑改造的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/30fcd919e476da35af6214dec16bb2bd0361b558?/hto=301
- **社区共享书架的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/1ef69c364be4d4c323ebe0b725daffeceb66ad2d?/625
- **社区家政服务的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1ef69c364be4d4c323ebe0b725daffeceb66ad2d?/qwz
- **科学运动指导的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/1ef69c364be4d4c323ebe0b725daffeceb66ad2d?/475/?sbt
- **节约用水实践的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/1ef69c364be4d4c323ebe0b725daffeceb66ad2d?/110=797
- **城市应急广播从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/1ef69c364be4d4c323ebe0b725daffeceb66ad2d?/nid=509
- **绿色出行服务的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/4afab5322dd3d2dad96813025b7463484dd4e6ba?/863
- **休闲运动入门的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/4afab5322dd3d2dad96813025b7463484dd4e6ba?/rhk
- **无障碍出行的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/4afab5322dd3d2dad96813025b7463484dd4e6ba?/527/?qox
- **数字便民地图的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/4afab5322dd3d2dad96813025b7463484dd4e6ba?/456=845
- **社区便民服务的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/4afab5322dd3d2dad96813025b7463484dd4e6ba?/lqv=768
- **儿童友好空间的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/63f799b94906fa22e443728903af2537f9f5c7a6?/774
- **公共文化活动的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/63f799b94906fa22e443728903af2537f9f5c7a6?/och
- **绿色校园实践中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/63f799b94906fa22e443728903af2537f9f5c7a6?/193/?ixz
- **生活技能分享的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/63f799b94906fa22e443728903af2537f9f5c7a6?/147=487
- **乡村文化活动的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/63f799b94906fa22e443728903af2537f9f5c7a6?/ojg=462
- **图书借阅体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/98268deb33d31d755a4b2cec78ffc367242c5899?/690
- **志愿者培训交流的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/98268deb33d31d755a4b2cec78ffc367242c5899?/wgr
- **社区商业活力中的几个关键细节 |来源：https://github.com/whitakertraci6/lPLm/commit/98268deb33d31d755a4b2cec78ffc367242c5899?/800/?tag
- **家庭节能实践的社区参与观察 |来源：https://github.com/whitakertraci6/lPLm/commit/98268deb33d31d755a4b2cec78ffc367242c5899?/118=974
- **城乡交流活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/98268deb33d31d755a4b2cec78ffc367242c5899?/lkq=551
- **无障碍信息设计的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1a650eba9448f495cb785beb7a1a1eec83eaa478?/822
- **智能手机助老的资源整合思路 |来源：https://github.com/whitakertraci6/lPLm/commit/1a650eba9448f495cb785beb7a1a1eec83eaa478?/nov
- **软件开发学习的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/1a650eba9448f495cb785beb7a1a1eec83eaa478?/031/?poi
- **邻里共享空间的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1a650eba9448f495cb785beb7a1a1eec83eaa478?/203=231
- **社区健康讲座的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1a650eba9448f495cb785beb7a1a1eec83eaa478?/nbr=795
- **光伏知识科普的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/16433daec25bd8b6e7b2491ec0097df83a0a5ba7?/866
- **骑行路线规划的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/16433daec25bd8b6e7b2491ec0097df83a0a5ba7?/cti
- **家庭教育交流的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/16433daec25bd8b6e7b2491ec0097df83a0a5ba7?/198/?bqd
- **公共空间导览的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/16433daec25bd8b6e7b2491ec0097df83a0a5ba7?/785=697
- **学校食育活动的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/16433daec25bd8b6e7b2491ec0097df83a0a5ba7?/vlh=929
- **城市建设科普的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7120ae383d5d47dfa1395a29938a00e6b6322e26?/757
- **城市文明实践的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/7120ae383d5d47dfa1395a29938a00e6b6322e26?/xkd
- **环境教育课程的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7120ae383d5d47dfa1395a29938a00e6b6322e26?/814/?bis
- **公共文化活动的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/7120ae383d5d47dfa1395a29938a00e6b6322e26?/792=558
- **家庭志愿活动的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/7120ae383d5d47dfa1395a29938a00e6b6322e26?/zii=254
- **数据分析入门有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/384a902dc29bc8ec9acf85af9ea9dc1d58963890?/784
- **城市生活服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/384a902dc29bc8ec9acf85af9ea9dc1d58963890?/cck
- **老旧小区改造从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/384a902dc29bc8ec9acf85af9ea9dc1d58963890?/706/?suw
- **家庭健康管理的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/384a902dc29bc8ec9acf85af9ea9dc1d58963890?/012=912
- **城市休闲步道的活动策划思路 |来源：https://github.com/whitakertraci6/lPLm/commit/384a902dc29bc8ec9acf85af9ea9dc1d58963890?/fop=234
- **城市地名文化的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/31d9d023c5872c8c6a3b0c23bba897f409855b65?/251
- **基层健康档案的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/31d9d023c5872c8c6a3b0c23bba897f409855b65?/xby
- **小区公共照明中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/31d9d023c5872c8c6a3b0c23bba897f409855b65?/716/?nhb
- **数字资源检索的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/31d9d023c5872c8c6a3b0c23bba897f409855b65?/533=651
- **社区垃圾回收的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/31d9d023c5872c8c6a3b0c23bba897f409855b65?/zok=642
- **农村环境治理的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/a1da00ffdf398bf1381ed13b8f76e70a7b573a5d?/169
- **街区小店体验的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a1da00ffdf398bf1381ed13b8f76e70a7b573a5d?/wkw
- **儿童阅读角的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a1da00ffdf398bf1381ed13b8f76e70a7b573a5d?/129/?ywq
- **乡村产业科普的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/a1da00ffdf398bf1381ed13b8f76e70a7b573a5d?/277=618
- **家庭急救准备的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/a1da00ffdf398bf1381ed13b8f76e70a7b573a5d?/prk=007
- **地方文化传播的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/bd35b44f207a51424707bf18beb1e47638d37a14?/762
- **文化遗产保护科普的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/bd35b44f207a51424707bf18beb1e47638d37a14?/knw
- **周末休闲规划的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/bd35b44f207a51424707bf18beb1e47638d37a14?/701/?lqv
- **公共交通信息服务中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/bd35b44f207a51424707bf18beb1e47638d37a14?/090=388
- **公交无障碍服务的服务反馈渠道 |来源：https://github.com/whitakertraci6/lPLm/commit/bd35b44f207a51424707bf18beb1e47638d37a14?/bav=668
- **科技馆参观体验的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/29c2f8691fa5583b2c11f2ce977bb082fa21048f?/716
- **家庭园艺实践的公共参与指南 |来源：https://github.com/whitakertraci6/lPLm/commit/29c2f8691fa5583b2c11f2ce977bb082fa21048f?/kso
- **社区科普课堂的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/29c2f8691fa5583b2c11f2ce977bb082fa21048f?/448/?tpm
- **城市共享单车的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/29c2f8691fa5583b2c11f2ce977bb082fa21048f?/570=216
- **城市地名文化的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/29c2f8691fa5583b2c11f2ce977bb082fa21048f?/fqn=674
- **本地历史资料的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/2707803c5f70b99b8fb1d6d1bf514d85cfb9a858?/026
- **社区垃圾分类的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/2707803c5f70b99b8fb1d6d1bf514d85cfb9a858?/cxj
- **邻里互助活动的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2707803c5f70b99b8fb1d6d1bf514d85cfb9a858?/802/?iri
- **城市建设科普的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/2707803c5f70b99b8fb1d6d1bf514d85cfb9a858?/930=653
- **农产品消费体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/2707803c5f70b99b8fb1d6d1bf514d85cfb9a858?/hhy=841
- **家庭饮食安排的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/f123596a270ec54867fdf6de3bfb8b0f6654dbd8?/157
- **绿色生活实践的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/f123596a270ec54867fdf6de3bfb8b0f6654dbd8?/esb
- **生成式工具使用有哪些值得关注的细节 |来源：https://github.com/whitakertraci6/lPLm/commit/f123596a270ec54867fdf6de3bfb8b0f6654dbd8?/406/?rqi
- **城市步行友好的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/f123596a270ec54867fdf6de3bfb8b0f6654dbd8?/799=905
- **城市生活记录的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/f123596a270ec54867fdf6de3bfb8b0f6654dbd8?/ngx=546
- **农贸市场环境的协商参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/b01e154408772e9ed2c3e6ee8c2c39604a30c9dc?/006
- **社区文化节活动的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/b01e154408772e9ed2c3e6ee8c2c39604a30c9dc?/vzv
- **乡村生活观察从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/b01e154408772e9ed2c3e6ee8c2c39604a30c9dc?/316/?zsv
- **运动安全知识的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/b01e154408772e9ed2c3e6ee8c2c39604a30c9dc?/362=979
- **科技馆参观体验的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/b01e154408772e9ed2c3e6ee8c2c39604a30c9dc?/ymi=156
- **社区活动空间的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/4081eea0177a1823bdbcc69b24d58af6ebdd2ce4?/291
- **街区绿化养护的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/4081eea0177a1823bdbcc69b24d58af6ebdd2ce4?/sjt
- **城市应急广播的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/4081eea0177a1823bdbcc69b24d58af6ebdd2ce4?/451/?edv
- **社区交通安全的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/4081eea0177a1823bdbcc69b24d58af6ebdd2ce4?/066=058
- **城市绿道建设的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/4081eea0177a1823bdbcc69b24d58af6ebdd2ce4?/vmy=404
- **城市博物馆服务的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/aaf04d797333edb39deb6de46c8058540134be8f?/264
- **社区生活指南的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/aaf04d797333edb39deb6de46c8058540134be8f?/iyl
- **社区宣传栏更新的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/aaf04d797333edb39deb6de46c8058540134be8f?/196/?prq
- **城市生活记录的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/aaf04d797333edb39deb6de46c8058540134be8f?/429=835
- **文明养宠科普的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/aaf04d797333edb39deb6de46c8058540134be8f?/ybn=713
- **绿色消费选择的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/1bcae9f078d325ce4da528a6f9adfe20a973bd4e?/845
- **传统手工艺体验的服务质量观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1bcae9f078d325ce4da528a6f9adfe20a973bd4e?/wsa
- **城市公共空间的家庭参与方式 |来源：https://github.com/whitakertraci6/lPLm/commit/1bcae9f078d325ce4da528a6f9adfe20a973bd4e?/685/?jqt
- **信息无障碍体验的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/1bcae9f078d325ce4da528a6f9adfe20a973bd4e?/296=815
- **街区小店体验的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/1bcae9f078d325ce4da528a6f9adfe20a973bd4e?/ynl=635
- **在线学习体验的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/d3df58586de24062c08916363959dc9060603535?/512
- **无障碍出行的适老服务细节 |来源：https://github.com/whitakertraci6/lPLm/commit/d3df58586de24062c08916363959dc9060603535?/jrx
- **城市慢跑路线的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/d3df58586de24062c08916363959dc9060603535?/746/?acc
- **通勤路线规划的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/d3df58586de24062c08916363959dc9060603535?/722=335
- **社区文化节活动的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/d3df58586de24062c08916363959dc9060603535?/ckj=938
- **公交站点体验的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/7eafa97508b93723c69cab154a3c9a9d4d918378?/309
- **城市共享单车的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/7eafa97508b93723c69cab154a3c9a9d4d918378?/fld
- **电子商务服务的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/7eafa97508b93723c69cab154a3c9a9d4d918378?/272/?tzo
- **家庭节能实践的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/7eafa97508b93723c69cab154a3c9a9d4d918378?/294=247
- **个人数据管理的实际需求与回应 |来源：https://github.com/whitakertraci6/lPLm/commit/7eafa97508b93723c69cab154a3c9a9d4d918378?/ifu=013
- **健康饮食教育的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a25b21b2d09b9c3122feef109512be745c345c5c?/559
- **城市便民驿站的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a25b21b2d09b9c3122feef109512be745c345c5c?/lve
- **无障碍出行的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/a25b21b2d09b9c3122feef109512be745c345c5c?/196/?hnt
- **数字支付体验的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/a25b21b2d09b9c3122feef109512be745c345c5c?/376=331
- **社区绿色空间的阅读与学习资源 |来源：https://github.com/whitakertraci6/lPLm/commit/a25b21b2d09b9c3122feef109512be745c345c5c?/nbf=467
- **社区艺术活动的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/b64e180199a2758c32e5b6b50dab340991c2b010?/048
- **城市水环境观察的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b64e180199a2758c32e5b6b50dab340991c2b010?/pmc
- **乡村公共阅读的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/b64e180199a2758c32e5b6b50dab340991c2b010?/113/?gzg
- **公共服务预约的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/b64e180199a2758c32e5b6b50dab340991c2b010?/056=234
- **街区更新实践的持续改进方向 |来源：https://github.com/whitakertraci6/lPLm/commit/b64e180199a2758c32e5b6b50dab340991c2b010?/oiz=957
- **地方美食文化的社区行动案例 |来源：https://github.com/whitakertraci6/lPLm/commit/1cb3d371dbe68909a26045c6a34427a40a85bfaa?/336
- **家庭志愿活动从需求出发看服务设计 |来源：https://github.com/whitakertraci6/lPLm/commit/1cb3d371dbe68909a26045c6a34427a40a85bfaa?/qia
- **个人信息保护的空间设计要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1cb3d371dbe68909a26045c6a34427a40a85bfaa?/218/?llj
- **社区商业活力的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/1cb3d371dbe68909a26045c6a34427a40a85bfaa?/218=199
- **街区更新实践的线上线下服务衔接 |来源：https://github.com/whitakertraci6/lPLm/commit/1cb3d371dbe68909a26045c6a34427a40a85bfaa?/uma=177
- **低碳社区实践的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/538d69b5f4b096de08b7398ed2fde960ed554fe9?/570
- **家庭运动计划的绿色实践方法 |来源：https://github.com/whitakertraci6/lPLm/commit/538d69b5f4b096de08b7398ed2fde960ed554fe9?/sdv
- **开源技术交流的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/538d69b5f4b096de08b7398ed2fde960ed554fe9?/660/?dmo
- **生活服务数字化的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/538d69b5f4b096de08b7398ed2fde960ed554fe9?/691=962
- **老年智能设备的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/538d69b5f4b096de08b7398ed2fde960ed554fe9?/zbg=684
- **社区科普课堂的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/036633a89c718753194ecc7a7156430d24c747bb?/665
- **全民健身活动的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/036633a89c718753194ecc7a7156430d24c747bb?/ovd
- **社区垃圾回收的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/036633a89c718753194ecc7a7156430d24c747bb?/240/?wzg
- **地方戏曲体验的常见问题梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/036633a89c718753194ecc7a7156430d24c747bb?/056=473
- **老年人日常照护的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/036633a89c718753194ecc7a7156430d24c747bb?/pnu=967
- **智慧城市体验的协作机制梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/385d4e6954432c36d68ffe1363d1ceca298cab1d?/253
- **绿色建筑理念的服务信息整理 |来源：https://github.com/whitakertraci6/lPLm/commit/385d4e6954432c36d68ffe1363d1ceca298cab1d?/ggo
- **学校食育活动的日常实践笔记 |来源：https://github.com/whitakertraci6/lPLm/commit/385d4e6954432c36d68ffe1363d1ceca298cab1d?/379/?wlm
- **低碳社区实践的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/385d4e6954432c36d68ffe1363d1ceca298cab1d?/492=562
- **小区公共照明的儿童友好细节 |来源：https://github.com/whitakertraci6/lPLm/commit/385d4e6954432c36d68ffe1363d1ceca298cab1d?/acp=625
- **青少年心理健康的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/a353004d29812b2aa98a458b8bb71400f719a1e3?/949
- **个人信息保护的居民参与机会 |来源：https://github.com/whitakertraci6/lPLm/commit/a353004d29812b2aa98a458b8bb71400f719a1e3?/pka
- **公共空间休憩的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/a353004d29812b2aa98a458b8bb71400f719a1e3?/853/?sqn
- **社区读书角建设的流程优化思路 |来源：https://github.com/whitakertraci6/lPLm/commit/a353004d29812b2aa98a458b8bb71400f719a1e3?/053=641
- **小区停车协商的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/a353004d29812b2aa98a458b8bb71400f719a1e3?/ohi=948
- **老旧小区改造的日常管理方法 |来源：https://github.com/whitakertraci6/lPLm/commit/1fbfc33468abe74d400fcc0675a4c8624304fd43?/211
- **小区公共照明的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/1fbfc33468abe74d400fcc0675a4c8624304fd43?/rzg
- **社区公共卫生的家庭实践清单 |来源：https://github.com/whitakertraci6/lPLm/commit/1fbfc33468abe74d400fcc0675a4c8624304fd43?/960/?zdh
- **公共场馆服务的长期维护要点 |来源：https://github.com/whitakertraci6/lPLm/commit/1fbfc33468abe74d400fcc0675a4c8624304fd43?/102=430
- **软件开发学习的线下体验记录 |来源：https://github.com/whitakertraci6/lPLm/commit/1fbfc33468abe74d400fcc0675a4c8624304fd43?/beb=805
- **个人数据管理的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/8b77022d71d8b8fa3e6be1aea927413d56f7d277?/126
- **学校体育活动的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/8b77022d71d8b8fa3e6be1aea927413d56f7d277?/pfv
- **家庭健康管理的便捷程度观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8b77022d71d8b8fa3e6be1aea927413d56f7d277?/029/?ogv
- **街区绿化养护的基础设施观察 |来源：https://github.com/whitakertraci6/lPLm/commit/8b77022d71d8b8fa3e6be1aea927413d56f7d277?/846=278
- **城市游园体验的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/8b77022d71d8b8fa3e6be1aea927413d56f7d277?/ema=146
- **街区更新实践的参与方式与路径 |来源：https://github.com/whitakertraci6/lPLm/commit/1c481f2900a593083e8331209ec42bd2f64bd5d9?/475
- **绿色办公实践从使用体验看服务改进 |来源：https://github.com/whitakertraci6/lPLm/commit/1c481f2900a593083e8331209ec42bd2f64bd5d9?/gul
- **传统节日科普的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/1c481f2900a593083e8331209ec42bd2f64bd5d9?/622/?mus
- **儿童安全出行的服务体验观察 |来源：https://github.com/whitakertraci6/lPLm/commit/1c481f2900a593083e8331209ec42bd2f64bd5d9?/578=366
- **数字课堂应用的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/1c481f2900a593083e8331209ec42bd2f64bd5d9?/uyf=920
- **数字档案服务的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/3c0518ae9229a865867e5eef59d4e1b66fcf6252?/967
- **城市公共自行车的便利性观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3c0518ae9229a865867e5eef59d4e1b66fcf6252?/sft
- **城市共享单车的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/3c0518ae9229a865867e5eef59d4e1b66fcf6252?/584/?bjf
- **社区读书角建设的常见误区提醒 |来源：https://github.com/whitakertraci6/lPLm/commit/3c0518ae9229a865867e5eef59d4e1b66fcf6252?/462=040
- **社区健康讲座的活动体验回顾 |来源：https://github.com/whitakertraci6/lPLm/commit/3c0518ae9229a865867e5eef59d4e1b66fcf6252?/wcr=444
- **青少年职业启蒙的活动组织技巧 |来源：https://github.com/whitakertraci6/lPLm/commit/af6723163db3dc864118b736afeb39cd1a6459f5?/191
- **公共卫生设施的行动步骤参考 |来源：https://github.com/whitakertraci6/lPLm/commit/af6723163db3dc864118b736afeb39cd1a6459f5?/msi
- **社区菜市场服务的设施维护观察 |来源：https://github.com/whitakertraci6/lPLm/commit/af6723163db3dc864118b736afeb39cd1a6459f5?/813/?xoo
- **城市环境志愿行动的使用门槛与改进 |来源：https://github.com/whitakertraci6/lPLm/commit/af6723163db3dc864118b736afeb39cd1a6459f5?/174=544
- **开源技术交流的学习资源整理 |来源：https://github.com/whitakertraci6/lPLm/commit/af6723163db3dc864118b736afeb39cd1a6459f5?/wey=337
- **社区消防演练的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d207cd397b8b372c6ac6c8309a816ffadacea794?/750
- **科普展览体验的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d207cd397b8b372c6ac6c8309a816ffadacea794?/hnv
- **环境教育课程的资源利用方法 |来源：https://github.com/whitakertraci6/lPLm/commit/d207cd397b8b372c6ac6c8309a816ffadacea794?/765/?mli
- **家庭运动计划的入门知识整理 |来源：https://github.com/whitakertraci6/lPLm/commit/d207cd397b8b372c6ac6c8309a816ffadacea794?/653=448
- **城市可持续生活的基础知识问答 |来源：https://github.com/whitakertraci6/lPLm/commit/d207cd397b8b372c6ac6c8309a816ffadacea794?/acn=344
- **城市博物馆活动的执行流程参考 |来源：https://github.com/whitakertraci6/lPLm/commit/c227c8aee3205e765fd1fc85f1f8bbcd3ab6b49f?/130
- **家庭防灾准备的组织方法与经验 |来源：https://github.com/whitakertraci6/lPLm/commit/c227c8aee3205e765fd1fc85f1f8bbcd3ab6b49f?/bcf
- **儿童运动体验的数字工具使用体验 |来源：https://github.com/whitakertraci6/lPLm/commit/c227c8aee3205e765fd1fc85f1f8bbcd3ab6b49f?/235/?qzr
- **文化遗产保护科普中的沟通与协作 |来源：https://github.com/whitakertraci6/lPLm/commit/c227c8aee3205e765fd1fc85f1f8bbcd3ab6b49f?/756=660
- **老年友好服务的日常使用指南 |来源：https://github.com/whitakertraci6/lPLm/commit/c227c8aee3205e765fd1fc85f1f8bbcd3ab6b49f?/yrc=745
- **科学教育活动的日常记录与分享 |来源：https://github.com/whitakertraci6/lPLm/commit/e992c7178a62596a52c9484107090fbedb8867b8?/758
- **农村环境治理的服务细节记录 |来源：https://github.com/whitakertraci6/lPLm/commit/e992c7178a62596a52c9484107090fbedb8867b8?/iyo
- **数据分析入门的安全使用提示 |来源：https://github.com/whitakertraci6/lPLm/commit/e992c7178a62596a52c9484107090fbedb8867b8?/590/?aeu
- **城市社区治理的服务范围梳理 |来源：https://github.com/whitakertraci6/lPLm/commit/e992c7178a62596a52c9484107090fbedb8867b8?/026=958
- **居民健康教育的数字化应用观察 |来源：https://github.com/whitakertraci6/lPLm/commit/e992c7178a62596a52c9484107090fbedb8867b8?/hfx=308

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  大发官网代理等*  
*仅供参考，不构成投资建议*
