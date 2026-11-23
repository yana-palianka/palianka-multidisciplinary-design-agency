# Palianka — multidisciplinary design agency

Studio site for Palianka: branding, websites, product design, exhibition, merch and motion, with cases for iGaming and other clients.

Two tabs at the top:

- **iGaming cases** (`#igaming`, default): the iGaming projects, Motion Graphics and Banners Production.
- **Other cases** (`#other`): work for other kinds of products.

A case slug in the address opens that case, e.g. `#onlyplay` or `#metarun`.

Static site, no build step. `index.html` at the root, images in `img/` and `banners/`, videos and their posters in `video/`.

Banners Production (iGaming tab) is seven rows of single banners that loop endlessly: drag, swipe, sideways trackpad scroll or arrow keys. The banners are in `banners/s/` as `<brand>-<kind>-<nn>-<width>.webp`, exported from the Figma files Websites by Palianka, IGaming Case Studies and Palianka Banners. Card covers are `img/cover-<slug>-1280.webp` and `-2400.webp`, exported from the "Обложки clean" page of the IGaming Case Studies Figma file.

Run locally:

```
npx serve .
```
