# plan-model-matrix

两份 AI 订阅计划的模型数据汇总页：散点图 + 次数表 + 价格表，方便自查。

- **GOAT**（`goat.html`）：Command Code GOAT 计划
- **Go**（`go.html`）：opencode Go 计划

每页包含：

- 📊 散点图：横轴 = 该计划下每 5 小时可用次数，纵轴 = 智能指数（Artificial Analysis Intelligence Index）
- 📋 次数表：每 5 小时 / 每周 / 每月可用次数
- 💰 价格表：输入 / 输出 / 缓存读 / 缓存写 / 每月额度

数据来源：官方计划文档 + Artificial Analysis 评测分，每日自动同步。

> ⚠️ 两家官方的次数计算口径不同，两页横轴**不能直接对比**，仅供各自查阅。

在线查看：https://steeeve.top/plan/goat/ · https://steeeve.top/plan/go/

本地打开 `goat.html` / `go.html` 即可浏览（静态单文件，无构建）。
