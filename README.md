# MD_pre

Markdown 文件修订展示项目的开发环境。当前仅配置工具链，没有业务代码或应用页面。

## 环境

- Node.js 24（`.nvmrc`）与 npm
- TypeScript 严格检查
- Vite 前端开发工具
- Vitest 测试工具
- EditorConfig、Git 忽略规则、依赖锁文件
- 可选 Dev Container / GitHub Codespaces 配置
- GitHub Actions 环境检查

## 使用

```bash
git clone https://github.com/Haloukaidi/MD_pre.git
cd MD_pre
npm ci
npm run typecheck
npm test
```

`npm test` 允许当前没有测试文件，后续添加测试后会正常执行。尚未创建页面入口，因此暂不运行开发服务器或生产构建。开始实现项目后可添加入口、源码与相应脚本。

## 开发容器

在支持 Dev Containers 的编辑器或 GitHub Codespaces 中打开仓库即可。容器使用 Node.js 24，并自动运行 `npm ci`。预留 5173 端口供后续 Vite 开发服务器使用。

当前未创建任何运行中的云端环境，也未部署网站。
