# [芙芙启动器 (FufuLauncher)](https://github.com/whitecode666/FufuLauncher)

![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)
![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![WinUI](https://img.shields.io/badge/UI-WinUI%203-8A2BE2)

> 一款基于 WinUI 3 的《原神》第三方启动工具，支持游戏注入、自动签到和多种实用功能。

[English](./README-en.md) | [Tiếng Việt](./README-vi.md)

---

## 📸 截图

> *（在此处添加应用截图）*

---

## ✨ 主要功能

### 🔐 账号管理
- 多账号快速切换，无需重复输入密码
- 本地加密存储，保护账号安全
- 支持米游社扫码登录

### 📅 自动签到
- 每天一键完成米游社/霍霍巴签到
- 支持云游戏签到
- 社区任务自动完成（点赞、阅读、分享）

### 🎮 游戏管理
- 自动检测游戏安装路径
- 实时版本更新公告
- 游戏资源预下载与完整性验证
- 服务器切换（官方/Bilibili/国际服）

### ⚡ 实用工具
- **养成计算器**：计算角色和武器培养所需资源
- **键盘连点器**：自动化点击操作
- **帧率监控**：实时显示游戏帧率
- **截图工具**：一键截取游戏画面
- **祈愿记录**：查看和分析抽卡数据
- **成就管理**：追踪成就进度

### 🚀 启动参数
- 自定义分辨率与窗口模式
- 自定义启动参数预设
- 多显示器支持

### 🔧 注入功能
- DLL 注入支持
- 预设管理系统
- 插件扩展支持

### 🎨 个性化
- 自定义背景（图片/视频/轮播）
- 自定义主题颜色
- 毛玻璃/亚克力效果
- 可调节透明度

---

## 📥 安装与使用

### 系统要求
- **操作系统**：Windows 10/11（64位）
- **运行库**：[.NET 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) 或更高版本
- **运行库**：[Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)（Windows 10 以上版本通常已内置）
- **运行库**：Visual C++ Redistributable v14

### 快速开始

1. **首次运行**：将显示用户协议，请仔细阅读并同意后继续
2. **设置游戏路径**：进入「设置」页面选择游戏安装目录（建议使用自动检测）
3. **登录账号**：在「账号」页面登录米游社账号以使用签到功能
4. **启动游戏**：主页点击「启动游戏」即可

> ⚠️ **重要提醒**：
> - 切换账号需要**管理员权限**
> - 建议先选择游戏路径，再以管理员身份运行程序
> - 注入功能需要**管理员权限**
> - 动态视频背景可能不稳定，建议使用静态图片

---

## 🏗️ 技术栈

- **UI 框架**：WinUI 3（Windows App SDK）
- **编程语言**：C# (.NET 8.0)
- **架构模式**：MVVM（CommunityToolkit.Mvvm）
- **数据库**：SQLite（本地设置存储）
- **注入技术**：原生 DLL 注入
- **后台服务**：Windows 原生 API + HTTP API

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！请遵循以下步骤：

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

### 报告问题
- [提交 Bug](https://github.com/whitecode666/FufuLauncher/issues/new?template=bug_report.yml)
- [请求功能](https://github.com/whitecode666/FufuLauncher/issues/new?template=feature_request.yml)

---

## 📄 许可证

本项目采用 [MIT License](../LICENSE) 开源协议。

版权所有 © 2026 whitecode666

---

## 🌟 支持项目

如果觉得本项目对你有帮助，欢迎在 GitHub 上给个 ⭐！

[![Star History Chart](https://api.star-history.com/svg?repos=whitecode666/FufuLauncher&type=date&legend=top-left)](https://www.star-history.com/#whitecode666/FufuLauncher&type=date&legend=top-left)

---

## 📞 联系方式

- [GitHub Issues](https://github.com/whitecode666/FufuLauncher/issues)
- [Telegram](https://github.com/whitecode666/FufuLauncher)

---

*本软件为第三方独立开发工具，与米哈游（miHoYo）及其关联公司无任何关联。*
*请支持官方正版游戏。*
