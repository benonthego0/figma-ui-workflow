# Figma UI Workflow

用于 Codex 的中文技能：把现有网站设计整理成可继续编辑、批量维护的 Figma 文件。

## 能做什么

- 按要求另存独立副本，核对目标文件。
- 整理原生 Auto layout、组件与实例、文字样式。
- 保留图片素材和可编辑结构，检查布局与长文本适配。
- 记录续作状态，明确验证结果和未完成项。

## 安装

下载 [figma-ui-workflow.zip](figma-ui-workflow.zip) 安装包（打开后点 Download raw file），解压后将 `figma-ui-workflow` 文件夹放到：
- Windows：`%USERPROFILE%\.codex\skills\`
- macOS / Linux：`~/.codex/skills/`
- 自定义 Codex 主目录：`$CODEX_HOME/skills/`

最终应存在 `skills/figma-ui-workflow/SKILL.md`，并保留同目录的 `references` 和 `agents` 文件夹。重新打开 Codex 会话后使用。

也可下载本仓库 ZIP，再解压其中的 `figma-ui-workflow.zip` 安装包。仓库以安装包形式分发，完整源文件均包含在安装包内。

## 使用示例

```text
$figma-ui-workflow
请优化这个 Figma 页面：[你的设计链接]
先另存副本，保留页面内容与品牌风格，整理自动布局、可复用组件与文字样式，并检查长文本适配。
```

## 前置条件

需要可编辑的 Figma 文件、相应权限及可用的 Figma 工具连接。本技能提供工作流程，不包含 Figma 连接器、账号或调用额度。原生工具路径需要当前版本的官方 Figma 技能；浏览器操作需要可用的电脑/浏览器工具。若有个人工具偏好，请在自己的 AGENTS.md 中配置。

## 文件结构

```text
figma-ui-workflow/
  SKILL.md
  agents/openai.yaml
  references/environment.md
  references/native-editing.md
  references/browser-operations.md
```

分享版本将原参考文档中的本机绝对路径替换为通用路径，技能正文与操作经验保留。适用于 Figma 文件整理与编辑，不用于单纯网页代码实现或静态效果图生成。

