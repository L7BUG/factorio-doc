# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库性质

异星工厂（Factorio）游戏攻略与参考文档的知识库，纯 Markdown 文档，无可执行代码。

## 语言

- 所有文档使用**简体中文**撰写
- 技术术语和游戏内专有名词保留原文或中英对照（如 Balancer/均分器、Lane Balancer/通道均衡器）
- 与用户对话始终使用简体中文

## 文档风格

- 使用表格呈现对比信息
- 使用 ASCII 图示说明布局和流程
- 每个文档聚焦单一主题，交叉引用时说明关系而非重复内容
- 所有外部链接指向官方 Mod 站 (mods.factorio.com)、FactorioBin、GitHub 等可靠来源

## 已有文档

| 文件 | 主题 |
|------|------|
| `异星工厂实用Mod推荐.md` | 按分类整理的实用 Mod 清单 |
| `均分器类型完全指南.md` | Balancer/TU/LB/Corner/Split/Merge 术语对比 |
| `卸货站均分器方案.md` | 6→6 LB + 6→2 B + 8→2 TU 卸货站方案 |
| `LTN与Cybersyn智能火车调度详解.md` | Cybersyn 与 LTN 对比 |
| `Blueprint-Sandboxes详细介绍.md` | 蓝图沙盒 Mod 指南 |
| `factoriobin-post-cgn0od-翻译.md` | Raynquist 均分器合集蓝图中英对照 |

## 新增文档规范

1. 先在 `~/game/异星工厂/` 下新建 `.md` 文件
2. 文件开头标注来源和兼容版本（Factorio 版本、Mod 版本）
3. 完成后 `git add` + `git commit`（提交信息用中文）
