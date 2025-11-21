---
sidebar_position: 1
---

# 教程简介

让我们在 **不到 5 分钟** 的时间内，快速了解 **Docusaurus**。

## 快速开始

你可以通过 **创建一个新站点** 来开始。

或者，立即通过 **[docusaurus.new](https://docusaurus.new)** 试用 Docusaurus。

### 准备工作

- [Node.js](https://nodejs.org/en/download/) 版本 20.0 或更高：
  - 安装 Node.js 时，建议勾选所有与依赖项相关的选项。

## 生成新站点

使用 **经典模板（classic template）** 生成一个新的 Docusaurus 站点。

运行以下命令后，经典模板会自动添加到你的项目中：

```bash
npm init docusaurus@latest my-website classic
```

你可以在命令提示符、PowerShell、终端，或代码编辑器的任意集成终端中输入该命令。

该命令还会自动安装运行 Docusaurus 所需的所有依赖项。

## 启动你的站点

运行开发服务器：

```bash
cd my-website
npm run start
```

`cd` 命令用于切换当前工作目录。为了操作你刚刚创建的 Docusaurus 站点，你需要先在终端中进入该目录。

`npm run start` 命令会在本地构建你的网站，并通过开发服务器启动，你可以在 http://localhost:3000/ 查看效果。

打开 `docs/intro.md`（即本页面）并修改几行内容：站点会**自动重新加载**并显示你的更改。

AABBCC