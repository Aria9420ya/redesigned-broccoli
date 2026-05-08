# 使用指南：如何唤醒和使用这个知识框架

## 一句话唤醒

你以后可以直接说：

> 用 COF PEM research skill，读取 `/Users/Zhuanz/Documents/New project` 的 `research_system` 知识库，按证据等级帮我处理这个任务：……

更短也可以：

> 用我的 COF PEM 知识库，帮我……

## 这个库最适合做什么

1. 找文献。
2. 整理文献。
3. 从文献里提取有效信息。
4. 整合成综述逻辑。
5. 输出论文文字、综述表格、机制图方案。
6. 设计实验路线和对照组。
7. 检查文字是否准确、有无夸大。

## 你有 DOI 时

直接发：

> 用 COF PEM research skill，核查这个 DOI：xxxxx，加入 evidence register 和 literature matrix。

我会做：

- 查题名、作者、期刊、年份、DOI。
- 能看到出版商页/全文就提取可靠信息。
- 看不到全文就标 `Abstract-only` 或 `Need full text`。
- 重要文献生成 paper note。

## 你有 PDF 时

把 PDF 放进项目，或告诉我路径，然后说：

> 精读这个 PDF，生成 paper note，并更新 evidence register、literature matrix 和 benchmark table。

PDF 最有价值，因为可以补齐摘要里没有的：

- RH
- 温度
- 膜厚
- 测试方向
- MEA 条件
- 催化剂负载
- 溶胀/吸水率/IEC
- 酸浸出率
- 复现细节

## 你想写综述时

可以说：

> 基于当前知识库，写一篇 COF 基质子交换膜综述大纲，按机制分类，不要按年份堆文献。

或者：

> 把 literature matrix 变成综述可用的比较表。

或者：

> 根据 evidence register，只用 Verified-primary 的文献写一段中文综述正文。

## 你想做图表时

可以说：

> 基于当前知识库，设计一张 COF/静电纺丝 PEM 综述机制图，给出图题、模块、逻辑和需要的数据。

或：

> 把 COF/Nafion、COF/SPEEK、COF/静电纺丝、酸负载 COF 做成对比表。

## 你想保证准确时

可以说：

> 检查这段综述文字是否准确，不准确或缺条件的地方请指出并改写。

我会按：

- `evidence_register.md`
- `fact_check_workflow.md`
- `quality_control.md`

来检查。

## 最推荐的长期工作流

1. 发 DOI 或 PDF。
2. 核查来源，更新 `evidence_register.md`。
3. 更新 `literature_matrix.md`。
4. 重要文献生成 `paper_notes/`。
5. 需要比较时更新 `benchmark_metrics_table.md`。
6. 写综述时读取这些文件，而不是重新靠聊天记忆。

## 你不用背指令

常用指令已经放在仓库根目录：

`PROMPTS.md`

以后你只要说：

> 打开 PROMPTS.md，按里面的“Read PDF”模式处理这篇文献。

或者：

> 按 PROMPTS.md 里的“Build Review Outline”模式，帮我写综述大纲。
