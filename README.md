# Vue + Electron 桌面应用开发模板

这是一个专门用于开发桌面应用的Vue + Electron模板项目，是我个人开发模板系列中的一个重要组成部分。

---

## 🎯 模板定位

**模板类型**: 桌面应用开发模板  
**适用场景**: 需要开发跨平台桌面应用的项目  
**技术栈**: Vue 3 + TypeScript + Electron + Vite

---

## 🚀 技术栈

- **前端框架**: Vue 3 + TypeScript + Vite
- **桌面应用**: Electron
- **开发工具**: VS Code 推荐配置
- **构建工具**: electron-builder
- **脚本支持**: 可集成Python脚本进行数据处理

---

## ✨ 核心特性

- 🖥️ **桌面应用**: 基于Electron，支持Windows、macOS、Linux
- 🎯 **前后端兼容**: 支持Web开发和桌面应用开发
- 🐍 **Python集成**: 可以方便地集成Python脚本进行数据处理
- 🔧 **现代化工具链**: 使用Vue 3 + TypeScript + Vite的现代化开发栈
- ⚡ **快速开发**: 热重载、TypeScript支持、现代化构建工具
- 📦 **一键打包**: 支持多平台应用打包和分发

---

## 🛠️ 开发环境

### 推荐IDE设置

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (并禁用Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)

### TypeScript支持

TypeScript默认无法处理`.vue`导入的类型信息，所以我们用`vue-tsc`替换`tsc` CLI进行类型检查。在编辑器中，我们需要[TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)来让TypeScript语言服务了解`.vue`类型。

如果独立的TypeScript插件感觉不够快，Volar还实现了一个更高效的[Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669)。您可以通过以下步骤启用它：

> 1. 禁用内置的TypeScript扩展
>    1. 从VSCode的命令面板运行`Extensions: Show Built-in Extensions`
>    2. 找到`TypeScript and JavaScript Language Features`，右键单击并选择`Disable (Workspace)`
> 2. 从命令面板运行`Developer: Reload Window`重新加载VSCode窗口

---

## 🎉 个人评价

这个桌面应用开发模板是我个人模板系列中最常用的之一，它提供了：

- **跨平台能力**: 一套代码运行在Windows、macOS、Linux
- **开发效率**: 现代化的工具链大大提升了桌面应用开发效率
- **扩展性**: Python脚本的集成让数据处理变得简单
- **稳定性**: 经过多次项目验证，非常稳定可靠

---

## 📝 使用说明

1. 克隆此模板项目
2. 安装依赖: `npm install`
3. 启动开发服务器: `npm run dev`
4. 构建桌面应用: `npm run build`

---

*这是一个专门用于桌面应用开发的模板，经过多次项目验证，非常适合快速启动桌面应用项目！*
