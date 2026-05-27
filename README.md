# Chronoscribe

A lightweight, offline-first Markdown editor .

一款精美的轻量级 Markdown 编辑器，离线可用。

**Download (Windows x64):** [Releases](https://github.com/zhuofushow/chronoscribe/releases)

**下载（Windows x64）：** [发布页](https://github.com/zhuofushow/chronoscribe/releases)

## Features / 特性

- **Real-time preview / 实时预览** — Split, edit-only, or preview-only views
- **File tree & drag-and-drop / 目录树与拖放** — Browse drives, open `.md` / `.markdown` / `.txt`
- **Bookmarks & recent files / 收藏与历史** — Persistent file paths in local app data
- **Light & dark themes / 明暗主题** — “Light Cone” amber-on-void palette
- **Math & extensions / 数学与扩展** — KaTeX, task lists, footnotes, admonition blocks
- **Local-first / 本地优先** — Bundled assets, no CDN; works without internet after install
- **Auto-update / 自动更新** — Signed updates via GitHub `latest.json` (Windows)
- **Small installer / 安装包小** — ~3.4 MB NSIS setup (x64)

## Tech stack / 技术栈

| | |
|---|---|
| Desktop / 桌面 | [Tauri 2](https://tauri.app/) (Rust) |
| UI / 界面 | Vanilla JavaScript |
| Markdown / 解析 | [markdown-it](https://github.com/markdown-it/markdown-it) (+ task lists, mark, footnote, container) |
| Math / 公式 | [KaTeX](https://katex.org/) |
| Fonts / 字体 | Space Mono, JetBrains Mono (bundled) |

## Getting started / 快速开始

1. Download `Chronoscribe_1.0.0_x64-setup.exe` from [Releases](https://github.com/zhuofushow/chronoscribe/releases).
2. Run the installer (English UI). Optional: desktop shortcut, run after install, set as default Markdown opener.
   
从 [Releases](https://github.com/zhuofushow/chronoscribe/releases) 下载安装包，按向导安装即可。安装完成后可直接启动；

**Requirements / 系统要求:** Windows 10/11, x64, WebView2 (installer can fetch runtime if missing).

## Themes / 主题

**Light Cone / 光锥之外**

- Background / 背景: `#050508`
- Accent / 强调: `#FFAA00`
- Effects / 特效: CRT scanlines, phosphor glow
- Fonts / 字体: Space Mono + JetBrains Mono

## Markdown support / Markdown 支持

- Headings, emphasis, links, images, blockquotes, lists, horizontal rules
- Task lists (GFM-style), tables, footnotes
- Container blocks: note, warning, tip, danger
- Inline and display math (`$…$`, `$$…$$`) via KaTeX

## License / 许可证

[MIT License](LICENSE.md)

## Acknowledgments / 致谢

Inspired by [Typora](https://typora.io/), [MarkText](https://github.com/marktext/marktext), [Obsidian](https://obsidian.md/), and the Wheeler–DeWitt equation.

Built with [Tauri](https://tauri.app/).
