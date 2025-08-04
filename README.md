# 个人开发模板项目

这是一个我个人常用的开发模板项目，集成了现代化的前端开发技术栈，支持前后端开发，并且可以方便地集成Python脚本。

## 🚀 技术栈

- **前端**: Vue 3 + TypeScript + Vite
- **桌面应用**: Electron
- **开发工具**: VS Code 推荐配置
- **脚本支持**: Python 脚本集成

## ✨ 特性

- 🎯 **前后端兼容**: 支持Web开发和桌面应用开发
- 🐍 **Python脚本**: 可以方便地集成Python脚本进行数据处理
- 🔧 **现代化工具链**: 使用Vue 3 + TypeScript + Vite的现代化开发栈
- 📱 **跨平台**: 基于Electron，支持Windows、macOS、Linux
- ⚡ **快速开发**: 热重载、TypeScript支持、现代化构建工具

## 🛠️ 开发环境

### 推荐IDE设置

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (并禁用Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)

### TypeScript支持

TypeScript默认无法处理`.vue`导入的类型信息，所以我们用`vue-tsc`替换`tsc` CLI进行类型检查。在编辑器中，我们需要[TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)来让TypeScript语言服务了解`.vue`类型。

如果独立的TypeScript插件感觉不够快，Volar还实现了一个更高效的[Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669)。您可以通过以下步骤启用它：

1. 禁用内置的TypeScript扩展
   1. 从VSCode的命令面板运行`Extensions: Show Built-in Extensions`
   2. 找到`TypeScript and JavaScript Language Features`，右键单击并选择`Disable (Workspace)`
2. 从命令面板运行`Developer: Reload Window`重新加载VSCode窗口

## 🎉 个人评价

这个模板项目是我个人非常喜欢的开发工具，它提供了：

- **灵活性**: 可以快速切换Web和桌面应用开发
- **效率**: 现代化的工具链大大提升了开发效率
- **扩展性**: Python脚本的集成让数据处理变得简单
- **稳定性**: 经过多次项目验证，非常稳定可靠

## 📝 使用说明

1. 克隆此模板项目
2. 安装依赖: `npm install`
3. 启动开发服务器: `npm run dev`
4. 构建桌面应用: `npm run build`

---

*这是一个个人常用的开发模板，经过多次项目验证，非常方便实用！*
