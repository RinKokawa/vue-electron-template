# Vue + Electron Desktop Application Template

This is a specialized Vue + Electron template project for developing desktop applications, and it's an important component of my personal development template series.

---

## 🎯 Template Positioning

**Template Type**: Desktop Application Development Template  
**Use Cases**: Projects that need to develop cross-platform desktop applications  
**Tech Stack**: Vue 3 + TypeScript + Electron + Vite

---

## 🚀 Technology Stack

- **Frontend Framework**: Vue 3 + TypeScript + Vite
- **Desktop Application**: Electron
- **Development Tools**: VS Code Recommended Configuration
- **Build Tools**: electron-builder
- **Script Support**: Can integrate Python scripts for data processing

---

## ✨ Core Features

- 🖥️ **Desktop Application**: Based on Electron, supports Windows, macOS, Linux
- 🎯 **Frontend-Backend Compatible**: Supports both Web and desktop application development
- 🐍 **Python Integration**: Can easily integrate Python scripts for data processing
- 🔧 **Modern Toolchain**: Uses Vue 3 + TypeScript + Vite modern development stack
- ⚡ **Rapid Development**: Hot reload, TypeScript support, modern build tools
- 📦 **One-Click Packaging**: Supports multi-platform application packaging and distribution

---

## 🛠️ Development Environment

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)

### TypeScript Support

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

> 1. Disable the built-in TypeScript Extension
>    1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
>    2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
> 2. Reload the VSCode window by running `Developer: Reload Window` from the command palette

---

## 🎉 Personal Review

This desktop application development template is one of the most commonly used in my personal template series, providing:

- **Cross-Platform Capability**: One codebase runs on Windows, macOS, Linux
- **Development Efficiency**: Modern toolchain greatly improves desktop application development efficiency
- **Extensibility**: Python script integration makes data processing simple
- **Stability**: Verified through multiple projects, very stable and reliable

---

## 📝 Usage Instructions

1. Clone this template project
2. Install dependencies: `npm install`
3. Start development server: `npm run dev`
4. Build desktop application: `npm run build`

---

*This is a template specifically designed for desktop application development, verified through multiple projects, perfect for quickly starting desktop application projects!* 