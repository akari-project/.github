## 任务

<!-- backlog 任务编号，例如 M1-06；没有对应任务时说明原因。 -->

## 规则编号

<!-- 本 PR 满足的规则编号，例如 BIL-07、CONV-12。 -->

## 验收标准

<!-- 逐条列出 backlog 中该任务的验收标准，并写明验证方式（自动化测试名称，或记录的手动验收过程，ENG-06）。 -->

- [ ] 1.
- [ ] 2.

## 检查清单

- [ ] 本仓库 `make ci` 通过（本地与 CI）
- [ ] 涉及 proto：`buf breaking` 通过；涉及 OpenAPI：Redocly lint 与 oasdiff 通过
- [ ] 新文件带 SPDX 头（CONV-25）；来自上游、不补头的文件已登记到 `REUSE.toml`
- [ ] 没有新增对外禁用词（subscribe、server、node、traffic，spec/30 API-01）
- [ ] 代码、日志、测试数据与 PR 描述中不含令牌、密码、密钥或代理凭据（CONV-24）
- [ ] 一次提交只改一个仓库；协议或接口变更已先在 `panel-spec` 合入（ARC-01、ARC-02）
- [ ] node-agent：修改原有文件已登记到 `UPSTREAM.md`
- [ ] 每个提交带 `Signed-off-by`（DCO，`git commit -s`）
- [ ] backlog 中该任务的状态已更新
