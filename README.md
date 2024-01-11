## 简介

E-component 是一个基于 Vue3、Vite、TypeScript、Unocss、Element plus、Pinia、VueUse 的后台模版，它使用了最新的前端技术栈，内置主题配置、动态菜单、权限校验等，基于 mock 实现的动态数据展示，可以当作开箱的模板，也可用于学习参考。

### 特性

- 使用 Vue3.3 Vite4 Pinia TypeScript 开发
- 支持 ElementPlus 暗黑模式、i18n 国际化
- 支持 VueRouter 动态权限路由、页面按钮权限、路由懒加载
- 使用 KeepAlive 对页面进行缓存
- 简单适配移动端展示
- 常用自定义指令开发（权限、复制、水印、节流、防抖）
- 使用 Prettier 统一格式化代码，集成 ESLint 代码校验规范
- 使用 husky、lint-staged、commitlint 规范提交信息

## 安装使用

- 安装依赖

```bash
pnpm install
```

- 运行

```bash
pnpm dev
```

- 打包

```bash
pnpm build
```
