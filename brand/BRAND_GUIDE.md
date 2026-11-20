# IDEs of Merge — Brand Kit

## Color System (OKLCH + Machado CVD Verified)

| Role | Hex | OKLCH L | Contrast vs `#000` | Contrast vs `#FFF` | Meaning |
| --- | --- | --- | --- | --- | --- |
| **Dark IDE Pane** | `#334366` | `0.386` | `2.14:1` | `9.83:1` | Dark-mode editor pane & sidebar |
| **Diff Deletion (`-`)** | `#CC2A2E` | `0.552` | `3.94:1` | `5.33:1` | Git deletions / Ides crimson |
| **Merged / Extension** | `#9261F5` | `0.619` | `5.25:1` | `4.00:1` | GitHub Merged PR / extension module |
| **Diff Addition (`+`)** | `#0ECA80` | `0.740` | `9.78:1` | `2.15:1` | Git additions |
| **Light IDE Pane** | `#C2D0E3` | `0.853` | `13.43:1` | `1.56:1` | Light-mode editor pane |

- **Deuteranopia red/green separation:** `ΔE_OK = 0.179` (`Protanopia = 0.338`, `Grayscale ΔL = 0.188`)
- **Avatar crop safe zone:** Optical center `(256, 256)` with `r ≤ 222px` (`13.3%` circular safe margin on `512×512`)
- **Zero `<mask>` SVG:** Pure pre-clipped boolean `<path>`s for universal compatibility in GitHub, Figma, Illustrator, browsers, and Marketplace renderers.

## Files Included

- `idesofmerge-mark.svg` — Primary transparent color mark (`1.0 KB`, zero `<mask>`)
- `idesofmerge-mark-1024.png` / `512.png` / `128.png` / `32.png` — Transparent PNGs (use `512` or `1024` for GitHub Org avatar & VS Code Marketplace publisher icon; `32` for favicon)
- `idesofmerge-mono.svg` — Single-color `fill="currentColor"` stamp (`1.1 KB`)
- `idesofmerge-mono-white-1024.png` & `idesofmerge-mono-dark-1024.png` — Transparent 1-color PNG stamps
- `idesofmerge-lockup-dark.svg` / `.png` & `idesofmerge-lockup-light.svg` / `.png` — Horizontal `IDEs of Merge` wordmark lockups
- `idesofmerge-social-preview.svg` & `.png` — `1280×640` GitHub Open Graph social preview banner

## GitHub Organization Profile README Snippet (`.github/profile/README.md`)

```html
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./idesofmerge-lockup-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./idesofmerge-lockup-light.svg">
    <img alt="IDEs of Merge" src="./idesofmerge-lockup-dark.svg" width="520">
  </picture>
</p>
```
