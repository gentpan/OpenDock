<div align="center">

# OpenDock

**以窗口为单位的 macOS 任务栏：每个窗口一个位置，点一下就到。**

[English](README.md) · 简体中文

</div>

这个仓库是 OpenDock 的问题反馈区，用来报告问题和提功能建议。App 的源代码不在这个仓库里。

> **状态：早期开发中。** 目前还没有公开发布的版本。

## 报告问题或提建议

[新建 issue](https://github.com/gentpan/OpenDock/issues/new/choose)，然后选一个模板：

- **报告问题**：有功能不正常。
- **功能建议**：希望 OpenDock 能做到的事。

提交前请先[搜一下已有的 issue](https://github.com/gentpan/OpenDock/issues?q=is%3Aissue)。如果别人已经报过同样的问题，在那条下面点个赞或补充你的情况就好，不用再开新的。

报告问题时附上诊断信息，能省掉一来一回的追问：打开 **设置 › 关于**，点 **诊断信息** 旁边的 **拷贝**，再粘贴到 issue 里。里面有 OpenDock 和 macOS 的版本、Mac 型号、显示器配置和外观设置。点拷贝不会发送任何东西，内容只放进剪贴板，由你自己粘贴。

中文英文都可以。

## OpenDock 是什么

从 Windows 转过来的人，会觉得 macOS 的 Dock 是反着的：它显示的是应用，不是窗口。开了五个访达文件夹，Dock 上只有一个访达图标。OpenDock 像 Windows 任务栏那样，把每个窗口都放到栏上，其余部分保持你熟悉的 macOS。

- **尊重你的习惯。** 除非你主动开启，OpenDock 不碰系统 Dock。改动之前先备份你的 Dock 设置，一键或退出时自动还原。
- **访达优先。** 每个访达文件夹窗口单独一项。把文件拖到某一项上悬停，那个窗口就会切到前台；松手放到访达项上，文件直接移进那个文件夹。
- **更干净的界面。** 更大的图标，宽度稳定的卡片，清楚的焦点高亮，所有设置集中在一个窗口里并且可以重置，任务栏可以放在底部、左侧或右侧。
- **内置启动器**，交互接近 Launchpad。

## 系统要求

- macOS 12 或更高版本（macOS 26 起使用 Liquid Glass 外观）
- 辅助功能权限（见下文）

## 辅助功能权限

OpenDock 通过 macOS 辅助功能 API 读取和切换窗口。首次启动时，它会请你到 **系统设置 › 隐私与安全性 › 辅助功能** 里打开开关。OpenDock 不需要屏幕录制权限。

如果开关看起来是开着的却不起作用（把 OpenDock 移到别的文件夹后可能出现）：先退出 OpenDock，在辅助功能列表里选中它并点减号移除，然后重新打开 OpenDock 再授权一次。

## 协议与致谢

OpenDock 以 GNU 通用公共许可证 v3.0 或更高版本（`GPL-3.0-or-later`）授权。

OpenDock 基于 **[Tungsten Edge（钨极）](https://github.com/moonbai-studio/tungsten-edge)** 开发，原项目 Copyright (C) 2026 Moonbai Studio，以 GPL-3.0-or-later 发布。

截图功能移植自 **[tendedero](https://github.com/alejandrobujan/tendedero)**，原项目 Copyright (c) 2026 Alejandro Buján，以 MIT 协议发布。

「Tungsten Edge」和「钨极」是 Moonbai Studio 的商标。OpenDock 是独立项目，与 Moonbai Studio 没有隶属或背书关系。
