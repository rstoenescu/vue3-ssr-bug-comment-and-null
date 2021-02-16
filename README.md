# Steps

1. yarn
2. yarn dev
3. Check browser console:

```
runtime-core.esm-bundler.js:38 [Vue warn]: Hydration children mismatch in <div>: server rendered element contains fewer child nodes than client vdom.
  at <Home onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< undefined > >
  at <RouterView>
  at <App>
```

# Point of interest

`/src/pages/Home.vue`. The rest of the files don't matter.
