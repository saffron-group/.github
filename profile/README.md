<h1 align="center">Saffron Group</h1>

<p align="center">
  <em>An engineering conglomerate.<br>
  Custom software, industrial operations, web systems, and the automation layer above them.</em>
</p>

<p align="center">
  <a href="https://saffrongroup.ai">saffrongroup.ai</a> ·
  <a href="https://saffronautomations.com">Saffron Automations</a> ·
  <a href="https://saffrondesigns.io">Saffron Designs</a>
</p>

<p align="center">
  Founded 2024 · Minneapolis, Minnesota · working across Minneapolis and New York
</p>

---

## What we engineer

**Engineering comes first.** Custom software with no off-the-shelf equivalent —
native and web applications, platforms, custom CRM builds and clean integration
into systems never designed to be integrated with, booking and scheduling built
around the operation rather than the reverse, and industrial operations down to
the protocol layer with OPC-UA and MQTT.

**Web sits on top of that.** Sites engineered past the point most studios stop,
and measured on the live URL rather than described.

**Advanced automation is the layer above both.** Reconciliation, categorisation,
month-end close, invoice chasing, revenue recovery, monitoring, audits and
reporting — each action written to an immutable, signed evidence log.

---

## We publish our own numbers, including the ones we lose

Most performance claims are a best run with no date and no method attached. That
is not a claim, it is a screenshot.

**[The Web Vitals Ledger](https://github.com/saffron-group/saffron-web-vitals-ledger)** —
five studio websites, four of them award-winning, one of them ours. Four
consecutive Lighthouse runs each. **The worst run is the published figure. No run
is discarded.**

Measured 1 September 2026, mobile profile, simulated Slow 4G, 4× CPU:

| Site | Performance | LCP |
|---|---:|---:|
| aristidebenoist.com | 100 | 1.06 s |
| **saffrondesigns.io** — ours | **98** | **2.34 s** |
| unseen.co | 88 | 3.36 s |
| obys.agency | 60 | 6.71 s |
| basement.studio | 51 | 7.51 s |

One of them beats us and is left at the top of the table.

The repository's `experiments` array records changes we tried, measured, and
either kept or threw away — including a performance fix shipped and **reverted
the same hour** because the number did not move, and two hypotheses that
sounded obviously right and were worth one and two milliseconds each.

Reproduce any row:

```bash
npm i -g lighthouse
git clone https://github.com/saffron-group/saffron-web-vitals-ledger
cd saffron-web-vitals-ledger && ./measure.sh https://saffrondesigns.io/
```

---

## How to check the rest of it

We would rather be checked than believed. Four artefacts, all published rather
than furnished on request:

| | |
|---|---|
| **[The public ledger](https://saffrondesigns.io/ledger)** | Every performance score we measure, worst run printed, with the method and the date. |
| **[The governance framework](https://saffrongroup.ai/#governance)** | Receipt-backed accountability, human-in-the-loop guardrails, least-privilege access — the escalation model written down rather than described. |
| **[The sub-processor register](https://saffronautomations.com/sub-processors)** | Every third party that could touch a client's data, named, with what it is used for. |
| **[Field notes](https://saffronautomations.com/blog)** | Including [the four questions to audit any automation vendor](https://saffronautomations.com/blog/audit-an-automation-vendor) — published so they can be used on us. |

---

## Why we are called Saffron

Saffron is the most expensive substance on earth by weight, and not because the
crocus is rare. Each flower carries three crimson threads, and every one of them
has to be drawn out by a human hand in a short autumn window. Machines have been
aimed at that problem for a century and fail on the same thing every time: the
judgement of the moment.

So the name is a constraint we run the company under, not a flourish. We build
systems that run unattended, and the risk in that business is not technical — it
is the drift toward automating the part that was actually doing the work.

> **Automate everything that dulls the hand. Never the hand itself.**

[The Canon sets it out in full →](https://saffrongroup.ai/canon)

---

<p align="center">
  <sub>
    <a href="https://saffrongroup.ai/about">About</a> ·
    <a href="https://www.linkedin.com/company/saffron-ai-group">LinkedIn</a> ·
    <a href="mailto:hello@saffrongroup.ai">hello@saffrongroup.ai</a>
  </sub>
</p>
