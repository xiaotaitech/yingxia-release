# 影匣

安卓上的影视客户端，有**手机版**和**电视版**两个应用，共用同一套站点配置与播放能力。本仓库只用于发布安装包和使用说明，源码在私有仓库维护。

影匣**不内置任何内容源**，首次打开后需要先导入配置（或手动添加站点）才能看片。

## 下载

| | 适用设备 | 最新版本 | GitHub 打不开时（备用） |
|---|---|---|---|
| **手机版** | 安卓手机、平板 | [yingxia.apk](https://github.com/xiaotaitech/yingxia-release/releases/latest/download/yingxia.apk) | [yingxia.apk](https://cdn.jsdelivr.net/gh/xiaotaitech/yingxia-release@dist/yingxia.apk) |
| **电视版** | 智能电视、电视盒子 | [yingxia-tv.apk](https://github.com/xiaotaitech/yingxia-release/releases/latest/download/yingxia-tv.apk) | [yingxia-tv.apk](https://cdn.jsdelivr.net/gh/xiaotaitech/yingxia-release@dist/yingxia-tv.apk) |

- 所有版本与更新说明：[Releases](https://github.com/xiaotaitech/yingxia-release/releases)。电视版从 **v0.4.0** 开始提供，此前的版本只有手机版。
- 都要求 Android 8.0 及以上。华为 HarmonyOS NEXT（纯血鸿蒙）不能安装安卓应用。
- 装好后在应用内「检查更新」直接升级：手机版只下载手机版安装包，电视版只下载电视版安装包，不会装错。

## 手机版和电视版怎么选

- **只用手机看**：装手机版。
- **在电视上看**：电视或盒子装电视版，用遥控器操作。
- **推荐两个都装**：先在手机版里导入配置，再用手机把配置**推送到电视**——电视上打开「设置 → 导入配置」会显示二维码，手机版扫码后勾选要推送的内容即可，电视上不用打字。手机和电视要连同一个网络。
- 手机版也可以把正在看的片子**投屏**到支持 DLNA 的电视上（不需要装电视版）。
- 两个应用的观看历史、收藏各自保存，互不同步。

## 安装到电视和盒子

1. 任选一种方式把 **yingxia-tv.apk** 装到电视上：
   - 用电视自带的浏览器打开上面的电视版下载地址；
   - 在电脑上下载后拷到 U 盘，插到电视上用文件管理器打开；
   - 用电视上的"当贝助手""快传"等应用从手机传过去。
2. 第一次安装时，按提示在电视的设置里允许"安装未知来源应用"（常见位置：「设置 → 安全/通用 → 未知来源」）。
3. 打开后在「设置 → 导入配置」用手机推送配置，或者输入配置地址。

## 使用说明

- **[手机版使用帮助（HELP.md）](HELP.md)**：小米、华为、OPPO、vivo 等手机安装时各种拦截提示的处理方法，导入配置、看片、追剧、投屏、分享给朋友、常见问题。应用内「我的 → 使用帮助」是同一份内容；「我的 → 电视版影匣」介绍电视版。
- **[电视版使用帮助（HELP-TV.md）](HELP-TV.md)**：遥控器操作、从手机推送配置、播放与直播、常见问题。应用内「设置 → 使用帮助」是同一份内容，页面上还有手机版的下载二维码。

## 反馈

使用中的问题请在 [Issues](https://github.com/xiaotaitech/yingxia-release/issues) 中反馈，并注明是手机版还是电视版。
