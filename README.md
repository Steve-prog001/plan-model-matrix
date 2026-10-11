# plan-model-matrix

两份 AI 订阅计划的模型数据汇总页：散点图 + 次数表 + 价格表 + 月 tokens，方便自查。

- **GOAT**（`goat.html`）：Command Code GOAT 计划
- **Go**（`go.html`）：opencode Go 计划

每页包含：

- 📊 散点图：每 5 小时 / 每周 / 每月 / 月 tokens 四个视图（月 tokens 按统一口径折算、对数轴），纵轴 = 智能指数（Artificial Analysis Intelligence Index）
- 📋 次数表：每 5 小时 / 每周 / 每月可用次数
- 💰 价格表：输入 / 输出 / 缓存读 / 缓存写 / 每月额度（额度列附「≈ 月 tokens」折算小字）
- 🖼 图表可导出 PNG（导出配色跟随当前明暗主题）

数据来源：官方计划文档 + Artificial Analysis 评测分，每日 2 次（09:00 / 19:00）自动同步。

> ⚠️ 两家官方的次数计算口径不同，两页横轴**不能直接对比**，仅供各自查阅。
>
> 📐 月 tokens 统一口径：混合单价 = 97%×缓存读价 + 2.5%×输入价 + 0.5%×输出价；第三方实测实际可得约为表中值的 0.6–0.9 倍。

在线查看：https://steeeve.top/plan/goat/ · https://steeeve.top/plan/go/

本地打开 `goat.html` / `go.html` 可直接查看页面（单文件静态、无构建）；图表数据由在线站点实时加载。
