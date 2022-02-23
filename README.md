# vue3-admin-template

> 这是一个基础的 vue3 admin 管理后台。它只包含了 Element-Plus UI & axios & svg-icon& permission control & lint，这些搭建后台必要的东西。


本架构使用的技术为：vue3(setup-script)+vite2+element-plus 的新一代的前端框架，It's fast!

使用 eslint+prettier+gitHooks 格式和校验代码,提高代码规范性和开发效率

Vite 需要 Node.js 版本 >= 12.0.0。

## 更新日志

---请查看架构文档

- [真香定律！带你用vue3+vite2撸后台（系列文章入口）](https://juejin.cn/post/7036302298435289095)


## 文档

- [真香定律！带你用vue3+vite2撸后台（系列文章入口）](https://juejin.cn/post/7036302298435289095)

## 线上体验

[github address](https://github.com/jzfai/vue3-admin-template.git)

[Access address](http://8.135.1.141/vue3-admin-template)

github 地址：  https://github.com/jzfai/vue3-admin-template.git

国内体验地址：http://8.135.1.141/vue3-admin-template


## 相关项目

框架有js，ts，plus和electron版本

- js版本：[vue3-element-admin](https://github.com/jzfai/vue3-admin-template.git)
- ts版本：[vue3-element-ts](https://github.com/jzfai/vue3-admin-ts.git)
- js实例参考plus版本：[vue3-element-plus](https://github.com/jzfai/vue3-admin-plus.git)
- electron版本：[vue3-element-electron](https://github.com/jzfai/vue3-admin-electron.git)
- react版本： [react-admin-template](https://github.com/jzfai/react-admin-template.git)
- java微服务后台数据：[micro-service-plus](https://github.com/jzfai/micro-service-plus)

> 开发和使用感受：两个字 真香！！！！！


## 构建步骤

```bash
# 克隆项目
git clone https://github.com/jzfai/vue3-admin-template.git

# 进入项目目录
cd  vue3-admin-template

# pnpm address https://pnpm.io/zh/motivation
# 安装依赖(建议用pnpm)
# 你可以使用 "npm -g i pnpm" 去安装pnpm
pnpm i

# 启动服务
pnpm run dev
```

浏览器访问 http://localhost:5001


## 发布

```bash
# 构建测试环境
pnpm run build-serve

# 构建生产环境
pnpm run build
```

## 其它

```bash
# 预览发布环境效果
pnpm run preview:build-serve

# 预览生产环境
pnpm run preview

# 代码格式检查并自动修复
pnpm run lint
```


