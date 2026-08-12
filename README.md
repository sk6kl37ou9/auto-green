# auto-green

每天自动在 GitHub 上生成一次空提交，让贡献墙保持绿色。

## 配置

- 自动提交作者：theone（GitHub 用户名 `sk6kl37ou9`）
- 邮箱使用 GitHub noreply 地址，提交会自动关联到账号
- 默认每天 UTC 00:00（北京时间 08:00）自动跑一次
- 想改时间，编辑 `.github/workflows/ci.yml` 里的 `cron`
- 想立即测试，到仓库 `Actions` 页面点 `Run workflow`

> 这是空提交，只为了让贡献墙好看，不代表真实代码贡献。
