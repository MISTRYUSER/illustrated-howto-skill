# 结构与写法

按复杂度取舍，不固定章节数或截图数。

## 推荐骨架

目标与适用范围 → 前提 → 按界面顺序的操作、截图、预期结果 → 实际生效验证 → 常见卡点与恢复 → 来源和核对时间。

## 步骤示例

### 添加一条规则

在**规则配置**区域选择**添加规则**。按钮在视野外时，先向右横向滚动。

【真实入口图：保留区域标题，红框标出添加按钮】

**预期结果：**出现带编号的规则卡片，其中有 IF 条件行和 RETURN 行。

在 IF 行选择第一个**请选择**，展开变量列表。

【点击后的局部图：标出下拉框，不沿用只显示入口按钮的图】

避免：“打开配置，按需选择合适参数，然后发布。”它没有可定位入口、参数依据或结果判据。

## 未知参数

| 参数 | 来源 | 未确认时 |
|---|---|---|
| 最小支持版本 | 对应发布记录，并与功能负责人核对 | 不猜版本，不提交 |
| 平台变量与枚举值 | 变量说明或官方接入规范 | 找不到时确认接入，不换旧字段凑数 |
| 阶段比例 | 发布计划或平台要求 | 数字只作示例，不冒充获批值 |

无法按文档配出规则的缺口，要写在前提或对应步骤旁，不能只在末尾笼统写“以实际为准”。

## 方法来源

- [Google Procedures](https://developers.google.com/style/procedures)：编号步骤、上下文、动作结果。
- [Google Images](https://developers.google.com/style/images)：真实截屏、相关区域裁剪和图注。
- [Microsoft Writing step-by-step instructions](https://learn.microsoft.com/en-us/style-guide/procedures-instructions/writing-step-by-step-instructions)：先位置后动作和步骤颗粒度。
- [GitHub Docs Style guide](https://docs.github.com/en/contributing/style-guide-and-content-model/style-guide)：优先清晰与意义。
- [Diátaxis How-to guides](https://diataxis.fr/how-to-guides/)：围绕具体任务，区分操作指南与解释材料。

这些来源支持写作方法，不证明任何内部平台的当前规则；产品操作另行核验。
