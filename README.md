# AI 排行榜 · 官方更新通道

这里保存现有客户端使用的固定更新文件。**下载和项目介绍请优先访问主仓库**，本仓库不是独立应用。

**[下载正式 Android APK](https://github.com/Aigooz/ai-rankboard/releases/latest/download/app-release.apk)** · [版本说明](https://github.com/Aigooz/ai-rankboard/releases/latest) · [项目源码](https://github.com/Aigooz/ai-rankboard) · [网页版](https://aigooz.github.io/ai-rankboard/)

当前 Android 版本：**0.20.20**（versionCode 70），Android 8.0+，包名 `com.ai.rankboard`。

## 备用下载与文件说明

- [app-release.apk](https://raw.githubusercontent.com/Aigooz/ai-rankboard-updates/main/app-release.apk)：原签名正式安装包，支持覆盖升级。
- [app-update.json](https://raw.githubusercontent.com/Aigooz/ai-rankboard-updates/main/app-update.json)：应用版本、下载地址、SHA-256、文件大小及版本说明；保留旧客户端兼容字段。
- `leaderboards.json` / `.sha256`：历史兼容快照。**当前榜单数据以主仓库的 [leaderboards.json](https://raw.githubusercontent.com/Aigooz/ai-rankboard/main/leaderboards.json) 为准**，不要用本仓库历史文件判断数据新鲜度。

新版 Android 已内置官方更新地址，不需要用户手动填写。系统通知和后台检查受 Android 权限、省电及网络限制，不是实时服务器推送。

iOS 清单字段为兼容用途，链接指向未签名构建流程，不代表可直接安装的 iOS 正式发行版。

## 维护约定

安装包与清单须在同一个提交中更新，保持文件哈希和版本一致；不得更换原发布签名或删除旧客户端依赖的固定地址。主仓库的正式 Release 会从这里读取签名包并再次校验，详见 [发布指南](https://github.com/Aigooz/ai-rankboard/blob/main/docs/RELEASING.md)。问题反馈请前往 [主仓库 Issues](https://github.com/Aigooz/ai-rankboard/issues)。
