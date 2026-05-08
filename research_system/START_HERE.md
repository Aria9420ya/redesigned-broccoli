# Fuel Cell Materials Research System

This project is organized as a long-term research workspace for COF/electrospun proton exchange membranes.

For copy-ready prompt templates, see `../PROMPTS.md`.

For a Chinese usage guide, see `USER_GUIDE_ZH.md`.

## How To Ask Codex

Use short commands like:

- "用 COF PEM research skill，帮我读这 5 篇文章并更新文献矩阵。"
- "根据现在的知识库，设计下一轮静电纺丝 COF/PFSA 膜实验。"
- "把这组 EIS/吸水率/溶胀数据解释成机制图。"
- "用 GitHub 看一下项目问题、提交记录和 CI，帮我调试。"
- "把今天的结论沉淀到知识库，聊天里只保留摘要。"

## Folder Map

- `research_system/knowledge/knowledge_map.md`: stable mechanism map and research questions.
- `research_system/knowledge/domain_taxonomy.md`: layered subject taxonomy from device to mechanism.
- `research_system/knowledge/glossary.md`: key terms and measurement vocabulary.
- `research_system/literature/literature_matrix.md`: structured paper notes.
- `research_system/literature/evidence_register.md`: source and confidence status for literature claims.
- `research_system/literature/fact_check_workflow.md`: required workflow before treating claims as facts.
- `research_system/literature/source_record_template.md`: template for auditable paper extraction.
- `research_system/literature/paper_notes/`: reusable A-core paper cards.
- `research_system/literature/literature_protocol.md`: paper search, screening, and extraction rules.
- `research_system/experiments/experiment_plan.md`: sample design and test plan.
- `research_system/experiments/route_decision_matrix.md`: route comparison and first-route selection logic.
- `research_system/experiments/sample_log_template.md`: reusable experiment batch record.
- `research_system/data_templates/benchmark_metrics_table.md`: paper and experiment comparison table.
- `research_system/writing/figure_storyboard.md`: figure-first manuscript logic.
- `research_system/quality_control.md`: accuracy, completeness, and effectiveness rules.
- `research_system/github/debug_workflow.md`: how to use GitHub for project work.
- `research_system/github/issue_backlog.md`: first GitHub issues to create.
- `research_system/roadmap.md`: staged path from literature map to manuscript figures.

## Context-Saving Rule

Do not keep full papers, long copied paragraphs, or raw data in chat. Put durable memory into files, then ask Codex to load only the relevant file for the next task.

## First Milestones

1. Extract 10-20 core papers into the literature matrix.
2. Choose the first membrane route and controls.
3. Build a sample naming system.
4. Record experiments with the sample log template.
5. Convert results into a figure-first manuscript outline.
