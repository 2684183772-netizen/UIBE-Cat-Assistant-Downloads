# UIBE Cat Assistant v0.1.0

首个公开下载版本。桌面显示一只穿蓝色 UIBE 毛衣的橘白猫咪，单击即可打开惠知 AI 校园信息检索与聊天网站。

## 主要功能

- 透明悬浮桌面猫咪。
- 支持拖动和 48 / 64 / 80 / 96 像素四档尺寸。
- 自动记住上次选择的大小。
- 待机呼吸、眨眼和摇尾巴动画。
- 单击打开惠知 AI；聊天窗口支持关闭、最小化和重新打开。
- 系统托盘菜单和退出功能。
- 不需要 Coze API Token。

## 下载文件

| 系统 | 文件 | SHA-256 |
| --- | --- | --- |
| macOS 通用安装镜像 | `UIBE Cat Assistant-0.1.0-mac-universal.dmg` | `0acb7b15dda435fc7f03a11d9e8a011d684c9837dfd315610d87e3f5c6c003dd` |
| macOS 通用 ZIP | `UIBE Cat Assistant-0.1.0-mac-universal.zip` | `0df27198fe5d9bddbb2c2ab6e10f351036ed45483ed77e53f411216708b6041f` |
| Windows x64 安装版 | `UIBE Cat Assistant-0.1.0-Setup-x64.exe` | `a19284ee8a55d5027fd7d8a3e33ee933d955d620e227c257460c3523e6d718b2` |
| Windows x64 便携版 | `UIBE Cat Assistant-0.1.0-Portable-x64.exe` | `0c9c27dba836bc46eddf4226394434697e9aaceac50d212a9571658e5a9f1fd6` |

## 系统要求

- macOS 13 Ventura 或更高版本；DMG/ZIP 均为 universal，支持 Apple Silicon 与 Intel。
- Windows 10/11 64 位。
- 访问惠知 AI 需要可用的互联网连接。

## 安装方法

### macOS DMG

1. 下载并核对 SHA-256。
2. 打开 DMG，将 `UIBE Cat Assistant` 拖入“应用程序”。
3. 从“应用程序”中启动。

### macOS ZIP

1. 下载并核对 SHA-256。
2. 解压 ZIP，将 `UIBE Cat Assistant.app` 移入“应用程序”。
3. 从“应用程序”中启动。

### Windows 安装版

1. 下载并核对 SHA-256。
2. 运行 `UIBE Cat Assistant-0.1.0-Setup-x64.exe`。
3. 按安装向导选择安装目录并完成安装。

### Windows 便携版

下载并核对 SHA-256 后，直接运行 `UIBE Cat Assistant-0.1.0-Portable-x64.exe`，无需安装。

## 安全提示

此版本尚未使用 Apple Developer ID 公证或 Windows Authenticode 证书签名，因此系统可能显示安全提示。

- macOS：先确认下载来源和 SHA-256；如果 Gatekeeper 阻止启动，请参考 [Apple 官方“安全地打开 Mac 上的 App”](https://support.apple.com/en-us/102445)。不要全局关闭系统安全功能。
- Windows：SmartScreen 会根据应用信誉和签名判断未知应用。请参考 [Microsoft SmartScreen 安全说明](https://support.microsoft.com/en-us/office/protect-my-pc-from-viruses)，确认校验值后再决定是否运行。
- 校园或单位统一管理的设备可能禁止运行未签名软件，请遵守设备管理策略。

## 数据与网络

- 安装包不包含 Coze API Token、GitHub Token、用户账号、聊天记录或个人配置。
- 猫咪单击后加载 `https://huizhi-ai.coze.site`，网站登录和数据处理规则以该网站为准。
- 应用不会绕过网站的登录、安全策略或权限限制。

## 已知限制

- 当前版本未签名/未公证。
- 暂不支持自动更新；后续版本需要用户重新下载安装。
