# consimeet-inventory-img

Public files for the ConSiMeet Investor Portal Blogger builds. The source stays in the private repo `dxkon123/consimeet-ai-conference`; this repo only holds what visitors' browsers must download.

| Path | Used by |
|---|---|
| `v5/*.webp` (17 images) | `ConSiMeet_V5_Ultimate_Investor_Portal_Blogger.html` and the Lite build |
| `v5/portal.css`, `v5/portal.js` | `ConSiMeet_V5_Ultimate_Investor_Portal_Blogger_Lite.html` only |
| `v5-1/` (17 images, `portal.css`, `portal.js`) | V5.1 Blogger builds (`ConSiMeet_V5_1_Investor_Portal_Blogger.html` and `_Blogger_Lite.html`) |

Served through jsDelivr: `https://cdn.jsdelivr.net/gh/dxkon123/consimeet-inventory-img@main/v5/<file>`.

jsDelivr caches `@main` for up to 12 hours. For a new portal version, add a new folder (for example `v6/`) instead of overwriting `v5/`, or purge the file at `https://purge.jsdelivr.net/gh/dxkon123/consimeet-inventory-img@main/v5/<file>`.

---

# consimeet-inventory-img