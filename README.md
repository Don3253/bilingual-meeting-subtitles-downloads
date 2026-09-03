# 双语会议字幕下载

这是 **WANGG Tools 双语会议字幕** 的公开下载仓库。这里只发布安装包、使用手册和校验值，应用源代码保存在私有仓库中，不在此公开。

## 下载

- [Windows 安装包 v1.1.0](https://github.com/Don3253/bilingual-meeting-subtitles-downloads/releases/download/v1.1.0/Bilingual-Meeting-Subtitles-Setup-1.1.0.exe)
- [中文使用手册 PDF v1.1.0](https://github.com/Don3253/bilingual-meeting-subtitles-downloads/releases/download/v1.1.0/Bilingual-Meeting-Subtitles-User-Guide-zh-CN-1.1.0.pdf)
- [WANGG Tools 软件网站](https://tools.harbor2don.com/#tools)

## 安全校验

下载后可在 PowerShell 中运行：

```powershell
Get-FileHash -Algorithm SHA256 .\Bilingual-Meeting-Subtitles-Setup-1.1.0.exe
```

应得到：

```text
EC455A46E15A65449E165904FDAE74524C14C6EBC7DC92777529BD881A50C9B0
```

完整校验值也见 [SHA256SUMS.txt](./SHA256SUMS.txt)。

## 隐私说明

实时语音识别和离线翻译在本机处理。音频只在内存中短暂处理，不保存为录音文件。只有用户主动调用云端大模型并确认后，会议文字才会发送给所选服务商。

## 反馈

欢迎在 [WANGG Tools 软件网站](https://tools.harbor2don.com/#tools) 的“评论 / 建议”入口留下真实体验和改进建议。

