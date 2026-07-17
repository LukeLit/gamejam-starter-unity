# GameJam / Talos hooks (stub)

This repository is a LukeLit **GitHub template** used by Metal Games GameJam git shepherd.

| Field | Value |
|-------|--------|
| Stack key | $stack |
| Template repo | LukeLit/gamejam-starter-unity |
| Upstream | [Khan-amil/GameJam-StarterKit](https://github.com/Khan-amil/GameJam-StarterKit) |

## Provision

Talos / site calls:

```http
POST /repos/LukeLit/gamejam-starter-unity/generate
```

Site defaults / env map: see LukeLit/metalgames-site → docs/GAMEJAM-GIT-TEMPLATES.md.

## Placeholder hooks (v1 stub)

Fill these in a later pass (tracked on metalgames-site issues linked from #89):

- gamejam.slug — submission slug once bound
- gamejam.gitRepoUrl — generated repo URL
- gamejam.store — Steam / itch metadata fields
- gamejam.wiki — SSOT pages under docs/wiki/
- CI / export pipeline wired to GameJam publish

Do not put secrets here.
