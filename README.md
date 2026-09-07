# FacePlugin assets

Shared **README screenshots** for FacePlugin product repositories.

Example pictures (`assets/examples/` in each product repo) are **not** stored here so a normal product clone still includes demo samples.

## Use in a product README

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
```

See [MANIFEST.md](MANIFEST.md) for hashes and which repos consume each file. Do not merge files that share a name across families — Android `home.png` is not iOS `home.png`.

## License

Screenshots are FacePlugin product documentation. All rights reserved.
