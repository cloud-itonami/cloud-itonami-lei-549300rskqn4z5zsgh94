# cloud-itonami-lei-549300rskqn4z5zsgh94

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by PT. Bank Mandiri (Persero) Tbk..**

This repository archives the publicly published Privacy Policy of **PT. Bank Mandiri (Persero) Tbk.** (ID), with source-url and retrieval-date provenance, per
ADR-2607110300 (`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`).
Read-only reference/archive repository — not a governed Advisor/Governor actor.

- LEI: `549300RSKQN4Z5ZSGH94` (GLEIF entity status ACTIVE, registration ISSUED)
- Source: https://www.bankmandiri.co.id/livin/
- Retrieved: 2026-07-25T05:18:33Z
- SHA-256 of archived text: `74c6c764be65fdaae996835da38347487cf62c329e78716c81630ff9474eb3eb`

Acquired by `scripts/lei-acquire.cljs` as part of the worldwide-broadening
continuation that followed the 2026-07-25 coverage audit, which found the
catalog's real reach was 27 countries with the United States at 55%.

## Cited registry facts

`facts.edn` records what GLEIF publishes about this LEI — the entity record, its
managing LOU, its ISO 20275 legal form, its parent-reporting exceptions, its one
instrument identifier and its four direct children — with `:source/url` and
`:source/retrieved-at` next to every value.

`kbb --backend sci scripts/verify-facts.cljk` re-fetches those sources and compares. It exits
`0` when the live registry still agrees, `1` when a citation is dead or a value
drifted, and `3` when it could not check at all (sources unreachable, `facts.edn`
missing or unreadable) — a run that could not answer must not look like a pass.
`--write` regenerates the file through the same builder the check uses, so it
cannot drift from its own generator.
