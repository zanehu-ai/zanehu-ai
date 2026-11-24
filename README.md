### Hi, I'm Zane Hu (胡正兴) 👋

**English** · [简体中文](#简体中文)

**AI Application Architect & Forward-Deployed Engineer (FDE)** · 9+ years building high-compliance distributed systems (**Java · Go · TypeScript**) and shipping production AI engineering workflows.

- 🏛️ **High-Compliance Enterprise Delivery**: Former **Head of Delivery Department at Hangzhou Nuowei**, serving as Technical Lead for a **RMB 20M+ provincial big-data privacy-computing platform** (10 core microservices, FATE interoperability, TEE integration, China MLPS Level 3 & commercial cryptography compliance) and **Dahua Secure Database** delivery (**5 software copyright registrations**).
- ⚙️ **0-to-1 Production Systems (Java · Go · TypeScript)**: Architected a high-concurrency **Java 21 / DDD** multi-tenant community platform (**120K+ cumulative users, ~RMB 5M annual gross receipts**), a **Next.js + PostgreSQL** multi-tenant cross-border SaaS with zero-float strict FIFO ledgers & blue-green zero-downtime releases, and a **Go + Wails v2 + Windows Service** warehouse weighing & scanning edge workstation.
- 🛡️ **Production-Safe AI & Guardrails**: Built open-source reference guardrails for **10-step single-transaction PostgreSQL row-lock AI payments** (`pg-ai-payment-guardrails`) and **deterministic AST anti-drift gates** (`agent-arch-guard`), alongside single-process **Remote MCP** starters (`x-forge`), least-privilege AI ops diagnostics (`x-observe`, zero shell/SSH access), and an on-site **6-role AI executive analytics workflow** for a manufacturing client.
- 🌏 **Location & Focus**: Based in **Hangzhou, China** · Open to senior **AI Architecture**, **Forward-Deployed Engineering (FDE)**, and **Cross-Border FinTech** roles across **Hangzhou, Shanghai, Shenzhen, Singapore & Southeast Asia**.

#### Selected Open-Source Repositories

| Repository | Stack | Focus |
| :--- | :--- | :--- |
| [`agent-arch-guard`](https://github.com/zanehu-ai/agent-arch-guard) | Node 22 · TypeScript · `ast-grep` · `ripgrep` | Deterministic AST architecture guardrails, 300-line diff ratchets & structural code-noise auditor to stop multi-agent coding drift (0 runtime deps, 14 tests + CI) |
| [`pg-ai-payment-guardrails`](https://github.com/zanehu-ai/pg-ai-payment-guardrails) | PostgreSQL · TypeScript · FIFO Ledger | 10-step single-transaction row-lock AI payment guardrails, SHA-256 whitelist & zero-float strict FIFO ledger reference implementation (13 concurrency/rollback tests + CI) |
| [`x-go`](https://github.com/zanehu-ai/x-go) | Go 1.25 · Gin · GORM | Reusable Go backend foundation library across 11 package areas (Config, MySQL/Redis, Auth/RBAC, Idempotency, Outbox, Rate Limiting & Observability) |
| [`x-ui`](https://github.com/zanehu-ai/x-ui) | TypeScript · React · Radix | 123-export accessible component library, AI chat primitives & opt-in theme system (`@zanehu-ai/x-ui`) · [Live Docs](https://ui.opcorbit.com) |
| [`qq-mail-mcp`](https://github.com/zanehu-ai/qq-mail-mcp) | Python 3.12 · MCP · macOS Keychain | Least-privilege read-only email MCP connector with zero-plaintext Keychain credentials |

#### Architecture Essays & Deep Dives (`zanehu.ai`)

- [Production-Safe AI Agent Payments: 10-Step PostgreSQL Row-Lock Guardrails](https://zanehu.ai/posts/opcorbit-architecture-walkthrough)
- [1 Person + N Agents in Production: Isolated Slots, 5-Layer AST Guardrails & Split Review](https://zanehu.ai/posts/multi-agent-engineering-sop)
- [From High-Concurrency DDD Commerce to Zero-Float FIFO Ledgers & Edge Workstations](https://zanehu.ai/case-studies/818cargo-to-opcorbit)
- [What 9 Years of High-Compliance Privacy Computing Taught Me About Building AI Systems](https://zanehu.ai/posts/why-opcorbit)

🌐 **Portfolio**: [zanehu.ai](https://zanehu.ai) ([Work](https://zanehu.ai/work) · [Writing](https://zanehu.ai/writing)) · 💼 **LinkedIn**: [linkedin.com/in/zanehu-ai](https://www.linkedin.com/in/zanehu-ai/) · 📫 **Email**: [zhxing.hu@gmail.com](mailto:zhxing.hu@gmail.com) · 🐦 **X**: [@zanehu_ai](https://x.com/zanehu_ai)

---

## 简体中文

**AI 应用架构师 / 前线部署架构师（FDE）** · 9 年分布式后端架构（**Java · Go · TypeScript 三主栈**）与高合规政企/金融一线交付经验。

- 🏛️ **高合规政企与金融交付负责**：前**杭州锘崴交付部门负责人**（统筹 8–12 人并行交付），作为项目技术负责人主导交付 **2,000 万级省级大数据局隐私计算基础平台**（10 大核心微服务集群、FATE 互联互通、TEE 软硬件联调、三级等保与商用密码评估）及**大华安全数据库**研发交付（沉淀 **5 项软件著作权**），实战支撑上海大数据中心、连连支付及多家大型商业银行 POC。
- ⚙️ **三主栈从 0 到 1 商业与硬件落地**：独立架构 **Java 21 / DDD** 高并发多租户社群交易平台（**累计 12 万+ 用户、年度平台实收流水约 500 万元**）；以 **Next.js + PostgreSQL** 交付多租户跨境商业 SaaS（全整数严格 FIFO 账本、行锁防负余额、蓝绿零停机发布）；以 **Go + Wails v2 + Windows 后台服务** 打造实体仓库称重扫描与离线队列重试工作站。
- 🛡️ **生产级 AI 安全护栏与开源参考实现**：开源了可运行验证的 **10 步 PostgreSQL 行锁 AI 代付护栏**（`pg-ai-payment-guardrails`）与 **多 Agent AST 防漂移门禁 CLI**（`agent-arch-guard`），并落地最小权限 AI 运维诊断（`x-observe`，零 Shell/SSH 授权）、单进程远程 MCP 启动母版（`x-forge`）及制造企业现场 **6 角色 AI 经营分析工作流**。
- 🌏 **意向方向与地区**：坐标**杭州** · 开放探讨 **杭州 / 上海 / 深圳 / 新加坡及东南亚出海** 的高级 AI 应用架构师、前线部署架构师（FDE）与跨境 FinTech 核心架构岗位。

#### 精选原创开源项目

| 仓库 | 技术栈 | 核心能力 |
| :--- | :--- | :--- |
| [`agent-arch-guard`](https://github.com/zanehu-ai/agent-arch-guard) | Node 22 · TypeScript · `ast-grep` · `ripgrep` | 多 Agent 防架构漂移 CLI 与消噪审计器（9 条 AST/棘轮规则，零运行时依赖，14 项单测与绿标 CI） |
| [`pg-ai-payment-guardrails`](https://github.com/zanehu-ai/pg-ai-payment-guardrails) | PostgreSQL · TypeScript · FIFO Ledger | 10 步单事务行锁 AI 代付护栏、收件地址指纹白名单与零浮点严格 FIFO 账本（13 项并发/回滚单测与绿标 CI） |
| [`x-go`](https://github.com/zanehu-ai/x-go) | Go 1.25 · Gin · GORM | 生产级 Go 后端基础组件库（覆盖 11 类核心基础包：配置、MySQL/Redis、鉴权多租户、幂等、事务发件箱、限流熔断与可观测） |
| [`x-ui`](https://github.com/zanehu-ai/x-ui) | TypeScript · React · Radix | 123 项导出的 React 组件库、AI 对话原语与多主题体系（`@zanehu-ai/x-ui`）· [在线文档](https://ui.opcorbit.com) |
| [`qq-mail-mcp`](https://github.com/zanehu-ai/qq-mail-mcp) | Python 3.12 · MCP · macOS Keychain | 最小权限只读邮件 MCP 连接器，凭证零明文托管于 macOS 钥匙串 |

#### 源码级架构深拆文章（`zanehu.ai/zh`）

- [AI 代付防失控实战：10 步单事务 PostgreSQL 行锁护栏](https://zanehu.ai/zh/posts/opcorbit-architecture-walkthrough)
- [1 Person + N Agents 生产研发工程纪律：隔离工位、写审分离与 5 层 AST 门禁](https://zanehu.ai/zh/posts/multi-agent-engineering-sop)
- [从 Java 21 高并发社群平台到跨境 SaaS 全整数 FIFO 账本与 Go 硬件工作站](https://zanehu.ai/zh/case-studies/818cargo-to-opcorbit)
- [九年高合规隐私计算与政企一线交付，如何塑形我的 AI 系统架构观](https://zanehu.ai/zh/posts/why-opcorbit)

🌐 **中文个人主页**：[zanehu.ai/zh](https://zanehu.ai/zh)（[精选作品](https://zanehu.ai/zh/work) · [技术专栏](https://zanehu.ai/zh/writing)） · 💼 **LinkedIn**：[linkedin.com/in/zanehu-ai](https://www.linkedin.com/in/zanehu-ai/) · 📫 **邮箱**：[zhxing.hu@gmail.com](mailto:zhxing.hu@gmail.com)
