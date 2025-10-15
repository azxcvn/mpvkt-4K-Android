# <img alt="app icon" src=".github/assets/app_icon.svg" width="48" /> mpvKt - Anime4K Enhanced Edition

## 项目说明 / Project Description

你们好，此项目是基于 https://github.com/abdallahmehiz/mpvKt 二改的 mpv 安卓移动本地视频播放器，修改内容为在播放界面，右上角三个点更多里面，最下面，增添了基于 Anime4K（https://github.com/bloc97/Anime4K）超分的功能，支持三档切换，分别是关闭，质量档，效率档。但实际测试只有效率档有效果，质量档无效果，本人水平有限，构建出来的安装包也很大，不知道怎么优化，此项目不再更新。

感谢 https://github.com/abdallahmehiz/mpvKt；https://github.com/bloc97/Anime4K

---

A modified version of mpv Android media player based on [mpvKt](https://github.com/abdallahmehiz/mpvKt) with integrated [Anime4K](https://github.com/bloc97/Anime4K) upscaling functionality.

## 新增功能 / New Features

- **Anime4K 超分辨率增强**: 在播放界面右上角菜单中新增 Anime4K 超分功能
- **三档模式切换**: 支持关闭、质量档、效率档三种模式
- **实时切换**: 播放过程中可随时切换超分模式

**注意**: 目前测试发现只有效率档有明显效果，质量档效果不明显。

## Anime4K Integration

This fork integrates Anime4K real-time upscaling into the original mpvKt player:

- **Three modes**: Off, Quality mode, Performance mode
- **Real-time switching**: Change upscaling modes during playback
- **Easy access**: Available in the player's more options menu (three dots in top-right corner)

**Note**: Currently, only Performance mode shows noticeable effects during testing.

## 原始功能 / Original Features

- 基于 mpv-android 的强大播放核心
- 更美观的播放器界面
- 改进的播放历史记录
- 易于自定义的设置选项

## 安装说明 / Installation

由于项目不再更新，请自行编译或查看原始项目的发布页面。

This project is no longer actively maintained. Please compile from source or check the original project's releases.

## 编译说明 / Build Instructions

1. Clone this repository
2. Open in Android Studio
3. Build the project (Note: The APK size may be larger due to Anime4K integration)

## 已知问题 / Known Issues

- APK 文件较大，暂未找到优化方案
- 质量档模式效果不明显
- 项目不再维护更新

## 致谢 / Acknowledgments

- [mpvKt](https://github.com/abdallahmehiz/mpvKt) - 原始项目基础
- [Anime4K](https://github.com/bloc97/Anime4K) - 超分算法支持
- [mpv-android](https://github.com/mpv-android/mpv-android) - MPV 播放核心

## 许可证 / License

本项目继承原项目的许可证条款。详见 LICENSE 文件。