# SparseArrayProgrammingConsortium.github.io

Build with:

```sh
bundle exec jekyll serve
```

GitHub Actions exports `assets/SAPCLogo.png` from `SAPCLogo.drawio` before the Jekyll build. To regenerate locally:

```sh
drawio --export --format png --transparent --theme light --scale 4 --output assets/SAPCLogo.png SAPCLogo.drawio
```
