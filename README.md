# WB Analyzer

WB Analyzer 是用于 Western blot 图像整理、泳道与条带识别、灰度定量及统计展示的 Windows 桌面软件。

## 下载

请从 [Latest Release](https://github.com/ZHAOYING0717/WB-Analyzer-Releases/releases/latest) 下载最新的正式安装程序。

- 支持系统：Windows 10/11 x64
- 当前版本：1.0.0
- 安装文件：`WB-Analyzer-Setup-1.0.0.exe`
- SHA-256：`58E8615E072428751BF8AD94579264606E3AB9EFE084C94401DB9864BC08355E`

下载后可使用 Windows PowerShell 核对文件：

```powershell
Get-FileHash .\WB-Analyzer-Setup-1.0.0.exe -Algorithm SHA256
```

## 许可证

本仓库仅提供 WB Analyzer 商业软件的安装程序和公开说明，不包含源代码。

软件分为 Free 与 Plus 状态。使用完整分析功能需要导入与设备匹配且在有效期内的合法许可证。许可证由软件提供者另行签发。

WB Analyzer 的原创程序、界面、文档和相关知识产权归赵梦颖所有。安装或使用软件前，请阅读随安装程序展示并安装到软件目录中的[《WB Analyzer 软件许可与用户协议》](WB%20Analyzer_软件许可与用户协议.md)。本仓库未采用开源软件许可证，也不授予源代码使用权。

## 安全提示

- 建议只从本仓库的 Releases 页面下载安装程序。
- 当前安装程序尚未配置 Windows 代码签名，Windows 可能显示“未知发布者”提示。
- 软件在本地离线处理用户选择的图像和项目文件，不主动上传实验数据。
- 软件用于科研辅助，自动识别和计算结果应结合原始数据与专业判断复核，不用于临床诊断或治疗决策。

## 第三方组件

安装目录中的 `THIRD_PARTY_NOTICES.txt` 和 `licenses` 文件夹包含第三方组件清单及许可证原文。

Copyright © 2026 赵梦颖. All rights reserved.
