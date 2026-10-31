# Gas Kim Hồng – brand assets

Public copies of the Gas Kim Hồng logo, banners and real product photos, used as image references by design tools.

- `brand/` – logo and the approved product backdrop
- `banners/` – home banners (2:1)
- `products/` – real cylinder photos: `*-cutout.png` (transparent) and `*-on-backdrop.jpg` (on the approved backdrop)

## Zalo Mini App banners (CDN, tag `v1`)

`banners/v1/` holds the sharp home banners the Mini App loads through jsDelivr:
`https://cdn.jsdelivr.net/gh/buiphucthinh/gas-kim-hong-brand-assets@v1/banners/v1/<group>/<file>.webp`

`banners/v1/manifest.json` lists every banner, its group (`home` = the 65 rotating first-slide banners, `official` = the 3 fixed slides), size and SHA-256.
Exported from the owner-approved originals: 2:1 at 1200×600, square at 1080×1080, WebP q82.
Do not overwrite files under a published tag; add `v2`. The Mini App keeps smaller bundled copies as a fallback if the CDN cannot be reached.
