# resources

本目录收录插件运行/部署时需要的配套文件（不属于插件运行时打包内容，`scripts/deploy.sh` 不打包本目录）。

| 文件 | 说明 |
|---|---|
| `waydroid-gamemode.sh` | Deck 上由 home-manager 管理的游戏模式入口脚本源文件。分辨率统一开关依赖它读取 `~/.local/share/waydroid/gamemode-resolution`，并在 Android 起来后执行 `waydroid prop set persist.waydroid.width/height`。 |

安装/更新方法见根目录 `README.md` 的「安装/更新配套启动脚本」小节。
