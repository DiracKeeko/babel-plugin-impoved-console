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

```
pnpm add @babel/generator@7.21.4 @babel/helper-plugin-utils@7.20.2

pnpm add -D @babel/core@7.21.4 @babel/preset-env@7.21.4 @babel/types@7.21.4 @types/babel__core@7.20.0 @types/babel__generator@7.6.4 @types/babel__helper-plugin-utils@7.10.0 @types/node@18.15.13 tsup@7.2.0
```
