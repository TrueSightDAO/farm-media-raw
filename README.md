# farm-media-raw

**Public** DAO media archive for raw farm media (HEIC/JPG photos) keyed by farm id — Content-API only, never cloned/branch-edited.

Visibility policy: **public by default** (per Governor Gary Teh) — raw GPS-tagged originals are provenance evidence; transparency is the point.

## Structure
```
<farm-id>/photos/          # raw HEIC/JPG originals (GPS-tagged)
<farm-id>/videos/          # (reserved — videos go to YouTube public, see FARM_MEDIA_PIPELINE.md)
```

## Farms
| Farm | Folder |
|---|---|
| Rancho Maranta | `rancho-maranta/` |
| La do Sitio (Paulo) | `la-do-sitio/` |
| Cleide | `cleide/` |
| Santa Anna Fazenda (Ana Lucia Araujo de Sousa) | `santa-anna-fazenda-para/` |

Manifest/index lives in `agentic_ai_context/FARM_MEDIA_MANIFESTS/<farm-id>.json` (sha256, GPS, duration, objects, yt_id).
