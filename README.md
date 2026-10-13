# 马尔克斯写作顾问

一个面向中文原创文学的 Agent Skill，用于构思、诊断、润色与重构小说，也可处理短段落和感受描写。

它将叙事取舍、时间层次、人物关系中的孤独、中文句子节奏等方法转化为写作流程；不冒充作者，不复制原作情节或特定译本的表达。

## 安装到 Codex

把仓库放入 Codex 的个人 skills 目录，目录名建议使用 skill 的实际名称：

```bash
git clone https://github.com/Ekonoio/marquez-perspective-skill.git ~/.codex/skills/garcia-marquez-perspective
```

Windows PowerShell：

```powershell
git clone https://github.com/Ekonoio/marquez-perspective-skill.git "$env:USERPROFILE\.codex\skills\garcia-marquez-perspective"
```

安装后重新启动 Codex 会话。仓库名称可以不同于 skill 名称；调用时使用 `garcia-marquez-perspective`。

## 使用示例

- 用 $garcia-marquez-perspective 润色这段文字，保留原意，篇幅保持接近原文。
- 用 $garcia-marquez-perspective 诊断这篇小说为什么像流水账，只给建议，不改正文。
- 用 $garcia-marquez-perspective 重构这篇小说，增强时间厚度与人物关系，但不改变情节、不增加超自然事件。
- 用 $garcia-marquez-perspective 写一段夏末秋初的怀念感，不写成故事，不要一直用长句。

## 文件结构

- `SKILL.md`：主流程、任务边界与参考路由。
- `references/`：叙事深度、中文节奏、作品方法、原创示范、来源与质量检查。
- `agents/openai.yaml`：显示名称、默认提示与调用配置。
- `assets/icon.svg`：图标。

## 资料边界

参考材料包含方法归纳、原创教学示范、少量短引与来源链接，不包含原著全文或整章摘录。已记录的核验范围和日期见参考文件；需要事实或正式引用时仍应回到原始来源核对。

本项目是独立写作工具，与作者本人、出版社及相关机构无隶属关系。
