# 星选口播更新发布

此仓库只存放可分发的 Windows 更新包、版本清单和 Chrome Web Store 上传包。

- 私有源码仓库：由维护者管理，不在此公开。
- Windows 程序：每次启动自动读取 `update.json`，下载并校验新版更新包。
- Chrome 扩展：通过 Chrome Web Store 的“不公开”发布渠道分发，安装一次后由 Chrome 自动更新。

## Chrome 应用店发布前的临时安装

下载 release 中名称为 `xingxuan-koubo-chrome-local-unpacked-*.zip` 的文件，先解压，再在 `chrome://extensions` 中开启开发者模式并点击“加载已解压的扩展程序”。选择的文件夹内必须能直接看到 `manifest.json`；Chrome 不能直接加载 ZIP 文件。

请同时安装并启动 Windows 主程序，否则扩展无法在本机生成转写文案或下载 TXT。
