```
cd nuxt-bridge
yarn
yarn build
NUXT_APP_CDN_URL=https://my.cdn yarn start
```

Result:

```html
<img src="/_nuxt/img/logo.8ee14a5.png" />
```

---

```
cd nuxt3
yarn
yarn build
NUXT_APP_CDN_URL=https://my.cdn yarn preview
```

Result:

```html
<img src="https://my.cdn/_nuxt/logo.bd6be0ef.png" />
```
