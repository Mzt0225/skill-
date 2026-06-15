# 经管类 AI 论文写作 Skill 新手指南

> 面向经济学、金融学、管理学、会计学等经管类专业研究者，零基础学会用 Claude Code Skill 辅助论文写作、文献检索、文献综述和图表设计。
>
> 最后更新：2026-06-15

---

## 目录

- [什么是 Skill，为什么要用](#什么是skill为什么要用)
- [Skill 怎么用：30 秒上手](#skill-怎么用30-秒上手)
- [适用人群](#适用人群)
- [Skill 全家福（6 个已安装）](#skill-全家福6-个已安装)
- [按场景查 Skill](#按场景查-skill)
- [推荐工作流](#推荐工作流)
- [如何安装这些 Skill](#如何安装这些-skill)
- [常见问题](#常见问题)

---

## 什么是 Skill，为什么要用

**Skill 是 Claude Code（AI 编程助手）的"专业技能包"。** 你可以把它理解成：

> 🧠 就像给你的 AI 助手装了一个"经管论文写作博士"的脑子——它会自动遵循顶级期刊的写作规范、经济学家公认的表达习惯、以及中英文顶刊的格式要求，而不是凭空瞎编。

**没有 Skill 时：** AI 只能给你通用的写作建议，不了解经济学论文的特殊规范（如识别策略怎么写、三线表怎么画、DID 结果怎么表述）。

**装上 Skill 后：** AI 会按照 50+ 位顶级经济学家（Cochrane, McCloskey, 季刊/经济研究规范）总结的方法论来写作和审查你的论文。

### Skill 能帮你做什么

| 场景 | 不用 Skill | 用 Skill |
|------|-----------|---------|
| 写引言 | "AI写的太泛了，没经济学味道" | 自动遵循报纸风格、先结论后细节 |
| 写识别策略 | "AI根本不懂DID/RD/IV怎么写" | 按计量规范解释识别假设和威胁 |
| 文献综述 | "搜到的都是水刊，还得自己筛" | 只收录SCI/SSCI，自动按ABS/JCR分级 |
| 中文论文 | "翻译腔太重，不像中文论文" | 按季刊/经济研究风格写，去除AI腔 |
| 制表制图 | "这个表格不符合三线表规范" | 自动检查表注、列数、面板格式 |
| 全文润色 | "要一行一行改，太累了" | 按清单逐项审查，给出具体修改建议 |

---

## Skill 怎么用：30 秒上手

### 第 1 步：打开终端，进入你的项目目录

```bash
cd /d/你的论文项目路径
claude
```

### 第 2 步：在 Claude Code 对话框中，输入 `/` + skill 名 + 你的需求

```
/econ-write 帮我写一篇关于最低工资对就业影响的论文引言
```

就这么简单。AI 会自动加载对应的 skill 知识库，按规范输出。

### 三个最常用的命令格式

```bash
# 格式 1：直接让 AI 写
/econ-write 写一段DID模型的识别策略说明

# 格式 2：让 AI 审查/修改已有内容
/econ-write 审查我的结果部分，检查风格问题

# 格式 3：让 AI 对已有文件操作
/econ-write 读取我的paper.tex，修改引言部分
```

> 💡 **提示：** Skill 名可以不用全打，输入 `/econ` 然后按 Tab 会自动补全。名字对就行，大小写无所谓。

---

## 适用人群

这套 Skill 专为以下场景设计：

| 适用领域 | 具体专业 |
|---------|---------|
| 经济学 | 劳动经济学、发展经济学、环境经济学、产业组织、宏观经济学、微观经济学 |
| 金融学 | 公司金融、资产定价、银行学、金融科技 |
| 管理学 | 战略管理、组织行为、市场营销、运营管理 |
| 会计学 | 财务会计、管理会计、审计 |
| 统计学/计量 | 应用计量、预测方法、政策评估 |
| 交叉学科 | 机器学习+经济、计算社会科学 |

**适用论文类型：** 实证论文（DID/RD/IV/面板）、理论模型、结构估计、混合方法、描述性研究

**适用阶段：** 课程论文 → 工作论文 → 期刊投稿 → 审稿回复 → 学位论文

---

## Skill 全家福（6 个已安装）

### 总览

| # | Skill 名 | 一句话说明 | 语言 | GitHub |
|---|----------|-----------|------|--------|
| 1 | `econ-writing-workflow` | 论文写作总管家，编排全流程 | 中/英 | [链接](https://github.com/juliaError/econ-TopJournal-writing-Skill) |
| 2 | `econ-write` | 英文论文写作专家（50+经济学家方法论） | 英文 | [链接](https://github.com/juliaError/econ-TopJournal-writing-Skill) |
| 3 | `cn-top-econ-writing` | 中文顶刊论文写作（季刊/经济研究风格） | 中文 | [链接](https://github.com/juliaError/econ-TopJournal-writing-Skill) |
| 4 | `econ-table-figure-design` | 表格图表设计规范 | 中/英 | [链接](https://github.com/juliaError/econ-TopJournal-writing-Skill) |
| 5 | `literature-review-econ-skill` | 英文文献搜索与综述（SCI/SSCI） | 英文 | [链接](https://github.com/caodoudou99/literature-review-econ-skill) |
| 6 | `academic-research-skills` | CNKI/Google Scholar/Nature等40个搜索插件 | 中/英 | [链接](https://github.com/YuanyuanMa03/academic-research-skills) |

---

### 1. `econ-writing-workflow` — 论文写作总管家

**GitHub：** https://github.com/juliaError/econ-TopJournal-writing-Skill

**一句话：** 不知道从哪里开始写论文？从这里进入，它会帮你规划全流程并路由到对应的子 skill。

**能做什么：**
- 从研究问题 + 结果包 → 生成完整论文大纲
- 按顺序起草各章节
- 全文论证逻辑审查
- 中英文风格切换
- 自动调用子 skill（econ-write / cn-top-econ-writing / econ-table-figure-design）

**使用案例：**

```
/econ-writing-workflow 我有DID回归结果，研究题目是数字金融对农村消费的影响，帮我规划写作流程
/econ-writing-workflow 审查我的论文整体论证结构，看逻辑是否严密
/econ-writing-workflow 将这篇英文论文改写为中文，目标《经济学（季刊）》
/econ-writing-workflow 检查全文英文是否地道，去除AI腔和翻译腔
```

---

### 2. `econ-write` — 英文论文写作

**GitHub：** https://github.com/juliaError/econ-TopJournal-writing-Skill

**一句话：** 用 50+ 位顶级经济学家的标准来写/改你的英文论文。

**能做什么：**
- 写摘要、引言、文献综述、理论部分、实证部分、结论
- 解释识别策略（DID, RD, IV, FE, Bunching 等）
- 审查全文风格问题
- LaTeX 格式检查
- 审稿意见回复
- 按特定期刊风格调整（如 Journal of Development Economics, Research Policy）

**使用案例：**

```
/econ-write write a clear introduction for my paper on minimum wage and employment
/econ-write rewrite this abstract, it's too vague right now
/econ-write review my results section for style violations
/econ-write explain the identification strategy for my fuzzy RD design
/econ-write draft a referee response letter for reviewer #2's comments
/econ-write check this manuscript for LaTeX formatting errors
```

---

### 3. `cn-top-econ-writing` — 中文顶刊写作

**GitHub：** https://github.com/juliaError/econ-TopJournal-writing-Skill

**一句话：** 按《经济学（季刊）》《经济研究》《管理世界》《中国工业经济》等中文顶刊规范写论文。

**能做什么：**
- 中国特色问题导向与政策含义框定
- 中文摘要 + 英文 Summary 规范写作
- 论证逻辑审查（中文论文特有的论证结构）
- 中文措辞润色，去除 AI 翻译腔
- 期刊投稿格式检查
- 中英文转换适配

**使用案例：**

```
/cn-top-econ-writing 帮我润色这篇论文的中文摘要，要符合《经济学（季刊）》风格
/cn-top-econ-writing 审查我的引言，看是否体现了中国特色制度背景
/cn-top-econ-writing 将这篇英文论文的贡献框定改写为中文语境
/cn-top-econ-writing 检查全文中文措辞，去除AI翻译腔，使其像学者写的
/cn-top-econ-writing 按照《经济研究》的格式调整论文结构
/cn-top-econ-writing 帮我写引言——碳市场对制造业企业减排的影响
```

---

### 4. `econ-table-figure-design` — 表格图表设计

**GitHub：** https://github.com/juliaError/econ-TopJournal-writing-Skill

**一句话：** 让表格图表达到发表级质量。

**能做什么：**
- 三线表规范检查与自动格式化
- 主回归表、稳健性检验表、异质性表、机制表设计
- 表注写作规范
- 事件研究图 (Event Study)、趋势图、Binscatter、地图设计
- 配色方案（含黑白打印兼容）
- 发表级导出质量检查

**使用案例：**

```
/econ-table-figure-design 按照三线表规范格式化我的主回归表
/econ-table-figure-design 设计一张展示DID动态效应的event study图
/econ-table-figure-design 检查我的异质性分析表，表注是否完整
/econ-table-figure-design 为论文设计配色方案，确保黑白打印也可读
/econ-table-figure-design 按《经济学（季刊）》规范检查所有图表
```

---

### 5. `literature-review-econ-skill` — 英文文献综述

**GitHub：** https://github.com/caodoudou99/literature-review-econ-skill

**一句话：** 搜索 SCI/SSCI 高水平文献，提取关键信息，写结构化综述。

**能做什么：**
- 搜索 30-50 篇高质量英文文献（SCI/SSCI + ABS/JCR 分级筛选）
- 自动排除水刊（Sustainability, Energies 等）
- 提取研究问题、数据、方法、识别策略、发现
- 按主题/方法/机制分组比较
- 输出 APA / GB/T 7714 / Harvard 引用格式
- 写英文综述段落

**使用案例：**

```
/literature-review-econ-skill 搜索30篇关于 carbon tax and innovation 的SCI/SSCI文献
/literature-review-econ-skill 搜索ESG rating divergence的文献，按研究方法分组比较
/literature-review-econ-skill 搜索fintech and household consumption的实证研究，写综述
/literature-review-econ-skill 根据这15篇论文，提取每篇的问题、方法、数据和结论
/literature-review-econ-skill 用GB/T 7714格式列出参考文献
```

> ⚠️ 该 skill 默认只搜英文 SCI/SSCI 期刊。如需中文文献（CNKI），请安装下面的 academic-research-skills 插件。

---

### 6. `academic-research-skills` — 多平台文献搜索插件集

**GitHub：** https://github.com/YuanyuanMa03/academic-research-skills

**一句话：** 40 个插件覆盖 CNKI、Google Scholar、Nature、ScienceDirect、Web of Science 五大平台。

**包含的插件：**

| 平台 | 数量 | 主要功能 |
|------|------|---------|
| **CNKI（知网）** | 10 | 搜索、高级搜索、下载全文、导出引用、期刊索引、论文详情 |
| **Google Scholar** | 6 | 搜索、被引查询、导出引用、全文获取 |
| **Nature** | 9 | 搜索、写作润色、审稿回复、论文转PPT、文献阅读 |
| **ScienceDirect** | 8 | 搜索、下载、导出、期刊浏览 |
| **Web of Science** | 7 | 搜索、导出、下载、论文详情 |

**安装方式（在 Claude Code 对话框输入）：**

```
/plugin marketplace add YuanyuanMa03/academic-research-skills
/plugin install cnki-search@academic-research-skills
/plugin install cnki-advanced-search@academic-research-skills
/plugin install cnki-download@academic-research-skills
/plugin install cnki-export@academic-research-skills
/plugin install cnki-journal-index@academic-research-skills
/plugin install cnki-journal-search@academic-research-skills
/plugin install cnki-journal-toc@academic-research-skills
/plugin install cnki-navigate-pages@academic-research-skills
/plugin install cnki-paper-detail@academic-research-skills
/plugin install cnki-parse-results@academic-research-skills
/plugin install gs-search@academic-research-skills
/plugin install gs-advanced-search@academic-research-skills
/plugin install gs-cited-by@academic-research-skills
/plugin install gs-export@academic-research-skills
/plugin install gs-fulltext@academic-research-skills
/plugin install gs-navigate-pages@academic-research-skills
/plugin install nature-writing@academic-research-skills
/plugin install nature-polishing@academic-research-skills
/plugin install nature-reader@academic-research-skills
/plugin install nature-response@academic-research-skills
/plugin install nature-paper2ppt@academic-research-skills
/plugin install nature-academic-search@academic-research-skills
/plugin install nature-citation@academic-research-skills
/plugin install nature-data@academic-research-skills
/plugin install nature-figure@academic-research-skills
/plugin install sd-search@academic-research-skills
/plugin install sd-advanced-search@academic-research-skills
/plugin install sd-download@academic-research-skills
/plugin install sd-export@academic-research-skills
/plugin install sd-journal-browse@academic-research-skills
/plugin install sd-navigate-pages@academic-research-skills
/plugin install sd-paper-detail@academic-research-skills
/plugin install sd-parse-results@academic-research-skills
/plugin install wos-search@academic-research-skills
/plugin install wos-dom@academic-research-skills
/plugin install wos-download@academic-research-skills
/plugin install wos-export@academic-research-skills
/plugin install wos-navigate-pages@academic-research-skills
/plugin install wos-paper-detail@academic-research-skills
/plugin install wos-parse-results@academic-research-skills
```

---

## 按场景查 Skill

> 💡 不知道用哪个 Skill？对着下表找到你的场景。

| 我想做什么 | 用什么 Skill |
|-----------|-------------|
| 从零开始写一篇论文 | `/econ-writing-workflow` → 它会引导你用其他 skill |
| 写/改英文引言 | `/econ-write` |
| 写/改中文引言 | `/cn-top-econ-writing` |
| 解释我的识别策略 | `/econ-write` 或 `/cn-top-econ-writing` |
| 写英文文献综述 | `/literature-review-econ-skill` |
| 在知网搜中文文献 | CNKI 插件（需先安装） |
| 在 Google Scholar 搜文献 | GS 插件（需先安装） |
| 画三线表 | `/econ-table-figure-design` |
| 画事件研究图 | `/econ-table-figure-design` |
| 检查英文论文风格 | `/econ-write review my ...` |
| 检查中文论文风格 | `/cn-top-econ-writing 审查...` |
| 回复审稿人 | `/econ-write draft referee response...` |
| 检查表格是否规范 | `/econ-table-figure-design` |
| 写 LaTeX 公式/格式 | `/econ-write` |
| 整篇论文润色 | `/econ-writing-workflow` |
| 中文论文全文审查 | `/cn-top-econ-writing` |
| 适配特定期刊风格 | `/econ-write` 或 `/cn-top-econ-writing` |

---

## 推荐工作流

### 工作流 A：从零开始写英文论文

```
第1步  /literature-review-econ-skill  搜索相关文献，确认研究空白
第2步  /econ-writing-workflow         规划写作流程，生成大纲
第3步  /econ-write                    写摘要 + 引言
第4步  /econ-write                    写文献综述（结合第1步结果）
第5步  /econ-write                    写理论/制度背景 + 识别策略
第6步  /econ-write                    写实证部分（数据、方法、结果）
第7步  /econ-table-figure-design      设计/检查表格图表
第8步  /econ-write                    写结论
第9步  /econ-writing-workflow         全文审查
```

### 工作流 B：从零开始写中文论文

```
第1步  /cn-top-econ-writing          确认中国特色问题导向
第2步  /econ-writing-workflow         规划写作流程
第3步  /cn-top-econ-writing           写中文摘要 + 引言
第4步  /cn-top-econ-writing           写制度背景 + 文献综述
第5步  /cn-top-econ-writing           写识别策略 + 实证分析
第6步  /econ-table-figure-design      按中文期刊规范制表
第7步  /cn-top-econ-writing           写结论与政策含义
第8步  /cn-top-econ-writing           全文风格审查 + 去AI腔
```

### 工作流 C：修改/润色现有论文

```
第1步  /econ-writing-workflow         评估整体论证结构
第2步  /econ-write 或 cn-top-econ-writing  逐节修改
第3步  /econ-table-figure-design      检查图表规范
第4步  /econ-write 或 cn-top-econ-writing  最终全文润色
```

### 工作流 D：纯文献综述

```
第1步  /literature-review-econ-skill  搜索 + 筛选 + 做成对比矩阵
第2步  /literature-review-econ-skill  写英文综述段落
第3步  /econ-write                    将综述整合进论文的 Related Literature
```

---

## 如何安装这些 Skill

### 一键安装（推荐）

```bash
# 1. econ-writing-workflow / econ-write / cn-top-econ-writing / econ-table-figure-design
git clone --depth 1 https://github.com/juliaError/econ-TopJournal-writing-Skill.git /tmp/s1
cp -r /tmp/s1/skills/econ-writing-workflow ~/.claude/skills/
cp -r /tmp/s1/skills/econ-write ~/.claude/skills/
cp -r /tmp/s1/skills/cn-top-econ-writing ~/.claude/skills/
cp -r /tmp/s1/skills/econ-table-figure-design ~/.claude/skills/
rm -rf /tmp/s1

# 2. literature-review-econ-skill
git clone --depth 1 https://github.com/caodoudou99/literature-review-econ-skill.git /tmp/s2
cp -r /tmp/s2/literature-review-econ-skill ~/.claude/skills/
rm -rf /tmp/s2

# 3. 刷新
# 在 Claude Code 中输入: /reload-skills
```

### 安装到项目级别

如果想只在某个项目中使用（不影响全局），把 `~/.claude/skills/` 替换为 `你的项目路径/.claude/skills/`。

### 验证安装

在 Claude Code 中：

```
/reload-skills
```

如果看到 skill 列表中出现以上名称，说明安装成功。

---

## 常见问题

**Q: Skill 和 ChatGPT 的 GPTs 有什么区别？**

A: Skill 是 Claude Code 的专业知识包，它直接嵌入在你的编程环境中，可以读写你的本地文件（论文 .tex/.md/.docx），而 GPTs 是网页端的对话机器人。Skill 可以审查你的整篇论文文件，GPTs 只能处理你粘贴的文本。

**Q: 需要付费吗？**

A: 所有 Skill 都是开源的（GitHub 免费下载）。Claude Code 本身需要 Anthropic API 费用或订阅。

**Q: 中文 skill 效果好吗？**

A: `cn-top-econ-writing` 专门针对《经济学（季刊）》《经济研究》等中文顶刊优化，在措辞、论证逻辑、政策含义等方面表现优于通用 AI。建议使用后仍需人工审读。

**Q: 文献综述 skill 能搜中文文献吗？**

A: `literature-review-econ-skill` 默认只搜英文 SCI/SSCI。如需中文文献（CNKI），请安装 `academic-research-skills` 插件集。

**Q: 这些 skill 会冲突吗？**

A: 不会。它们是相互配合的——`econ-writing-workflow` 是总管家，在需要时会提示你使用对应的子 skill。你也可以随时独立调用任何一个。

---

## 补充推荐（未安装）

| 项目 | 说明 | GitHub |
|------|------|--------|
| efficient-literature-survey | 10-100篇文献PDF→结构化综述，原生支持CNKI加密PDF | [链接](https://github.com/namooubn/efficient-literature-survey) |
| agent-research-skills | 31个skill的全流程学术研究包 | [链接](https://github.com/lingzhi227/agent-research-skills) |

---

> 📌 **一句话总结：** 这套 Skill 让 AI 从"通用写作助手"变成"经管领域论文专家"——它知道顶级期刊的标准、经济学家的写作习惯、以及中英文各自的行文规范。装上它，你的 AI 才真正懂经管论文。
