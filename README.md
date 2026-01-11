# NeoFoy - LED Matrix Light Effects Community

🌟 **NeoFoy** 是一个开源的智能箱包/服装 LED 矩阵光效社区平台。  
目标：打造全球最大的 LED 光效分享与实时预览生态，让创作者轻松上传、分享、预览自定义动画效果，并一键下载 JSON 文件用于实际硬件。

项目目前处于早期开发阶段，欢迎 star、fork、issue 和 PR！

## ✨ 核心功能（当前/规划中）

- 社区首页：瀑布流展示各种光效（赛博朋克、日落、律动等）
- 效果详情页：全屏实时预览 + 参数调节（速度、颜色等）
- LED 矩阵模拟器：高性能 Canvas 渲染，支持圆形灯珠 + 多层光晕效果
- JSON 协议标准化：跨平台无损传输光效文件
- 一键下载 & 未来同步到硬件/App

## 🛠️ 技术栈

- **Frontend**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS + 玻璃拟态效果
- **State Management**: Zustand
- **Routing**: React Router
- **Animation/UI**: Framer Motion + lucide-react icons
- **Components/Layout**: react-masonry-css（瀑布流）
- **License**: MIT

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/LEDFOY/NeoFoy.git
cd NeoFoy
2. 安装依赖
Bashnpm install
# 或使用 pnpm / yarn / bun
# pnpm install
# yarn install
3. 启动开发服务器
Bashnpm run dev
# 访问 http://localhost:5173
4. 构建生产版本
Bashnpm run build
# 输出在 dist/ 目录
📂 项目结构
textNeoFoy/
├── public/               # 静态资源（favicon 等）
├── src/
│   ├── components/       # 可复用组件（LEDSimulator.tsx 等）
│   ├── pages/            # 页面组件（Community.tsx, EffectDetail.tsx）
│   ├── store/            # Zustand store
│   ├── types/            # TypeScript 类型定义（effect.ts）
│   ├── styles/           # 全局 CSS / Tailwind 配置
│   ├── App.tsx
│   └── main.tsx
├── .gitignore
├── LICENSE               # MIT License
├── package.json
├── tsconfig.json
├── vite.config.ts
└── tailwind.config.js
🖼️ 截图（待添加）
（建议稍后添加实际运行截图，可以用 macOS 的截屏或 Vercel 部署后的页面）

社区瀑布流
效果详情页全屏预览
参数调节实时变化

📈 未来计划

用户认证 & 上传光效功能
后端集成（Supabase / Firebase）存储 JSON 文件
更真实的 WebGL / Three.js 渲染
移动端适配 + PWA 支持
光效分类、搜索、点赞、评论系统
与真实硬件（ESP32 + WS2812）同步方案

🤝 贡献指南
欢迎任何形式的贡献！

Fork 本仓库
创建你的特性分支 (git checkout -b feature/awesome-feature)
提交代码 (git commit -m 'Add awesome feature')
推送分支 (git push origin feature/awesome-feature)
提交 Pull Request

请确保代码风格一致（ESLint + Prettier），并在 PR 中说明变更内容。
📄 License
本项目采用 MIT License 开源。

Created with ❤️ by Foy
最后更新：2026 年 1 月
欢迎 Star & Follow！✨
