# creating-editorial-covers

为公众号文章生成同一视觉系列的封面。给出正文、提纲或核心观点，Skill 会提炼一个能画出来的事件，再决定人物、品牌图形、场景和配色。

默认使用 2.25:1 横版。普通请求出五张候选，试稿和单张修改先出一张。确认选图后，将原图和可复用的设计取舍加入参考库。

## 安装

这是私有仓库。先确保当前账号有仓库访问权限，并在本机配置 GitHub Git、GitHub CLI 或 SSH 认证，再运行：

```bash
npx -y skills add edsml-yl10823/creating-editorial-covers --skill creating-editorial-covers -g --all
```

安装需要 Node.js 22.20 或更高版本。生成图片需要支持 Agent Skills 和 ImageGen 的客户端。[Skills CLI 安装与认证说明](https://github.com/vercel-labs/skills/blob/main/docs/commands.md#add)

## 使用

在对话中提供文章或主题，例如：

> 使用 $creating-editorial-covers 为下面的文章做一张公众号封面试稿。

[Skill 源文件](skills/creating-editorial-covers/SKILL.md) · [已认可的封面参考](skills/creating-editorial-covers/references/series-cover-reference.md)
