<!-- SPDX-License-Identifier: Apache-2.0 -->

# 安全策略

## 报告漏洞

请使用 GitHub 的**私密漏洞报告**，不要通过公开的 issue、pull request 或讨论报告安全问题。

1. 打开受影响仓库的 **Security** 页，选择 **Report a vulnerability**（地址为 `https://github.com/akari-project/<仓库>/security/advisories/new`）。
2. 说明受影响的仓库、版本或提交、复现步骤、影响范围，以及你建议的修复方式（如有）。
3. 报告中不要附带真实用户的数据、凭据或令牌；需要示例时请使用测试数据。

不确定问题属于哪个仓库时，在 [panel](https://github.com/akari-project/panel/security/advisories/new) 仓库报告。

## 响应时限

| 阶段 | 时限 |
|---|---|
| 确认收到 | 3 个工作日内 |
| 初步评估（是否确认、严重程度） | 10 个工作日内 |
| 发布修复 | 严重与高危 30 天内；其他 90 天内 |

修复发布后，我们会发布 GitHub 安全公告，并在报告者同意时致谢。请在修复发布或报告满 90 天之前（以先到者为准）不要公开细节；需要延长时我们会与你协商。

## 支持的版本

| 版本 | 是否提供安全修复 |
|---|---|
| 1.0 之前 | 只修复各仓库默认分支的最新代码，不回溯到旧提交 |

1.0 发布后，本表改为列出获得安全修复的版本线。

## 范围

- 范围内：`panel`、`panel-spec`、`node-agent`、`client`、`workspace`，以及 `sing-box`、`xray-core` 两个 fork 中本组织的补丁（见各 fork 的 `PATCHES.md`）。
- 内核本身（sing-box、Xray-core）或 Xboard-Node 上游代码中的问题，请同时报告给对应的上游项目；我们会在确认后跟进修复。
- 部署者自行配置导致的问题（如弱口令、公开的管理端口）不在范围内，但欢迎通过普通 issue 提出文档改进建议。
