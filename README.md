# 连续视频特征轨迹跟踪

独立课程实验 006/02。

- 网站：[运行真实示例](https://hub-fover.github.io/Vision-Lab-006-02-Tracking/)
- 源码：[GitHub](https://github.com/hub-fover/Vision-Lab-006-02-Tracking)
- 课件关联：第 3–22 页。比较开启和关闭补点的轨迹寿命，特征 ID 不表示物体身份。

本仓库包含本实验网页、真实样例、运行时及资源来源说明，可部署到任意静态服务器。无需其他课程仓库；相机要求 HTTPS。打开即运行实拍样例，可导入自己的数据。

本地运行：

```sh
python -m http.server 8000
```

浏览器打开 http://localhost:8000/。请通过 HTTP/HTTPS 运行，不使用 file://。

验证：`npm test` 检查随附资源 SHA-256。许可证及素材来源见 LICENSES.md、THIRD_PARTY_NOTICES.md（如适用）及各 assets 下 metadata/来源台账。
