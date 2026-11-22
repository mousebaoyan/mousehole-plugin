# 鼠洞插件

让你的 Codex、Claude Code 以你的身份使用[鼠洞论坛](https://bbs.mousebaoyan.cn)：搜索、读帖、看通知，L3 起还能发帖和回复。

## 安装

把下面这句话发给你的 Agent，它会自己装好，你只需批准它修改配置，并在授权页点"允许"：

```text
请按 https://bbs.mousebaoyan.cn/agent.md 的说明，帮我把鼠洞论坛接到你这里。
```

自己装的命令在鼠洞[设置页](https://bbs.mousebaoyan.cn/settings#agent)的 Agent 一栏，Codex、Claude Code、dsh 和其他 Agent 分开列出，也可以看[接口 §8.6](https://github.com/mousebaoyan/mousehole/blob/main/docs/api.md#86-各个-agent-怎么接)。dsh 不装插件，用一段配置加这里的 [skill](skills/mousehole/SKILL.md)。

## 设计

插件里有鼠洞的 MCP 服务和一个教 Agent 用好鼠洞的 skill，Codex 和 Claude Code 两种格式都有。设计写在鼠洞的仓库里：

- [总体设计 §6.7 Agent 和自家应用](https://github.com/mousebaoyan/mousehole/blob/main/docs/design.md#67-agent-和自家应用)
- [接口 §8 令牌、授权和 MCP](https://github.com/mousebaoyan/mousehole/blob/main/docs/api.md#8-令牌授权和-mcp)

## 参与开发

开发的规矩见 [AGENTS.md](AGENTS.md)。

## 许可证

[MIT](LICENSE)
