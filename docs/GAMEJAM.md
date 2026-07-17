# GameJam / Talos hooks

This repository is a LukeLit **GitHub template** used by Metal Games GameJam git shepherd (`stack: unity`).

| Field | Value |
|-------|--------|
| Stack key | `unity` |
| Template repo | LukeLit/gamejam-starter-unity |
| Upstream | [Khan-amil/GameJam-StarterKit](https://github.com/Khan-amil/GameJam-StarterKit) (MIT) — see `UPSTREAM.md` |

## Provision

```http
POST /repos/LukeLit/gamejam-starter-unity/generate
```

After create, the site **overwrites this file** with filled bind fields from the submission SSOT and bootstraps `docs/wiki/`.

Player Settings (Company Name / Product Name) are **not** auto-patched in v2 — copy from the store table written into this file after provision.

Hosted Unity CI on GitHub-hosted runners is out of scope; use local/editor smoke before publish.

See: LukeLit/metalgames-site → `docs/GAMEJAM-GIT-TEMPLATES.md`.

## Secrets

Do not put secrets here. Keep upstream LICENSE notices intact.
