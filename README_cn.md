# EasyTransfer

[English](README.md) | 简体中文

EasyTransfer是一个免费、简单、易用的 P2P 文件传输工具。您仅需要访问一个简单的网页，就可以使用设备代码连接到**任何网络**中的**任何设备**。

它使用 webRTC 构建，**无需扫码**、**无需分享 URL 链接**、**无需上传文件到服务器**。

## 使用方法

1. 在需要传输文件的两台设备上访问 [EasyTransfer](https://file.ch3nyang.top/)。
2. 将任意一台设备的四位设备代码输入到另一台设备的设备代码输入框中，并点击连接按钮。
3. 等待连接成功后，您可以将文件拖放到网页上的文件区域，或者点击文件区域选择文件。支持一次性发送多个文件。

## 注意事项

- 信令及数据可能存在泄漏风险，请勿传输隐私文件。
- 本项目全部托管在免费的服务器上，请不要滥用。

## TODO

- [x] 支持大文件传输
- [x] 优化传输速度
- [ ] 支持拍照传输
- [ ] 支持纯文本传输

## 致谢

- 感谢 [metered](https://www.metered.ca/) 提供免费的 STUN 和 TURN 服务器。
- 感谢 [glitch](https://glitch.com/) 提供了免费的信令服务器。