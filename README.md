# oneday-pinger

OneDay APP 的推送提醒定时器：每 10 分钟调用一次 `/api/push/reminders/run-due`，到点的提醒（每日自检 / 每周复盘）由服务端发推送。提醒时间在 OneDay 设置页配置。

仅含定时 workflow，无任何应用代码 / 数据。
