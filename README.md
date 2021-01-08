# Websocket automatic code reloading

Use this library to automatically reload the page when you restart your development web server (on save).

Made to work with the [Waveorb Web Development Framework.](https://waveorb.com)

### Usage

Copy the `dev.js` file to `app/assets/js` and include it with:

```js
${process.env.NODE_ENV === 'development' ? '<script src="/js/dev.js"></script>' : ''}
```

MIT Licensed. Enjoy!
