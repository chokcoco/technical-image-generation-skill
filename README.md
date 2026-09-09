# Technical Image Generation Skill / 技术插图生成 Skill

`technical-image-generation-skill` 用于制作有明确解释任务的技术插图。它定义了一套可复用的水彩信息图语言：米白纸纹、细墨线、低饱和蓝绿紫橙、编号卡片、清楚的箭头和克制的图例。

`technical-image-generation-skill` creates technical illustrations with a clear explanatory job. It defines a reusable watercolor-infographic language: off-white paper texture, fine ink outlines, muted blue/green/purple/orange, numbered cards, readable arrows, and restrained legends.

它不绑定任何产品、工作流或发布渠道。你可以把它用于文章、演示文稿、设计文档、产品说明、培训材料或技术复盘；前提是图片确实能让读者更快理解一个问题。

It is not tied to any product, workflow, or publication channel. Use it in articles, slide decks, design documents, product explainers, training material, or technical retrospectives, as long as the image genuinely helps readers understand a question faster.

## Skill Overview / Skill 总览

<img src="assets/technical-image-generation-overview-v1.png" alt="Technical Image Generation Skill overview with seven technical illustration families" width="100%">

这张总览图把七种解释任务放在同一张图里，并用底部图例强调清晰文字、结构关系和统一视觉语言。

This overview places the seven explanatory jobs in one visual and uses its bottom legend to emphasize readable copy, structural relationships, and one coherent visual language.

## What It Covers / 覆盖范围

- 全景概览与心智模型 / ecosystem overviews and mental models
- 流程、生命周期与反馈回路 / processes, lifecycles, and feedback loops
- 系统架构与边界说明 / system architecture and boundaries
- 方案对比与取舍 / option comparison and trade-offs
- 单一机制下钻 / single-mechanism deep dives
- 抽象概念的技术解释 / technical explanation of abstract concepts
- 数据趋势与决策提示 / data trends and decision cues

## How To Use / 使用方法

1. 阅读 [SKILL.md](SKILL.md)，明确图片要回答的问题，并选择对应的 `references/` 模板。
2. 写出一句话结论，列出必须逐字保留的文字。
3. 按模板填充内容，再用主 Skill 的 Prompt 框架组织成完整请求。
4. 生成后依照 [quality-checklist.md](references/quality-checklist.md) 检查文字、关系、版式与风格。
5. 每轮只修一个最影响理解的问题；连续三轮仍无改善时，缩小范围或拆图。

1. Read [SKILL.md](SKILL.md), state the question the visual must answer, and choose the relevant `references/` template.
2. Write the one-sentence takeaway and list text that must remain verbatim.
3. Fill the selected template, then assemble a complete request using the core prompt frame.
4. After generation, check copy, relationships, layout, and style with [quality-checklist.md](references/quality-checklist.md).
5. Repair only the single issue that most harms comprehension per round; after three unsuccessful rounds, narrow or split the visual.

## Sample Gallery / 样例展示

每个图型保留一张代表图。图片先以宫格展示，随后说明各图型的构图要点。

One representative image is kept for each illustration family. The grid appears first, followed by notes on each composition pattern.

### Images / 图片展示

<table>
<tr>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-process-v1.png" alt="Process technical illustration" width="100%">
<br/><strong>Process / 流程</strong>
<br/><sub>编号主路径与失败分支。<br/>Numbered primary path with failure branches.</sub>
</td>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-architecture-v1.png" alt="Architecture technical illustration" width="100%">
<br/><strong>Architecture / 架构</strong>
<br/><sub>组件、职责与关系边界。<br/>Components, responsibilities, and relationship boundaries.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-overview-pattern-v1.png" alt="Overview technical illustration" width="100%">
<br/><strong>Overview / 总览</strong>
<br/><sub>全局路径加一个局部放大区。<br/>Whole-system path with one bounded zoom-in.</sub>
</td>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-comparison-v1.png" alt="Comparison technical illustration" width="100%">
<br/><strong>Comparison / 对比</strong>
<br/><sub>固定维度下的选择与取舍。<br/>Choices and trade-offs on fixed dimensions.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-deep-dive-v1.png" alt="Deep-dive technical illustration" width="100%">
<br/><strong>Deep Dive / 机制下钻</strong>
<br/><sub>聚焦一个可追踪的局部机制。<br/>One traceable local mechanism.</sub>
</td>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-conceptual-explainer-v1.png" alt="Conceptual-explainer technical illustration" width="100%">
<br/><strong>Conceptual Explainer / 概念解释</strong>
<br/><sub>从直觉回到术语与适用边界。<br/>From intuition back to terms and scope.</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="assets/technical-image-generation-data-story-v1.png" alt="Data-story technical illustration" width="100%">
<br/><strong>Data Story / 数据故事</strong>
<br/><sub>指标、观察点与决策在同一路径上。<br/>Metrics, observations, and decisions on one path.</sub>
</td>
<td width="50%" valign="top"></td>
</tr>
</table>

### Process / 流程

编号主路径与失败分支。先读通主路径，再从底部或侧边回收异常、拒绝和反馈。

Numbered primary path with failure branches. Make the main path readable first, then collect exceptions, rejections, and feedback below or beside it.

### Architecture / 架构

组件、职责与关系边界。先稳定地划分组件和职责，再让连线解释协作关系。

Components, responsibilities, and relationship boundaries. Establish components and responsibilities first, then use connections to explain cooperation.

### Overview / 总览

全局路径加一个局部放大区。读者先获得全貌，再看到影响决策的局部机制。

A whole-system path with one bounded zoom-in. Readers see the whole first, then the local mechanism that affects the decision.

### Comparison / 对比

固定维度下的选择与取舍。用统一卡片、少量颜色和简短判断组织横向比较。

Choices and trade-offs on fixed dimensions. Use consistent cards, a small color vocabulary, and concise judgments for comparison.

### Deep Dive / 机制下钻

聚焦一个可追踪的局部机制，不试图概述整个系统。

Focus on one traceable local mechanism rather than attempting to summarize the whole system.

### Conceptual Explainer / 概念解释

从直觉回到术语与适用边界。概念图也需要说明范围，不能只留下好看的隐喻。

Move from intuition back to terms and scope. A conceptual illustration needs boundaries; it cannot stop at an attractive metaphor.

### Data Story / 数据故事

把指标、观察点与决策放在同一路径，并保留单位、基线和条件。

Put metrics, observation points, and decisions on one path while retaining units, baselines, and conditions.

## What Good Output Looks Like / 好图的标准

一张合格图不是“内容很多的漂亮图片”。它应让读者在几秒内知道主题，在半分钟内走完整条主路径，并能在回看时准确找到关键边界、反馈或例外。文字、数字与连线出错时，宁可重做，也不要拿“手绘感”搪塞。

A good output is not merely a pretty image with lots of content. Within seconds, readers should know the topic; within half a minute, they should be able to follow the primary path and find key boundaries, feedback, or exceptions on return. If copy, numbers, or connections are wrong, regenerate; “hand-drawn character” is not an excuse.

## Directory Layout / 目录结构

```text
technical-image-generation-skill/
├── SKILL.md
├── README.md
└── references/
    ├── architecture-support.md
    ├── comparison.md
    ├── conceptual-explainer.md
    ├── data-story.md
    ├── deep-dive.md
    ├── overview.md
    ├── process.md
    └── quality-checklist.md
```
