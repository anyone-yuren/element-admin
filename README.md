
## 简介

[vue-element-admin](http://panjiachen.github.io/vue-element-admin) 是一个后台集成解决方案，它基于 [vue](https://github.com/vuejs/vue) 和 [element](https://github.com/ElemeFE/element)。它使用了最新的前端技术栈，内置了 i18 国际化解决方案，动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型。相信不管你的需求是什么，本项目都能帮助到你。

- [在线访问](http://panjiachen.github.io/vue-element-admin)

- [使用文档](https://panjiachen.github.io/vue-element-admin-site/zh/)


**本项目的定位是后台集成方案，不适合当基础模板来开发。**

- 模板建议使用: [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template)


# 安装依赖
npm install

# 建议不要用 cnpm 安装 会有各种诡异的bug 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:9527

## 发布

```bash
# 构建测试环境
npm run build:sit

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# --report to build with bundle size analytics
npm run build:prod

# --generate a bundle size analytics. default: bundle-report.html
npm run build:prod --generate_report

# --preview to start a server in local to preview
npm run build:prod --preview

# lint code
npm run lint

# auto fix
npm run lint -- --fix
```
