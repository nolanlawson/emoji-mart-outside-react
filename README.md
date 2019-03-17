emoji-mart-outside-react
=====

Demo of how to use [emoji-mart](https://github.com/missive/emoji-mart) without React, as a custom element. This uses [remount](https://github.com/rstacruz/remount) and [preact](https://github.com/developit/preact). The total JS bundle size is **68K**.

In the end, you just have a custom element:

```html
<emoji-picker></emoji-picker>
```

Usage:

    npm install
    npm run build
    npm start

Then see the server at http://localhost:8080.
