# Saffron

**An applied-intelligence and software engineering company, founded in 2024 in Minneapolis, Minnesota, by Aladdin Hamed.**

Home: [saffronsystems.io](https://saffronsystems.io).

> Every autonomous action leaves a verifiable receipt.

## The Saffron family

The canonical list, with status, lives at [saffronsystems.io/press#family](https://saffronsystems.io/press#family). This table mirrors it.

| Property | What it is | Relationship | Status |
|---|---|---|---|
| [saffronsystems.io](https://saffronsystems.io) | Saffron's home: the company, its founder and its divisions | Company | Live |
| [saffronsystems.io/software](https://saffronsystems.io/software) | Saffron Systems: software and application engineering | Division | Live |
| [saffrondesigns.io](https://saffrondesigns.io) | Saffron Designs: websites engineered to be measured, plus search and answer-engine visibility | Division | Live |
| [saffronautomations.com](https://saffronautomations.com) | Saffron Automations: agentic systems that run operational work | Division | Live |
| [saffronstudios.io](https://saffronstudios.io) | Saffron Studios, the newest division | Division | In development |
| [saffronbrowser.com](https://saffronbrowser.com) | Saffron Browser: hosted headless-browser and web-data API ([docs](https://saffronbrowser.dev)) | Product | Live |

saffrongroup.ai was Saffron's former home and now redirects to saffronsystems.io.

## Public repositories

| Repository | What it is | What it does not prove |
|---|---|---|
| [saffron-web-vitals-ledger](https://github.com/saffron-group/saffron-web-vitals-ledger) | Lighthouse measurements of studio websites: one configuration, four runs, the worst run published, raw data included | Performance of any client system |
| [saffron-quality-gate](https://github.com/saffron-group/saffron-quality-gate) | Saffron's engineering standard as a runnable command-line check | That a codebase is correct; it flags known failure patterns |
| [saffron-mobile-enhancer](https://github.com/saffron-group/saffron-mobile-enhancer) | A drop-in script that adds mobile UX features to a website | Results on any specific site |

How Saffron proves what it ships: [saffronsystems.io/software/release-proof](https://saffronsystems.io/software/release-proof), with a signed attestation you can verify yourself.

## Operating doctrine

- Production deploys: explicit human go. No exceptions.
- Branch protection on production repos: no force-push, no deletions.
- Git is the only deploy lane for production-tracked projects.
- No fabricated numbers. Ever.
- Copy rule: never "AI" in client-facing copy; say "applied intelligence" or "agentic".

## Structure

- `core`: production repos, admin
- `agents`: empire agents, push (PR-gated by protection)
- `clients`: client work, isolated
- `r-and-d`: experiments and dormant work, read

Nothing can match the human touch.
