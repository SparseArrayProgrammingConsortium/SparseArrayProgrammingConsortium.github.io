# SparseArrayProgrammingConsortium.github.io

Build with:

```sh
bundle exec jekyll serve
```

GitHub Actions exports `assets/SAPCLogo.svg` from `SAPCLogo.drawio` before the Jekyll build. To regenerate locally:

```sh
drawio --export --format svg --transparent --theme light --embed-svg-fonts false --output assets/SAPCLogo.svg SAPCLogo.drawio
```
