# Adaptive Learning Lab

### [🚀 Launch the Free Math Worksheet App](https://vam1l.github.io/Adaptive-Learning-Lab/)

**For parents and homeschoolers:** Click **Launch the Free Math Worksheet App** above. No GitHub account, installation, or subscription is required. Select a grade, administer a short skill check, and generate printable practice worksheets and answer keys.

> **Early alpha:** The tool is for math fluency and targeted practice, not a validated diagnostic assessment or replacement for a complete math curriculum. Student scores are stored locally in your browser; use a nickname and export backups to avoid losing progress.

**Website:** https://vam1l.github.io/Adaptive-Learning-Lab/

---

An open-source, local-first parent-guided mathematics **fluency and prerequisite-remediation** prototype. Intended to complement, not replace, conceptual math instruction from a school curriculum, Beast Academy, AoPS, or another provider.

## Run
For most families, use the [public app link](https://vam1l.github.io/Adaptive-Learning-Lab/). Developers can also open [index.html](./index.html) in any modern browser or publish the static files elsewhere. No build tools, API keys, accounts, or dependencies. Print as PDF using the browser's Print dialog.

## Online assessment (new)\nSelect a skill in **Online auto-graded skill check**, choose **Start assessment**, and let the student enter answers. The parent then selects **Independent**, **Prompted**, or **Taught / modeled** using the on-page definitions and presses **Grade and save**. The program displays an item-by-item answer review and stores the score locally. Select **Print administration guide** for a one-page parent reference. This is a short instructional check, not a standardized or validated diagnostic assessment.\n\n## What works in this alpha
- Grade 2–6 selection; limited standard-tagged arithmetic and prerequisite skills
- Print-ready 8-question screening probes and five-day differentiated worksheet packets
- Deterministic seeded problem generation and a separate answer key
- Per-skill parent scoring (0–8) with independence/support annotation
- Transparent prerequisite-aware practice prioritization
- Local-only progress tracking, six-observation review prompt
- CSV export, JSON backup/restore, complete data deletion

## Educational and measurement limitations
**Not a validated diagnostic test, proficiency indicator, or full curriculum.** These eight-item checks are too short for high-confidence mastery classification. Parallel forms have not been empirically equated; cutoffs and priority rules are heuristics. Generated problems are computationally deterministic but require ongoing content review. Grade-specific standards listed are representative rather than comprehensive. Parental instructional support and conceptual teaching remain necessary.

Suggested starting protocol: baseline, a short weekly skill probe, weekly practice adjustment, a formal review after ~6 instructional weeks with comparable observations, broader screening at 8–12 weeks. This is a pragmatic schedule, not a universal optimum. Consider intervention intensity and measure reliability.

Research basis: [IES/WWC 2021 math intervention practice guide](https://ies.ed.gov/ncee/wwc/PracticeGuide/26) and [NCII data-based individualization](https://intensiveintervention.org/). This software has **not** undergone an effectiveness study.

## Privacy
All data are stored in this browser's localStorage keyed by nickname; no cloud transmission. Other device users sharing a browser profile can access locally stored records. Avoid real names or sensitive educational/medical information. Deleting browser storage erases data; export a backup first. Never commit student records to public GitHub.

## Roadmap before a public education beta
1. Add K–1 and complete K–6 Common Core skill coverage with reviewed instructional content.
2. Build item banks with comparable forms, tests, independent review, and item analysis.
3. Add clinically neutral misconception tagging and worked visual examples.
4. Add longitudinal skill-specific trend lines and explicit, transparent intervention decision rules.
5. Accessibility audit, cross-browser testing, CSP review, and stronger import validation.
6. Independent educators review content; pilot with parents before claiming efficacy.

## License
Original source in this subfolder is released under the MIT license; see LICENSE.
