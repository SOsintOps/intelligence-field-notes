# Version History

Changelog of the Intelligence Field Notes.

---

## 0.1.3 — 2026

- **Fixed:** "How to Write an Intelligence Product in the BLUF Format" is attributed as what it is, an anonymous teaching exercise built on an assessment by the US DOJ National Drug Intelligence Center, not a DOJ document ([Report Writing](report-writing.md#further-reading), [Reading List](reading-list.md)).

---

## 0.1.2 — 2026

- **New:** [Source Evaluation](source-evaluation.md#one-exception-machine-graded-cti-feeds) and the [FAQ](faq.md#does-every-sosintops-tool-use-the-4-x-4-system) explain why Elementary CTI keeps the 6 x 6 system for machine-graded feed items, and how to convert its grades when an item moves into a case report.
- **New:** [Analytic Techniques](analytic-techniques.md#techniques-as-ai-procedures) has a section on running structured techniques as AI procedures, with Il Conclave as the example; the premortem is credited to Gary Klein with a link to his article.
- **Docs:** [Related Projects](related-projects.md) adds Claudii Exploratores, Il Conclave, 13proof and Project Anima Simulacrum.

---

## 0.1.1 — 2026

- **Docs:** Every text is linked at its first mention in a page, not only in *Further Reading*: ICD 203, the UNODC manual and the Berkeley Protocol in the README, the UNODC manual in [Source Evaluation](source-evaluation.md), Heuer in [Analytic Techniques](analytic-techniques.md) and in the [FAQ](faq.md).
- **Changed:** `tools/targets.json` syncs Quaesitor in its development repository only; the public one receives the copies through its release script.

---

## 0.1.0 — 2026

- **New:** First release. The method pages that the SOsintOps tools carried in their own guidelines, merged, corrected and extended into one set: [Analytic Standards](analytic-standards.md) (intelligence cycle with feedback, ICD 203 standards checked against the directive as amended), [OSINT Methodology](osint-methodology.md) (OSINT cycle, 5W1H, collection discipline, OPSEC, legal limits), [Analytic Techniques](analytic-techniques.md) (biases, key assumptions check, ACH in Heuer's eight steps, contrarian and imaginative techniques, deception), [Estimative Language](estimative-language.md) (one ICD 203 row, confidence kept apart from likelihood), [Source Evaluation](source-evaluation.md) (UNODC 4 x 4, who the source is in OSINT, conversion from 6 x 6).
- **New:** [Report Writing](report-writing.md): BLUF, structure, facts versus judgements, sourcing, prose rules from the CIA style manual, handling, a release checklist. No SOsintOps repository had a report-writing guide before.
- **New:** [Reading List](reading-list.md) with a link for every text, absorbing the awesome-intelligence-writing list by Ygor Maximo (MIT), every link checked and the dead ones replaced or dropped.
- **New:** [Related Projects](related-projects.md), [FAQ](faq.md).
- **New:** `tools/sync_core.py` and `tools/targets.json`: copy the pages into the SOsintOps tools that are used offline, each copy marked with its origin and version.
