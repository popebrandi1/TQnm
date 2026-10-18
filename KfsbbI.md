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

- **社区宣传栏更新的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/cgjBi8.md?/955=359
- **家庭健康管理的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/cgjBi8.md?/ziu=291
- **科普展览体验的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md
- **家庭健康科普的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/f1de2ba271e4893b686a91da70109af487d3eb4b?/417
- **老旧小区改造的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/f1de2ba271e4893b686a91da70109af487d3eb4b?/itt
- **数字支付体验的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/f1de2ba271e4893b686a91da70109af487d3eb4b?/294/?pkj
- **社区垃圾回收的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/f1de2ba271e4893b686a91da70109af487d3eb4b?/151=044
- **城市生活服务的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/f1de2ba271e4893b686a91da70109af487d3eb4b?/kjf=043
- **物业服务沟通的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md?/215
- **安全出行教育的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md?/blo
- **节约用水实践的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md?/540/?hog
- **家庭用电安全的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md?/970=083
- **城市生活服务的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/8qfSHz.md?/ddg=915
- **社区活动报名的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md
- **社区活动策划的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/ea8de0c52eaae8cd61876b2c102168e9861fd52d?/064
- **网络安全教育的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/ea8de0c52eaae8cd61876b2c102168e9861fd52d?/wlc
- **医院导诊服务的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/ea8de0c52eaae8cd61876b2c102168e9861fd52d?/364/?amu
- **公共文化活动的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/ea8de0c52eaae8cd61876b2c102168e9861fd52d?/427=190
- **儿童友好街区的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/ea8de0c52eaae8cd61876b2c102168e9861fd52d?/wko=552
- **本地旅行体验的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md?/034
- **乡村休闲旅游的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md?/zmt
- **绿色快递包装的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md?/229/?ymo
- **旧物循环利用的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md?/711=584
- **图书馆亲子空间的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/LyG6eA.md?/bpj=816
- **跨代沟通活动中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md
- **社区学习活动的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/17d4f118a93a0dd009a9f434397bf265ddc7a66d?/431
- **公共服务咨询的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/17d4f118a93a0dd009a9f434397bf265ddc7a66d?/bfa
- **节能生活方式的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/17d4f118a93a0dd009a9f434397bf265ddc7a66d?/350/?fle
- **公园无障碍服务的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/17d4f118a93a0dd009a9f434397bf265ddc7a66d?/240=224
- **农村环境治理的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/17d4f118a93a0dd009a9f434397bf265ddc7a66d?/hoh=083
- **户外活动组织的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md?/674
- **电动汽车充电的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md?/oba
- **机器人科普活动的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md?/995/?evw
- **数字地图应用的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md?/367=077
- **志愿者培训交流的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/pUstkj.md?/hde=902
- **地方文化传播的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md
- **城乡公共服务的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/63ff8f6b6fb22e04f5e1761fbe1e5a8af84e21dd?/060
- **数字支付体验有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/63ff8f6b6fb22e04f5e1761fbe1e5a8af84e21dd?/uer
- **社区便民集市的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/63ff8f6b6fb22e04f5e1761fbe1e5a8af84e21dd?/205/?qqf
- **家庭节能实践的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/63ff8f6b6fb22e04f5e1761fbe1e5a8af84e21dd?/375=851
- **社区环保活动从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/63ff8f6b6fb22e04f5e1761fbe1e5a8af84e21dd?/vqj=586
- **城市公共自行车的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md?/088
- **城市社区治理的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md?/pyl
- **骑行路线规划的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md?/582/?ekx
- **城市雨天出行的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md?/137=540
- **低碳社区实践有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/jLQbyg.md?/fta=648
- **无障碍出行的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md
- **城市空气科普的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/b8eec0aedd42f7dd4b89e5cba4ce348ba8181429?/283
- **节能家电使用的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/commit/b8eec0aedd42f7dd4b89e5cba4ce348ba8181429?/ofq
- **本地消费场景的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/b8eec0aedd42f7dd4b89e5cba4ce348ba8181429?/248/?hsk
- **小区电梯维护的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/b8eec0aedd42f7dd4b89e5cba4ce348ba8181429?/972=912
- **绿色出行服务的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/b8eec0aedd42f7dd4b89e5cba4ce348ba8181429?/eln=762
- **家庭节能实践的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md?/667
- **老年数字阅读的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md?/gyh
- **城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md?/814/?fos
- **基层健康档案中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md?/977=994
- **社区故事采集的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/RXeavX.md?/dmz=693
- **老年智能设备的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md
- **乡村公共服务的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/0656ab7804b2ba3e77d52538cb3c0a251c28acf1?/552
- **城市公共标识的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/0656ab7804b2ba3e77d52538cb3c0a251c28acf1?/aca
- **新能源知识普及的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/0656ab7804b2ba3e77d52538cb3c0a251c28acf1?/885/?hvn
- **街区绿化养护的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/0656ab7804b2ba3e77d52538cb3c0a251c28acf1?/927=979
- **社区安全巡查的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/0656ab7804b2ba3e77d52538cb3c0a251c28acf1?/nsc=058
- **绿色消费选择的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md?/198
- **公共场所导视的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md?/tby
- **家庭环保行动的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md?/887/?yrx
- **无障碍出行的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md?/771=486
- **绿色出行服务的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/61goaK.md?/ixl=925
- **小区公共照明的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md
- **老年数字阅读从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/3ab8d56b56f0fcec4fb9c4eebd2e4db4aceece68?/246
- **公共卫生宣传的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/3ab8d56b56f0fcec4fb9c4eebd2e4db4aceece68?/bgu
- **便民维修服务的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/3ab8d56b56f0fcec4fb9c4eebd2e4db4aceece68?/592/?kxp
- **社区艺术活动的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/3ab8d56b56f0fcec4fb9c4eebd2e4db4aceece68?/309=299
- **公共服务预约的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/3ab8d56b56f0fcec4fb9c4eebd2e4db4aceece68?/bgq=967
- **旧物循环利用的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md?/271
- **亲子阅读活动的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md?/hre
- **街区小店体验从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md?/856/?khr
- **儿童友好街区的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md?/597=615
- **青少年科普实践的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/kp5TpN.md?/erh=068
- **公共服务数字化的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md
- **城市公共艺术的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/6fef81153b7841792368ec6e57ebe00b443b5e44?/752
- **老旧小区改造的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/6fef81153b7841792368ec6e57ebe00b443b5e44?/nnh
- **公共服务预约的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/6fef81153b7841792368ec6e57ebe00b443b5e44?/157/?ltj
- **家庭急救准备有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/6fef81153b7841792368ec6e57ebe00b443b5e44?/463=777
- **社区邻里服务的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/6fef81153b7841792368ec6e57ebe00b443b5e44?/qvm=873
- **城市骑行环境的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md?/244
- **环境教育课程从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md?/wzq
- **城市雨天出行的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md?/229/?iku
- **城市步行友好的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md?/589=874
- **科学教育活动的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/PwXTpP.md?/bsr=676
- **社区健康讲座的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md
- **城市适老服务的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/ac8c07764d6bd6db0d59a98ccf621db6bd78a8b9?/760
- **乡村教育资源的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/ac8c07764d6bd6db0d59a98ccf621db6bd78a8b9?/vna
- **非遗课堂体验的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/ac8c07764d6bd6db0d59a98ccf621db6bd78a8b9?/730/?nzr
- **健康饮食教育的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/ac8c07764d6bd6db0d59a98ccf621db6bd78a8b9?/910=222
- **校园安全教育的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/ac8c07764d6bd6db0d59a98ccf621db6bd78a8b9?/jqo=177
- **基层服务创新的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md?/250
- **数字创意课程的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md?/ajl
- **租房信息服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md?/241/?mvp
- **社区慢性病防控的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md?/083=035
- **劳动教育实践的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/7GI9ys.md?/sco=236
- **光伏知识科普的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md
- **科学健身方法中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/52f25b18dff97b8f63cb5e638dfbbb1642e751bd?/081
- **日常摄影记录的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/52f25b18dff97b8f63cb5e638dfbbb1642e751bd?/oeu
- **城市应急科普有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/52f25b18dff97b8f63cb5e638dfbbb1642e751bd?/632/?kpt
- **运动安全知识的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/52f25b18dff97b8f63cb5e638dfbbb1642e751bd?/470=850
- **家庭阅读计划的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/52f25b18dff97b8f63cb5e638dfbbb1642e751bd?/fby=744
- **社区垃圾分类的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md?/002
- **家庭节能设备的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md?/yom
- **光伏知识科普的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md?/229/?ofl
- **城市夜间生活的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md?/742=902
- **数字课堂应用的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jqba0i.md?/isz=506
- **数字艺术创作的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md
- **软件开发学习的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/b50eb0d80dc9fc023b65d504f077b9f50f2177c2?/846
- **社区志愿服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/b50eb0d80dc9fc023b65d504f077b9f50f2177c2?/liw
- **数字学习资源的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/b50eb0d80dc9fc023b65d504f077b9f50f2177c2?/905/?jiq
- **科学运动指导的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/commit/b50eb0d80dc9fc023b65d504f077b9f50f2177c2?/758=619
- **家庭饮食安排的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/b50eb0d80dc9fc023b65d504f077b9f50f2177c2?/qfc=758
- **公共场所导视的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md?/890
- **家庭食品保存的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md?/ywb
- **文化讲座服务的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md?/598/?tyr
- **家庭理财科普的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md?/798=443
- **街区道路维护的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/rnHWsc.md?/ahj=786
- **公共空间休憩的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md
- **健康信息获取的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/b7b509f5a43eea682421b609992325b3a7405593?/118
- **电子商务服务的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/b7b509f5a43eea682421b609992325b3a7405593?/njt
- **社区信息发布中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/b7b509f5a43eea682421b609992325b3a7405593?/885/?hlu
- **节约用水实践的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/b7b509f5a43eea682421b609992325b3a7405593?/869=885
- **儿童安全出行的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/b7b509f5a43eea682421b609992325b3a7405593?/coj=404
- **校园阅读活动的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md?/837
- **节假日出行安排的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md?/wzk
- **社区便民集市的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md?/708/?yvx
- **科学信息获取的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md?/874=093
- **旧物循环利用的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/nsDvu0.md?/fju=232
- **便民服务地图的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md
- **乡村生态旅游的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/b40e73823cb6f610d8958e61e73aa49d851daab5?/718
- **乡村电商实践的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/b40e73823cb6f610d8958e61e73aa49d851daab5?/xpr
- **社区学习活动的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/b40e73823cb6f610d8958e61e73aa49d851daab5?/540/?ymc
- **城市环境志愿行动的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/b40e73823cb6f610d8958e61e73aa49d851daab5?/135=097
- **家庭安全提示的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/b40e73823cb6f610d8958e61e73aa49d851daab5?/cuj=306
- **城市适老服务的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md?/252
- **老年数字阅读的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md?/jln
- **公共服务评价的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md?/472/?gmt
- **传统节日科普的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md?/751=572
- **智慧停车服务的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/0lOjpI.md?/zpr=345
- **健康饮水科普的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md
- **城市文明实践中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/e553d3fa64f805d9e8eddfe7367e1ceec6088754?/607
- **乡村生活观察的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/e553d3fa64f805d9e8eddfe7367e1ceec6088754?/tic
- **数字公共文化的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/e553d3fa64f805d9e8eddfe7367e1ceec6088754?/684/?zom
- **老年人文化生活有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/e553d3fa64f805d9e8eddfe7367e1ceec6088754?/603=831
- **亲子科普活动的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/e553d3fa64f805d9e8eddfe7367e1ceec6088754?/avp=299
- **街区绿化养护的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md?/506
- **便民服务窗口的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md?/scf
- **无障碍信息设计的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md?/057/?tyy
- **读书会组织的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md?/678=081
- **公共交通接驳的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/4wBzu9.md?/hcg=663
- **城市建设科普的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md
- **乡村产业科普的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/2ee94692db1bfac8480cf952dbbd52b1e50e1a0e?/379
- **城市宠物友好空间的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/2ee94692db1bfac8480cf952dbbd52b1e50e1a0e?/khk
- **乡村休闲旅游的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/2ee94692db1bfac8480cf952dbbd52b1e50e1a0e?/770/?spx
- **公共服务指南的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/commit/2ee94692db1bfac8480cf952dbbd52b1e50e1a0e?/019=035
- **公共卫生宣传的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/2ee94692db1bfac8480cf952dbbd52b1e50e1a0e?/wab=739
- **公益活动组织中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md?/162
- **社区知识分享的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md?/kuo
- **儿童友好空间的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md?/449/?urk
- **城市环境志愿行动的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md?/479=799
- **农贸市场环境的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/IiGRPk.md?/row=105
- **居家防滑改造的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md
- **小区停车协商的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/7bdc8da96b73154d8cecca58c874369315baba18?/284
- **文化讲座服务的实际需求与回应 |来源：https://github.com/wongtroy166/PpWk/commit/7bdc8da96b73154d8cecca58c874369315baba18?/pfa
- **数字资源检索的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/commit/7bdc8da96b73154d8cecca58c874369315baba18?/047/?bwi
- **城乡交流活动的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/7bdc8da96b73154d8cecca58c874369315baba18?/630=101
- **社区文化节活动有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/7bdc8da96b73154d8cecca58c874369315baba18?/ura=074
- **骑行路线规划的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md?/266
- **社区公共卫生的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md?/qgt
- **社区体育组织的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md?/327/?bwe
- **科普展览体验的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md?/555=711
- **青少年户外教育的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/gpn8fw.md?/rcf=819
- **传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md
- **数字阅读服务的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/f9c69e9f5aebe50621d1edc28aa30b1c48227766?/306
- **乡村生活观察的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/f9c69e9f5aebe50621d1edc28aa30b1c48227766?/ohu
- **老年人文化生活的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/f9c69e9f5aebe50621d1edc28aa30b1c48227766?/766/?knu
- **公共设施使用的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/f9c69e9f5aebe50621d1edc28aa30b1c48227766?/229=010
- **公园休闲体验的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/commit/f9c69e9f5aebe50621d1edc28aa30b1c48227766?/iqy=086
- **数字课堂应用的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md?/807
- **公交无障碍服务的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md?/mbz
- **便民维修服务有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md?/039/?nda
- **节日文化体验的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md?/529=591
- **社区活动报名的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/wtGmSP.md?/mym=731
- **科学运动指导的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md
- **在线教育体验的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/9f8cae1f4f64a98001fc8acd12ca7a3f320b6f7c?/755
- **城市博物馆服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/9f8cae1f4f64a98001fc8acd12ca7a3f320b6f7c?/gnd
- **社区安全巡查的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/9f8cae1f4f64a98001fc8acd12ca7a3f320b6f7c?/716/?mqm
- **全民健身活动的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/9f8cae1f4f64a98001fc8acd12ca7a3f320b6f7c?/779=286
- **城市基础设施的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/9f8cae1f4f64a98001fc8acd12ca7a3f320b6f7c?/fvv=787
- **乡村文化活动的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md?/566
- **城市微更新实践的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md?/ybh
- **居家防滑改造的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md?/437/?eoz
- **城市慢行系统的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md?/352=880
- **社区快递服务的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/ERvEwF.md?/ghy=973
- **数据分析入门的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md
- **地方旅游导览的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/9e45a12c9dc7098b014fbc9e7d7fa82be385e833?/632
- **居家适老化改造从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/9e45a12c9dc7098b014fbc9e7d7fa82be385e833?/rlf
- **农业科普体验的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/9e45a12c9dc7098b014fbc9e7d7fa82be385e833?/354/?bmo
- **城市水环境观察的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/9e45a12c9dc7098b014fbc9e7d7fa82be385e833?/297=603
- **家庭阅读计划中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/9e45a12c9dc7098b014fbc9e7d7fa82be385e833?/jnq=380
- **信息无障碍体验的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md?/418
- **家庭健康管理的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md?/gww
- **城市运动公园的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md?/030/?sjd
- **社区便利生活的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md?/411=732
- **城市慢行系统的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/RRxwOU.md?/dbs=212
- **食品配送体验的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md
- **小区电梯维护的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/3253e9428d139b41dead2ff41979e22bd14bb922?/306
- **城市休闲步道的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/3253e9428d139b41dead2ff41979e22bd14bb922?/tei
- **医院导诊服务从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/3253e9428d139b41dead2ff41979e22bd14bb922?/510/?ccj
- **社区宣传栏更新的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/3253e9428d139b41dead2ff41979e22bd14bb922?/526=675
- **邻里互助活动的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/3253e9428d139b41dead2ff41979e22bd14bb922?/tfx=170
- **智慧城市体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md?/977
- **志愿服务平台的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md?/tvh
- **传统节日科普的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md?/117/?jjl
- **基层健康档案的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md?/517=921
- **社区交通安全的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/b4iFSA.md?/vxu=614
- **社区托育服务的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md
- **乡村文化活动的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/commit/535a4cd542bd53aaa24f4260bf19ba059b67600f?/361
- **社区宣传栏更新的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/535a4cd542bd53aaa24f4260bf19ba059b67600f?/mwy
- **非遗体验活动的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/commit/535a4cd542bd53aaa24f4260bf19ba059b67600f?/305/?ine
- **社区商业活力的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/535a4cd542bd53aaa24f4260bf19ba059b67600f?/096=127
- **地方旅游导览的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/535a4cd542bd53aaa24f4260bf19ba059b67600f?/njd=676
- **社区绿色空间的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md?/772
- **社区防暑服务的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md?/lqg
- **绿色办公实践的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md?/081/?apw
- **城市住房服务的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md?/063=782
- **运动安全知识的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/CqQPvp.md?/xaw=477
- **图书馆亲子空间的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md
- **开放式学习空间的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/0e666d75801da8769cd7aa61b5699c80c028bb60?/326
- **校园安全教育的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/0e666d75801da8769cd7aa61b5699c80c028bb60?/qxw
- **图书馆亲子空间的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/0e666d75801da8769cd7aa61b5699c80c028bb60?/365/?omd
- **街区小店体验的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/0e666d75801da8769cd7aa61b5699c80c028bb60?/706=299
- **乡村教育资源的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/0e666d75801da8769cd7aa61b5699c80c028bb60?/hkz=964
- **应急物资管理的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md?/874
- **社区菜市场服务的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md?/uyf
- **社会体育指导的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md?/139/?krk
- **家庭健康管理的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md?/811=852
- **居家防滑改造的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/5gg0OE.md?/ufm=724
- **社区应急准备的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md
- **节能生活方式的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/0911cc23694fc2142f4837de3d54becfd9e71505?/301
- **文化场馆预约从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/0911cc23694fc2142f4837de3d54becfd9e71505?/qwm
- **家庭园艺实践的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/0911cc23694fc2142f4837de3d54becfd9e71505?/248/?zyu
- **社区艺术活动的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/0911cc23694fc2142f4837de3d54becfd9e71505?/524=399
- **数字素养提升的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/0911cc23694fc2142f4837de3d54becfd9e71505?/whs=861
- **社区花园共建的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md?/495
- **青少年科普实践的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md?/jdo
- **节约用水实践的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md?/529/?ewj
- **家庭科学教育的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md?/363=527
- **数字档案服务的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/tnpyH9.md?/hqv=356
- **科学教育活动的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md
- **生活服务数字化的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/f432fde7494236bfe6886d27cbfd0d624bfd886d?/652
- **家庭网络使用中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/f432fde7494236bfe6886d27cbfd0d624bfd886d?/thx
- **社区读书角建设从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/f432fde7494236bfe6886d27cbfd0d624bfd886d?/966/?eku
- **数字素养提升中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/f432fde7494236bfe6886d27cbfd0d624bfd886d?/825=743
- **健康饮食教育中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/f432fde7494236bfe6886d27cbfd0d624bfd886d?/qqs=200
- **城市人文观察的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md?/011
- **乡村生态观察从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md?/zzd
- **文化讲座服务的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md?/900/?vud
- **骑行路线规划的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md?/706=491
- **骑行路线规划的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/BX6qvd.md?/hfq=468
- **学校食育活动的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md
- **社区托育服务的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/082fe441c568f6f8888e216ae575d04c4d7f8f3e?/920
- **城市雨天出行的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/082fe441c568f6f8888e216ae575d04c4d7f8f3e?/fda
- **公益活动组织有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/082fe441c568f6f8888e216ae575d04c4d7f8f3e?/130/?zid
- **家庭健康科普的空间设计要点 |来源：https://github.com/wongtroy166/PpWk/commit/082fe441c568f6f8888e216ae575d04c4d7f8f3e?/337=808
- **公共服务数字化从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/082fe441c568f6f8888e216ae575d04c4d7f8f3e?/orj=862
- **城市文明实践的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md?/909
- **租房信息服务的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md?/wzl
- **公共服务咨询的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md?/113/?brz
- **便民服务窗口的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md?/144=528
- **图书馆亲子空间的家庭参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/quG3nN.md?/epu=711
- **学校体育活动的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md
- **无障碍信息设计的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/commit/10afe80b0b735535b7ad35ab0df4a576d7f876f7?/843
- **地方戏曲体验中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/10afe80b0b735535b7ad35ab0df4a576d7f876f7?/gaj
- **社区宣传栏更新的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/10afe80b0b735535b7ad35ab0df4a576d7f876f7?/254/?rav
- **城市公共标识的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/commit/10afe80b0b735535b7ad35ab0df4a576d7f876f7?/971=413
- **基层健康服务的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/10afe80b0b735535b7ad35ab0df4a576d7f876f7?/rat=871
- **公园休闲体验的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md?/296
- **远程协作工具的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md?/ohc
- **低碳社区实践的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md?/463/?ihv
- **智慧城市体验的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md?/904=868
- **科普展览体验的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/yJ1P0s.md?/ame=759
- **地方旅游导览的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md
- **公园亲子设施的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/2f536902de301fb5dfd8ccc4a230067d5fa97f7a?/407
- **软件开发学习的长期维护要点 |来源：https://github.com/wongtroy166/PpWk/commit/2f536902de301fb5dfd8ccc4a230067d5fa97f7a?/ang
- **便民服务窗口的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/commit/2f536902de301fb5dfd8ccc4a230067d5fa97f7a?/748/?nlz
- **开放数据应用的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/2f536902de301fb5dfd8ccc4a230067d5fa97f7a?/186=051
- **家庭节能实践的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/2f536902de301fb5dfd8ccc4a230067d5fa97f7a?/oyx=670
- **电动汽车充电的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md?/338
- **城市可持续生活的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md?/skn
- **城市夜间生活的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md?/214/?qna
- **图书馆数字服务中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md?/816=204
- **公园休闲体验的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/lhA0up.md?/rps=099
- **小区电梯维护的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md
- **社区商业活力的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/a2b644a123a1df177b287d4fc32f5c39bcfe264f?/919
- **音乐欣赏活动的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/a2b644a123a1df177b287d4fc32f5c39bcfe264f?/kgq
- **城市住房服务的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/a2b644a123a1df177b287d4fc32f5c39bcfe264f?/422/?lom
- **开源技术交流的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/a2b644a123a1df177b287d4fc32f5c39bcfe264f?/246=950
- **小区公共照明的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/commit/a2b644a123a1df177b287d4fc32f5c39bcfe264f?/fup=329
- **城市夜间照明的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md?/007
- **运动安全知识的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md?/alj
- **文化讲座服务有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md?/129/?cbl
- **青少年职业启蒙的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md?/097=050
- **社区科普课堂中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/OOhLDb.md?/nkn=440
- **儿童运动体验的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md
- **社区公共议事的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/c868a4069ddab5664be9d36e6e4bb83f78f2becd?/736
- **社区庭院绿化的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/c868a4069ddab5664be9d36e6e4bb83f78f2becd?/ywh
- **创业经验分享的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/c868a4069ddab5664be9d36e6e4bb83f78f2becd?/801/?hfl
- **公共空间照明的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/c868a4069ddab5664be9d36e6e4bb83f78f2becd?/372=728
- **社区公共餐饮的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/c868a4069ddab5664be9d36e6e4bb83f78f2becd?/ulh=328
- **乡村生态旅游的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md?/758
- **社区科普课堂的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md?/xjh
- **健康饮水科普的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md?/506/?nda
- **青少年户外教育的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md?/855=552
- **公共设施使用的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/blob/main/h5tUJo.md?/lco=506
- **生活垃圾回收的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md
- **乡村公共服务的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/commit/12982bedf53c2737a2baeacb8d2f9245b6becc3a?/547
- **小区公共照明的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/12982bedf53c2737a2baeacb8d2f9245b6becc3a?/doh
- **乡村文化活动的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/12982bedf53c2737a2baeacb8d2f9245b6becc3a?/303/?xtn
- **终身学习资源的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/12982bedf53c2737a2baeacb8d2f9245b6becc3a?/660=445
- **家庭节能实践的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/12982bedf53c2737a2baeacb8d2f9245b6becc3a?/chd=355
- **社区便利生活的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md?/300
- **城乡交流活动的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md?/ufj
- **科学观察活动的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md?/111/?rdj
- **家庭节能实践的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md?/194=519
- **科学观察活动中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/QE5rF8.md?/npo=278
- **图书馆数字服务的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md
- **节约用水实践的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/commit/016cd1cd54c5aada3e613257092712b7330f9f01?/099
- **城市绿道建设的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/016cd1cd54c5aada3e613257092712b7330f9f01?/lnv
- **社区活动策划的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/016cd1cd54c5aada3e613257092712b7330f9f01?/697/?qvf
- **城市公共饮水的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/016cd1cd54c5aada3e613257092712b7330f9f01?/350=682
- **家庭消费规划的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/commit/016cd1cd54c5aada3e613257092712b7330f9f01?/wld=339
- **课后服务体验的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md?/850
- **青少年科普实践的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md?/smk
- **城市公共饮水的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md?/025/?vqb
- **急救知识普及的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md?/361=427
- **社区科普课堂的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZHaEgy.md?/iyy=835
- **旧物循环利用的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md
- **公共卫生设施的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/0724e429d84485bc1d3207f1e90822b80e891bb9?/552
- **零废弃生活尝试的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/0724e429d84485bc1d3207f1e90822b80e891bb9?/rfo
- **社区活动策划的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/commit/0724e429d84485bc1d3207f1e90822b80e891bb9?/252/?sqg
- **个人信息保护的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/commit/0724e429d84485bc1d3207f1e90822b80e891bb9?/413=470
- **数字阅读服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/commit/0724e429d84485bc1d3207f1e90822b80e891bb9?/krv=642
- **社区设施共享的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md?/299
- **网络信息辨识的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md?/vlk
- **本地旅行体验的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md?/568/?fyv
- **公共空间照明的服务范围梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md?/169=857
- **口袋公园建设的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/hl1h9v.md?/wtp=582
- **通勤路线规划的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md
- **城市公共艺术的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/e66c17a48541e3c90c657c0319866eb80d5a582d?/222
- **劳动教育实践的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/e66c17a48541e3c90c657c0319866eb80d5a582d?/zab
- **文化遗产保护科普中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/commit/e66c17a48541e3c90c657c0319866eb80d5a582d?/576/?qpo
- **家庭志愿活动的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/e66c17a48541e3c90c657c0319866eb80d5a582d?/504=708
- **数字资源检索的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/e66c17a48541e3c90c657c0319866eb80d5a582d?/jui=360
- **绿色消费选择中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md?/723
- **社区邻里服务中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md?/lzm
- **社区宣传栏更新的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md?/437/?uhv
- **社区老年食堂从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md?/599=402
- **城市公共饮水的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/RcIin5.md?/ypi=304
- **节约用水实践的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md
- **食品安全科普的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/5e6b2ad79202b5adee1b8594b939e6b190032e50?/400
- **社区家校合作的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/5e6b2ad79202b5adee1b8594b939e6b190032e50?/kzn
- **绿色快递包装的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/5e6b2ad79202b5adee1b8594b939e6b190032e50?/181/?qlw
- **社区绿色空间的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/5e6b2ad79202b5adee1b8594b939e6b190032e50?/862=847
- **小区停车协商的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/5e6b2ad79202b5adee1b8594b939e6b190032e50?/kyw=129
- **城市游园体验的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md?/393
- **读书会组织的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md?/kpv
- **乡村教育资源的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md?/945/?omy
- **公共文化活动中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md?/644=044
- **智慧城市体验的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/XVSjPF.md?/jxx=143
- **公共服务数字化的实用信息清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md
- **校园阅读活动的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/commit/1ce648380f0a78f061a075cea30e35b826bcf31f?/917
- **数据分析入门中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/commit/1ce648380f0a78f061a075cea30e35b826bcf31f?/jgk
- **社区设施共享的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/1ce648380f0a78f061a075cea30e35b826bcf31f?/440/?hjm
- **社区生活指南的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/1ce648380f0a78f061a075cea30e35b826bcf31f?/686=325
- **社区公共卫生的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/1ce648380f0a78f061a075cea30e35b826bcf31f?/qet=543
- **就业技能培训的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md?/502
- **街区小店体验的服务质量观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md?/jhf
- **城市水环境观察中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md?/274/?xxf
- **公共设施维护的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md?/017=649
- **社区艺术活动的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/rvxcvT.md?/ith=210
- **家庭健康管理的公共参与指南 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md
- **城乡交通衔接的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/6c9d87893618a18ad4127cc510374e7adaf970bc?/465
- **开放式学习空间的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/6c9d87893618a18ad4127cc510374e7adaf970bc?/aiz
- **小区电梯维护的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/commit/6c9d87893618a18ad4127cc510374e7adaf970bc?/351/?whj
- **公共服务沟通的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/commit/6c9d87893618a18ad4127cc510374e7adaf970bc?/990=195
- **乡村公共服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/6c9d87893618a18ad4127cc510374e7adaf970bc?/utx=992
- **便民服务地图的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md?/505
- **节气饮食文化的组织方法与经验 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md?/mnt
- **家庭健康管理的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md?/244/?afh
- **城市文化路线的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md?/886=901
- **儿童户外活动的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/QHkVhy.md?/pnk=281
- **农产品品牌传播从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md
- **城市空气科普有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/96b98963785f3ca8fc506b6f895d416fc555898a?/498
- **城市农夫市集的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/commit/96b98963785f3ca8fc506b6f895d416fc555898a?/mxx
- **乡村休闲旅游的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/96b98963785f3ca8fc506b6f895d416fc555898a?/691/?rkc
- **社区故事采集的阅读与学习资源 |来源：https://github.com/wongtroy166/PpWk/commit/96b98963785f3ca8fc506b6f895d416fc555898a?/153=978
- **乡村电商实践的参与方式与路径 |来源：https://github.com/wongtroy166/PpWk/commit/96b98963785f3ca8fc506b6f895d416fc555898a?/pzg=823
- **城市应急广播的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md?/895
- **绿色生活实践的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md?/nyv
- **本地消费场景的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md?/824/?vyz
- **社区心理支持的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md?/195=561
- **低碳社区实践从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/yPZb8c.md?/ixl=614
- **城市展览体验的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md
- **远程协作工具的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/b7cb7ea1363070cf6db9b4ac834861233ba02074?/610
- **课后服务体验的便民做法梳理 |来源：https://github.com/wongtroy166/PpWk/commit/b7cb7ea1363070cf6db9b4ac834861233ba02074?/qbm
- **老年友好服务的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/b7cb7ea1363070cf6db9b4ac834861233ba02074?/860/?uyv
- **科技馆参观体验的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/commit/b7cb7ea1363070cf6db9b4ac834861233ba02074?/248=863
- **社区文化传播的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/b7cb7ea1363070cf6db9b4ac834861233ba02074?/wrn=844
- **数字便民地图的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md?/589
- **市民意见收集的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md?/lmx
- **数字公共文化的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md?/890/?nye
- **城市基础设施的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md?/693=980
- **线上办事服务的常见问题梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/YO7OPE.md?/gzm=340
- **家庭阅读计划的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md
- **无障碍信息设计的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/e6d80e7a1e1b80ebd1e2a62d7aa095a6b784a0f0?/400
- **公共服务预约的日常实践笔记 |来源：https://github.com/wongtroy166/PpWk/commit/e6d80e7a1e1b80ebd1e2a62d7aa095a6b784a0f0?/nqp
- **社区环保活动的活动组织技巧 |来源：https://github.com/wongtroy166/PpWk/commit/e6d80e7a1e1b80ebd1e2a62d7aa095a6b784a0f0?/599/?yfm
- **社区学习活动的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/e6d80e7a1e1b80ebd1e2a62d7aa095a6b784a0f0?/379=919
- **社会体育指导的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/commit/e6d80e7a1e1b80ebd1e2a62d7aa095a6b784a0f0?/esh=930
- **城市水环境观察的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md?/148
- **市民热线服务的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md?/lgf
- **智慧城市体验的使用门槛与改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md?/336/?vrm
- **社区生活指南的数字工具使用体验 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md?/633=887
- **社区活动策划的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/Jo16Cg.md?/ojl=621
- **数字公共文化中的沟通与协作 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md
- **药品使用科普的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/commit/e3d72e2dcc259cb10f0de7b419c9120d7c431907?/657
- **开放式学习空间的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/e3d72e2dcc259cb10f0de7b419c9120d7c431907?/rnv
- **城市夜间照明的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/e3d72e2dcc259cb10f0de7b419c9120d7c431907?/747/?avh
- **农村环境治理的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/e3d72e2dcc259cb10f0de7b419c9120d7c431907?/722=131
- **学校体育活动的日常使用指南 |来源：https://github.com/wongtroy166/PpWk/commit/e3d72e2dcc259cb10f0de7b419c9120d7c431907?/rpy=216
- **社区知识分享的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md?/402
- **社区停车服务的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md?/qga
- **线上阅读资源的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md?/841/?vob
- **社区公共餐饮的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md?/628=961
- **城市公共标识的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/0Ipfp7.md?/eic=239
- **街区更新实践有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md
- **城市农夫市集的基础知识问答 |来源：https://github.com/wongtroy166/PpWk/commit/9ec7a693d781413be1f530d59994e9e7d8df5c7f?/336
- **社区停车服务的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/9ec7a693d781413be1f530d59994e9e7d8df5c7f?/jmg
- **旧物循环利用的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/commit/9ec7a693d781413be1f530d59994e9e7d8df5c7f?/422/?tdj
- **社区消防演练的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/commit/9ec7a693d781413be1f530d59994e9e7d8df5c7f?/948=519
- **城市共享单车的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/9ec7a693d781413be1f530d59994e9e7d8df5c7f?/qoh=472
- **网络安全教育的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md?/273
- **公共服务数字化的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md?/fem
- **城市公共饮水中的几个关键细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md?/792/?ksn
- **校园社团活动的家庭实践清单 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md?/411=787
- **节气饮食文化的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/Ohyf49.md?/isj=574
- **社区停车服务的适老服务细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md
- **社区宠物管理有哪些值得关注的细节 |来源：https://github.com/wongtroy166/PpWk/commit/7b161d513c07ecaf95977a168af5eddc4e286422?/747
- **电动汽车充电的社区参与观察 |来源：https://github.com/wongtroy166/PpWk/commit/7b161d513c07ecaf95977a168af5eddc4e286422?/vua
- **市民热线服务的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/7b161d513c07ecaf95977a168af5eddc4e286422?/738/?geq
- **社区读书角建设的线下体验记录 |来源：https://github.com/wongtroy166/PpWk/commit/7b161d513c07ecaf95977a168af5eddc4e286422?/578=101
- **公共交通接驳的执行流程参考 |来源：https://github.com/wongtroy166/PpWk/commit/7b161d513c07ecaf95977a168af5eddc4e286422?/qxe=620
- **社区阅读服务的数字化应用观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md?/787
- **传统手工艺体验的流程优化思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md?/mwe
- **市民意见收集的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md?/186/?drd
- **生活垃圾回收的便捷程度观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md?/458=219
- **城市树木认养从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/blob/main/obhpKU.md?/tek=929
- **休闲运动入门的安全使用提示 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md
- **小微企业服务的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/commit/de03d7164ed2c87e3450e26e4b4c0481adf7c2a2?/454
- **邻里共享空间的持续改进方向 |来源：https://github.com/wongtroy166/PpWk/commit/de03d7164ed2c87e3450e26e4b4c0481adf7c2a2?/cml
- **基层健康档案的居民参与机会 |来源：https://github.com/wongtroy166/PpWk/commit/de03d7164ed2c87e3450e26e4b4c0481adf7c2a2?/035/?kuy
- **口袋公园建设的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/commit/de03d7164ed2c87e3450e26e4b4c0481adf7c2a2?/410=990
- **校园节能行动的服务信息整理 |来源：https://github.com/wongtroy166/PpWk/commit/de03d7164ed2c87e3450e26e4b4c0481adf7c2a2?/ilc=682
- **数字档案服务的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md?/454
- **小微企业服务的资源利用方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md?/ejv
- **老年人文化生活的设施维护观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md?/783/?pwj
- **数字支付体验的行动步骤参考 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md?/723=057
- **绿色生活实践的活动体验回顾 |来源：https://github.com/wongtroy166/PpWk/blob/main/ZVk1y8.md?/roy=575
- **社区体育组织的儿童友好细节 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md
- **社区花园共建的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/e3ef78f1642843846e2c664d4f9b6e8e3da82b4c?/108
- **社区艺术活动的服务细节记录 |来源：https://github.com/wongtroy166/PpWk/commit/e3ef78f1642843846e2c664d4f9b6e8e3da82b4c?/tdx
- **城市运动公园的便利性观察 |来源：https://github.com/wongtroy166/PpWk/commit/e3ef78f1642843846e2c664d4f9b6e8e3da82b4c?/456/?uku
- **市民热线服务的服务体验观察 |来源：https://github.com/wongtroy166/PpWk/commit/e3ef78f1642843846e2c664d4f9b6e8e3da82b4c?/761=777
- **青少年科技社团的绿色实践方法 |来源：https://github.com/wongtroy166/PpWk/commit/e3ef78f1642843846e2c664d4f9b6e8e3da82b4c?/fll=437
- **户外活动组织的便利性观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md?/610
- **城市夜间生活的活动策划思路 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md?/ibn
- **城市树木认养的协作机制梳理 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md?/348/?uwn
- **社区宣传栏更新的协商参与方式 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md?/423=677
- **儿童友好街区的服务反馈渠道 |来源：https://github.com/wongtroy166/PpWk/blob/main/mkFgli.md?/fos=746
- **城市公共空间的日常记录与分享 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md
- **城市公共厕所的入门知识整理 |来源：https://github.com/wongtroy166/PpWk/commit/dc21a5e8633321578ca78d012a42861109724c4d?/914
- **地方美食文化的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/commit/dc21a5e8633321578ca78d012a42861109724c4d?/cmo
- **乡村文化空间的资源整合思路 |来源：https://github.com/wongtroy166/PpWk/commit/dc21a5e8633321578ca78d012a42861109724c4d?/698/?fys
- **终身学习资源从使用体验看服务改进 |来源：https://github.com/wongtroy166/PpWk/commit/dc21a5e8633321578ca78d012a42861109724c4d?/953=421
- **信息无障碍体验的空间使用体验 |来源：https://github.com/wongtroy166/PpWk/commit/dc21a5e8633321578ca78d012a42861109724c4d?/goc=633
- **家庭急救准备的学习资源整理 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md?/894
- **社区便民服务的日常管理方法 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md?/sys
- **街道综合服务的常见误区提醒 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md?/209/?jnk
- **绿色办公实践的基础设施观察 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md?/080=480
- **社区家校合作的线上线下服务衔接 |来源：https://github.com/wongtroy166/PpWk/blob/main/4oBIfs.md?/adc=141
- **志愿者培训交流的社区行动案例 |来源：https://github.com/wongtroy166/PpWk/blob/main/wRuqrv.md
- **数字资源检索的公共信息获取方式 |来源：https://github.com/wongtroy166/PpWk/commit/2df3ca4f65bf4595040a8cc39460f307dc45b1c3?/484
- **社区读书角建设从需求出发看服务设计 |来源：https://github.com/wongtroy166/PpWk/commit/2df3ca4f65bf4595040a8cc39460f307dc45b1c3?/uid

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
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  所有75彩票下载等*  
*仅供参考，不构成投资建议*
