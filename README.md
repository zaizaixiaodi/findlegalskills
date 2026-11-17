# Find Legal Skills

让你的 AI 助手直接查询 [法律AI雷达](https://betterlawyer.cn) 收录的法律 AI 项目：按律师工作场景、业务领域和上手难度找 Skill、MCP、插件和应用，查看详情并比较。

数据每日从 GitHub 更新，收录标准和分类见网站。

## 安装

**方式一：让 AI 帮你装**

把下面这句话发给你的 AI 助手（支持 Skill 的客户端，如 ChatGPT、Claude Code、WorkBuddy）：

```
请读取 https://betterlawyer.cn/api/site/radar/skill/package，说明权限并在我确认后安装为 findlegalskills，然后查询法律 AI 工具。
```

AI 会先说明要装什么、装在哪里，你确认后再装。

**方式二：命令行**

```bash
mkdir -p .claude/skills/findlegalskills && curl -fsSL https://raw.githubusercontent.com/zaizaixiaodi/findlegalskills/main/skills/findlegalskills/SKILL.md -o .claude/skills/findlegalskills/SKILL.md
```

装好后重新打开客户端。

已验证的客户端：ChatGPT（2026-11-17）。最新列表见 [betterlawyer.cn/skill](https://betterlawyer.cn/skill)。

## 试试这样问

- 用 findlegalskills 找几个适合中文合同审查的工具，挑 3 个比较一下
- 有没有能帮我做类案检索的开源项目？
- 劳动人事方向有哪些装进 AI 就能用的 Skill？

## 它会做什么、不会做什么

- 只读取 betterlawyer.cn 的公开查询接口，不需要账号或密钥。
- 不上传你的客户材料或案情，不调用付费服务，不替你安装第三方项目。
- Star 只代表热度，不代表质量；收录不等于推荐。工具信息不构成法律意见。

## 反馈

发现遗漏的好项目或信息有误，欢迎到 [投稿与合作](https://betterlawyer.cn/submit) 告诉我们，或在本仓库提 Issue。

## 许可证

MIT
