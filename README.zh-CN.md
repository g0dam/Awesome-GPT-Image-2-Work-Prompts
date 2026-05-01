# Awesome GPT Image 2 Work Prompts

50 条面向真实工作场景的 GPT Image 2 双语 Prompt，覆盖营销、电商、销售、品牌系统、运营、教育培训、HR、客户成功、社群活动和创始人战略等类别。

这个仓库适合直接挂到 GitHub，也适合后续接入网站的 Prompts 页面。每条 prompt 都有结构化 JSON、英文 Markdown、中文 Markdown 和一张对应的生成图片。

[English README](README.md)

## 这个仓库有什么

- 50 条原创 GPT Image 2 / ChatGPT Images 2.0 工作场景 prompt。
- 英文和简体中文两个版本。
- 可直接给网站或后台导入的 `data/prompts.json`。
- 每条 prompt 独立 Markdown 文件：`prompts/en/` 和 `prompts/zh-CN/`。
- 50 张对应 PNG 示例图：`images/`。
- 按工作属性需求整理的分类索引：`categories/`。

## 适合谁使用

这个素材库适合：

- AI prompt 导航站或 prompt marketplace；
- GPT Image 2 prompt gallery；
- SaaS 网站中的 AI 图片生成案例页；
- 营销、销售、HR、运营团队内部 prompt 库；
- 面向中英文用户的 AI 工具网站。

## 分类

| 分类 | 典型用途 |
| --- | --- |
| 营销增长 | LinkedIn 发布图、广告素材、邮件 Banner、App Store 图 |
| 产品电商 | 产品主视觉、商品信息图、开箱图、前后对比图 |
| 品牌设计系统 | Moodboard、Design Token、Logo 规范、图标风格 |
| 销售提案 | 投资人问题页、ROI 图、销售单页、案例研究 |
| 教育培训 | 微课卡片、解释图、工作坊议程、安全清单、证书 |
| 数据运营 | 周报看板、流程图、事故时间线、库存计划 |
| HR 内部沟通 | 新人入职地图、福利说明、全员会、价值观卡片 |
| 客户成功支持 | 帮助中心、功能采用邮件、支持升级流、健康分 |
| 活动社群 | Webinar、社群挑战、Meetup 回顾、Hackathon 项目板 |
| 创始人战略 | 市场地图、定价页、路线图、高管备忘录、运营模型 |

## JSON 数据格式

`data/prompts.json` 是主数据源，适合给网站、CMS 或后台导入。每条记录包含：

- `id` 和 `slug`
- 中英文 `title`
- 中英文 `category`
- 中英文 `target_user`
- 中英文 `use_case`
- 中英文 `prompt`
- prompt 结构和约束
- `image_path`
- 不包含本机绝对路径的生成元信息

示例：

```json
{
  "id": "gptimg2-work-001",
  "slug": "linkedin-launch-carousel-cover",
  "category": {
    "slug": "marketing-growth",
    "en": "Marketing & Growth",
    "zh": "营销增长"
  },
  "image_path": "images/gptimg2-work-001-linkedin-launch-carousel-cover.png"
}
```

## Prompt 设计原则

这个库不是按“好玩风格”分类，而是按用户的工作属性需求分类。每条 prompt 都尽量具备可复用的业务资产结构：目标用户、使用场景、交付物、版式方向、文字规则、视觉限制和负面约束。

这些 prompt 是基于公开资料研究后的原创改写。X、GitHub、Reddit 和公开 prompt gallery 只作为模式、类别和结构参考，不直接复制第三方完整 prompt。

## SEO 与 GEO 说明

这个仓库主要覆盖以下搜索意图：

- GPT Image 2 prompts
- ChatGPT Images 2.0 prompts
- GPT Image 2 prompt examples
- AI image prompts for work
- business AI image generation prompts
- bilingual AI image prompt dataset
- prompt library JSON for websites

GEO 方面，README 使用了直接回答、清晰分类、明确用途、可复用 JSON、来源策略和中英双语结构，方便 ChatGPT、Perplexity、Gemini、Claude、Copilot 等 AI 搜索或回答引擎准确理解和引用。

## 仓库结构

```text
.
├── categories/
├── data/
│   ├── prompts.json
│   └── sources.json
├── images/
├── prompts/
│   ├── en/
│   └── zh-CN/
├── LICENSE
├── README.md
└── README.zh-CN.md
```

## 模型命名说明

当前公开语境里同时存在 `GPT Image 2` 和 `ChatGPT Images 2.0` 两种叫法。这个仓库在元数据中保留两种命名，方便开发者文档、网站页面和 prompt 搜索场景使用。

## 授权

见 [LICENSE](LICENSE)。
