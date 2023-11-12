## compiler 编译时
- compiler-core 核心
- compiler-dom 浏览器编译时
- compiler-sfc vue文件
- compiler-ssr 服务端

## reactivity 响应式
- reactivity

## runtimer 运行时
- runtime-core 核心
- runtime-dom 浏览器运行时

## shared 共享工具

## vue
src/index.ts 入口

## 打包配置 sourceMap
`"build": "node scripts/build.js -s"` 添加 -s
其原理在 `scripts/build.js` 文件下 设置 `sourceMap`，通过 `const args = require('minimist')(process.argv.slice(2))` 获取到配置数据
使用了 `minimist` 包，将 node 命令解析成 对象数据