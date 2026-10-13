# 好好学习卡片（Good Good Study Card）

中文 | **[English](README.md)**

<p align="center">
  <img src="docs/og.png" alt="好好学习卡片" width="720">
</p>

<p align="center">
  <strong>用间隔重复算法，高效记住任何内容。</strong><br>
  Android · iOS · HarmonyOS · Windows · macOS · Linux
</p>

---

**好好学习卡片**是一款跨平台背单词 / 背知识卡片应用，只为一件事而生：*把记忆做扎实*。创建 Markdown 卡片、添加图片、跨平台分享卡片组——离线优先，无需账号，数据默认留在你的设备上。

## 核心功能

- **间隔重复算法，完全透明** —— 简化 SM-2 算法为每张卡片安排最佳复习时机，每个评分按钮直接显示下次间隔。
- **四种学习模式** —— 牌组学习、全局待复习、收藏夹、单卡学习，外加「新 / 学习中 / 已掌握」看板，全局进度一目了然。
- **丰富的卡片内容** —— 问题与答案均支持 Markdown，每张卡片最多 8 张图片，9 种分类颜色快速区分主题。
- **跨平台分享** —— 导出 `.ggsdeck` / `.ggscard` 文件即可在安卓、iOS、鸿蒙、Windows 之间互导。无需账号，无需服务器。
- **桌面小组件** —— 主屏与锁屏小组件直接翻卡学习，无需打开应用。
- **学习统计** —— 连续学习天数、学习时长、正确率、每日活动时间线与各牌组表现。
- **离线优先 · 数据自留** —— 无需注册，数据默认只存在本机；回收站保留 30 天，误删随时可恢复。
- **三种提醒** —— 单卡定时提醒、每日学习提醒、定期备份提醒，学习节奏不断档。
- **平台专属能力** —— iOS：iCloud 同步、Siri 快捷指令；HarmonyOS：华为云备份、碰一碰分享。

## 下载

测试版以 [GitHub Releases](https://github.com/codepromax-cn/ggsc/releases) 形式发布，正式版的商店上架正在准备中。

| 平台 | 版本 | 下载 | SHA-256 |
|---|---|---|---|
| Android | `1.0-test.20261004`（测试版） | [ggsc-release-20261004.apk](https://github.com/codepromax-cn/ggsc/releases/download/v1.0-test.20261004/ggsc-release-20261004.apk) (29.1 MB) | `1ed0b2f69361b2e6f0b5d487ff25dcc2b42b1a1153f8dc1601e59a9949a2fad7` |
| Linux (x64) | `1.0.0-test.20261004`（测试版） | [ggsc-1.0.0-test.20261004-x64.AppImage](https://github.com/codepromax-cn/ggsc/releases/download/v1.0.0-test.20261004/ggsc-1.0.0-test.20261004-x64.AppImage) (138.3 MB) | `2925c5850111a225388c7d2dcfacc6b22186002e030ea7ce70e8c5ddbb8cd899` |
| Windows (x64) | `0.1.0-test.20261014`（测试版） | [GoodGoodStudyCard-Setup-0.1.0-test.20261014.exe](https://github.com/codepromax-cn/ggsc/releases/download/v0.1.0-test.20261014/GoodGoodStudyCard-Setup-0.1.0-test.20261014.exe) (47.8 MB) | `06d9a0d766589a4e0205aebba639f11bf7b6d6504693437c6e88c29cd96fc543` |
| iOS | — | 即将上线 | — |
| HarmonyOS | — | 即将上线 | — |
| macOS | — | 开发中 | — |

**安装说明**

- **Android**：APK 未通过 Play 商店分发——安装时按提示允许浏览器「安装未知应用」即可。
- **Linux**：为 AppImage 添加可执行权限后运行：
  ```bash
  chmod +x ggsc-1.0.0-test.20261004-x64.AppImage
  ./ggsc-1.0.0-test.20261004-x64.AppImage
  ```
- **Windows**：双击 NSIS 安装包即可安装（无需管理员权限）。首次启动时 Windows SmartScreen 会提示「未知发布者」，点击「更多信息 → 仍要运行」继续。需要 Windows 10 1909 及以上，x64。

## 截图

<!-- 将应用截图放入 docs/ 后取消注释：
<p align="center">
  <img src="docs/screenshot-study.png" width="270" alt="学习界面">
  <img src="docs/screenshot-deck.png" width="270" alt="牌组详情">
  <img src="docs/screenshot-board.png" width="270" alt="看板">
</p>
-->

## 官网与牌组广场

访问 **[ggscard.cn](https://ggscard.cn)** —— 项目官网：

- 浏览**牌组广场**，下载 `.ggsdeck` 文件，或直接输入短 ID（如 `AB3X9K`）把整组卡导进应用。
- 中英文**图文教程**，覆盖每一个功能。
- 浏览器里直接**在线试用**真实的学习交互——装之前先试试。

## 关于本仓库

本仓库托管好好学习卡片的**发布文件与版本说明**。每个测试版都是一个带校验和的标签发布（`v<版本号>`）。产品官网、牌组广场与文档请访问 [ggscard.cn](https://ggscard.cn)。
