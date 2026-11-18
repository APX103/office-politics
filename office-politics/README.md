# office-politics · 职场罗盘

一个 ZCode 插件：把戈登·塔洛克（Gordon Tullock）《官僚体制的政治》（*The Politics of Bureaucracy*）的等级制分析框架，变成日常职场对话里可用的局势分析技能。

## 它做什么

当你聊到任何工作话题——接下来要做的任务、工作交接、同事、领导、汇报、晋升、绩效、跨部门协作、带团队——技能自动启用，用书中的分析框架给出清醒、可操作的判断：

- **画利益地图**：谁是实际能奖惩你的领导、谁是观望者、谁是潜在同盟者
- **看穿信息流**：信息如何逐层失真、汇报应该从上级已知的因素搭起
- **识别实际奖励标准**：组织提拔人的真实依据 vs 宣称依据
- **场景化行动清单**：交接、汇报、站队、述职、背锅、躺平等十个高频场景

## 安装

### 通过本仓库（GitHub）

1. ZCode → Plugin Marketplace → Add → Add Plugin Marketplace，粘贴本仓库地址
2. Personal → 找到该 marketplace → office-politics → Install
3. 安装后在技能选择器中确认 `office-politics` 可见

### 本地开发

```text
office-politics/
  .zcode-plugin/plugin.json
  skills/office-politics/SKILL.md          # 技能入口：触发条件、分析流程、输出格式
  skills/office-politics/references/
    framework.md                            # 20 个核心概念（含章节出处）
    scenarios.md                            # 10 个高频场景手册
    quotes.md                               # 原文关键摘录
```

本地测试：把本目录（含 `.zcode-plugin`）所在路径作为本地 marketplace 添加即可。

## 技能内容结构

| 文件 | 内容 |
|---|---|
| SKILL.md | 触发条件、立场与红线、五步分析流程、输出格式、场景速查表 |
| framework.md | 塔洛克工具箱 20 条：政治/经济关系、世界地图、侍臣与男爵、A/B/C 信息模型、控制技术、用结果判断、假核算等 |
| scenarios.md | 场景 A-J：交接、汇报、同事、站队、晋升、带团队、跨部门、新环境、背锅、躺平 |
| quotes.md | 按主题分组的原文摘录（标注章节） |

## 立场

- 描述性分析工具，不是道德说教：假设组织中人人理性自利（自利≠只有升官，也包括安全、省力、避责），用它**预测行为**。
- 不教唆害人：阴暗手段只作防御性认知；主动建议限于正当手段。
- 分析可以冷，建议必须可执行。

## 版本

- 0.1.0 初始版本

*基于《官僚体制的政治》[美] 戈登·塔洛克 著（中译本）整理。*
