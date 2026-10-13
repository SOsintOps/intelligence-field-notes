# Related Projects

The public SOsintOps projects. These notes are the method behind them; each tool's own guidelines say what is specific to its work and point back here for the rest.

## Workstations and Toolkits
- **[Exploratores](https://github.com/SOsintOps/Exploratores)** - A browser-based OSINT toolkit with no backend: curated search tools for people, phones, domains, images, companies and social platforms, plus the Redactor (browser-side removal of personal data before text goes to an AI model), a multi-country IBAN checker and an embedded CyberChef. [Try it online](https://sosintops.github.io/Exploratores/).
- **[Argos](https://github.com/SOsintOps/Argos)** - Turns a clean Ubuntu Budgie 24.04 or 26.04 LTS virtual machine into an OSINT workstation: installs the tools, adds a menu entry per task, and saves every result in a case folder with the command used, the output and SHA-256 hashes. Ships the report templates built on [Report Writing](report-writing.md).
- **[Speculator](https://github.com/SOsintOps/Speculator-Project)** - The sister project of Argos for Debian 13: the same idea, one installer, Zenity launchers and one evidence folder per target, with the same report templates.
- **[Wukong](https://github.com/SOsintOps/Wukong)** - A China-focused spin-off of Speculator: a Debian workstation with a Chinese language and culture layer (fonts, Pinyin input, dictionaries), Chinese platforms and company-research tools, and a method adapted to the Chinese-language internet.

- **[Claudii Exploratores](https://github.com/SOsintOps/claudii-exploratores)** - The Exploratores catalogue of OSINT tools as an agent skill and an MCP server for Claude: it classifies an indicator and builds the matching search links, with the analytic standards and OPSEC rules of these notes as its method reference. Alpha.

## Analysis
- **[Quaesitor](https://github.com/SOsintOps/quaesitor)** - A local case graph for OSINT investigations (people, phones, accounts, companies, vehicles, places, documents) with the UNODC link-analysis method, Follow the Money relations and PDF export. A fork of OSInt Graph by Andrea Cumini.
- **[Elementary CTI](https://github.com/SOsintOps/elementary-CTI)** - A ransomware threat-intelligence aggregator: victim and attack data from tracking sources, enriched with MITRE ATT&CK, payment and operational data, in a web interface for the analyst, with AI-assisted assessments written to ICD 203 and BLUF rules.
- **[Aethelburg](https://github.com/SOsintOps/Aethelburg-project)** - A local desktop platform for analysing UK Companies House data to find shell companies and anomalous corporate structures: risk scoring, geo-intelligence, link analysis and investigative reports.
- **[Acta Diurna](https://github.com/SOsintOps/acta-diurna)** - An OSINT dashboard (in Italian) for monitoring and analysing news on law-enforcement operations in Italy, with source checks and structured reports.

## Method and Process
- **[Codex Machinae](https://github.com/SOsintOps/codex-machinae)** - A modular playbook for building software with LLM collaborators; its classification module covers ATT&CK, STIX, TLP and F3EAD for intelligence tooling.
- **[Il Conclave](https://github.com/SOsintOps/il-conclave)** - A Claude Code skill (in Italian) that puts a question or a decision through four forced analytic procedures, among them ACH and a premortem, then an anonymous peer review, a debate round and a confidence-weighted synthesis. See [Techniques as AI Procedures](analytic-techniques.md#techniques-as-ai-procedures).
- **[13proof](https://github.com/SOsintOps/13proof)** - A six-stage AI audit for technical documentation: accuracy, secrets, code synchronisation, terminology and style. Not an intelligence tool, but the same discipline applied to documents: every finding traced to a line and a reason.

## Other Projects
- **[Project Anima Simulacrum](https://github.com/SOsintOps/Project-Anima-Simulacrum)** - An AI engine that reads narrative texts and builds dynamic personality profiles for language models. Far from intelligence work, but a reminder for profiling: a profile drawn from what someone writes describes the writing, not the person.

## Forks Maintained for OSINT Work
- **[TelEgrapherX](https://github.com/SOsintOps/TelEgrapherX)** - A fork of Telegram Explorer (TEx) for collecting and analysing Telegram groups and channels.
- **[Maigret](https://github.com/SOsintOps/maigret)** - A fork of soxoj's username-search tool, with a web interface of our own.
- **[TGchat-analytics](https://github.com/SOsintOps/TGchat-analytics)** - A fork of chat-analytics for statistical reports on exported chats.
