胶片 · Jiaopian 网页版（iPhone Safari / iOS 15+）

部署与使用：
1. 将仓库通过 GitHub Pages 发布为 HTTPS 静态网站。
2. iPhone 使用 Safari 打开网站。
3. 点击“开启相机”并允许 Safari 使用相机。
4. Safari 分享菜单 → 添加到主屏幕，即可像 App 一样启动。

功能：相机取景、胶卷风格、曝光视觉模拟、日期水印、拍摄参数记录、36 张计数、照片本地档案、单张查看、索引导出。

限制：
- 相机必须从 HTTPS 页面打开。
- 这是网页/PWA，不是原生 iOS App。
- ISO 和 EV 用于视觉模拟及记录，不会直接控制 iPhone 相机硬件曝光。
- 闪光灯控制受 Safari 限制。
- 照片保存在 Safari IndexedDB；清除网站数据可能丢失。
- 尚未完成多型号 iPhone 真机测试，请先拍摄测试。