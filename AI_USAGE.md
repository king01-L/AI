# AI 使用声明 · AI Usage Statement

| 项目 | 内容 |
| --- | --- |
| 仓库 | [king01-L/AI](https://github.com/king01-L/AI) |
| 维护者 | [@king01-L](https://github.com/king01-L) |
| 文档版本 | v1.0 |
| 生效日期 | 2026-11-05 |
| 适用范围 | 本仓库全部内容，包括文档、代码、测试、示例数据与提交记录 |
| 许可 | 以仓库根目录 `LICENSE` 为准；未提供 `LICENSE` 时默认保留所有权利 |

## 摘要

本仓库在创作与维护过程中可能使用生成式人工智能（AI）工具作为**辅助手段**。所有内容均经过人类作者审核，最终由人类作者对准确性、合法性与安全性负责。本声明说明 AI 的使用范围与程度、内容标识方式、人工审核流程，以及数据、隐私与知识产权方面的边界。

> 本声明文档自身在 AI 辅助下起草，经维护者审阅后发布，符合本声明第 4 节所述标识规则。

## 1. 目的与原则

本声明用于向访问者、使用者与贡献者透明披露 AI 参与情况，并确立以下原则：

1. **透明**：如实披露 AI 参与的环节与程度，不隐瞒、不夸大。
2. **可追溯**：关键内容保留人工审核记录，必要时可回溯至具体提交。
3. **人类负责**：AI 是工具而非作者，全部责任由人类维护者承担。
4. **最小必要**：仅向 AI 工具提供完成任务所必需的信息，避免过度共享。

## 2. AI 工具的使用范围

| 用途 | AI 参与程度 | 说明 |
| --- | --- | --- |
| 文档起草、润色与排版 | 辅助 | 由 AI 生成提纲或措辞，人工调整与定稿 |
| 代码生成与重构 | 辅助 | 样板代码、注释、单元测试；核心逻辑由人工设计并复核 |
| 调试与排错 | 辅助 | 用于分析日志、提出假设，结论以实际复现为准 |
| 数据分析与可视化 | 辅助 | 用于探索性分析与绘图草稿，结果须人工验证 |
| 翻译与术语对照 | 辅助 | 术语一致性检查，专有名词以人工确认为准 |
| 设计与创意 | 辅助 | 灵感与方案候选，最终设计由人工决定 |
| 事实性结论与引用 | 不使用或仅作线索 | 事实、数据与引用必须人工核查原始来源 |

**明确禁止**的用法包括：生成虚假信息或伪造数据/引用、冒充他人身份、规避平台审核机制、侵犯他人隐私或知识产权，以及任何违反法律法规或所用 AI 工具服务条款的行为。

## 3. 人工审核与责任划分

1. 人类维护者对本仓库全部内容的准确性、合法性、安全性与完整性负责。
2. 所有 AI 输出一律视为**草稿**，须经人工阅读、验证与修改后方可采纳。
3. 代码须通过构建、测试与代码审查；文档须核对事实、来源与引用后方可发布。
4. 若发现 AI 导致的错误，维护者应及时修正，并在提交说明中注明修正原因。

## 4. AI 生成内容的标识

### 4.1 标识等级

| 标识 | 含义 |
| --- | --- |
| `Human-only` | 未使用 AI 参与创作 |
| `AI-assisted` | 内容由人类主导，AI 参与起草、补全或润色 |
| `AI-generated` | 内容主要由 AI 产出，经人工审核与修订后采纳 |

### 4.2 标识方式

- **文档**：在文末或相关章节注明标识等级与 AI 参与范围。
- **代码**：在文件头或相关函数/模块的注释中注明。
- **提交记录**：在 commit message 中使用 trailer，例如：

```text
AI-Assisted: yes (tool: <工具或模型名称>; scope: docs|code|tests)
Reviewed-by: <审核人>
```

### 4.3 标识的作用与边界

标识仅用于透明披露，**不构成对内容质量或权利状态的背书**。未标注的内容不等于未使用 AI；标注亦不豁免第 3 节规定的人工审核责任。

## 5. 数据与隐私保护

1. 不向第三方 AI 服务提交：访问令牌与密钥、个人身份信息、未公开的第三方数据、受保密协议约束的材料。
2. 使用前确认工具的数据留存、日志与训练政策；对敏感场景优先采用本地或离线模型。
3. 示例数据应为合成数据或已获授权的数据，不包含可识别到个人的真实信息。
4. 遵循数据最小化原则：只提交与任务直接相关的内容。

## 6. 知识产权与许可

1. 本仓库内容的授权条件以根目录 `LICENSE` 文件为准；未声明许可时默认保留所有权利。
2. 对于 AI 生成或 AI 辅助的内容，维护者仅就人类创作部分主张权利，不对 AI 工具的输出主张额外权利；同时不保证此类内容在全球范围内不存在第三方权利主张。
3. 引用第三方资料时须注明来源并遵守其许可条款。AI 工具给出的"引用"须逐条核实，不得直接采信。
4. 本声明不构成法律意见。如需商业使用，请自行开展权利尽职调查。

## 7. 事实核查与局限性

1. 生成式 AI 可能产生不准确、过时、不完整或看似合理但实际错误的内容（即"幻觉"）。
2. 本仓库内容仅供学习、研究与参考，**不构成法律、医疗、财务或其他专业建议**。
3. 对外发布或据此作出决策前，请以权威原始来源为准。
4. 若发现内容错误，欢迎通过 Issue 反馈，维护者将尽快核实与更正。

## 8. 合规与伦理

使用者与贡献者应遵守所在司法辖区的法律法规、GitHub 社区准则以及所用 AI 工具的服务条款。不得利用本仓库或 AI 工具从事骚扰、歧视、欺骗、制造虚假信息或其他有害行为。

## 9. 使用记录

| 日期 | 环节 | 工具/模型 | 参与程度 | 人工处理 |
| --- | --- | --- | --- | --- |
| 2026-11-05 | 本声明文档起草与措辞润色 | DeepSeek（大语言模型） | 辅助 | 维护者审阅、修订并提交 |

> 后续如有新增 AI 使用场景，请在此表追加记录，保持与第 4 节标识一致。

## 10. 更新与联系

本声明随仓库演进持续更新。对声明内容有疑问、异议或改进建议，欢迎通过仓库 [Issues](https://github.com/king01-L/AI/issues) 联系维护者。

| 版本 | 日期 | 变更说明 |
| --- | --- | --- |
| v1.0 | 2026-11-05 | 首次发布 |

---

## English Summary

This repository may use generative AI tools as **assistive instruments** in drafting documentation, generating boilerplate code, debugging, and polishing text. All content is reviewed by a human maintainer, who remains solely responsible for its accuracy, legality, and safety.

- AI outputs are treated as drafts and must be verified before adoption.
- AI involvement is disclosed with three levels: `Human-only`, `AI-assisted`, and `AI-generated`.
- No secrets, personal data, or confidential third-party material are submitted to AI services.
- Facts, data, and citations are verified against primary sources; AI-provided references are never trusted blindly.
- This statement is not legal advice, and the repository content is not professional advice.

For questions, please open an issue at <https://github.com/king01-L/AI/issues>.