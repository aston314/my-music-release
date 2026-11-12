# My Music+

插件驱动的音乐播放器。

本仓库提供经过校验的正式 Android APK、版本说明、更新清单，以及插件市场的公共目录缓存。应用源代码保存在私有仓库，不在这里发布。

[下载安装包](https://github.com/aston314/my-music-release/releases/latest)

国内网络使用应用内置下载线路，失败后自动尝试下一条及 GitHub 直连。首次安装带“版本更新”功能的新版本需手动覆盖安装；之后可在应用设置中检查更新。

每份 APK 均附有 update.json 和 SHA256SUMS.txt。请使用同一签名的正式包覆盖升级，以保留账号、音乐源和设置。

插件目录位于 [plugin-catalog.json](plugin-catalog.json)，由 GitHub Action 每 6 小时从 [MyGo Music 官方插件页面](https://music.egoist.dev/zh/plugins)同步一次，也可在 Actions 手动运行。同步失败或目录异常时保留上次成功的数据。目录用于 App 展示插件市场，插件包与版本仍由各自原仓库提供。
