# jotang-skills

个人定制的 Claude Code 技能（Skills）、工程 SOP 与自动化工作流合集，旨在为高效率、规范驱动（Spec-Driven）和测试驱动（Test-Driven）的全栈 AI 开发提供赋能。

## 核心理念

- **规范驱动（OpenSpec）：** 在写下一行代码之前，先锁定架构边界、系统不变量和实现契约。
- **测试驱动（Superpowers）：** 强制执行严格的“红-绿-重构”（Red-Green-Refactor）循环与子代理任务拆解，消除 AI 幻觉和未验证的逻辑。
- **闭环归档：** 在验证通过后，自动将增量规范（Delta Specs）合并回单一真实数据源（`openspec/current/`）。

---

## 仓库目录结构

```text
jotang-skills/
├── README.md
└── sdd-workflow/                 # 4阶段 SDD + TDD 闭环 SOP
    ├── SKILL.md                  # 核心技能定义与状态机规则
    └── references/               # 可选：提案与任务的模板