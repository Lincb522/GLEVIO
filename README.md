<div align="center">
  <img src="assets/icon.png" width="104" alt="GLEVIO 应用图标" />
  <br /><br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-light.svg" />
    <img src="assets/wordmark.svg" width="228" alt="GLEVIO" />
  </picture>
  <p><b>把应用，放回顺手的地方。</b></p>
  <p>适用于 macOS 26 的原生应用启动器</p>
  <p>
    <img src="https://img.shields.io/badge/macOS-26%2B-202126?logo=apple&amp;logoColor=white" alt="macOS 26 及以上" />
    <img src="https://img.shields.io/badge/Apple_Silicon_%26_Intel-Universal-535966" alt="Apple Silicon 与 Intel 通用版本" />
    <img src="https://img.shields.io/github/v/release/Lincb522/GLEVIO?color=596be9&amp;label=版本" alt="最新版本" />
  </p>
  <p><b><a href="https://github.com/Lincb522/GLEVIO/releases/latest/download/GLEVIO.dmg">下载 macOS 版</a></b> &nbsp; · &nbsp; <a href="https://github.com/Lincb522/GLEVIO/releases">版本记录</a> &nbsp; · &nbsp; <a href="https://github.com/Lincb522/GLEVIO/issues">反馈问题</a></p>
  <br />
  <img src="assets/launcher.png" width="1080" alt="GLEVIO 应用网格，支持搜索、文件夹和分页" />
</div>

## 熟悉的应用网格

全屏浏览应用，直接输入名称、拼音或首字母搜索。鼠标滚轮、触控板横滑和拖动空白区域都能翻页，方向键与 Return 也能完成启动。

| 整理应用 | 调整外观 |
| :--- | :--- |
| 系统应用自动归类，支持拖动建立文件夹 | 文件夹可选毛玻璃或原生液态玻璃 |
| 按名称排序、文件夹优先、自定义列数与图标大小 | 使用系统壁纸、自选图片或纯色背景 |
| 智能整理先预览，可选择类别并撤销 | 图片背景可调模糊与暗度，设置自动保存 |
| 将真实应用拖到 Dock，保留快捷入口 | 支持系统减少动态效果与减少透明度设置 |

## 让本地 agent 帮助分类

支持 **Codex CLI** 和 **Claude Code**。在设置中选择已安装并登录的 CLI，再从「智能整理」生成分类建议，确认后应用。

已有文件夹和隐藏应用会保留。只提供应用名称、标识和类别；CLI 会使用你配置的模型，可能连接云端服务。生成过程可停止，未得到有效建议时仍可使用内置规则整理。

## 卸载时，一起查看关联文件

右键应用选择「卸载应用…」，或选中后按 `⌘ Delete`，查看应用本体、支持数据、缓存、偏好设置与其他可识别关联文件，再将勾选项目移到废纸篓。

按名称匹配的数据默认不勾选。系统应用受保护，运行中的应用需先退出；共享容器与后台组件会显示并保留，钥匙串、驱动和任意自定义目录不在自动清理范围内。

## 安装与使用

1. [下载安装包](https://github.com/Lincb522/GLEVIO/releases/latest/download/GLEVIO.dmg)，打开 DMG，将 **GLEVIO** 拖入「应用程序」。也可使用 [ZIP 版本](https://github.com/Lincb522/GLEVIO/releases/latest/download/GLEVIO.zip)。
2. 打开 GLEVIO，通过 Dock、菜单栏或 **⌥ ⌘ Space** 显示与隐藏。
3. 在设置中选择文件夹材质、背景与排列方式；「检查更新」会读取这里发布的最新版本，提供下载入口。

| 操作 | 快捷方式 |
| :--- | :--- |
| 显示 / 隐藏 | `⌥ ⌘ Space` |
| 搜索应用 | 直接输入，支持拼音 |
| 选择并打开 | 方向键 → `Return` |
| 返回上一级 | `Esc` |
| 翻页 | 滚轮 / 触控板横滑 / 拖动空白处 |
| 卸载所选应用 | `⌘ Delete` |

> 当前版本使用本地签名，尚未完成 Apple 公证。首次打开可能需要在「系统设置 → 隐私与安全」中确认允许，参见 [Apple 的打开说明](https://support.apple.com/zh-cn/102445)。每个版本同时提供 SHA-256 校验文件。

---

**开发者：ZIJIU522**

此仓库用于 GLEVIO 的下载与更新发布。应用源代码不在此仓库公开。
