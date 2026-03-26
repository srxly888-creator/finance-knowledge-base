# YouTube 频道字幕整理

## 已收录频道

### ✅ 最佳拍档 (@bestpartners)
- **状态**：已下载 6 个视频字幕（+1）
- **大小**：226 KB（+50KB）
- **主题**：AI 与创业、硬科技、投资趋势
- **最新视频**：
  1. **【人工智能】Cursor要凉了么** ⭐新增（2026-03-25）
     - 主题：Insight Partners创始人谈Cursor、自主Agent、SaaS海啸
     - 时长：25分54秒
     - 重点：Murdoch警告Cursor已过时，自主Agent才是未来

  2. YC 的初心 | AI 正在改变优秀创始人的定义
  3. TeraFab 可行么 | 马斯克 | 2 纳米
  4. 如何用 AI 让收入翻倍 | Reid Hoffman
  5. 马斯克的巨硬还能硬下去么 | MacroHard
  6. 从 SaaS 到 SaaaS | 摩根士丹利 TMT 峰会

### ❌ 小林说书 (@xiao_lin_shuo)
- **状态**：无可用字幕
- **原因**：该频道视频未提供字幕（手动/自动生成）
- **视频数**：5 个
- **订阅者**：1.28K
- **主题**：《演员的自我修养》讲书笔记系列

## 待收录频道

- 硅谷101 (@TheValley101)
- 有点在李 (@validli2025)
- 文森說書 (@vincent_reading)

## 下载方法

使用 `yt-dlp` 工具下载字幕：

```bash
# 下载单个视频字幕
yt-dlp --write-sub --write-auto-sub --sub-lang "zh-Hans,zh,en" --skip-download -o "%(title)s_[%(id)s]" "VIDEO_URL"

# 批量下载频道字幕
yt-dlp --write-sub --write-auto-sub --sub-lang "zh-Hans,zh,en" --skip-download -o "%(title)s_[%(id)s]" "https://www.youtube.com/@CHANNEL_NAME/videos"
```

## 字幕格式

- **格式**：SRT (SubRip) / VTT (WebVTT)
- **编码**：UTF-8
- **语言**：简体中文 (zh-Hans)
- **类型**：自动生成字幕 (ASR) 或手动上传字幕

---

**更新时间**：2026-03-25 08:35
**维护者**：srxly888-creator
