# Oriz Forge — Dev tools

> A developer toolbox forge — a growing collection of small, fast utilities for building, smithing, and shipping code.

**Live at**: https://dev.oriz.in · **Status**: scaffold

## What this is

A browser-based developer toolkit. Encoders, decoders, formatters, generators, and converters — every tool runs locally so your snippets and secrets stay on your machine.

## Per-feature inventory

| Feature | Status |
|---|---|
| JSON formatter / validator | 📜 planned |
| Base64 encode / decode | 📜 planned |
| URL encode / decode | 📜 planned |
| JWT decoder | 📜 planned |
| UUID generator | 📜 planned |
| Hash generator (MD5 / SHA) | 📜 planned |
| Regex tester | 📜 planned |
| Cron expression builder | 📜 planned |
| Diff viewer | 📜 planned |
| Colour picker / converter | 📜 planned |

## App-specific env vars

None beyond the family-wide set at `templates/.env.example`.

## Local dev

```bash
# from the workspace root (c:/D/oriz)
pnpm -F @chirag127/oriz-dev-tools dev
```

## Knowledge

See [`./knowledge/`](./knowledge/) for app-specific decisions, runbooks, and services. Family rules / decisions / architecture live at the master repo's [`knowledge/`](../../../../knowledge/).

## License

Source-available, all rights reserved. See master [`LICENSE`](../../../../LICENSE) — same terms across the family.
