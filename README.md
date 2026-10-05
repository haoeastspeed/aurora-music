# 极光音乐 Aurora Music

> 一款**完全原生自研**的 Windows 音乐播放器：单文件、零第三方依赖、绿色运行，解码能力强、音效专业、界面简洁美观，并支持在线音源与自定义音源、自动更新。

![版本](https://img.shields.io/badge/版本-1.2.7-2DD4BF) ![平台](https://img.shields.io/badge/平台-Windows%207%2F8%2F10%2F11-5B8DEF) ![依赖](https://img.shields.io/badge/第三方依赖-0-A855F7) ![许可](https://img.shields.io/badge/许可-免费使用-6366F1)

## 下载

- **最新版本：[v1.3.2](https://github.com/haoeastspeed/aurora-music/releases/latest)**
- 直接下载：[`AuroraMusic.exe`](https://github.com/haoeastspeed/aurora-music/releases/download/v1.3.2/AuroraMusic.exe)
- 产品主页：<https://haoeastspeed.github.io/aurora-music/>

下载后双击即可运行，无需安装、无需运行库（系统自带 .NET Framework 4.x）。

## 核心特性

- **原生自研内核**：直接调用系统 Media Foundation 解码，WASAPI / waveOut 渲染；JSON、FFT、标签、歌词、DSP 全部自主实现，不依赖任何第三方库。
- **强解码能力**：MP3、FLAC、APE、WAV、AAC、M4A、ALAC、OGG、Opus、WMA、DSF 等常见格式，支持无损与整轨 CUE 分轨。
- **专业音效 / 调音**：10 段 EQ 与多组预设、低音 / 高音增强、3D 立体声扩展、混响、回声、响度压缩、电子管 / 磁带饱和、人声消除、声道平衡、前置增益、防爆音限幅器，以及淡入淡出无缝播放。
- **多种频谱可视化**：柱状、镜像、波形、极光帷幕、点阵等多种模式可一键切换，主界面可开关。
- **歌词体验**：无歌词时自动在线搜索匹配（时长智能对齐），也可手动搜索多个版本、预览并一键替换，歌词自动缓存绑定、离线可用；主窗口歌词面板可显示 / 隐藏；桌面歌词置顶、可锁定、可调整区域大小与透明度、字体大小，带播放控制与进度条，右键即可解锁。
- **在线音源**：接入网易云公开接口、苹果官方预览，以及 Audius、ccMixter 上由艺术家授权或属于知识共享（CC）协议的资源。
- **自定义音源**：支持以 JavaScript 脚本（兼容落雪音源脚本的事件 / CommonJS 形态）导入合法音源，可添加多个、按源名称独立显示；脚本也可自定义搜索与推荐。
- **本地音乐管理**：多文件夹扫描与实时监听、标签 / 封面写回、批量重命名、智能歌单、播放统计、ReplayGain 响度扫描。
- **媒体库工具箱**：格式转换 / 转码（WAV、MP3、M4A、WMA、FLAC）、自研**无损 FLAC 编码**、MusicBrainz 在线标签与封面补全、重复文件检测、缺失标签 / 封面清理向导、按标签自动归档移动。
- **外观与无障碍**：深色 / 浅色双主题、8 套强调配色自由切换；支持键盘焦点导航、UI Automation 与触屏热区，高 DPI 下清晰锐利。
- **便捷能力**：全局快捷键与多媒体键、迷你模式、睡眠定时、记忆播放、高 DPI 适配、**GitHub 自动更新**。

## 自动更新

软件启动后会在后台检查本仓库的 [`update.json`](update.json)；发现新版本时提示下载，校验 SHA256 后自动替换并重启，整个过程无需另行安装。也可以在「设置 → 关于 → 检查更新」中手动检查。

## 版权与合规说明

本软件仅提供播放与管理工具，不存储、不上传任何音乐内容。在线内容来自各平台公开接口或艺术家授权 / 开放许可资源：

- Audius、ccMixter 等平台的资源由**艺术家授权**或遵循 **Creative Commons** 许可，请按相应许可使用；
- 苹果 iTunes / Apple Music 仅播放厂商官方公开的试听片段；
- 对国内平台仅使用其公开 Web 接口，播放地址由服务端校验后下发，**不实现任何加密 / 签名破解**；服务端不返回地址的付费内容不予播放与下载。

请尊重创作者与版权，勿将本软件用于侵权用途。自定义音源脚本由用户自行导入，其内容与合规性由导入者负责。

## 关于源代码

本公开仓库**仅发布编译成品、产品主页与更新清单，不公开源代码**，以保护原创成果。如发现问题，欢迎在 [Issues](https://github.com/haoeastspeed/aurora-music/issues) 反馈。
