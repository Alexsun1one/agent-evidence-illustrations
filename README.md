# Agent Evidence Illustrations / 证据链配图

> 给证据链、信任边界、交接审核、复盘回放类文章生成“审计剧场 / 证据物件美学”正文配图。

这个 skill 是一个窄题材视觉包：当文章在讲一个判断为什么可信、证据从哪来、谁盖章、哪里该停、如何复盘时，它把抽象关系画成票据、红章、证据带、待审托盘、权限门、旧照片和回放胶带。不必满屏工程图，也可以像一张漂亮的调查杂志插图。

## 示例图

<p><img src="examples/images/03-trust-before-conclusion.png" alt="先证据后结论" width="100%"><br><sub>先证据后结论：故事、照片和笔记先被比较，再进入结论信封。</sub></p>
<p><img src="examples/images/01-audit-office-trust-gate.png" alt="审计办公室信任门" width="100%"><br><sub>审计办公室信任门</sub></p>
<p><img src="examples/images/02-grid-collage-article-pipeline.png" alt="文章流程配图" width="100%"><br><sub>文章流程配图</sub></p>

## 它能做什么

- 把 claim、evidence、review、permission、handoff 画成可理解的物件关系。
- 用原创“审计办公室”隐喻世界，避免复制别人的 mascot/IP。
- 适合 AI agent、工程治理、信任边界、安全审核、协作流程文章。
- 让读者看到“证据从哪来、谁盖章、哪里被拒、哪里可回放”。

## 安装

把这个仓库克隆到本机 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Alexsun1one/agent-evidence-illustrations.git ~/.codex/skills/agent-evidence-illustrations
```

如果你的 Agent 使用其它 skills 目录，也可以把包含 `SKILL.md` 的这个仓库复制过去。

## 怎么用

示例请求：

```text
用 agent-evidence-illustrations 生成一张中文正文配图：主题是 AI Agent 交接、证据链、权限门和人工审核。要求画面像荒诞但清楚的审计办公室。
```

Skill 入口是 [`SKILL.md`](SKILL.md)。细则在 [`references/`](references/)；如果这个仓库带脚本，脚本在 [`scripts/`](scripts/)。

## 质量要求

- 先服务内容，再服务风格；图必须解释一个具体想法。
- 中文默认要可读，标题、caption、标签不能只当装饰纹理。
- 同一组图要风格统一，但每张图要贴合自己的段落/用途。
- 示例图是工作流参考，不是唯一模板。

## 公众号

更完整的拆解、提示词、案例复盘、AI 写作和产品实践，我会继续写在公众号里。下面是我的真实公众号二维码/搜一搜卡片，不是仿造的装饰二维码。

<p align="center">
  <img src="assets/wechat-official-account.png" alt="微信搜一搜：正在逐渐AI化" width="720">
</p>

## 开源协议

MIT。见 [`LICENSE`](LICENSE)。

## 声明

这是 Sun Wuyuan / Alexsun1one 的原创开源 Skill 包。它不隶属于 OpenAI、GitHub、微信或任何被提及的平台。请不要用它去复制受保护 IP、仿冒在世艺术家，或暗示不存在的品牌背书。
