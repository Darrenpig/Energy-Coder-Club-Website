# Energy Coder Club Website

新能源编程俱乐部官方网站 - 一个现代化的 React + TypeScript 项目。

## 🚀 快速启动

### Windows 用户（推荐）

**一键启动开发环境：**
```powershell
# PowerShell 脚本（推荐）
.\start-dev.ps1

# 或批处理文件
.\start-dev.bat
```

**环境检查：**
```powershell
# 检查开发环境配置
.\check-env.ps1
```

### 手动启动

1. **安装 Node.js**（必需）
   - 访问 [Node.js 官网](https://nodejs.org/) 下载 LTS 版本
   - 或查看 `SETUP_GUIDE.md` 获取详细安装指南

2. **安装依赖：**
```bash
# 使用 npm
npm install

# 或使用 bun（更快）
bun install
```

3. **启动开发服务器：**
```bash
npm run dev
# 或 bun dev
```

4. **构建生产版本：**
```bash
npm run build
# 或 bun run build
```

## 🛠️ 技术栈

- **前端框架：** React 18.2.0 + TypeScript 5.7.2
- **构建工具：** Vite 6.3.1
- **样式框架：** Tailwind CSS 3.4.1
- **UI 组件：** shadcn/ui + Radix UI
- **路由：** React Router 7.5.1
- **状态管理：** Zustand
- **图标：** Lucide React
- **国际化：** 自定义 i18n 解决方案

## 📁 项目结构

```
src/
├── components/          # 可复用组件
│   ├── auth/           # 认证相关
│   ├── forms/          # 表单组件
│   ├── home/           # 首页组件
│   ├── layout/         # 布局组件
│   └── ui/             # UI 基础组件
├── contexts/           # React Context
├── hooks/              # 自定义 Hooks
├── lib/                # 工具库和配置
├── pages/              # 页面组件
├── services/           # API 服务
└── store/              # 状态管理
```

## 🌐 开发信息

- **本地服务器：** http://localhost:5173
- **构建输出：** `dist/` 目录
- **代码检查：** ESLint + TypeScript
- **样式：** Tailwind CSS + CSS Modules
- **响应式设计：** 移动端优先
