## 安装

```ts
// npm
npm i babel-plugin-improved-console
// yarn
yarn add babel-plugin-improved-console
// pnpm
pnpm i babel-plugin-improved-console
```

## 使用

```ts
// babel.config.js

module.exports = {
  plugins: [
    // ...plugins
    [
      'improved-console',
      // tip 默认是 ↓======↓
      {
        tip: '↓======↓',
      },
    ],
  ],
}
```

