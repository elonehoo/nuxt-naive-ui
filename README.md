<p align='center'>
<img src='./public' alt="nuxt-naive-ui - Zero-config Nuxt Framework for Naive-ui"><br>
Zero-config Nuxt Framework for Naive-ui
</p>

<p align='center'>
<a href='https://www.npmjs.com/package/nuxt-naive-ui' target="__blank">
<img src='https://img.shields.io/npm/v/nuxt-naive-ui?color=00DC82&label=' alt="NPM version">
</a>

<br>

## Features
- Zero-config required
- Auto-import component and imports
- unocss CSS support

## Setup

**npm**

```bash
npm install nuxt-naive-ui
```

**yarn**

```bash
yarn add nuxt-naive-ui
```

**pnpm**

```bash
pnpm install nuxt-naive-ui
```

## Nuxt Config

```ts
export default defineNuxtConfig({
  modules: [
    '@huntersofbook/naive-ui-nuxt'
  ],
})
```

## Composables

```vue
<script setup lang="ts">
import { darkTheme } from 'naive-ui'
</script>

<template>
  <NConfigProvider :theme="darkTheme">
    <NGlobalStyle />
    <div>
      Nuxt module playground!
      <NButton>Default</NButton>
    </div>
  </NConfigProvider>
</template>
```

## License

## License

[MIT](./LICENSE) License © 2023-Present [Elone Hoo](https://github.com/elonehoo)
