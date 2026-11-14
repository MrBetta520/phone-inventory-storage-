# PhoneStock V3.4 GitHub Pages 网页版

## 部署到 GitHub Pages

1. 新建一个 GitHub 仓库，或打开现有仓库。
2. 把本文件夹中的全部文件上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/(root)`，然后保存。
6. 等待 GitHub Pages 发布完成后，用显示的网址打开。

## 数据说明

- 数据自动保存在当前浏览器的 IndexedDB 中，不上传到 GitHub。
- 同一个网址在不同电脑、不同浏览器或不同浏览器用户中，数据彼此独立。
- 请定期使用“数据与客户 → 导出数据 → 完整备份 JSON”。
- 与“快递单号”版本的 Windows 桌面版 V3.4 使用相同 JSON 数据结构。
- 在另一台设备上使用“导入数据”，系统会合并 JSON 数据，不会覆盖当前数据。
- 不要清除该网站的浏览器数据，否则本机数据会被删除。
- GitHub Pages 必须使用 HTTPS；发布后的 Pages 地址会自动满足此要求。

## 安装成应用

- Windows / Mac：在 Chrome 或 Edge 地址栏选择“安装应用”。
- iPad / iPhone：用 Safari 打开，点“分享 → 添加到主屏幕”。
- 安装后可离线打开；首次使用和更新版本时需要联网。

## 蓝牙扫码器与内置键盘

- 蓝牙扫码器保持 HID Keyboard Mode 和 Enter / CR 后缀即可继续使用。
- iPhone 连接蓝牙扫码器后通常会隐藏系统键盘，因此可点击输入框右侧的 `⌨️` 按钮。
- IMEI、UPC 和数量字段显示数字键盘；其他文字字段显示 iOS 风格 QWERTY 键盘。
- 内置键盘支持字母大小写、数字符号、空格、删除、清除、下一项和确认。
- 本版本不使用手机摄像头，也不会请求摄像头权限。
