# Evidence-backed development history

_Audit snapshot: 25 August 2026_

This page records the chronology that can be supported by native Git history and dated project artifacts on the development laptop. It separates the date work was created from the later date a public-safe version was curated for GitHub.

It does **not** convert file timestamps into Git commits, estimate hours from commit counts, or assign random historical dates. A commit records a repository change, not the duration of the work behind it.

## Native Git histories

These repositories retain an inspectable commit sequence. Counts are the native commits present before the documentation update that published this audit. Private-repository counts were checked against the local clone and its matching remote head; their contents are not exposed here.

| Repository | Visibility | Native commits | Verifiable window | What the history shows |
|---|---|---:|---|---|
| [Amina](https://github.com/Abkob/Amina/commits/main/) | Public | 31 | 23 Jun–25 Aug 2026 | Application development, storage/search work, interface evolution, and public-repository hardening |
| [WSP Offline System](https://github.com/Abkob/WSP_automationexcel/commits/main/) | Public | 14 | 9 Jun–25 Aug 2026 | Recovery, data-safety cleanup, indexing work, installer releases, packaging, and audited documentation |
| Sinmar | Private; access on request | 32 | 1–6 Jul 2026 | Deployment, backup, authentication, sales/register workflows, UI refinements, and calculation fixes |
| BCI and Epilepsy Research | Private; access on request | 10 | 25 Sep 2025–25 Aug 2026 | Week-based notebook organization followed by reproducibility, provenance, and evidence-boundary documentation |
| [ECG Feature Detector](https://github.com/Abkob/ECG_FE_Detector_Interface/commits/main/) | Public | 5 | 21–25 Aug 2026 | Initial detector, private-upload handling, analysis controls, tests, and the disclosed ECG–EEG literature review |
| [Research Portfolio](https://github.com/Abkob/Research_Portfolio/commits/main/) | Public | 5 | 25 Aug 2026 | Public curation of local and Drive projects, artifact manifests, attribution, and publication boundaries |

## Work that predates its public repository

Some team projects were developed as notebooks, reports, CAD files, and shared folders rather than in a local Git repository. Their public repositories therefore begin with a curation commit. The underlying artifacts supply an earlier, more limited chronology.

| Project | Dated evidence | Public-history interpretation |
|---|---|---|
| [AARS Agro-Remediation](https://github.com/Abkob/AARS_Agro_Remediation/blob/main/PROJECT_HISTORY.md) | Six project PDFs carry creation metadata from 26 Jun–20 Jul 2025 | The documents support a 2025 design-work window; the exact notebook edit sequence is not recoverable, and the curated repository began on 25 Aug 2026 |
| [MotorBrace](https://github.com/Abkob/MotorBrace_BCI_EMG/blob/main/PROJECT_HISTORY.md) | Research proposal dated 26 Aug 2025 and mechanical report dated 16 Sep 2025 in embedded PDF metadata | The reports predate the public repository; notebook chronology is not reconstructed without source version history |
| BCI and Epilepsy Research (private archive) | Meeting report and technical notes carry PDF metadata from 25 and 28 Jul 2025 | Those research artifacts predate the first retained Git commit on 25 Sep 2025; access can be provided privately |
| [Smart Prosthetic Liner](https://github.com/Abkob/Research_Portfolio/tree/main/projects/smart-prosthetic-liner) | Iterative CAD/print-package archives dated 28 Apr–24 May 2026 plus the later team report and reviews | The portfolio preserves inspectable final artifacts and dated filenames, while avoiding an invented commit-by-commit reconstruction |
| [NeuroSense](https://github.com/Abkob/Research_Portfolio/tree/main/projects/neurosense) | The team concept note identifies the April 2026 hackathon context | The attributable concept note, classifier plan, anonymized interface, and code snapshot were publicly curated on 25 Aug 2026 |

## Foundations without backfilled claims

- [Machine Learning Research Syllabus](https://github.com/Abkob/Machine_Learning_Syllabus) began as a public evidence ledger on 25 August 2026.
- [LeetCode](https://github.com/Abkob/LeetCode) and [DeepML](https://github.com/Abkob/DeepML) began with tested repository infrastructure and a count of zero completed solutions. Future entries are counted only when a real solution and its tests are committed.
- The [GitHub profile repository](https://github.com/Abkob/Abkob) records presentation and documentation work; it is not counted as technical project output.

## How to interpret this record

- **Native commit date:** verifiable through the linked Git history.
- **Artifact date:** embedded document metadata, an explicitly dated filename, or an internal document date. It supports chronology but does not prove hours or individual authorship by itself.
- **Public curation date:** when a sanitized, attributed subset was published to GitHub; it may be later than the original work.
- **Team artifact:** remains team-attributed unless the source explicitly records an individual contribution.

For code quality, evaluation boundaries, reports, and runnable artifacts, start with the [Research Portfolio](https://github.com/Abkob/Research_Portfolio).
