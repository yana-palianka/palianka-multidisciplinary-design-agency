# Palianka — multidisciplinary design agency

Studio site for Palianka: branding, websites, product design, exhibition, merch and motion, with cases for iGaming and other clients.

Two tabs at the top:

- **iGaming cases** (`#igaming`, default): the iGaming projects, Motion Graphics and Banners Production.
- **Other cases** (`#other`): work for other kinds of products.

A case slug in the address opens that case, e.g. `#onlyplay` or `#metarun`.

Static site, no build step. `index.html` at the root, images in `img/` and `banners/`, videos and their posters in `video/`. Card covers are `img/cover-<slug>-1280.webp` and `-2400.webp`, exported from the "Обложки clean" page of the IGaming Case Studies Figma file.

Run locally:

```
npx serve .
```
