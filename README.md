# Intelligence Field Notes 0.1.2

![version](https://img.shields.io/badge/version-0.1.2-blue)
![licence](https://img.shields.io/badge/licence-CC%20BY%204.0-lightgrey)
![language](https://img.shields.io/badge/language-en--GB-blue)
![last commit](https://img.shields.io/github/last-commit/SOsintOps/intelligence-field-notes)

**Personal notes on intelligence analysis, OSINT method and the writing of intelligence reports, made available to everyone for convenience. They make no claim to be exhaustive: they are a practitioner's notebook, kept in order, with a link to every source they lean on.**

Version 0.1.2 documents the one exception to the 4 x 4 grading (machine-graded CTI feeds in Elementary CTI), adds a note on running analytic techniques as AI procedures and lists the remaining public SOsintOps projects. Version 0.1.1 linked every text at its first mention, not only in the reading lists, and syncs Quaesitor through its development repository. Version 0.1.0 was the first release: the method pages that the SOsintOps tools used to carry in separate, drifting copies, merged into one set, checked against the original texts and extended with the report-writing guide none of them had. See the full [version history](docs/versionhistory.md).

---

## Contents

| Page | What it covers |
| :--- | :--- |
| [Analytic Standards](docs/analytic-standards.md) | The intelligence cycle; the five analytic and nine tradecraft standards of ICD 203; information, intelligence and evidence |
| [OSINT Methodology](docs/osint-methodology.md) | The OSINT cycle, the 5W1H method, collection discipline, OPSEC, legal and ethical limits |
| [Analytic Techniques](docs/analytic-techniques.md) | Cognitive biases in OSINT; key assumptions check, ACH, indicators, devil's advocacy, premortem; deception |
| [Estimative Language](docs/estimative-language.md) | The ICD 203 likelihood scale, confidence levels, and the rules for not mixing them |
| [Source Evaluation](docs/source-evaluation.md) | The UNODC 4 x 4 grading, who the source is in OSINT, provenance, sanitisation, converting from 6 x 6 |
| [Report Writing](docs/report-writing.md) | Bottom line up front, report structure, facts versus judgements, sourcing, prose rules, checklist |
| [Reading List](docs/reading-list.md) | Every text the notes draw on, linked, plus a curated list on intelligence writing |
| [Related Projects](docs/related-projects.md) | The SOsintOps tools that put these notes into practice |
| [FAQ](docs/faq.md) | The choices behind the notes and how the tools use them |

---

## What These Notes Are, and Are Not

They are notes: a working summary of public standards ([ICD 203](https://www.dni.gov/files/documents/ICD/ICD-203.pdf), the UNODC [*Criminal Intelligence: Manual for Analysts*](https://www.unodc.org/documents/organized-crime/Law-Enforcement/Criminal_Intelligence_for_Analysts.pdf), the [Berkeley Protocol](https://humanrights.berkeley.edu/publications/berkeley-protocol-on-digital-open-source-investigations/)), of the classic texts (Heuer, Pherson, Kent) and of practice. They are not an official doctrine, a course or a substitute for the texts they summarise; where they disagree with a standard, the standard is right and an [issue](https://github.com/SOsintOps/intelligence-field-notes/issues) is welcome.

Three choices run through all the pages:
- **One grading system:** the UNODC 4 x 4 (source A, B, C, X; information 1 to 4), with one documented exception for machine-graded CTI feeds.
- **One likelihood row:** the first row of the ICD 203 scale, from *almost no chance* to *almost certain*, with confidence stated separately.
- **The report is the product:** charts, graphs and dashboards support a written report; they never replace it.

---

## How the SOsintOps Tools Use Them

Each SOsintOps tool keeps a short guidelines page about what is specific to its work and links here for the common method. The workstations used offline (Argos, Speculator, Wukong, Exploratores, Quaesitor) also carry a copy of the pages in a `field-notes` folder, generated at release time:

```bash
python tools/sync_core.py            # copy the pages into the repositories next to this one
python tools/sync_core.py --check    # show what would change, write nothing
```

The targets are listed in [`tools/targets.json`](tools/targets.json). Quaesitor is synced in its development repository and reaches the public one through its own release script. Each copy is marked with its origin and version; edit the original here, never the copy.

---

## Related Projects

[Exploratores](https://github.com/SOsintOps/Exploratores) · [Argos](https://github.com/SOsintOps/Argos) · [Speculator](https://github.com/SOsintOps/Speculator-Project) · [Wukong](https://github.com/SOsintOps/Wukong) · [Quaesitor](https://github.com/SOsintOps/quaesitor) · [Elementary CTI](https://github.com/SOsintOps/elementary-CTI) · [Aethelburg](https://github.com/SOsintOps/Aethelburg-project) · [Acta Diurna](https://github.com/SOsintOps/acta-diurna) · [Codex Machinae](https://github.com/SOsintOps/codex-machinae) · [Il Conclave](https://github.com/SOsintOps/il-conclave) · [Claudii Exploratores](https://github.com/SOsintOps/claudii-exploratores) — one line on each in [Related Projects](docs/related-projects.md).

---

## Credits

- The intelligence-writing section of the [Reading List](docs/reading-list.md#intelligence-writing) absorbs [awesome-intelligence-writing](https://github.com/mxm0z/awesome-intelligence-writing) by Ygor Maximo (MIT licence), with every link rechecked.
- The source-evaluation and link-analysis method is rewritten in our own words from the UNODC [*Criminal Intelligence: Manual for Analysts*](https://www.unodc.org/documents/organized-crime/Law-Enforcement/Criminal_Intelligence_for_Analysts.pdf) (2011), which is linked and should be read in full.
- ICD 203 and ICD 206 are public documents of the US Office of the Director of National Intelligence.

---

## Licence

The notes are released under the [Creative Commons Attribution 4.0 International](LICENSE) licence. The scripts in `tools/` are under the [MIT licence](tools/LICENSE).
