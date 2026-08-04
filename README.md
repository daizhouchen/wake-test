# wake-test · 番茄工作法计时器 + PR Review 流程试验场

> QoderWake 测试仓库：一个**单文件番茄钟 Web 应用**，同时作为 AI 辅助 Code Review 工作流的演练场——每次功能迭代走完整的 PR → Review → Merge 流程并留档。

## 这是什么

- **应用本体**：`index.html`（单文件，零依赖），番茄工作法计时器，含专注/休息模式切换、专注场次计数与累计时长统计、明暗主题。
- **流程档案**：每次改动以 PR 形式提交，Review 记录完整留档：
  - `REVIEWS.md` — 结构化 Review 记录（摘要 / 优点 / 问题 / 结论）
  - `REVIEW_LOG.md` — Review 日志（文件变更 / 分支 / 状态）
  - `reviews/` — 单次 PR 的独立 Review 文档

## 为什么值得看

这个仓库展示的不是"一个大项目"，而是**把小改动也做成可审计交付**的习惯：

1. 功能再小（如 +9 行的专注计数器），也走分支 → PR → Review → 合并的完整链路
2. Review 记录同时检查功能正确性、代码风格一致性与逻辑准确性
3. AI 辅助审查与人工判断的分工在记录中可见

## 使用

直接用浏览器打开 `index.html` 即可，无任何构建与依赖。

## Update Log

- 2026-06-29: PR #8 — 番茄钟新增专注场次计数与累计时长（+9 行，已 Review 合并）
- 2026-06-29: Minor improvement — added timestamp for PR workflow testing

---

Part of [**daizhouchen 实验集**](https://github.com/daizhouchen) · [作品集站点](https://daizhouchen.github.io)
