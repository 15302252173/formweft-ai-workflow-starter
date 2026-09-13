# Animated subtitles without an upload / 离线制作动效字幕

FORMWEFT Motion Workbench offline editor, version 1.5.0. Package checked on 2026-09-13.

**[Download the complete offline source package](formweft-motion-workbench-1.5.0-source.zip)** · [Official guide and latest download](https://formweft.com/en/resources/formweft-motion-workbench?utm_source=github&utm_medium=resource&utm_campaign=offline_motion_guide)

This is a copy of the public FORMWEFT package, with the original files and MIT license preserved. It is separate from the learning exercises elsewhere in this repository. The archive includes the actual editor source, not just sample media.

## Start with one short clip

1. Download and extract the ZIP. Open its README.md and then index.html in a current desktop browser.
2. Import a short video you have permission to use and an existing SRT subtitle file. For a first exercise, use the [fictional practice kit](https://github.com/15302252173/formweft-ai-workflow-starter/releases/tag/motion-practice-20260912).
3. Adjust one caption's text, placement and animation. Check whether it covers a face or other important detail.
4. Preview the beginning and end of each caption, including a gap between captions. Save your project JSON before exporting.
5. Export a short range with the source audio, if your video has audio. Browser capabilities determine the available format; check the saved file's picture, duration and audio sync before sharing.

The included sample video in the practice kit is intentionally silent. It cannot demonstrate audio preservation. Use a separate authorized clip with sound to check audio.

## Which edition are you using?

| Edition | Input and processing | What to expect |
| --- | --- | --- |
| Offline 1.5.0 package linked above | Local video, existing SRT, browser editing and export | No account or speech-recognition model in this package. Watermark is off by default and can be enabled. |
| Live web workbench | Basic local editing plus optional separately configured AI workflows | Optional cloud workflows can send supplied material to the selected service. Read that workflow's instructions before using it. |
| Enterprise services | Custom AI workspaces and team training | Separate paid work, quoted by project scope. Downloading this editor does not include enterprise delivery. |

## Source and license

The source archive contains index.html, app.js, core.js, exporter.js, workbench.css, README.md, LICENSE.txt, SKILL.md, examples and project-format documentation. The package's original code and documentation use the MIT license, copyright 2026 FORMWEFT. Keep its license and copyright notice when redistributing. The license does not grant rights to media you import.

SHA-256 of this exact archive:

`c98aa3b2f9590bbfd713ee6e91823189f9d8e6895d48f0358c14adeb76fde53c`

The official download may change as new versions ship. This copy preserves version 1.5.0. This guide records the package contents and workflow; it is not a claim that every browser or device has been tested.

## 中文：先完成一个短片练习

**[下载完整离线源码包](formweft-motion-workbench-1.5.0-source.zip)**。这是官网公开的 1.5.0 原包副本，保留源码、文档和 MIT 许可；不是仅包含字幕样例的练习包。

1. 解压后先读 README.md，再用现代桌面浏览器打开 index.html。
2. 导入有权使用的短视频和已有 SRT 字幕。没有素材时可使用上方链接的虚构练习包。
3. 修改一条字幕，调整位置和动效，检查是否遮挡人脸或关键信息。
4. 预览每条字幕的起止点和字幕间隙，导出前保存项目 JSON。
5. 先导出一小段，再打开成品检查画面、时长和音画同步。练习包的视频本身无声；验证原声保留需要另用带声音的授权素材。

离线包不包含语音识别模型，使用已有 SRT。水印默认关闭，可自行开启。官网在线版另有可选 AI 工作流，云端功能可能向所选服务发送输入资料，不能把整站所有功能都称为完全离线。

MIT 适用于包内 FORMWEFT 原创代码与文档，不授予导入素材的版权。企业 AI 工作台定制与培训另按项目范围报价。这个指南不代表客户案例或业务效果。

[中文官网教程](https://formweft.com/resources/formweft-motion-workbench?utm_source=github&utm_medium=resource&utm_campaign=offline_motion_guide) · [更多免费学习资源](https://formweft.com/resources?utm_source=github&utm_medium=resource&utm_campaign=offline_motion_guide)
