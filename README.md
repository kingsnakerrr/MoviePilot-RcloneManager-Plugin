# MoviePilot Rclone Manager 控制台插件

MoviePilot V2 的独立插件仓库。这里**只维护 MoviePilot 插件**；Rclone Manager 本体继续在 [dbonline-media-stack](https://github.com/kingsnakerrr/dbonline-media-stack/tree/main/rclone-manager) 更新。

在 MoviePilot V2 的插件市场添加第三方仓库：

```text
https://github.com/kingsnakerrr/MoviePilot-RcloneManager-Plugin
```

然后安装“Rclone Manager 控制台”。插件只负责独立服务的安装状态、启动／停止、实时传输监控及原管理页面跳转，不会替代或修改 Rclone Manager 的传输任务。部署条件与安全注意事项见 [插件说明](plugins.v2/rclonemanager/README.md)。

插件目录：`plugins.v2/rclonemanager`；市场清单：`package.v2.json`。后续插件版本只在本仓库发布，原仓库中的旧插件文件仅作为兼容存档。
