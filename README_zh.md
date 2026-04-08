<p align="center">
    <img src="assets/logo.ico" width="128" alt="XFolder Logo">
</p>

# XFolder

[English](README.md) | [中文](README_zh.md)

XFolder 是一款专为 macOS 打造的现代化文件管理器。它融合了多窗格视图、文件目录树及多标签页 (Tabs) 管理等核心特性，旨在提供比 Finder 更高效、更灵活的文件浏览体验。

本项目基于 C# (Avalonia UI) 和 Swift 构建。

## 📸 预览 (Preview)

<p align="center">
    <img src="assets/xfolder_light.png" width="100%" alt="Light Mode">
    <img src="assets/xfolder_dark.png" width="100%" alt="Dark Mode">
</p>

## 📥 下载与安装 (Download)

本软件暂不开源代码。您可以直接从 GitHub Releases 页面下载最新版本的 macOS 安装包。

[👉 前往下载页面 (GitHub Releases)](https://github.com/zebrapixel/XFolder/releases) 
*(请根据实际发布的 URL 更新此链接)*

### 安装步骤
1. 下载最新的 `XFolder-Installer.dmg` 文件。
2. 双击打开 `.dmg` 文件。
3. 将 `XFolder` 图标拖拽至 `Applications` (应用程序) 文件夹中。
4. 从启动台或应用程序文件夹中点击 `XFolder` 启动。

> **注意**: 由于未进行 Apple 开发者签名（视情况修改），初次运行时若提示“无法打开”或“未知开发者”，请前往 **设置** > **隐私与安全性** 中点击“仍要打开”。

## ✨ 主要特性 (Features)

*   **多窗格布局** - 支持水平、垂直及混合布局，灵活管理文件
*   **多标签页管理** - 在每个窗格中打开多个文件夹
*   **目录树视图** - 通过内置的目录树导航文件夹层级
*   **快捷访问** - 将常用文件夹（如桌面、文档、下载）固定到侧边栏，实现快速访问
*   **面包屑路径导航** - 直观的面包屑路径导航栏，显示完整目录层级，支持点击切换

## ⌨️ 常用快捷键 (Shortcuts)

XFolder 支持丰富的键盘快捷键以提升效率：

### User Interface / Navigation
| Action | Shortcut |
| :--- | :--- |
| **Navigate Back** | `⌥` + `←` |
| **Navigate Forward** | `⌥` + `→` |
| **Navigate to Parent** | `Delete` |
| **Next Pane** | `⌃` + `⇧` + `→` |
| **Previous Pane** | `⌃` + `⇧` + `←` |
| **Details View** | `⌃` + `0` or `⌃` + `Num 0` |
| **Grid View** | `⌃` + `1` or `⌃` + `Num 1` |
| **Open in Finder** | `⌘` + `E` |
| **Open Terminal** | `⌃` + `~` |

### File Operations
| Action | Shortcut |
| :--- | :--- |
| **Copy** | `⌘` + `C` |
| **Copy Item Path** | `⌘` + `⇧` + `C` |
| **Cut** | `⌘` + `X` |
| **Paste** | `⌘` + `V` |
| **Select All** | `⌘` + `A` |
| **Delete** | `Delete` or `⌘` + `D` |
| **Delete Permanently** | `⇧` + `Delete` |
| **Rename** | `F2` |
| **Open** | `Enter` |
| **New Folder** | `⌘` + `⇧` + `N` |

### Tabs & Editing
| Action | Shortcut |
| :--- | :--- |
| **New Tab** | `⌘` + `T` |
| **Next Tab** | `⌘` + `→` |
| **Previous Tab** | `⌘` + `←` |
| **Close Tab** | `⌘` + `W` |
| **Duplicate Tab** | `⌘` + `⇧` + `T` |
| **Undo** | `⌘` + `Z` |
| **Redo** | `⌘` + `Y` |

*(更多快捷键请在应用内查看帮助菜单)*

## 💬 反馈与支持 (Feedback)

如果您在使用过程中遇到 Bug 或有新的功能建议，欢迎在 GitHub Issues 中提出。

*   [提交 Bug 反馈](https://github.com/zebrapixel/XFolder/issues)
*   [功能建议](https://github.com/zebrapixel/XFolder/issues)

## 🙏 致谢 (Acknowledgements)

特别感谢以下项目对本软件的支持：

*   **[AvaloniaUI](https://github.com/AvaloniaUI/Avalonia)**: 强大的跨平台 .NET UI 框架。
*   **[Files](https://github.com/files-community/Files)**: 优秀的 Windows 文件管理器，本项目参考了其部分架构设计和代码。
*   **[Q-Dir](https://www.q-dir.com)**: 经典的多窗口资源管理器，提供了重要的设计灵感。

## 📄 许可说明 (License)

XFolder 是私有软件 (Proprietary Software)，版权所有 (c)。
保留所有权利。未经授权，禁止反编译、修改、重新打包或用于商业分发。
