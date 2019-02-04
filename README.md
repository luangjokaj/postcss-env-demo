# PostCSS-env Demo

This repository is a simple demonstration of Postcss-preset-env.
PostCSS Preset Env lets you convert modern CSS into something most browsers can understand, determining the polyfills you need based on your targeted browsers or runtime environments, using [cssdb](https://cssdb.org/).

Try it out:
---
**Install dependencies:**

```
$ npm install
```

**Run development:**

```
$ npm run dev
```

- ☝ This this will start watching for any changes in your main style entry point:

```
src/assets/css/styles.css
```
- 👇 It will also output the compiled styles in:
```
dist/assets/css/styles.css
```

**Run production:**

```
$ npm run prod
```

- ☝ This command does exactely the same as `dev`. The difference is that it minifies the CSS output and it does not watch for any new changes.

---

The CSS output will be always saved in:

```
dist/assets/css/styles.css
```
