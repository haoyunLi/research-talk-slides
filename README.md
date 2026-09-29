# Research Talk Slides

一个帮助规划、制作和检查科研报告幻灯片的 Codex skill。它整理了 *Presentation Structure Guide.pages* 和 *St Marys Rd.m4a* 教学录音中的方法，重点是让听众从开场就能理解研究问题、意义和后续方法。

## 能做什么

- 默认按“背景与动机 → 意义与潜在影响 → 已有工作与缺口 → 一句话研究问题 → 方法概览”的顺序组织 slides，让每页自然引出下一页。
- 把研究问题写成一句话，并说明拟议工具或模型的输入与输出。
- 为每页确定一个核心信息，用简单的一句话作标题；只看标题也能大致读懂整套 slides 的逻辑。
- 用加粗、下划线或对比色突出少量关键词；只扫关键词也能抓住该页做了什么或发现了什么。
- 根据听众背景和报告时长调整细节。
- 检查研究问题、模型输出和声称的影响是否连得起来。

录音中的癌症免疫治疗与 enhancer 活性案例被整理为两种讲故事的示例：从重要问题出发，解释现有测量或分析的不足，再引出可用数据、具体研究目标和计算方法。更详细的提炼见 [source notes](references/source-notes.md)。

## 安装

将仓库克隆到 Codex 的 skills 目录：

```bash
git clone https://github.com/haoyunLi/research-talk-slides.git ~/.codex/skills/research-talk-slides
```

如果已经有同名目录，请先保留自己的修改，再更新其中的 `SKILL.md` 和 `references/source-notes.md`。

## 使用示例

在 Codex 中提出具体任务，并提供自己的研究材料、听众和时长。例如：

> 使用 research-talk-slides，帮我规划一个 20 分钟组会报告的开场。听众主要是计算生物学研究生。先给逐页提纲，不要制作幻灯片文件。

也可以请它检查现有 deck 的叙事、修改标题与过渡，或在明确提出时制作 slides。skill 会按请求产出提纲、幻灯片、讲稿或修改建议。

## 仓库内容

| 文件 | 内容 |
| --- | --- |
| [SKILL.md](SKILL.md) | Codex skill 的工作指引 |
| [references/source-notes.md](references/source-notes.md) | 页面指南与录音案例的提炼 |
