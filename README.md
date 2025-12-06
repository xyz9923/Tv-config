<div align="center">

# 📺 Tv-config

**精选影视资源配置仓库 | 支持 LunaTV/DECOTV**

[![GitHub stars](https://img.shields.io/github/stars/xyz9923/Tv-config?style=flat-square)](https://github.com/xyz9923/Tv-config/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xyz9923/Tv-config?style=flat-square)](https://github.com/xyz9923/Tv-config/network)


</div>

---

## 📖 简介

本仓库提供精心整理的影视资源站点配置文件，支持多种主流电视盒子应用。所有配置均经过去重和优化处理，确保资源的有效性和多样性。

## 🎯 推荐客户端

推荐使用 **DECOTV** 客户端（LUNATV 项目的二次开发），支持多平台，界面简洁流畅。

---

## 📂 配置文件说明

### 🌟 自用.json（推荐）

**文件路径**: `lunatv/自用.json`

**适用于**: LunaTV、DECOTV 等项目

包含 涵盖影视、动漫、综艺等类型。其中影视资源 50+ 个，含10+个 NSFW 内容。

> ✅ **已通过有效性检查**（2025-12-04）

#### 🔗 使用方法

**方法一：直接订阅（推荐）**
```
https://raw.githubusercontent.com/xyz9923/Tv-config/main/lunatv/自用.json
```

**方法二：手动导入**
1. 下载 `lunatv/自用.json` 文件
2. 在客户端中选择「导入配置」
3. 选择下载的 JSON 文件
4. 等待导入完成

---

### 📋 其他配置文件

| 文件名 | 说明 | 
|--------|------|
| `config.json` | 完整配置 |
| `媒体.json` | 影视媒体专用 | 
| `媒体去重后.json` | 去重后的媒体配置 | 
| `老司机.json` | 成人内容 | 
| `老司机去重后.json` | 去重后的成人内容 |

---

## 🤖 AI 提示词 (AI Prompt)

**文件路径**: `AI-prompt.txt`

这是一个专门设计的 AI 提示词，用于帮助您将任意来源的 JSON 数据转换为本项目支持的格式。

### ✨ 主要功能
- **智能格式转换**: 支持转换为 `omnibox` 或 `lunatv` 格式
- **自动补全**: 自动生成缺失的 `id` (UUID) 和 `time` (ISO 8601)
- **智能映射**: 自动识别并映射 `name`, `url` 等关键字段
- **默认值填充**: 自动处理 `type`, `isActive` 等字段的默认值

### 🚀 使用方法
1. 复制 `AI-prompt.txt` 的全部内容
2. 发送给 ChatGPT / Claude / Gemini 等 AI 助手
3. 按照提示输入您的源 JSON 数据和目标 LUNATV或者omnibox格式
4. AI 助手会返回转换后的 JSON 数据
5. 将返回的 JSON 数据复制到您的客户端中

---

---

## 📚 配置来源

本仓库配置文件来源于以下优质项目和社区：

### 🔗 推荐仓库
- **LunaTV-config**: https://github.com/hafrey1/LunaTV-config
  - LunaTV 官方推荐配置仓库
  - 资源丰富，更新及时

- **Source-Collector**: https://github.com/adminlove520/Source-Collector
  - 影视资源站点采集项目

### 💬 社区讨论
- **Linux.do 讨论帖 #1**: https://linux.do/t/topic/997817
 - `source-collector` 仓库

- **Linux.do 讨论帖 #2**: https://linux.do/t/topic/1133648
  - `媒体.json` 和 `老司机.json` 来源

### 🔧 处理说明
- 基于 `source-collector` 仓库中的 `sites_export_2025-09-29.json`
- 使用 `config.json` 作为参照进行去重处理
- 确保资源的唯一性和有效性

---

## ⚠️ 免责声明

1. 本仓库仅提供资源站点配置信息，不存储任何影视内容
2. 所有资源均来自互联网公开渠道，版权归原作者所有
3. 请遵守当地法律法规，支持正版内容
4. 本项目仅供学习交流使用，请勿用于商业用途
5. 使用本配置产生的任何问题，与本仓库无关

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

如果您有优质的资源站点推荐，或发现配置问题，请：

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

---

## 📞 联系方式

- **GitHub Issues**: [提交问题](https://github.com/xyz9923/Tv-config/issues)
- **讨论区**: [参与讨论](https://github.com/xyz9923/Tv-config/discussions)

---



<div align="center">

**⭐ 如果这个项目对您有帮助，请给一个 Star！⭐**

Made with ❤️ by xyz9923

</div>


