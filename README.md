# Agent Skills

可下载使用的 Agent Skills。**仅限非商业用途；商业使用须另行获得作者授权。**

## 已发布技能

| 技能 | 说明 |
| --- | --- |
| [阿里国际站产品视觉策划](skills/alibaba-product-visual-planning/SKILL.md) | 分析产品图片、文档和参考图，规划主图、卖点附图和场景应用图，输出设计思路与执行方案。 |

该技能只输出方案，不直接生成或修改最终图片。技能正文保留作者原稿。

## 下载与安装

1. 在仓库首页点击 **Code → Download ZIP**，解压。
2. 将 `skills/alibaba-product-visual-planning` 整个文件夹复制到支持 Agent Skills 的工具的技能目录。
3. 对于 Codex，可复制到个人技能目录 `~/.codex/skills/`；如果安装环境采用其他技能目录，请遵循该环境的配置。
4. 重新打开会话或刷新技能列表，并确认技能已被识别。

安装后的结构：

```text
技能目录/
└── alibaba-product-visual-planning/
    └── SKILL.md
```

也可直接阅读 SKILL.md，将其作为对话中的工作要求；这种方式不等同于安装技能。

## 调用示例

```text
请使用 $alibaba-product-visual-planning，为我的产品规划 1 张主图、
3 张卖点附图和 1 张场景应用图，仅输出设计思路。
我会提供产品图片、规格、目标市场和品牌要求。
```

建议提供产品图片和参数、核心卖点、目标市场和客户、图片用途与数量、
品牌要求及禁止修改的内容。图片分析需要所用工具支持图片理解；
PDF、Word、Excel 等资料的读取取决于工具能力。

## 许可与商业使用

本仓库原创技能文档及说明采用 **CC BY-NC 4.0（署名—非商业性使用）**。
允许按许可条款进行非商业性的复制、分享和修改，须署名、提供许可链接并注明修改。
商业使用须事先取得作者单独授权。

“免费下载”不代表可以免费用于店铺经营、商业客户项目、付费培训等商业目的。
技能主题涉及电商，不代表已授予商业使用权。

- 作者：[LesliesCocky](https://github.com/LesliesCocky)
- [仓库许可声明](LICENSE)
- [完整许可条款](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

第三方产品资料、图片、品牌及其他素材的权利归各自权利人所有。

