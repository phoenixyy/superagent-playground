# superagent-playground
superagent-playground-test-dsh

## 项目简介

本仓库是 dsh-superagent 的测试仓库，用于验证自动化代理处理 Issue、提交 PR 和响应评审的流程，不包含生产代码。

This repository is a test repository for dsh-superagent. It is used to exercise how the automated agent handles issues, opens pull requests and responds to reviews, and contains no production code.

### 使用说明

1. 新建 Issue 描述需求，并在正文或评论中 `@yuanyao-dsh-super-agent` 触发代理处理。
2. 代理确认请求后会从独立分支提交 PR，请在 PR 中审阅改动并留下评审意见。
3. 本仓库仅用于测试，请勿提交敏感信息或真实业务数据；PR 由人工审阅后合并。

## 常见问题

**问：这个仓库是做什么用的？**

答：这是一个用于测试 DSH Super Agent 的演练仓库，用来验证 Agent 从接收需求到提交 PR 的完整流程，不包含正式的业务代码。

**问：我可以在这里提交改动吗？**

答：可以。建议从 `main` 新建分支并通过 Pull Request 提交，经审核后再合并。
