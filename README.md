# PokeCall

**[English](#english) | [中文](#中文)**

---

## English

A Pokémon-battle themed incoming-call UI module for Android (LSPosed/Xposed).

When a call comes in, instead of the stock dialer screen, you get a GBA-style Pokémon battle: a wild Pokémon (or trainer) appears, and you answer the call by choosing **FIGHT** or reject it by choosing **RUN**.

*Inspired by the PokeCall jailbreak tweak for iOS.*

![PokeCall incoming-call battle screen](https://raw.githubusercontent.com/Xposed-Modules-Repo/com.sai.pokecall/main/screenshot.jpg)

### Features

- 🎮 GBA-style battle encounter animation (gen 2 / gen 3 sprites)
- 📞 Full incoming-call takeover: system call screen and banner are suppressed
- 🎨 Light / dark battle themes, OLED black mode
- 🔔 Pokémon battle ringtones + sound effects
- 👤 Per-contact customization: assign a trainer and Pokémon to specific contacts
- 📍 Caller location lookup (offline phone-number database)
- 🎵 Six selectable battle ringtones
- 🇨🇳 Chinese / English battle-text toggle (pixel Chinese font)

### Requirements

- LSPosed (or Xposed framework) on Android 10+ (API 29+)
- Tested and verified on **Xiaomi 17 Ultra, HyperOS 4 (Android 17)**

### Installation

1. Install the APK
2. Enable the module in LSPosed manager
3. Check the scopes: `com.android.incallui`, `com.android.server.telecom`, `com.android.systemui`, `com.android.contacts`, `com.android.phone`, `android`
4. Soft-reboot

### Usage

- Incoming call → battle screen appears
- **FIGHT** = answer the call
- **RUN** = reject / hang up
- Long-press or tap the banner to expand/collapse
- Set your trainer & Pokémon in the app, customize per-contact in "Customise contacts"

### Notes

- The system dialer remains the default call app; this module only presents the incoming-call UI.

### Feedback

Found a bug or have a feature request? Open an issue: <https://github.com/Xposed-Modules-Repo/com.sai.pokecall/issues>

---

## 中文

精灵宝可梦战斗主题来电界面模块（LSPosed / Xposed）。

来电时不再显示系统拨号界面，取而代之的是 GBA 像素风宝可梦对战：野生宝可梦（或训练家）登场，选择 **FIGHT** 接听，选择 **RUN** 拒接。

*灵感来源于 iOS 越狱插件 PokeCall。*

![来电战斗界面截图](https://raw.githubusercontent.com/Xposed-Modules-Repo/com.sai.pokecall/main/screenshot.jpg)

### 功能特性

- 🎮 GBA 像素风遇敌动画（第二世代 / 第三世代精灵素材）
- 📞 完全接管来电界面：系统来电界面与横幅全部屏蔽
- 🎨 浅色 / 深色战斗主题，OLED 纯黑模式
- 🔔 宝可梦战斗铃声 + 音效
- 👤 按联系人自定义：为指定联系人分配专属训练家与精灵
- 📍 来电归属地查询（离线号码库）
- 🎵 六首可选战斗铃声
- 🇨🇳 战斗中文字幕中英切换（点阵中文字体）

### 系统要求

- Android 10+（API 29+）并安装 LSPosed（或 Xposed 框架）
- 已在 **小米 17 Ultra，HyperOS 4（Android 17）** 实测通过

### 安装

1. 安装 APK
2. 在 LSPosed 管理器中启用模块
3. 勾选作用域：`com.android.incallui`、`com.android.server.telecom`、`com.android.systemui`、`com.android.contacts`、`com.android.phone`、`android`
4. 软重启

### 使用方法

- 来电 → 战斗界面弹出
- **FIGHT** = 接听
- **RUN** = 拒接 / 挂断
- 长按或点击横幅可展开 / 收起
- 在 App 内设置训练家与精灵，可在"自定义联系人"中按联系人单独配置

### 说明

- 系统拨号器仍是默认电话应用，本模块只接管来电显示界面。

### 反馈

遇到问题或有功能建议？欢迎提交 Issue：<https://github.com/Xposed-Modules-Repo/com.sai.pokecall/issues>

---

Author / 作者：SAI
