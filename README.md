# Good Good Study Card

**[中文文档](README.zh-CN.md)** | English

<p align="center">
  <img src="docs/og.png" alt="Good Good Study Card" width="720">
</p>

<p align="center">
  <strong>Remember anything, efficiently, with spaced repetition.</strong><br>
  Android · iOS · HarmonyOS · macOS · Linux
</p>

---

**Good Good Study Card** (好好学习卡片) is a cross-platform flashcard app built around one idea: *make memory stick*. Create Markdown cards, attach images, and share decks across platforms — offline-first, no account required, your data stays on your device.

## Highlights

- **Spaced repetition, fully transparent** — a simplified SM-2 algorithm schedules each card's optimal review time. Every rating button previews its resulting interval.
- **Four study modes** — deck study, global due cards, favorites, and single-card study, plus a New / Learning / Mastered board for the whole library at a glance.
- **Rich card content** — Markdown on both sides, up to 8 images per card, and 9 category colors to keep topics distinguishable.
- **Cross-platform sharing** — export a `.ggsdeck` / `.ggscard` file and import it on Android, iOS, or HarmonyOS. No account, no server in between.
- **Home-screen widgets** — flip through cards right from the home or lock screen, no need to open the app.
- **Study statistics** — streaks, study time, accuracy, a daily activity timeline, and per-deck performance.
- **Offline-first, your data** — no sign-up; data lives on your device by default. A recycle bin keeps deleted content recoverable for 30 days.
- **Three kinds of reminders** — per-card timed reminders, a daily study reminder, and periodic backup reminders.
- **Platform exclusives** — iOS: iCloud sync and Siri shortcuts. HarmonyOS: HUAWEI Cloud backup and tap-to-share.

## Downloads

Beta builds are published as [GitHub Releases](https://github.com/codepromax-cn/ggsc/releases). Store listings for the stable release are on the way.

| Platform | Build | Download | SHA-256 |
|---|---|---|---|
| Android | `1.0-test.20260920` (beta) | [ggsc-release-20260920.apk](https://github.com/codepromax-cn/ggsc/releases/download/v1.0-test.20260920/ggsc-release-20260920.apk) (29.1 MB) | `a66d20c8863e559e236da501888f9ee5ccdd647727ca002af3ac51b4b924be9c` |
| Linux (x64) | `1.0.0-test.20260927` (beta) | [ggsc-1.0.0-test.20260927-x64.AppImage](https://github.com/codepromax-cn/ggsc/releases/download/v1.0.0-test.20260927/ggsc-1.0.0-test.20260927-x64.AppImage) (138.3 MB) | `57cb7de60c43150abc4f1a65fb6459ea612a2e463aa0d38a7d51445a67bc900b` |
| iOS | — | Coming soon | — |
| HarmonyOS | — | Coming soon | — |
| macOS | — | In development | — |

**Install notes**

- **Android**: the APK is signed outside Play Store — allow "install unknown apps" for your browser when prompted.
- **Linux**: make the AppImage executable, then run it:
  ```bash
  chmod +x ggsc-1.0.0-test.20260927-x64.AppImage
  ./ggsc-1.0.0-test.20260927-x64.AppImage
  ```

## Screenshots

<!-- Drop app screenshots into docs/ and uncomment:
<p align="center">
  <img src="docs/screenshot-study.png" width="270" alt="Study flow">
  <img src="docs/screenshot-deck.png" width="270" alt="Deck detail">
  <img src="docs/screenshot-board.png" width="270" alt="Board">
</p>
-->

## Website & deck gallery

Visit **[ggscard.cn](https://ggscard.cn)** — the project's home on the web:

- Browse the **deck gallery**, download `.ggsdeck` files, or import a deck straight into the app by its short ID (e.g. `AB3X9K`).
- Illustrated **tutorials** for every feature, in English and Chinese.
- A live in-browser **demo** of the real study interaction — try it before you install.

## About this repository

This repository hosts **release binaries and release notes** for Good Good Study Card. Each beta drop is a tagged release (`v<version>`) with its checksums in the release notes. For the product website, deck gallery, and documentation, see [ggscard.cn](https://ggscard.cn).
