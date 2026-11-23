# Palianka — multidisciplinary design agency

Studio site for Palianka: branding, websites, product design, exhibition, merch and motion, with cases for iGaming and other clients.

Two tabs at the top:

- **iGaming cases** (`#igaming`, default): the iGaming projects, Motion Graphics and Banners Production.
- **Other cases** (`#other`): work for other kinds of products.

A case slug in the address opens that case, e.g. `#onlyplay` or `#metarun`.

Static site, no build step. `index.html` at the root, images in `img/` and `banners/`, videos and their posters in `video/`.

Banners Production (iGaming tab) is seven rows of single banners that loop endlessly: drag, swipe, sideways trackpad scroll or arrow keys. The banners are in `banners/s/` as `<brand>-<kind>-<nn>-<width>.webp`, exported from the Figma files Websites by Palianka, IGaming Case Studies and Palianka Banners. Card covers are `img/cover-<slug>-1280.webp` and `-2400.webp`, exported from the "Обложки clean" page of the IGaming Case Studies Figma file.

The Fotando case (`#fotando`) follows the Figma file "Fotando Behance Case" module by module instead of the usual case template: the visual modules are `img/fo-*` (exported at 2400 px wide, plus 1280), and the text blocks, credits and links are HTML set in Albert Sans, sized to the 1675 px Figma frame.

Run locally:

```
npx serve .
```
