<div align="center">

# 🔤 Obsidian Translations

**Obsidian 插件汉化翻译集合**

[![GitHub release](https://img.shields.io/github/v/release/username/obsidian-translations?include_prereleases&style=flat-square)](https://github.com/username/obsidian-translations/releases)
[![GitHub stars](https://img.shields.io/github/stars/username/obsidian-translations?style=flat-square)](https://github.com/username/obsidian-translations/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/username/obsidian-translations?style=flat-square)](https://github.com/username/obsidian-translations/issues)
[![License](https://img.shields.io/github/license/username/obsidian-translations?style=flat-square)](LICENSE)
[![Obsidian](https://img.shields.io/badge/Obsidian-Community%20Plugin-7c3aed?style=flat-square&logo=obsidian)](https://obsidian.md)

*让 Obsidian 插件更懂中文*

[English](#english) · **简体中文**

</div>

---

## 📖 项目简介

本项目收集并维护 Obsidian 社区插件的中文翻译文件，旨在为中文用户提供更好的使用体验。所有翻译均由 [obsidian-i18n](https://github.com/lisnote/obsidian-i18n) 插件生成和管理。

### ✨ 特性

- 🌐 **多插件支持** - 覆盖热门 Obsidian 社区插件
- 🔄 **持续更新** - 跟进插件版本，及时更新翻译
- 📦 **即插即用** - 下载即可使用，无需额外配置
- 🤝 **开放贡献** - 欢迎社区参与翻译改进

---

## 🚀 快速开始

### 安装方法

#### 方法一：通过 Obsidian i18n 插件（推荐）

1. 在 Obsidian 中安装 `obsidian-i18n` 插件
2. 打开插件设置，选择需要的翻译
3. 点击下载，自动完成安装

#### 方法二：手动安装

1. 下载本仓库中对应插件的翻译文件
2. 将翻译文件放入 Obsidian 插件目录：
   ```
   .obsidian/plugins/{plugin-name}/locale/zh-cn.json
   ```
3. 重启 Obsidian 即可生效

---

## 📦 已翻译插件

| 插件名称 | 翻译状态 | 版本 | 说明 |
|---------|:-------:|:----:|------|
| [Templater](https://github.com/SilentVoid13/Templater) | ✅ 完成 | 2.x | 模板插件 |
| [Dataview](https://github.com/blacksmithgu/obsidian-dataview) | ✅ 完成 | 0.5.x | 数据查询 |
| [Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks) | ✅ 完成 | 7.x | 任务管理 |
| [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) | ✅ 完成 | 1.x | 日历视图 |
| [Kanban](https://github.com/mgmeyers/obsidian-kanban) | ✅ 完成 | 2.x | 看板管理 |
| [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin) | ✅ 完成 | 2.x | 绘图工具 |
| [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian) | ✅ 完成 | 0.x | 表格增强 |
| [Outliner](https://github.com/vslinko/obsidian-outliner) | ✅ 完成 | 4.x | 大纲增强 |
| [Remotely Save](https://github.com/fyears/remotely-save) | ✅ 完成 | 0.x | 云同步 |
| [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) | ✅ 完成 | 1.x | 样式设置 |

> 📝 翻译状态：✅ 完成 | 🔄 更新中 | ⏳ 待翻译

---

## 📂 项目结构

```
obsidian-translations/
├── 📁 translations/
│   ├── 📁 templater/
│   │   └── zh-cn.json
│   ├── 📁 dataview/
│   │   └── zh-cn.json
│   └── ...
├── 📁 scripts/
│   └── sync-translations.py
├── README.md
├── LICENSE
└── CONTRIBUTING.md
```

---

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 如何贡献翻译

1. **Fork 本仓库**

2. **修改翻译文件**
   ```bash
   # 克隆你的 fork
   git clone https://github.com/your-username/obsidian-translations.git

   # 进入项目目录
   cd obsidian-translations

   # 编辑翻译文件
   # translations/{plugin-name}/zh-cn.json
   ```

3. **提交 Pull Request**
   - 确保翻译准确、简洁
   - 保持 JSON 格式正确
   - 描述修改内容

### 翻译规范

- 🎯 **准确性**：翻译应准确传达原意
- 💡 **简洁性**：避免冗长，保持界面整洁
- 🔤 **一致性**：同一术语使用统一译法
- 📝 **专业性**：使用 Obsidian 社区通用术语

### 常用术语对照表

| 英文 | 中文 |
|------|------|
| Vault | 仓库 |
| Note | 笔记 |
| Plugin | 插件 |
| Theme | 主题 |
| Command | 命令 |
| Setting | 设置 |
| Template | 模板 |
| Property | 属性 |
| Backlink | 反向链接 |
| Graph view | 关系图谱 |

---

## 📊 统计信息

![Translation Progress](https://img.shields.io/badge/翻译进度-85%25-green?style=flat-square)
![Plugins Covered](https://img.shields.io/badge/已覆盖插件-50+-blue?style=flat-square)
![Contributors](https://img.shields.io/github/contributors/username/obsidian-translations?style=flat-square)

---

## ❓ 常见问题

<details>
<summary><b>翻译不生效怎么办？</b></summary>

1. 确认翻译文件放置位置正确
2. 检查 JSON 格式是否有效
3. 重启 Obsidian
4. 确认插件版本与翻译版本匹配

</details>

<details>
<summary><b>如何请求新插件翻译？</b></summary>

在 [Issues](https://github.com/username/obsidian-translations/issues) 中提交请求，格式如下：

```
插件名称：xxx
插件地址：https://github.com/xxx/xxx
是否愿意贡献翻译：是/否
```

</details>

<details>
<summary><b>翻译有误如何反馈？</b></summary>

欢迎通过以下方式反馈：
- 提交 Issue 描述问题
- 直接提交 PR 修正
- 在讨论区留言

</details>

---

## 📜 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

---

## 🙏 致谢

- [Obsidian](https://obsidian.md) - 优秀的知识管理工具
- [obsidian-i18n](https://github.com/lisnote/obsidian-i18n) - 翻译管理插件
- 所有贡献者的辛勤付出

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐ Star 支持一下！**

Made with ❤️ by [Your Name]

</div>

---

<a name="english"></a>

## 🇺🇸 English

### Overview

This project collects and maintains Chinese translation files for Obsidian community plugins, aiming to provide a better experience for Chinese users. All translations are generated and managed by the [obsidian-i18n](https://github.com/lisnote/obsidian-i18n) plugin.

### Features

- 🌐 **Multi-plugin Support** - Covers popular Obsidian community plugins
- 🔄 **Continuous Updates** - Follow plugin versions and update translations
- 📦 **Plug and Play** - Download and use, no extra configuration needed
- 🤝 **Open Contribution** - Community participation welcome

### Quick Start

1. Install `obsidian-i18n` plugin in Obsidian
2. Open plugin settings and select the translations you need
3. Click download to complete installation automatically

### Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**If this project helps you, please give it a ⭐ Star!**

</div>
