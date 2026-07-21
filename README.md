# DailyTracker Assets

Public image assets for the DailyTracker iOS app, served over
[jsDelivr](https://www.jsdelivr.com/) so bulk art never has to ship inside the app bundle.

**This repository contains artwork only** — no source code, no personal data, no backups.

## Usage

Images are referenced from the app via a pinned tag:

```
https://cdn.jsdelivr.net/gh/taimoormirza1999/DailyTracker-assets@v1/images/<name>.png
```

Pin a tag rather than `@main` — jsDelivr caches aggressively, so a tag is what makes
updates predictable. After adding or changing images, publish a new tag (`v2`, `v3`, …)
and bump `RemoteAssets.version` in the app.

## Layout

```
images/     PNG artwork, transparent background
```
