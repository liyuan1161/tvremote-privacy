[English](#tv-remote-glow-privacy-policy) · [简体中文](#电视遥控器隐私政策) · [Support / 技术支持](#support--技术支持)

# TV Remote Glow Privacy Policy

Effective date: October 4, 2026

Developer: Ledi

TV Remote Glow ("the App") turns your iPhone or iPad into a remote control for a TV on the same Wi-Fi. This policy explains how the App handles information.

## Usage Statistics and Crash Reports

The App has no accounts and no ads, doesn't sell or share personal information, and doesn't track you across other apps or websites.

To make the App work better, it uses Google Firebase Analytics and Crashlytics to collect anonymous usage statistics and crash reports:

- **Usage:** which screens and controls are used (for example, how often each remote button or the touchpad is used), whether connecting to a TV succeeded or why it failed, and whether the Playglow recommendation was shown or tapped.
- **Crashes:** the crash log, app version, device model, and system version.
- **Identifier:** a random app-instance ID that Firebase creates on install. It resets when you delete the App, and it isn't the advertising identifier (IDFA).

These statistics never include your TV's name or network address, the text you type, or your name, contacts, or location. They aren't linked to your identity or used for advertising or tracking. Google processes the data under the [Firebase privacy terms](https://firebase.google.com/support/privacy); analytics data is kept for up to 14 months.

## Local Network

The App asks for Local Network access to find TVs on your Wi-Fi (through the Bonjour services `_rc._tcp` and `_androidtvremote2._tcp`) and to send remote-control commands, typed text, and app-launch requests directly to the TV you choose. This traffic stays on your local network between your device and the TV. No other devices are contacted.

## Data Stored on Your Device

- The TV you chose (its name, network address, and type) is saved on your device so the App and its Home Screen widget can reconnect to it.
- To pair with an Android TV or Google TV, the App creates a key and a self-signed certificate and keeps them in your device's Keychain. The TV remembers this certificate so you don't need to pair again.

This information never leaves your device except to talk to your TV, and it isn't included in the usage statistics. Deleting the App removes the saved TV; you can also remove the pairing in the TV's settings.

## Children's Privacy

The App doesn't knowingly collect personal information from anyone, including children; the anonymous statistics above contain no personal details.

## Changes to This Policy

If this policy changes materially, the effective date on this page will be updated.

## Contact Us

For privacy questions, open an issue in this repository (see [Support](#support--技术支持)).

---

# 电视遥控器隐私政策

生效日期：2026 年 10 月 4 日

开发者：Ledi

电视遥控器（以下简称“本 App”）可以把你的 iPhone 或 iPad 变成同一 Wi-Fi 下电视的遥控器。本政策说明本 App 如何处理信息。

## 使用统计与崩溃报告

本 App 没有账号、没有广告，不出售或分享个人信息，也不会跨 App 或网站追踪你。

为了改进体验，本 App 使用 Google Firebase Analytics 和 Crashlytics 收集匿名的使用统计和崩溃报告：

- **使用情况**：用了哪些页面和按键（例如各遥控按键、触控板的使用次数），连接电视是否成功及失败原因，以及趣光推荐是否展示、是否被点击。
- **崩溃信息**：崩溃日志、App 版本、设备型号和系统版本。
- **标识符**：Firebase 安装时生成的随机 App 实例 ID。删除本 App 后会重置；它不是广告标识符（IDFA）。

这些统计不包含电视名称或网络地址、你输入的文字，也不包含姓名、联系人或位置。它们不会与你的身份关联，也不会用于广告或追踪。数据由 Google 按 [Firebase 隐私条款](https://firebase.google.com/support/privacy) 处理，统计数据最长保留 14 个月。

## 本地网络

本 App 申请“本地网络”权限，用于在你的 Wi-Fi 中发现电视（通过 Bonjour 服务 `_rc._tcp` 和 `_androidtvremote2._tcp`），并把遥控指令、输入的文字和打开应用的请求直接发送给你选择的电视。这些通信只在你的设备和电视之间的局域网内进行，不会访问其他设备。

## 保存在你设备上的数据

- 你选择的电视（名称、网络地址和类型）保存在你的设备上，方便本 App 和桌面小组件重新连接。
- 与 Android TV 或 Google TV 配对时，本 App 会生成一个密钥和自签名证书，保存在设备的钥匙串中。电视会记住这个证书，之后无需重新配对。

这些信息除了用于和你的电视通信外，不会离开你的设备，也不会出现在使用统计中。删除本 App 会清除保存的电视；你也可以在电视的设置中移除配对。

## 儿童隐私

本 App 不会有意收集任何人（包括儿童）的个人信息；上述匿名统计不包含个人身份信息。

## 政策变更

如本政策有重大变更，本页面的生效日期会随之更新。

## 联系我们

如有隐私相关问题，请在本仓库提交 Issue（见[技术支持](#support--技术支持)）。

---

# Support / 技术支持

**Can't find the TV? / 找不到电视？**
Make sure the phone and the TV are on the same Wi-Fi and the TV is on, and allow Local Network access in iPhone Settings › Privacy & Security › Local Network. You can also type the TV's IP address, shown in the TV's network settings.
确认手机和电视连在同一个 Wi-Fi，电视已开机，并在 iPhone“设置 › 隐私与安全性 › 本地网络”中允许本 App 访问。也可以手动输入电视的 IP 地址（在电视的网络设置里能看到）。

**Supported TVs / 支持的电视**
Android TV and Google TV (pair once with the code shown on the TV), and Mainland China Xiaomi / Redmi TVs.
Android TV 和 Google TV（首次使用时输入电视上显示的配对码），以及中国大陆版小米 / Redmi 电视。

**Contact / 联系方式**
Open an issue at https://github.com/liyuan1161/tvremote-privacy/issues
请在 https://github.com/liyuan1161/tvremote-privacy/issues 提交 Issue。
