# Hiphople Infographics Hosting

Target repository name:

```text
Hwajila/Rhythmer-infographics
```

This package is meant to host the original PNG files outside HIPHOPLE so the post can reference them by URL instead of uploading them through HIPHOPLE's image system.

## Files

- `images/` contains the original high-resolution PNGs.
- `index.html` is a simple gallery page for GitHub Pages or local preview.
- `hiphople-snippet.html` contains the HTML image tags to paste into HIPHOPLE source mode after the repo is public.

## Final image URL pattern

Use jsDelivr over the public GitHub repo:

```html
<img src="https://cdn.jsdelivr.net/gh/Hwajila/Rhythmer-infographics@main/images/reviewer_total_votes_ko.png" style="width:100%;max-width:100%;height:auto;" alt="">
```

If you replace an image later and the CDN cache does not update immediately, append a version query, for example `?v=2`.
