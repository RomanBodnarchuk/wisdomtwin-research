# WisdomTwin Research

Open research by Roman Bodnarchuk, WisdomTwin, Inc.

This repository distributes three preprints and one technical whitepaper. None is peer reviewed. They propose architectures, controls and evaluation methods; they report no measured WisdomTwin enterprise-effectiveness results. Hosting copies are distribution locations, not additional research contributions.

## Reports

| Record | Version | Title and PDF | Status |
|---|---|---|---|
| WT-100-001 | 2.0 | [Judgment Latency in Regulated Enterprises: A Conceptual Framework and Research Agenda for Role-Specific AI Decision Support](papers/WT-100-001/v2.0/paper.pdf) | preprint |
| WT-200-001 | 1.0 | [The WisdomTwin Trust Layer: A Testable Control Specification for Role-Specific AI Decision Support](papers/WT-200-001/v1.0/paper.pdf) | preprint |
| WT-300-001 | 1.0 | [Measuring Judgment Latency and Net Time Recovery: A Staged Pilot Protocol for Role-Specific AI Decision Support](papers/WT-300-001/v1.0/paper.pdf) | preprint |
| WT-WP-001 | 1.0 | [Sovereign Judgment Twins: A reference architecture for governed enterprise decision support](papers/WT-WP-001/v1.0/paper.pdf) | technical whitepaper — proposed architecture |

## Source and citation

[Research library](https://wisdomtwin-research-library.wisdomtwin-ai.chatgpt.site/) · [Author ORCID](https://orcid.org/0009-0004-3113-2118)

Each version folder contains the released PDF, editable source and BibTeX/RIS citations. Canonical publication URLs are preserved in `catalog.json`; GitHub is a distribution mirror. Use the individual paper citation, not the repository citation, when citing a claim. No DOI is assigned in this distribution.

## Verification

On October 16, 2026, every distributed file was retrieved from the public research library and checked against its release SHA-256 manifest. `SHA256SUMS.txt` records the files actually distributed here. The website HTML fragment is excluded because its served bytes did not match the release manifest; none of the four paper PDFs had a checksum mismatch. Files are unchanged research releases; the repository date is a distribution date.

## License and disclosures

Original paper text and author-created figures: CC BY 4.0, subject to third-party rights identified by the papers. Generative-AI assistance and the author’s commercial interest are disclosed in the reports. This repository includes no private enterprise corpus or participant data.

Proposed controls do not establish regulatory compliance; synthetic examples are not empirical results. The pilot protocol is not a completed study or a preregistration.

## Publication operations

Maintain record ID, version, author, license, canonical URL and checksum across mirrors. Search for prior deposits before depositing. Record real repository identifiers and DOI receipts only after successful publication. Do not label these reports peer reviewed.

## Hosted HTML mirror

[Browse the four-report site](https://romanbodnarchuk.github.io/wisdomtwin-research/). Regenerate its pages with `python3 tools/build_site.py`; release PDFs are checked against catalog checksums before rendering.
