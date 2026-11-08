# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 变更

- 实验室子模块改名：`examples/default` → `examples/quanttide-crowd-lab`（仓 quanttide-laboratory-of-crowdsourcing-management → quanttide-crowd-lab）
- 众包任务书下线站点、集中入档并上线 qtclass lite：`apps/qtcrowd` 站点任务清单清空（0 任务，站点与档案解耦、移除 `data:sync`），`data/profile` 为事实源——六篇业务线任务书保留，集中 learn 十篇、academy 三篇，lite 任务书 12 → 19 篇


### 新增

- 注册子模块：`apps/qtclass`（量潮课堂，quanttide/qtclass）
- 注册子模块：`apps/qtcloud-crowd`、`packages/quanttide-crowd-toolkit`、`examples/default`
- 注册子模块：`data/context`、`data/journal`、`data/intention`
- 注册子模块：`apps/qtcrowd`（量潮众包平台，与 quanttide-tech/apps 共用）
- 注册子模块：`data/roadmap`、`data/insight`、`data/brochure`（众包管理路线图/洞察/宣传册）

## [0.1.0] - 2026-08-21

### 新增

- 初始化众包管理领域仓库
