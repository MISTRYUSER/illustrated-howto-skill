# Illustrated How-to Skill · 图文操作教程

为软件操作编写可照着完成任务的详细图文教程，适用于云文档、产品后台和开发平台的操作手册。

## 核心做法

- 用“位置 → 动作 → 预期结果”组织步骤。
- 保留必要的多图，连起入口、点击后界面和下一步；不按截图数量凑内容。
- 使用真实截图与清晰标注，区分现场核验、官方示例和解释示意。
- 写清权限、未知参数、停止位置与成功判据，不用教程制作授权代替发布授权。
- 核验云文档保存、目录、图片尺寸及正常阅读版面。
- 用户要求时进行独立匿名评审，默认意图清晰度权重为 70%。

## 安装

将本仓库的 `illustrated-howto/` 目录放到客户端支持的 Agent Skills 目录中。

Codex 的手动安装示例（已有同名 Skill 时先备份）：

```sh
git clone https://github.com/MISTRYUSER/illustrated-howto-skill.git
mkdir -p ~/.codex/skills
cp -R illustrated-howto-skill/illustrated-howto ~/.codex/skills/
```

## 使用

```text
使用 $illustrated-howto，给这个平台写一份可照着操作的详细图文教程。
请保留连续入口图，截图加清晰标注，不提交任何生产配置。
```

也可以要求修改已有教程，或对多份文档做匿名盲评。Skill 本身不包含浏览器、文档连接器或截图工具，需要宿主提供相应能力。

## 文件

- [`SKILL.md`](illustrated-howto/SKILL.md)：入口与核心流程。
- [`patterns.md`](illustrated-howto/references/patterns.md)：写作骨架、步骤示例与官方参考。
- [`cloud-authoring.md`](illustrated-howto/references/cloud-authoring.md)：云文档编辑及版面检查。
- [`blind-review.md`](illustrated-howto/references/blind-review.md)：按需匿名评审量表。

本仓库仅包含通用方法，不包含业务代码、内部平台截图、账号数据或凭证。

## License

MIT
