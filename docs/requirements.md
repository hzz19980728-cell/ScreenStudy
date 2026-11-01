# 安装所需软件

适用版本：ScreenStudy / 双屏日语伴读 0.35 · By 快转风景Nevermore

## 必装的软件已经在包里

**ScreenStudy-0.35.apk** 就是软件本体，放在分享包的 `01_安装包`。内含日文 OCR 模型和分词逻辑，不需要再装独立识字工具、Java、Python、Android Studio，也不需要安装电脑运行环境。

设备要求：Android 8.0（API 26）及以上；若要同时显示游戏和伴读，系统需要提供可运行独立应用的副屏。APK 内含 arm64-v8a、armeabi-v7a、x86、x86_64 架构库。满足系统版本不代表已在所有设备实测，详细范围见适配说明。

## 联网翻译必备：自己的服务账号和 API 密钥

这不是另一个必须安装的 App。在服务商网页申请 API 密钥，回到本软件中填写即可。默认接口示例：

- [DeepSeek 官方 API 平台](https://platform.deepseek.com/)
- [DeepSeek 官方接入文档](https://api-docs.deepseek.com/zh-cn/)

需要可用网络和该服务的有效额度。安装官方聊天 App 并不能自动给本软件提供 API 密钥。密钥由使用者自行配置，不向别人索取或共用作者的密钥。

## 仅日语朗读需要：支持离线日语的 TTS 引擎及语音包

先去系统设置搜索“文字转语音”或“TTS”，检查是否已有支持日语的引擎。已有的就不用重复安装；没有时可通过设备正规应用商店获取支持日语离线语音的引擎。

Google 的官方选项：[Speech Recognition & Synthesis / Google 语音服务](https://play.google.com/store/apps/details?id=com.google.android.tts)。是否可下载取决于设备、地区和商店环境。

1. 在系统“文字转语音输出”中选择该引擎。
2. 进入引擎设置，选择“安装语音数据”，下载 **日语 / 日本語** 的离线语音包。
3. 回到软件的“设置 → 日语朗读”，试听日语。
4. 如有声音，才算配置完成。只装引擎而没有装日语数据，可能依然无法朗读。

官方参考：[Android 文字转语音设置](https://support.google.com/accessibility/android/answer/6006983?hl=zh-Hans)。

第三方引擎及语音包不随本分享包重新打包；请使用官方入口安装更新。无法访问 Google Play 时，可以使用设备厂商提供的引擎，但必须确认支持离线日语；不需要为基础识别、看中文或点词去安装 TTS。

## 只有电脑安装排障才需要：Android Platform-Tools

通常用掌机文件管理器点 APK 即可。只有希望从电脑安装或提供故障信息时，才需要 [Google 官方 Platform-Tools](https://developer.android.com/tools/releases/platform-tools)，页面可选择 Windows / Mac / Linux 下载。

此工具是可选的。普通用户无需开启 USB 调试，也无需安装 Android Studio。本分享包附带官方入口链接，没有附带来历不明的“激活器”、破解工具或一键授权软件。
