# 仓库导航

按用途整理的开源项目与设计技能。每个 Fork 保留原项目来源、作者和许可证；仓库收录与实际安装、运行验证分别管理。

## AI 接手入口

管理本账号仓库前，先读 [AGENTS.md：仓库管理规则](https://github.com/yunhangfang-max/yunhangfang-max/blob/main/AGENTS.md)，再核实本次账号、仓库和授权范围。

换用 Codex、Dot 或其他 AI 时，可以直接发送：

> 请先读取 https://github.com/yunhangfang-max/yunhangfang-max 中的 README.md 和 AGENTS.md，核实绑定账号与仓库现状，再按其中规则完成我本次要求的仓库管理；完成后更新导航并读回验证。

`AGENTS.md` 的自动读取范围取决于工具和当前工作目录；在其他仓库或仅通过浏览器访问时，请明确给出上面的入口。

## 设计 Skill

| 仓库 | 适合做什么 | 技能入口 | 上游 |
|---|---|---|---|
| [Unslop](https://github.com/yunhangfang-max/unslop) | 打磨已有网页与应用界面：布局、字体、配色、文案、细节和动效 | [SKILL.md](https://github.com/yunhangfang-max/unslop/blob/main/skills/unslop/SKILL.md) | [heydamir/unslop](https://github.com/heydamir/unslop) |
| [Huashu Design](https://github.com/yunhangfang-max/huashu-design) | HTML 原型、设计方向探索、幻灯片、可编辑 PPTX、动画和信息图 | [SKILL.md](https://github.com/yunhangfang-max/huashu-design/blob/master/SKILL.md) | [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) |

已有界面需要精修，先看 **Unslop**；要做原型、演示稿或视觉设计，先看 **Huashu Design**。后者不替代生产应用的后端开发。

Huashu Design 依赖仓库里的 `references/`、`assets/`、`scripts/`、`demos/`，安装时应保留完整目录，不能只复制 `SKILL.md`。具体安装与依赖以各仓库 README 为准。

## AI 工具

| 仓库 | 用途 | 上游 |
|---|---|---|
| [OpenMausBot](https://github.com/yunhangfang-max/OpenMausBot) | 本地优先的多智能体聊天、任务协作与工具工作台 | [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) |

## 量化研究

| 仓库 | 用途 | 上游 |
|---|---|---|
| [tick-stock-panel](https://github.com/yunhangfang-max/tick-stock-panel) | 自托管 A 股策略研究、监控、回测和数据源扩展工作台 | [shy3130/tick-stock-panel](https://github.com/shy3130/tick-stock-panel) |

## 交易框架

| 仓库 | 用途 | 上游 |
|---|---|---|
| [vnpy / VeighNa](https://github.com/yunhangfang-max/vnpy) | 基于 Python 的量化交易平台开发框架与二次开发参考 | [vnpy/vnpy](https://github.com/vnpy/vnpy) |

## 分类与维护

- 分类标准、收录流程、Fork 更新及验收要求统一见 [AGENTS.md](https://github.com/yunhangfang-max/yunhangfang-max/blob/main/AGENTS.md)。
- 这里只维护项目清单和用途入口，避免多份管理规则产生冲突。

## 设计技能署名与许可

**Unslop** 由 **Damir Sokolovsky / [@heydamir](https://github.com/heydamir)** 创建，采用 [CC BY 4.0](https://github.com/yunhangfang-max/unslop/blob/main/LICENSE)。复制或改编时保留署名、许可证和[上游链接](https://github.com/heydamir/unslop)。

**Huashu Design** 由 **花叔 / [alchaincyf](https://github.com/alchaincyf)** 维护，主体采用 [MIT](https://github.com/yunhangfang-max/huashu-design/blob/master/LICENSE)。`assets/style-specimens/xhs/_kit/stickers/` 演示贴纸另有 [PolyForm Shield 许可](https://github.com/yunhangfang-max/huashu-design/blob/master/assets/style-specimens/xhs/_kit/stickers/LICENSE.md)，不与主体 MIT 混用。

其他项目及其第三方组件按各仓库原有许可执行。
