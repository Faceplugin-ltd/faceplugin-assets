# FacePlugin assets

Shared **README screenshots** and **brand** files for FacePlugin product repositories.

Example pictures (`assets/examples/` in each product repo) are **not** stored here so a normal product clone still includes demo samples.

## Brand

```html
<img alt="FacePlugin" src="https://raw.githubusercontent.com/Faceplugin-ltd/faceplugin-assets/main/brand/favicon.png" width="200"/>
```

| File | Use |
|------|-----|
| [`brand/favicon.png`](brand/favicon.png) | Square FP mark |
| [`brand/logo.png`](brand/logo.png) | Wordmark (transparent) |
| [`brand/favicon.ico`](brand/favicon.ico) | Browser tab icon |
| [`brand/apple-touch-icon.png`](brand/apple-touch-icon.png) | Apple touch icon |

## Use screenshots in a product README

```html
<img src="https://raw.githubusercontent.com/Faceplugin-ltd/faceplugin-assets/main/screenshots/face-recognition/android/home.png" alt="Home" width="240"/>
```

Layout:

```
screenshots/
  document-reader/{desktop,docker,windows,mobile}/
  face-recognition/{desktop,windows,android,ios,flutter}/
  face-liveness/{desktop,windows,mobile}/
  id-document-liveness/desktop/
brand/
  favicon.png
  logo.png
  favicon.ico
  apple-touch-icon.png
```

See [MANIFEST.md](MANIFEST.md) for hashes and which repos consume each file. Do not merge files that share a name across families — Android `home.png` is not iOS `home.png`.

## License

Screenshots and brand assets are FacePlugin product documentation. All rights reserved.
