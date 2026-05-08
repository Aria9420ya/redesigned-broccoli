# COF PEM Research Prompt Library

Use these prompts to activate the research system in this repository.

## Universal Wake-Up Prompt

用 COF PEM research skill，并读取这个项目的 `research_system` 知识库。所有文献信息必须按 `evidence_register.md` 标注证据等级；没有核实的内容不要当事实。现在帮我处理下面这个任务：

## Find Literature

用 COF PEM research skill，围绕“COF 静电纺丝质子交换膜/燃料电池膜”查找近 3-5 年高相关文献。要求：

- 优先找综述、COF/Nafion、COF/PFSA、COF/SPEEK、COF/静电纺丝、低湿/高温 PEM 文献。
- 每篇给 DOI、题名、年份、期刊、为什么相关。
- 按 `Verified-primary`、`Abstract-only`、`To verify` 标证据等级。
- 更新 `literature_matrix.md` 和 `evidence_register.md`。

## Add DOI

用 COF PEM research skill，核查这些 DOI，并加入知识库：

DOI:

- 

要求：

- 先核查题名、作者、期刊、年份、DOI。
- 能看到全文就提取实验条件；只能看到摘要就标 `Abstract-only`。
- 更新 `evidence_register.md`。
- 如果与研究方向高度相关，更新 `literature_matrix.md` 并生成 paper note。

## Read PDF

用 COF PEM research skill，精读这个 PDF，并按知识库标准提取信息：

文件路径：

要求：

- 生成 paper note。
- 提取材料体系、制备路线、对照组、关键数据、测试条件、机制解释、复现风险。
- 更新 `evidence_register.md`、`literature_matrix.md` 和必要的 benchmark table。
- 不确定或缺失的字段必须标出来。

## Extract Useful Information

用 COF PEM research skill，从这篇文献中提取对我有用的信息。重点不是普通摘要，而是：

- 这篇文献解决了什么科学问题。
- 它的材料体系和结构设计是什么。
- 关键实验条件和数据是什么。
- 哪些数据可以和我的路线比较。
- 哪些地方不能直接相信或需要复现验证。
- 对我的实验路线有什么启发。

## Compare Papers

用 COF PEM research skill，比较这些文献：

文献/DOI/PDF：

比较维度：

- COF 类型和功能基团
- 聚合物/支撑体
- 是否静电纺丝
- 质子传导机制
- RH/温度/膜厚/测试方向
- 溶胀、吸水率、IEC、机械性能
- MEA 或燃料电池性能
- 复现风险
- 哪篇最适合我的研究路线

输出为综述可用的表格。

## Build Review Outline

用 COF PEM research skill，基于当前知识库写一篇综述大纲，主题是：

主题：

要求：

- 只使用 `evidence_register.md` 中已核实或明确标注证据等级的文献。
- 按机制和材料体系组织，而不是按年份堆文献。
- 给出一级标题、二级标题、每节要回答的问题、关键文献和建议图表。

## Write Review Text

用 COF PEM research skill，基于当前知识库写一段综述正文：

章节主题：

要求：

- 学术中文。
- 不编造引用，不夸大。
- 每个关键判断说明来自哪些文献或证据等级。
- 对未核实内容使用“有待进一步核实/公开摘要显示/需要全文确认”。

## Make Review Tables

用 COF PEM research skill，把当前文献库整理成综述表格：

表格主题：

可选表格：

- COF 基 PEM 文献总表
- 静电纺丝 COF/PFSA 或 COF/Nafion 路线表
- 低湿/高温 PEM 性能对比表
- 质子传导机制对比表
- 复现风险和缺失数据表

要求：每个数值都带 RH、温度、膜厚/测试方向，如果缺失就标 `Need full text`。

## Make Figure Plan

用 COF PEM research skill，基于当前知识库设计综述图表：

图表目标：

输出：

- 图题
- 图中模块
- 每个模块表达的科学逻辑
- 需要哪些文献和数据支撑
- 哪些信息还缺失

## Check Accuracy

用 COF PEM research skill，检查下面这段综述文字是否准确：

文本：

要求：

- 标出可能不准确、夸大、缺少证据、缺少条件的句子。
- 对每个问题说明应该查哪篇文献或哪个 evidence entry。
- 给出更稳妥的改写。

## Update Knowledge Base After Discussion

用 COF PEM research skill，把我们今天讨论中已经核实的内容沉淀到知识库。要求：

- 更新对应文件。
- 未核实内容进入 `Needs Further Verification`。
- 最后告诉我改了哪些文件，以及下一步最小任务是什么。
