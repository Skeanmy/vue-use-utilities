# useDebounceRef

> Vue3 Offical Document [customRef](https://v3.cn.vuejs.org/api/refs-api.html#customref) demo

## Usage

```html
<input v-model="text" />
```

```js
import { useDebouncedRef } from '@vueblocks/vue-use-core'

export default {
  setup() {
    return {
      text: useDebouncedRef('hello')
    }
  }
}
```

## Typing

```ts
declare const useDebouncedRef: (value: any, delay?: number) => Ref;
```
