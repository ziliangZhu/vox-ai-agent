# VoxAgent

VoxAgent is a telephony runtime for AI agents. It helps AI builders connect existing text agents, workflows, and business systems to real phone scenarios.

VoxAgent 是面向 AI Agent 的电话语音运行时，帮助团队把现有 Text Agent、AI 工作流和业务系统接入真实电话场景。

[Official Website / 官网](https://vox-ai.teddymobile.cn/) · [Product Overview / 产品介绍](https://vox-ai.teddymobile.cn/product) · [Request Trial / 申请试用](https://vox-ai.teddymobile.cn/trial/apply) · [Contact / 联系我们](./CONTACT.md)

## What Is VoxAgent? / VoxAgent 是什么？

VoxAgent provides the runtime layer between AI agents and real telephone networks. It is designed for teams that already have an AI agent, LLM workflow, RAG system, or business automation flow and want to make it work through phone calls instead of only web chat or browser voice demos.

VoxAgent 提供 AI Agent 与真实电话网络之间的运行时层。它适合已经拥有 AI Agent、LLM 工作流、RAG 系统或业务自动化流程，并希望把能力从网页聊天、浏览器语音 Demo 扩展到真实电话通话的团队。

VoxAgent focuses on phone entry, real-time voice interaction, runtime events, webhook integration, trial workflows, and production access preparation. Teams keep control of their own LLM, prompts, business logic, RAG, and tools while VoxAgent handles the telephony runtime layer.

VoxAgent 聚焦电话入口、实时语音交互、运行时事件、Webhook 集成、试用流程和生产接入准备。团队仍然掌控自己的 LLM、Prompt、业务逻辑、RAG 和工具调用，VoxAgent 负责电话语音运行时这一层。

## Who It Is For / 适合谁？

- AI builders moving existing text agents into real phone calls. / 希望把现有 Text Agent 接入真实电话通话的 AI Builder。
- AI sales teams handling lead follow-up, qualification, appointment confirmation, and batch outbound calls. / 需要线索跟进、意向筛选、预约确认和批量外呼的 AI 销售团队。
- AI customer service teams building inbound support, callbacks, surveys, and multi-turn clarification flows. / 构建来电接待、回访、满意度调研和多轮澄清流程的 AI 客服团队。
- AI medical, education, legal, financial, and professional service teams that need long conversations and traceable processes. / 需要长对话、流程可追溯的医疗随访、教育、法律、金融和专业服务团队。
- Product and engineering teams that do not want to build carrier access, number resources, SIP handling, voice runtime, and production access workflows from scratch. / 不希望从零自建线路接入、号码资源、SIP 处理、语音运行时和生产接入流程的产品与工程团队。

## Core Capabilities / 核心能力

- **Phone number and call entry / 电话号码与通话入口**: inbound calls, outbound calls, and batch outbound call scenarios. / 支持来电、外呼和批量外呼场景。
- **Real-time voice runtime / 实时语音运行时**: low-latency phone conversation support for long, multi-turn, high-interaction scenarios. / 面向长通话、多轮对话和高互动场景提供低延迟电话语音交互能力。
- **Runtime event model / 运行时事件模型**: call lifecycle, ASR transcript, agent response, and call completion events. / 覆盖通话生命周期、ASR 转写、Agent 回复和通话结束事件。
- **Webhook integration / Webhook 集成**: connect phone events with existing AI agents, business systems, and automation services. / 将电话事件连接到现有 AI Agent、业务系统和自动化服务。
- **Developer portal workflow / 开发者门户流程**: trial application, sandbox validation, production preparation, and access review. / 支持试用申请、沙箱验证、生产准备和接入审核流程。

## Common Scenarios / 常见场景

- **AI Sales / AI 销售**: lead follow-up, opportunity qualification, appointment confirmation, and CRM workflow integration. / 线索跟进、商机筛选、预约确认和 CRM 流程集成。
- **AI Customer Service / AI 客服**: inbound support, callback handling, satisfaction surveys, and conversation summaries. / 来电接待、回访处理、满意度调研和通话总结。
- **AI Medical Follow-Up / AI 医疗随访**: medication reminders, recovery tracking, revisit reminders, and traceable follow-up records. / 用药提醒、恢复跟踪、复诊提醒和可追溯随访记录。
- **AI Education / AI 教育**: oral practice, trial lesson conversion, after-class follow-up, and continuous learning tracking. / 口语练习、试听课转化、课后回访和持续学习跟踪。
- **Professional Services / 专业服务**: consultation triage, information collection, identity checks, and rule-constrained conversations. / 咨询分流、信息收集、身份核验和规则约束型对话。

## Public Resources / 公开资源

- Official website / 官网: https://vox-ai.teddymobile.cn/

## Current Status / 当前状态

VoxAgent is available through the official website and developer portal. Public product pages and documentation can be read without login. Trial, sandbox, organization, bot configuration, and production access workflows may require registration, review, or authentication.

VoxAgent 已通过官网和开发者门户对外展示。公开产品页面和文档无需登录即可阅读。试用、沙箱、组织、Bot 配置和生产接入流程可能需要注册、审核或身份认证。

See [ROADMAP.md](./ROADMAP.md) for public-facing product directions.

查看 [ROADMAP.md](./ROADMAP.md) 了解对外产品方向。

## Contact Us / 联系我们

For product evaluation, trial access, integration discussion, or partnership inquiries, start from the official website:

如需产品评估、试用接入、集成讨论或商务合作，请优先通过官网和以下方式联系我们：

- Website / 官网: https://vox-ai.teddymobile.cn/
- Trial application / 申请试用: https://vox-ai.teddymobile.cn/trial/apply
- Email / 邮箱: zhuziliang@teddymobile.cn
- GitHub contact guide / GitHub 联系说明: [CONTACT.md](./CONTACT.md)

For DingTalk contact, see [CONTACT.md](./CONTACT.md).

如需通过钉钉联系，请查看 [CONTACT.md](./CONTACT.md)。

## Repository Scope / 仓库范围

This repository is maintained as a public project introduction and community-facing information hub. It may include product documentation, website links, contact information, roadmap notes, and supporting materials, but it should not be treated as a complete production deployment package.

本仓库作为公开项目介绍和社区信息入口维护，主要包含产品介绍、官网链接、联系方式、路线图和相关公开材料，不应被视为完整的生产部署包。

Source code, environment variables, credentials, private customer data, production phone numbers, and account-specific configuration are not provided through this public repository.

本公开仓库不提供源码、环境变量、凭证、私有客户数据、生产电话号码或账号级配置。

## Legal Notice / 法律说明

Unless explicitly stated otherwise, all product names, trademarks, documentation, images, and brand materials in this repository are provided for project introduction and community engagement only. See [LICENSE](./LICENSE) for details.

除非另有明确说明，本仓库中的产品名称、商标、文档、图片和品牌材料仅用于项目介绍和社区沟通。详情请查看 [LICENSE](./LICENSE)。
