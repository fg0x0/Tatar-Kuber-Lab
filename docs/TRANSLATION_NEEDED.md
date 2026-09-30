# Translation needed — Mongolian

A worklist, not a translation. **Nothing here has been machine-translated**, and
nothing should be.

Generated 2026-09-30 by classifying every tracked `.md` as entirely English,
bilingual (has a `Монгол хэл дээр` half), or mixed.

---

## Low — contributor-facing

| Section | File | Words | Note |
|---|---|---:|---|
| Our Pledge / Our Standards / Enforcement Responsibilities / Scope / Enforcement / Attribution | `CODE_OF_CONDUCT.md` | 313 | **Do not hand-translate.** It is the Contributor Covenant, which has an official Mongolian translation — use that rather than writing a second, divergent wording of a document whose exact phrasing is the point. |

That is the only entirely-English file in this repo.

---

## The real gap here is not a file — it is the README's Mongolian half

`README.md` and `CONTRIBUTING.md` both carry a Mongolian half already, but the
README's halves are **not** symmetric, and that asymmetry is recorded rather
than hidden: `scripts/check-readme-parity.py` holds an `EN_ONLY_SECTIONS`
allowlist naming five sections that exist only in English.

| Section (English only) | Why it was left English |
|---|---|
| Pipeline this repo demonstrates | the diagram under it is language-neutral |
| Full run (real scanners, local — no cluster) | maintainer workflow |
| Live cluster (Kind) | maintainer workflow |
| Notes | scanner version pins, upstream caveats |
| License | licence text is English regardless |

Roughly **950 words** across those five. They are a deliberate choice, not an
oversight — the Mongolian half is a quick start by design. Writing any of them
in Mongolian is welcome; when one is written, **remove its name from
`EN_ONLY_SECTIONS`** or the parity check will keep discounting it and stop
noticing future drift in that section.

## If you translate one thing

Nothing in this repo is urgent. It is a fixture corpus for Tatar-Kuber, read by
maintainers rather than operators — put the time into Tatar-Shield's issue
templates or Tatar-Relay's Burp inject guide first.
