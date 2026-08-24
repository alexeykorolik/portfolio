# Portfolio visual assets

The current preview blocks are intentional placeholders. They keep the editorial layout stable without inventing screenshots or fake product interfaces.

## Required captures

Add these real assets when available:

```text
assets/scoutboard-home-desktop.webp
assets/scoutboard-catalog-desktop.webp
assets/scoutboard-mobile.webp
assets/parastore-home-desktop.webp
assets/chessmeet-app-mobile.webp
```

## Where they go

- `scoutboard-home-desktop.webp` replaces the hero preview in `case-study.html`.
- `scoutboard-catalog-desktop.webp` replaces the catalog preview in the case gallery.
- `scoutboard-mobile.webp` replaces the mobile preview in the case gallery.
- `parastore-home-desktop.webp` replaces the Para Store preview on Home and Work.
- `chessmeet-app-mobile.webp` replaces the ChessMeet preview on Work.

## Capture guidance

- Use real production or local interfaces only.
- Export WebP or compressed PNG at 2x display size.
- Crop out browser chrome unless it is useful context.
- Keep desktop captures around 1600px wide and mobile captures around 800px wide.
- Do not add client data, private admin information or credentials to screenshots.

The CSS preview containers are already responsive, so adding the assets should only require replacing the placeholder elements with `<img>` elements and meaningful `alt` text.
