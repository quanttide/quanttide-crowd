# quanttide-crowd

量潮众包管理

## 概述

量潮众包管理（quanttide-crowd）是量潮知识管理体系中的**众包管理**领域，以管理实践方式承载众包市场的需求发单、执行接单与标准交易过程。

## 领域边界

- **需求发单**：需求拆解为标准任务、交付标准与验收准则定义
- **执行接单**：执行方注册准入、标准内竞价、接单履约
- **标准交易**：标准任务、标准交付、标准验收，验收准则兜底
- **信用沉淀**：执行方信用记录、标准执行率、认证与导流

> 与 data 领域的分工：本领域承载「众包市场运营」（发单、接单、信用），data 承载「垂直业务承接」（qtdata 认证供应商池与高价值订单）。
> 与 product 领域的分工：本领域承载「标准任务与验收」，product 承载「产品研发需求刻画」。

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtcloud-crowd` | QtCloud 众包管理云 (git submodule) |
| `apps/qtcrowd` | 量潮众包平台 (git submodule → qtcrowd，与 quanttide-tech/apps 共用) |
| `packages/quanttide-crowd-toolkit` | 众包管理工具集 (git submodule) |
| `examples/default` | 众包管理实验室 (git submodule → quanttide-laboratory-of-crowdsourcing-management) |
| `data/context` | 众包管理语境 (git submodule → quanttide-context-of-crowd-sourcing) |
| `data/journal` | 众包管理日志 (git submodule → quanttide-journal-of-crowd-sourcing) |
| `data/intention` | 众包管理意图 (git submodule → quanttide-intention-of-crowd-sourcing) |
| `data/profile` | 众包管理画像 (git submodule → quanttide-profile-of-crowd-sourcing) |
| `data/roadmap` | 众包管理路线图 (git submodule → quanttide-roadmap-of-crowd-sourcing) |
| `data/insight` | 众包管理洞察 (git submodule → quanttide-insight-of-crowd-sourcing) |
| `data/brochure` | 众包管理宣传册 (git submodule → quanttide-brochure-of-crowd-sourcing) |

## 许可

[CC BY 4.0](LICENSE)
