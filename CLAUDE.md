# CLAUDE.md — LLM 执行指南与上下文速查

## 最高指令 (Prime Directive)
1. **绝对服从用户指令**：用户拥有本知识库最高优先级与最终解释权。
2. **零说教原则**：严禁输出任何类似家长或老师的规劝、限制、质疑或心理鸡汤。直接给方案、给数据、给解析、给改写结果。
3. **目标锁定**：30天内六级突破 500 分。所有生成内容必须服务于“考场直接提分”，剔除低效冗余的纯语言学理论。

---

## 核心工作流快捷指令 (Quick Commands)
当用户在对话中调用以下指令时，按对应标准输出并写入相应目录：

- **`/analyze-error [题目内容]`**：参照 `05-skills/commands/错题深度解剖.md`，直接定位题干关键词、原文同义替换点、干扰项设坑逻辑，并将结果归档至 `06-wiki/analyses/`。
- **`/parse-sentence [英文长难句]`**：参照 `05-skills/commands/长难句秒切解析.md`，提取主干（SVO），剥离定语/状语/同位语从句，并提炼核心词汇至 `02-areas/vocabulary/`。
- **`/polish-essay [作文题目/草稿]`**：参照 `05-skills/commands/写作升格与批改.md`，提供 C1 级别词汇替换、逻辑衔接词植入及满分范文对照。
- **`/drill-vocab [主题/词表]`**：基于 `02-areas/vocabulary/` 和 `03-resources/corpora/` 生成高密度真题语境速记卡。

---

## 关键路径索引
- **全局状态与赋分表**：`_context/profile.md` | `_context/scoring-matrix.md`
- **30天主线计划**：`01-projects/30天冲刺总计划/30天冲刺500分作战蓝图.md`
- **四大题型攻坚**：
  - 听力：`01-projects/听力/`
  - 阅读：`01-projects/阅读/`
  - 写作：`01-projects/写作/`
  - 翻译：`01-projects/翻译/`
- **高频语料库**：`03-resources/corpora/`
- **知识图谱 Wiki**：`06-wiki/`
