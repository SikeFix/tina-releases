<div align="center">

# Tina

**一个能陪你聊天、查看 AI 工作进度，也能接上旧会话的桌面伙伴。**

[官网](https://tina.keorigin.com/) · [完整使用教程](https://tina.keorigin.com/home/guide.html) · [选择下载方式](https://tina.keorigin.com/home/download.html)

</div>

## 下载最新版

| 设备 | 直接下载 | 包含什么 |
|---|---|---|
| Mac · Apple 芯片 | [Tina-macos-arm64.zip](https://github.com/SikeFix/tina-releases/releases/latest/download/Tina-macos-arm64.zip) | Tina.app 桌宠、菜单栏、完整工作台 |
| Windows · x64 | [Tina-windows-amd64.zip](https://github.com/SikeFix/tina-releases/releases/latest/download/Tina-windows-amd64.zip) | 后台服务、浏览器工作台和安装脚本 |
| iPhone | [打开手机网页版](https://tina.keorigin.com/app/) | 连接已绑定的电脑；原生 App 暂无公开签名安装包 |
| Linux / Intel Mac | [查看所有发布文件](https://github.com/SikeFix/tina-releases/releases/latest) | 对应平台的命令行与浏览器工作台 |

这些直达链接始终指向最新正式版。每个版本另保留带版本号的 ZIP，方便回退。下载后可用发布页里的 SHA256SUMS 校验文件。

## 第一次使用

1. Mac：解压后把 Tina.app 放进“应用程序”，打开桌宠或菜单栏里的完整工作台。Windows：解压并运行“安装.bat”。
2. 在“偏好与设置 → 模型与渠道”添加自己的模型接口和密钥，并点“测试连接”。密钥保存在本机。
3. 要在手机查看电脑，先在电脑的“偏好与设置 → 手机连接”绑定易登录账号，再扫码或在手机登录[网页工作台](https://tina.keorigin.com/app/)。
4. 网页右上角账号菜单可以查看当前账号、切换账号或退出登录。

详细步骤和常见问题见[完整使用教程](https://tina.keorigin.com/home/guide.html)。

## 现在能做什么

- 和 Tina 文字、图片或语音对话；Mac 上的桌宠可常驻、隐藏和恢复。
- 在“任务与会话”查看本机 Codex、ZCode、DeepSeek 等工具的已有记录和已验证的运行进展，引用会话请 Tina 整理，也可通过可用的原生入口继续原任务。
- 让 Tina 派发新任务、汇报结果；关键操作仍按原工具的审批机制处理。
- 保存主人偏好与生活记忆，生成复盘，安排提醒和定时任务。
- 用一个 SSO 账号绑定多台电脑，从手机选择电脑查看；Tina 对话可在绑定的电脑间同步。

外部工具是否能直接续接，取决于该工具提供的原生通道和当前连接状态。界面会区分“排队等待”“已发送”和“已执行”。

## 平台与安装说明

macOS 桌宠需要 macOS 13+ 和 Apple 芯片。当前 Mac 安装包采用本地签名，没有 Developer ID 公证；首次打开可能需要在“系统设置 → 隐私与安全性”中确认。Windows 和 Linux 版本尚未完成与 Mac 同等程度的真机验证。iOS 原生项目仍需开发者签名，暂不提供可直接安装的 IPA。

此公开仓库只存放发布产物，源码仓库目前为私有。问题和建议可通过本仓库的 [Issues](https://github.com/SikeFix/tina-releases/issues) 提交。
