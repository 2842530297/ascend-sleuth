# Fork + PR 通路测试

这份文件用来验证一个 GitHub 细粒度令牌能否走通「fork → 提交 → 申请合并」这条链路。它由测试脚本通过 GitHub API 生成，不含项目内容。

- 验证时间：2026-11-24（Asia/Shanghai）
- 上游仓库：`pillumina/ascend-sleuth`；fork：`2842530297/ascend-sleuth`
- 发起方式：REST API 创建分支与提交，未改动本地工作副本

分支创建成功说明令牌对这个 fork 有写权限；本 PR 创建成功说明令牌在上游仓库有发起合并请求的权限。测试到此为止，可以关闭这个 PR，不需要合入。
