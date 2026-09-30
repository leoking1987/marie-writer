# Marie Writer

> 为 Marie Wang 打造的中文个人品牌写作 Skill：把真实经历、现场观察、清醒判断和高端房产审美，写成有生活感、可信、能自然转化的内容。

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827)
![Language](https://img.shields.io/badge/language-简体中文-dc2626)
![Focus](https://img.shields.io/badge/focus-Marie_Wang-c084fc)

## 它能做什么

`marie-writer` 用于创作、改写和审核 Marie Wang 的中文个人品牌内容，包括：

- YouTube 长视频与短视频口播稿
- 小红书、朋友圈和社交媒体长文
- 豪宅与社区实拍
- 湾区房产分析、卖房案例与客户决策内容
- 创业复盘、女性成长与个人品牌内容
- Marie 与 Kevin 的双人对谈稿

它不是替 Marie 写一篇“漂亮但不像她”的公司稿，而是让内容听起来像 Marie 本人在说话：有具体经历，有现场细节，有清楚判断，也愿意承认代价、硬伤和复杂性。

## Marie 的声音

| 维度 | 标准 |
|---|---|
| 真诚 | 只使用有来源的真实经历，敢谈失败、疲惫、误判和代价 |
| 清醒 | 不歌颂无效吃苦，关注方向、成本、适配和机会成本 |
| 锋利 | 结论明确、有边界，不靠攻击别人显得有观点 |
| 有生命力 | 对事业、空间、材质、阳光和更好生活有真实热情 |
| 有画面 | 用动作、场景、数字和感官细节代替空洞形容词 |
| 有判断 | 不只罗列信息，要说明适合谁、不适合谁、为什么 |
| 有分寸 | 不编客户、不泄露隐私、不保证涨价、不制造假稀缺 |

## 内容原则

- **先解决一个真实问题。** 每段都要增加新事实、差异、原因、取舍标准或行动。
- **逻辑清楚优先。** 只读各段首句，也应能看懂整篇推理。
- **信息密、说得顺。** 每段推动同一个决定，口述一遍能听懂；三项质量门槛高于固定模板、故事感、金句、案例与 CTA。
- **完整脚本不注水。** 按核心取舍分配篇幅，不擅自缩成短视频，不靠学校名单、重复提醒和冗长开头凑时长；情境稿按已发生与待决事项的时间顺序推进。
- **故事必须有用。** 真实故事只在能解释判断变化时出现，不为“故事感”硬加情节。
- **审美必须具体。** 不只说高级、奢华、绝美，要写光线、动线、材质、隐私、维护和实际体验。
- **优点与代价同时存在。** Marie 的专业感来自能看见硬伤，不来自把一切说成完美。
- **转化必须自然。** 先交付观点或决策价值，再决定是否需要一个相关 CTA。
- **汇总、逐笔价格和详细案例都可以引用。** 31 笔成交价中的任意一笔都可按地区、价位或房型单独使用；五笔另有完整过程细节，可按主题展开。精确比较必须核验日期、面积与房况，不能补造缺失字段。

## 动笔前的写法选择

房产决策型口播或结构性改写，若尚未指定写法，先展示 2–4 张预览卡：真实口吻的开场样稿、段落骨架、素材缺口和效果预估。用户选择后按该骨架成稿，Marie 的口吻、事实与隐私规则仍然适用。

流程、十一种方法卡、判断力方法论和预估规则已内置，无需另装 `script-angle`。已指定写法、局部润色、审核、小红书短帖或创业成长等非房产口播内容会跳过选择流程。留存预估是结构判断，不是实测保证；不能把示例数字或模拟情境写成 Marie 的真实客户经历。

## 安装

### 让 Codex 安装

把仓库地址发给 Codex，并告诉它：

```text
请从 https://github.com/leoking1987/marie-writer 安装 marie-writer Skill。
```

### 手动安装

macOS / Linux：

```bash
git clone https://github.com/leoking1987/marie-writer.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/marie-writer"
```

Windows PowerShell：

```powershell
git clone https://github.com/leoking1987/marie-writer.git `
  "$env:USERPROFILE\.codex\skills\marie-writer"
```

安装完成后，在支持 Skills 的 Codex 环境中通过 `$marie-writer` 调用。

## 使用示例

### 豪宅实拍

```text
使用 $marie-writer，写一条 Palo Alto 豪宅实拍口播稿。
重点讲采光、动线、后院和隐私的真实取舍，
不要只堆“高级、顶级、奢华”等形容词。
```

### 卖房案例

```text
使用 $marie-writer，把这组真实成交资料写成案例复盘。
区分 Marie 亲自做的事和团队完成的事，保护客户隐私，
只保留能解释结果的困难、动作和证据。
```

### 地区成交价引用

```text
使用 $marie-writer，写一条 Palo Alto 不同房型价格差异的口播。
从 transaction-cases.md 的 31 笔逐笔索引选择相关成交价，
成交价可以单独引用；只有需要解释过程时才展开五笔详细案例。
```

### 创业与成长

```text
使用 $marie-writer，写一篇 Marie 关于第一次创业失败的朋友圈长文。
从具体瞬间开始，写清真实代价和认知变化，
不要写成“失败后逆袭”的成功学故事。
```

### 审核现有稿件

```text
使用 $marie-writer 审核这篇稿子。
检查它是否像 Marie 本人在讲话，是否有具体场景和判断，
有没有公关腔、AI 排比、虚构亲历或强压销售。
```

## 项目结构

```text
marie-writer/
├── AGENTS.md
├── README.md
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── content-playbook.md
    ├── persona.md
    ├── script-angle/
    │   ├── guide.md
    │   ├── conversion-score.md
    │   ├── ledger-template.md
    │   ├── method-cards.md
    │   └── methodology.md
    ├── transaction-cases.md
    └── voice-guide.md
```

- [`SKILL.md`](SKILL.md)：工作流、事实边界、案例使用规则和交付标准。
- [`AGENTS.md`](AGENTS.md)：仓库维护规则，以及 README 强制同步要求。
- [`persona.md`](references/persona.md)：Marie 的人物定位、人生主线、价值观和内容母题。
- [`voice-guide.md`](references/voice-guide.md)：口语节奏、故事方法、审美表达、锋利度和禁忌。
- [`content-playbook.md`](references/content-playbook.md)：内容结构、标题开头、平台适配和 CTA。
- [`transaction-cases.md`](references/transaction-cases.md)：31 笔去地址成交价格索引、团队业绩汇总，以及五笔可按主题展开的完整交易案例。
- [`script-angle/guide.md`](references/script-angle/guide.md)：动笔前的写法筛选、预览卡和用户选择流程；配套资料按需读取。

## 事实与隐私边界

- 只有来源明确的经历，才能写成 Marie 的第一人称经历。
- 团队完成的事写“我们”或“团队”，不能自动改成“我”。
- 客户案例默认去标识化，不披露可反推身份、公司、职位、住址或交易组合的信息。
- 房价、库存、利率、税务、法规和市场排名等时效信息，需要重新核验日期与口径。
- 案例只有能直接证明当前观点时才出现；不相关时宁可不用。
- 无法核验的关键事实使用 `[待确认：…]`，不能伪装成成稿事实。

## 规则优先级

发生冲突时，按以下顺序执行：

1. 用户在当前任务中的明确要求
2. 事实核验与隐私边界（不能用风格或模板豁免）
3. `SKILL.md` 的出品最高优先级：逻辑清楚、信息密、说得顺
4. `SKILL.md` 工作流、人物底盘与声音规则
5. 用户选定的写法骨架，再由内容结构手册补充包装与平台适配

成交案例还必须遵守 `references/transaction-cases.md` 中的事实与公开边界。

## 维护约定

`README.md` 必须与 Skill 同步维护。凡是修改 `SKILL.md`、`agents/`、`references/`、`scripts/` 或 `assets/`，都必须在同一轮工作、同一个提交中：

1. 更新 README 中受影响的能力说明、规则、目录和使用示例；
2. 清理失效链接、过期路径和与当前 Skill 冲突的旧描述；
3. 运行 Skill 校验并检查 README 的本地链接；
4. 即使 README 正文无需改写，也要更新下方同步日期，留下已复核的记录。

详细执行规则见 [`AGENTS.md`](AGENTS.md)。

**最近同步：2026-09-30（出品优先级、内置写法选择与 31 笔成交引用规则已复核）**

## 其他智能体

这个仓库采用 Codex Skill 结构。其他智能体如果不支持 Skill 自动发现，仍可读取 `SKILL.md` 和 `references/` 作为项目级写作规范，但能否自动调用取决于具体客户端。

## 更新

在 Skill 目录执行：

```bash
git pull origin main
```

仓库地址：<https://github.com/leoking1987/marie-writer>
