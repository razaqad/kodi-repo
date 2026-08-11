# Kodi Repository

Personal Kodi repository hosting **POV SIMKL** — a fork of POV that uses
[SIMKL](https://simkl.com) for watched-status tracking instead of Trakt.

## Install

1. Kodi → Settings → File manager → **Add source**, enter exactly:
   ```
   https://razaqad.github.io/kodi-repo/
   ```
   Name it `povsimkl`.
2. Settings → Add-ons → **Install from zip file** → `povsimkl` → `zips` →
   `repository.povsimkl` → `repository.povsimkl-1.0.1.zip`
3. **Install from repository** → POV SIMKL Repository → Video add-ons → **POV SIMKL**

Updates then arrive through the repository.

> Use the GitHub Pages URL above, **not** `raw.githubusercontent.com`. Raw serves
> individual files but never directory listings, so Kodi cannot browse it and
> adding it as a source fails.

## Contents

| Add-on | Version |
|---|---|
| `plugin.video.pov.simkl` | 1.0.0 |
| `repository.povsimkl` | 1.0.1 |

## Credits

POV is by **kodifitzwell**. This is an unofficial fork replacing the Trakt
integration with SIMKL. Licensed GPL-3.0, as upstream.
