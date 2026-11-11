# 开源 Skill / 工具精选（useful-oss-skills）

> 由「开源Skill猎手」维护的精选清单，面向跨境电商运营、自动化与 AI 助理场景。

## 简介

本仓库汇总**活跃维护、文档相对清楚、可复用**的开源项目与 AI Agent Skill（含工具、框架、MCP/连接器、工作流模板）。

**筛选标准（摘要）**

- 近一年仍有推送（优先 2025 年后活跃）
- 文档/说明可读，星标与社区采用有一定参考价值（小众但强相关的跨境工具也会收录）
- 可复用：Skill 包、MCP、自动化框架、电商 SDK、内容流水线等
- **不编造**星标与描述；数据来自 GitHub 公开检索（抓取日见文末）

**更新节奏**

- 每周一约 09:00（Asia/Shanghai）例行更新
- 用户说「更新开源清单」时可立刻刷新

**第一版条目数**：25

## 目录

- [AI Agent / Skills](#AI-Agent-Skills)
- [MCP 与连接器](#MCP-与连接器)
- [自动化与爬虫](#自动化与爬虫)
- [电商与运营](#电商与运营)
- [内容与图片](#内容与图片)
- [通用效率](#通用效率)
- [线下门店](#线下门店)

## AI Agent / Skills

### [anthropics/skills](https://github.com/anthropics/skills)

- **一句话**：Anthropic 官方 Agent Skills 公开仓库，可复用的技能包与规范参考。
- **适合场景**：给 Claude / 兼容 Agent 装官方技能，做二次开发与规范对齐
- **星标**：186,964
- **近况**：最近推送约 2026-10-28（GitHub `pushed_at` UTC 日期）

### [obra/superpowers](https://github.com/obra/superpowers)

- **一句话**：面向编程 Agent 的技能框架与软件开发方法论，社区采用极广。
- **适合场景**：统一 Claude Code / Cursor 等编码 Agent 的工作流与技能体系
- **星标**：311,545
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)

- **一句话**：收录 2800+ 可复用 AI Agent Skills，覆盖 Claude Code、Codex、Cursor、Gemini CLI。
- **适合场景**：快速检索现成技能包，扩展客服、运营、开发助手能力
- **星标**：49,079
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

## MCP 与连接器

### [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)

- **一句话**：社区主流 MCP Server 精选目录，按场景与语言分类齐全。
- **适合场景**：挑选浏览器、数据库、电商、办公类 MCP 插件
- **星标**：97,239
- **近况**：最近推送约 2026-11-02（GitHub `pushed_at` UTC 日期）

### [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)

- **一句话**：Model Context Protocol 官方参考服务器集合。
- **适合场景**：学习标准 MCP 实现，对接文件系统、Git、浏览器等基础能力
- **星标**：91,765
- **近况**：最近推送约 2026-10-29（GitHub `pushed_at` UTC 日期）

### [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp)

- **一句话**：微软官方 Playwright MCP Server，让 Agent 操控浏览器。
- **适合场景**：在 Claude / Cursor 里驱动网页操作、测试与抓取
- **星标**：39,118
- **近况**：最近推送约 2026-11-01（GitHub `pushed_at` UTC 日期）

### [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server)

- **一句话**：Firecrawl 官方 MCP：搜索、抓取、结构化网页上下文给 Agent。
- **适合场景**：竞品调研、商品页解析、知识库采集接入 Agent
- **星标**：7,755
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp)

- **一句话**：Shopify API 的 MCP Server，可在 Claude / Cursor 中调用店铺能力。
- **适合场景**：Shopify 店铺商品、订单相关操作的 Agent 化
- **星标**：239
- **近况**：最近推送约 2026-04-05（GitHub `pushed_at` UTC 日期）

## 自动化与爬虫

### [browser-use/browser-use](https://github.com/browser-use/browser-use)

- **一句话**：开源 AI 浏览器 Agent 库，支持本地与云端隐身浏览器。
- **适合场景**：卖家后台自动化、多站点流程、登录态网页任务
- **星标**：119,918
- **近况**：最近推送约 2026-11-02（GitHub `pushed_at` UTC 日期）

### [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern)

- **一句话**：用视觉 + LLM 自动化浏览器工作流的开源 RPA。
- **适合场景**：页面结构常变的后台操作、表单填写、跨站流程
- **星标**：23,336
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [microsoft/playwright](https://github.com/microsoft/playwright)

- **一句话**：跨浏览器 Web 自动化与测试框架，生态完善。
- **适合场景**：稳定脚本化店铺操作、E2E 测试、页面抓取底座
- **星标**：99,171
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [n8n-io/n8n](https://github.com/n8n-io/n8n)

- **一句话**：可自托管的工作流自动化平台，原生支持 AI 节点。
- **适合场景**：订单通知、库存同步、客服工单、定时运营流水线
- **星标**：209,432
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [enescingoz/awesome-n8n-templates](https://github.com/enescingoz/awesome-n8n-templates)

- **一句话**：280+ 免费 n8n 模板，覆盖 Gmail、表格、消息与常见 SaaS。
- **适合场景**：快速复用现成运营与办公自动化流程
- **星标**：26,244
- **近况**：最近推送约 2026-09-12（GitHub `pushed_at` UTC 日期）

### [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai)

- **一句话**：面向 LLM 的开源爬虫，把网页转成干净 Markdown。
- **适合场景**：竞品页、政策页、商品详情采集后喂给 Agent / RAG
- **星标**：86,822
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)

- **一句话**：为 AI Agent 设计的网页数据 API / 爬取库。
- **适合场景**：大规模站点抓取、搜索增强、结构化数据抽取
- **星标**：198,164
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

## 电商与运营

### [medusajs/medusa](https://github.com/medusajs/medusa)

- **一句话**：面向开发者与 Agent 的灵活开源电商平台。
- **适合场景**：自建独立站 / headless 商城、订单与目录 API
- **星标**：37,069
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [easycb/easycb-go](https://github.com/easycb/easycb-go)

- **一句话**：Go 语言跨境卖家开放平台 SDK：TikTok Shop、Shopee、Lazada、SHEIN、Ozon 等。
- **适合场景**：多平台订单/商品接口对接、跨境卖家工具后端
- **星标**：173
- **近况**：最近推送约 2026-08-24（GitHub `pushed_at` UTC 日期）

### [Shopify/shopify_python_api](https://github.com/Shopify/shopify_python_api)

- **一句话**：Shopify 官方 Python Admin API 客户端库。
- **适合场景**：用 Python 管理 Shopify 商品、订单与应用集成
- **星标**：1,430
- **近况**：最近推送约 2026-08-25（GitHub `pushed_at` UTC 日期）

### [BetaStreetOmnis/xhs_ai_publisher](https://github.com/BetaStreetOmnis/xhs_ai_publisher)

- **一句话**：小红书 AI 内容创作与发布工具（桌面端 + FastAPI + 浏览器自动化）。
- **适合场景**：种草内容生成、预览发布、社媒引流获客
- **星标**：2,095
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

## 内容与图片

### [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI)

- **一句话**：模块化扩散模型 GUI / API，本地图像与工作流生产主力。
- **适合场景**：商品主图、详情图、广告素材批量生成与节点工作流
- **星标**：144,787
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)

- **一句话**：强大 OCR / 文档结构化工具，把图片与 PDF 变成可用数据。
- **适合场景**：发票、面单、包装图、竞品截图文字提取
- **星标**：92,190
- **近况**：最近推送约 2026-09-16（GitHub `pushed_at` UTC 日期）

### [blader/humanizer](https://github.com/blader/humanizer)

- **一句话**：Agent Skill：去除 AI 写作痕迹，让文案更自然。
- **适合场景**：Listing、社媒文案、客服话术润色去 AI 感
- **星标**：64,203
- **近况**：最近推送约 2026-10-28（GitHub `pushed_at` UTC 日期）

## 通用效率

### [langgenius/dify](https://github.com/langgenius/dify)

- **一句话**：开源 LLM 应用平台：Agent 工作流、RAG、工具编排。
- **适合场景**：自建客服 Agent、知识库问答、运营助手后台
- **星标**：160,317
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)

- **一句话**：AI Agent Skill 安全扫描器，检测恶意与风险技能。
- **适合场景**：安装第三方 Skill / MCP 前做安全体检
- **星标**：24,105
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）

### [googleworkspace/cli](https://github.com/googleworkspace/cli)

- **一句话**：Google Workspace CLI（Drive/Gmail/Calendar/Sheets 等），含 AI agent skills。
- **适合场景**：用命令行 / Agent 操作表格、邮件、日历做运营协作
- **星标**：32,079
- **近况**：最近推送约 2026-11-03（GitHub `pushed_at` UTC 日期）


## 线下门店

面向线下电器店等实体零售：进销存、收银 POS、客户与售后维修单、下单；优先中文可用、可接微信小程序。星标与推送时间来自 GitHub API（检索日 2026-11-11），推送日期已换算为 Asia/Shanghai。

### [jishenghua/jshERP](https://github.com/jishenghua/jshERP)

- **一句话**：国产开源进销存 ERP（管伊佳，原华夏 ERP），覆盖零售、采购、销售、仓库与财务，可商用。
- **适合场景**：电器店日常进销存、零售开单、采购入库、库存调拨与组装拆卸；不含专用维修工单，微信移动端主要在官方网络版。
- **上手难度**：中（需自建服务器，部署 Java 8 + MySQL + Redis + Nginx；有中文部署教程与打包文件）
- **许可证/限制**：Apache-2.0，开源可商用；官方另有网络版（约 198 元/年）与付费插件。
- **星标**：4,697
- **近况**：最近推送 2026-11-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-11T07:03:26Z）

### [fushengqian/fuint](https://github.com/fushengqian/fuint)

- **一句话**：面向实体店的会员营销 + POS 收银系统，支持微信小程序 / H5，打通线上下单与代客收银。
- **适合场景**：电器店前台收银、会员储值/积分/次卡、店员代客下单与小票打印；库存采购深度不如专职 ERP，也无专用维修工单。
- **上手难度**：中（需自建服务器，JDK 17 + MySQL + Redis；可用宝塔降低门槛；前端小程序在配套仓库）
- **许可证/限制**：AGPL-3.0；README 要求保留版权，商用需购买源码授权。
- **星标**：1,800
- **近况**：最近推送 2026-11-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-11T03:35:43Z）

### [gongfuxiang/shopxo](https://github.com/gongfuxiang/shopxo)

- **一句话**：企业级开源商城，支持微信等六端小程序、多门店与进销存（部分能力为应用商店插件）。
- **适合场景**：给电器店做微信小程序下单、多门店核销/代客下单；完整进销存、收银等能力多在应用商店，需单独确认是否免费。
- **上手难度**：中（需自建 PHP 服务器，基于 ThinkPHP 8；有安装与文档站点）
- **许可证/限制**：MIT，核心可商用、可二次开发；进销存 / 多门店 / 收银等扩展常见于官方应用商店，可能收费。
- **星标**：3,349
- **近况**：最近推送 2026-11-03（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-03T11:25:55Z）

### [crmeb/CRMEB](https://github.com/crmeb/CRMEB)

- **一句话**：文档较完善的开源微信小程序商城，覆盖下单、会员与营销，声明可免费商用。
- **适合场景**：顾客用微信小程序浏览电器并下单、会员与优惠券运营；偏线上商城，不是门店进销存或维修工单系统。
- **上手难度**：中偏低（需自建 PHP 服务器；提供 Docker / 宝塔文档，不支持普通虚拟主机）
- **许可证/限制**：Apache-2.0，开源版声明可免费商用、无隐藏功能限制；另有插件/主题市场，扩展可能收费。
- **星标**：9,467
- **近况**：最近推送 2026-10-28（Asia/Shanghai，来自 GitHub `pushed_at` 2026-10-28T07:28:48Z）

### [xmosnewone/ICEPOS-Cashier-System](https://github.com/xmosnewone/ICEPOS-Cashier-System)

- **一句话**：全代码开源的门店收银系统，支持离线、扫码枪、小票打印与微信/支付宝收款。
- **适合场景**：电器店柜台收银、多门店、库存校验与促销；移动端可适配小程序。社区较小，不是完整进销存或维修工单。
- **上手难度**：中偏低（收银端可装在单台 Windows 电脑，另需 PHP 7.2–7.4 + MySQL 后台；有官方安装文档与用户手册）
- **许可证/限制**：Apache-2.0，可商用，但须保留「佛山市顺德区方程软件开发工作室」版权标注。
- **星标**：110
- **近况**：最近推送 2026-06-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-06-11T13:59:01Z）

### [Dolibarr/dolibarr](https://github.com/Dolibarr/dolibarr)

- **一句话**：较轻量的开源 ERP/CRM，含库存、订单、POS 与干预/售后工单，支持多语言（含中文）。
- **适合场景**：想用一套系统管进销存、客户、收银台和上门/售后维修单的电器店；无官方微信小程序。
- **上手难度**：中（需自建 PHP + MySQL/MariaDB；Windows 可用 DoliWamp 一键包，也有 Docker）
- **许可证/限制**：GPL-3.0-or-later，可自用商用，改衍生作品需保持 GPL；部分第三方扩展可能收费。
- **星标**：7,850
- **近况**：最近推送 2026-11-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-11T12:45:50Z）

### [frappe/erpnext](https://github.com/frappe/erpnext)

- **一句话**：功能完整且全部开源的 ERP，含库存、POS、采购、客户支持与资产/序列号管理。
- **适合场景**：需要序列号/质保、库存与售后支持、收银台一体化的电器店；有社区中文翻译，无官方微信小程序。
- **上手难度**：高（需自建 Frappe 环境或 Docker，学习曲线陡，一般要技术人员实施）
- **许可证/限制**：GPL-3.0，模块全部开源可商用，衍生作品需保持 GPL；官方 Frappe Cloud 托管另行收费。
- **星标**：41,187
- **近况**：最近推送 2026-11-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-11T12:43:48Z）

### [odoo/odoo](https://github.com/odoo/odoo)

- **一句话**：生态最全的开源 ERP，社区版含库存、POS、CRM 与维修模块；高级功能多在付费企业版。
- **适合场景**：希望一套系统覆盖进销存、收银、客户和维修工单的电器店；有中文界面，微信需第三方应用。
- **上手难度**：高（需自建 Python + PostgreSQL，或使用官方付费云；模块多、实施复杂）
- **许可证/限制**：社区版 LGPLv3；会计本地化、部分高级 POS/现场服务等常见于付费 Enterprise。GitHub 许可证元数据为 Other。
- **星标**：55,709
- **近况**：最近推送 2026-11-11（Asia/Shanghai，来自 GitHub `pushed_at` 2026-11-11T12:11:41Z）

## 更新记录

### 2026-11-11

- 新增「线下门店」分类，共 8 条（管伊佳 jshERP、fuint、ShopXO、CRMEB、ICEPOS、Dolibarr、ERPNext、Odoo）。
- 数据来源：GitHub `search/repositories` + `get_repository` + README 核对；星标与 `pushed_at` 为检索当日快照，推送日期已换算 Asia/Shanghai。
- 本批侧重：中小电器店进销存、收银 POS、客户/维修单、微信小程序下单；已标注商用限制与是否需自建服务器。

### 2026-11-03（第一版）

- 全部为新增，共 25 条。
- 数据来源：GitHub `search/repositories` + 公开页面核对；星标与推送时间为检索当日快照，后续会漂移。
- 本版侧重：AI Agent Skills、MCP、浏览器/工作流自动化、跨境电商 SDK、内容与图片流水线、通用效率工具。

---

*免责声明：第三方仓库可能要求 API Key、合规审核或存在安全风险。安装 Skill / MCP 前建议用安全扫描（如 NVIDIA/SkillSpector）并遵守各平台服务条款。*
