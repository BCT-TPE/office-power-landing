# Office Power Landing Page

This directory contains the standalone Office Power landing page published at:

https://ginny-chang.github.io/office-power/0911.html

The source was copied from deployment commit
`646dda2cafdff3e0ab5b3b5dc8a735d5eb049783` so this package matches the
referenced production version.

## Develop

```bash
npm ci
npm run dev
```

## Build

```bash
npm run build
```

Set `BASE_PATH` when deploying below a URL prefix:

```bash
BASE_PATH=/office-power/ npm run build
```
