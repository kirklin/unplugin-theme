# unplugin-theme

[![NPM version](https://img.shields.io/npm/v/unplugin-theme?color=a1b858&label=)](https://www.npmjs.com/package/unplugin-theme)

## Install

```bash
npm i unplugin-theme
```

<details>
<summary>Vite</summary><br>

```ts
// vite.config.ts
import Starter from "unplugin-theme/vite";

export default defineConfig({
  plugins: [
    Starter({ /* options */ }),
  ],
});
```

Example: [`playground/`](./playground/)

<br></details>

<details>
<summary>Rollup</summary><br>

```ts
// rollup.config.js
import Starter from "unplugin-theme/rollup";

export default {
  plugins: [
    Starter({ /* options */ }),
  ],
};
```

<br></details>


<details>
<summary>Webpack</summary><br>

```ts
// webpack.config.js
module.exports = {
  /* ... */
  plugins: [
    require("unplugin-theme/webpack")({ /* options */ })
  ]
};
```

<br></details>

<details>
<summary>Nuxt</summary><br>

```ts
// nuxt.config.js
export default {
  buildModules: [
    ["unplugin-theme/nuxt", { /* options */ }],
  ],
};
```

> This module works for both Nuxt 2 and [Nuxt Vite](https://github.com/nuxt/vite)

<br></details>

<details>
<summary>Vue CLI</summary><br>

```ts
// vue.config.js
module.exports = {
  configureWebpack: {
    plugins: [
      require("unplugin-theme/webpack")({ /* options */ }),
    ],
  },
};
```

<br></details>

<details>
<summary>esbuild</summary><br>

```ts
// esbuild.config.js
import { build } from "esbuild";
import Starter from "unplugin-theme/esbuild";

build({
  plugins: [Starter()],
});
```

<br></details>


## License

[MIT](./LICENSE) License © 2022 [Kirk Lin](https://github.com/kirklin)
