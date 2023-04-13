# Showcase of an issue between [@unpic/react/next](https://github.com/ascorbic/unpic-img) and [pnpm](https://pnpm.io/)

## Instructions
```
pnpm install
pnpm dev
```

and you should see the error when loading `localhost:3000` :

```
Error: Cannot find module '(...)/node_modules/.pnpm/@unpic+react@0.0.20_ld2jel3hspngo3u5lti2kgl2sq/node_modules/next/dist/shared/lib/image-config' imported from (...)/node_modules/.pnpm/@unpic+react@0.0.20_ld2jel3hspngo3u5lti2kgl2sq/node_modules/@unpic/react/dist/next.mjs
Did you mean to import next@13.2.4_biqbaboplfbrettd7655fr4n2y/node_modules/next/dist/shared/lib/image-config.js?
```