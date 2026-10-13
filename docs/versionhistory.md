# Version History

Changelog of the Intelligence Field Notes.

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
