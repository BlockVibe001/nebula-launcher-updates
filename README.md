# 星云启动器（Nebula Launcher）更新仓库

本仓库用于承载 **星云启动器** 的版本更新信息。

## 启动器如何使用本仓库

启动器「设置 → 更新地址」默认指向本仓库：

```
https://github.com/BlockVibe001/nebula-launcher-updates
```

启动器点击「检查更新」时，会读取本仓库最新的 Release（tag_name），并与当前版本号比较：

- tag 版本高于当前版本 → 提示有新版本，并提供 Release 下载页链接；
- tag 版本等于当前版本 → 提示已是最新。

## 如何发布新版本（重要）

1. 在 GitHub 网页打开本仓库 → 右侧 **Releases** → **Draft a new release**；
2. **Tag** 填写版本号（格式 `vX.Y.Z`，如 `v1.0.0`、`v0.1.1`），**版本号必须大于当前启动器版本**，否则不会被识别为更新；
3. 填写标题与更新说明；
4. 点击 **Publish release** 发布。

> 注意：只有已发布的 Release（且带版本 tag）才会被启动器识别；草稿（Draft）不会被读到。
