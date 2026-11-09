# 咨询诊断 PPT 技能

`consulting-diagnostic-ppt` 是一个面向中文管理咨询交付的 Codex 技能。把 Word、Excel、访谈纪要或已有 PPT 整理成现状诊断、根因分析、改进方案和行动计划。技能负责汇报逻辑、页型选择和咨询风格，PPT Master 负责生成可编辑的 PowerPoint。

## 安装

在 Codex 中发送下面这段话。

> 请用 `$skill-installer` 安装 `zhouhn312121-code/consulting-diagnostic-ppt` 仓库下的 `consulting-diagnostic-ppt` 技能，并安装 PPT Master。

也可以从 [GitHub Releases](https://github.com/zhouhn312121-code/consulting-diagnostic-ppt/releases) 下载 ZIP，解压后把整个技能文件夹放进 `~/.agents/skills/`。确认入口位于 `~/.agents/skills/consulting-diagnostic-ppt/SKILL.md`。如果技能尚未出现，重启 Codex 后再调用。

首次生成 PPTX 前，需要安装 [PPT Master](https://github.com/hugohe3/ppt-master) 及其 Python 依赖。请按上游仓库的安装说明配置；如果已安装，可以直接开始。

## 使用流程

| 场景 | 怎么用 |
| --- | --- |
| 常规出稿 | 上传材料，说明汇报对象、用途和资料范围。技能会先提出整份 PPT 的主线、关键章节的顺序和各章的逻辑，如总分、递进或对比。有影响讲法的歧义会先问你，等你确认后再选模板并绘制。 |
| 快速出稿 | 明确说「快速出一版」。在适用的快速流程下，技能会自行判断主线、章节结构和页型，直接交可编辑初稿。 |
| 修改一页 | 提供最近一版 PPT，说明页码、要调整的内容及版式要求。 |
| 沉淀偏好 | 你确认定稿后，技能会总结可复用的改稿偏好。你另行确认采用后，技能才会更新本地风格指南。 |

### 第一次可以这样用

> 用 `$consulting-diagnostic-ppt` 把附件做成一份给事业部负责人的专项诊断 PPT。Excel 只参考「现状诊断&根因分析&解决方案」工作表。先给我整体主线、建议页数和关键章节的逻辑，等我确认后再绘制，交付可编辑 PPTX。

### 使用自己的模板

把你的 PPTX 模板随任务上传，并说明它是版式参考还是需要直接填充的模板。技能会根据内容关系匹配页型。若你已有对应的 101 页蓝色系列模板，可以上传它，或放到技能目录内的 `assets/blue-series-template.pptx`，配合页型索引按页码复用。仅安装公开版时，也可以使用内置风格指南生成新页。

## 技能文件

- [SKILL.md](consulting-diagnostic-ppt/SKILL.md) 定义调用、出稿和迭代规则。
- [咨询风格指南](consulting-diagnostic-ppt/references/style-guide.md) 收录诊断叙事、流程对照、根因矩阵和行动表等画法。
- [蓝色系列页型索引](consulting-diagnostic-ppt/references/blue-layout-index.md) 按总分、流程、比较等关系组织页型。
