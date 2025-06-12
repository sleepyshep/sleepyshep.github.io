# 📝 Hexo Blog

这是一个基于 [Hexo](https://hexo.io/) 框架构建的**个人博客系统**，前端采用深度自定义的 [Matery 主题](https://github.com/blinkfox/hexo-theme-matery)，并扩展了博客的**前后台功能**，实现了内容创作与展示的一体化。

## 🔧 项目简介

该博客系统不仅支持传统的静态展示，还包括一个完整的**后台管理系统**，用于：

* 📝 撰写和发布文章
* ⚙️ 修改博客配置信息
* 🔍 实时查看展示效果

前台页面使用 Hexo + Matery 渲染，后台管理部分可配合 Node.js、Express 等后端框架部署。

## ✨ 主要特性

在原始 Matery 主题的基础上进行了深度优化和功能拓展，包括但不限于：

* 💬 集成 **Valine 评论系统**
* 💬 增加 **Tidio 在线聊天支持**
* 😊 支持文章内容中插入 Emoji
* 🎵 自定义 **音乐播放器** 与 **视频播放模块**
* 🖼️ 实现图片懒加载，提升性能体验
* 🏗️ 使用 **Gulp 自动化构建工具** 实现 JS/CSS 压缩优化
* 🌄 支持动态博客背景图展示
* 📅 显示博客建站时间与统计信息

## 🚀 快速开始

### 安装 Hexo

```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
```

### 安装主题

```bash
git clone https://github.com/blinkfox/hexo-theme-matery.git themes/matery
```

### 替换为你的自定义主题版本

你可以将本仓库克隆到 `themes/matery` 中，替换原始主题：

```bash
git clone https://github.com/your-username/your-repo-name.git themes/matery
```

## 📃 License

本项目基于 [MIT License](LICENSE) 发布。主题原作者版权归属原始仓库。
