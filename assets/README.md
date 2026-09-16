# Assets needed

Drop these files into this folder before deploying:

| File | Purpose | Recommended size | Notes |
|---|---|---|---|
| `avatar.jpg` | Circular profile photo shown at the top of the page | 512×512px (square, 1:1) | Center the face; the circular crop mask will cut corners. JPG or PNG, <300KB. |
| `og-image.jpg` | Social share preview (link previews on WhatsApp, Instagram, Facebook, Twitter/X) | 1200×630px | Should look good even when cropped to a square by some apps. Include her name/logo, not just a photo, since some platforms crop aggressively. |
| `favicon.png` | Browser tab icon | 512×512px (will be scaled down) | Simple mark works best at small sizes — e.g. just the avatar or a monogram. |

## Also remember to

- Replace `PLACEHOLDER_INSTAGRAM_HANDLE` in `index.html` (two places: the link button href and the `<link rel="me">` tag) with the real Instagram handle.
