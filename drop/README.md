# Drop folder — full-size screenshots

Put original screenshots here. Chat compresses images. Files in this folder stay full resolution.

1. Copy screenshots into `drop/`.
2. Say **process drop**.
3. They get renamed `YYYY-MM-DD_short-description.ext`, moved into `_assets/`, and logged.

| If the screenshot is… | It goes to |
|------------------------|------------|
| Google Business Profile | `_assets/gbp/` |
| Google reviews | `_assets/reviews/` |
| Google Search Console | `_assets/gsc/` |
| Google Analytics | `_assets/ga4/` |
| Vercel Analytics or Speed Insights | `_assets/vercel/` |
| Prior-site Squarespace (legacy only) | `_assets/squarespace/` |
| Vendor dashboards | `_assets/vendors/` |
| Anything else | `_assets/misc/` |

The live site is not on Squarespace. Prior-site Squarespace shots are legacy context only. Prefer quality WebP when filing (`cwebp -q 90`).
