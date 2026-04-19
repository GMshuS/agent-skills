# JavaScript前端编码规范

## 1. 基本风格
- 使用2空格缩进
- 字符串使用单引号（'）
- 始终使用分号

## 2. 模块规范
- 使用`const`声明常量
- 前端模块使用ES6 import/export语法
- 避免直接操作DOM，优先使用框架提供的API

## 3. 异步处理
- 优先使用async/await
- 回调函数遵循Error-first约定
- 避免回调地狱（Callback Hell）

## 4. 错误处理
- 使用try/catch处理同步错误
- 异步错误使用`.catch()`或Error-first回调
- 始终处理Promise拒绝

## 5. 性能优化
- 避免阻塞主线程，使用Web Workers处理复杂计算
- 懒加载非关键资源
- 合理使用浏览器缓存

## 6. 安全实践
- 验证所有用户输入，防止XSS攻击
- 避免`eval()`和动态代码执行
- 使用CSP（内容安全策略）增强安全性

## 7. 目录结构
- `src/` 存放源代码
  - `components/` 存放可复用组件
  - `pages/` 存放页面组件
  - `utils/` 存放工具函数
  - `styles/` 存放样式文件
- `public/` 存放静态资源
- `test/` 存放测试代码
- 根目录放置 `package.json`、`.eslintrc.js` 和 `README.md`