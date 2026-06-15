# Mamdouh Muhammad - Academic Publications Index

Mamdouh Muhammad, PhD researcher in AI-based cybersecurity for smart grids.

This repository is the central academic publication index and archive. It organizes
publication metadata, BibTeX entries, links, slides, posters, figures, and
reproducibility notes, and points to separate dedicated repositories that hold
substantial code.

## Research areas

- AI for cybersecurity
- Smart-grid security
- Intrusion detection systems
- Industrial control systems
- Modbus/TCP security
- Flow-based IDS
- Dataset bias and reproducibility
- LLM-assisted security systems
- SDN security

## Publications

Sorted newest to oldest. Some entries contain `TODO` placeholders that require manual
verification (see each publication folder).

| Year | Title | Venue | Status | Links | Code | Slides | BibTeX |
|------|-------|-------|--------|-------|------|--------|--------|
| 2026 | Parameter-Efficient LLMs for Flow-Based Intrusion Detection | TODO | TODO | [folder](publications/2026-peft-llm-flow-ids/) | [code](publications/2026-peft-llm-flow-ids/links.md) | [slides](publications/2026-peft-llm-flow-ids/slides/) | [bib](publications/2026-peft-llm-flow-ids/bibtex.bib) |
| 2026 | Recurrent Biases and Fallacies in Dataset-Driven Intrusion Detection Research | TODO | TODO | [folder](publications/2026-recurrent-biases-dataset-driven-ids/) | [code](publications/2026-recurrent-biases-dataset-driven-ids/links.md) | [slides](publications/2026-recurrent-biases-dataset-driven-ids/slides/) | [bib](publications/2026-recurrent-biases-dataset-driven-ids/bibtex.bib) |
| 2025 | Virtualized Real-Time Flow-based IDPS for Modbus/TCP Traffic | TODO | Under review | [folder](publications/2025-virtualized-real-time-flow-based-idps-modbus/) | [code](publications/2025-virtualized-real-time-flow-based-idps-modbus/links.md) | [slides](publications/2025-virtualized-real-time-flow-based-idps-modbus/slides/) | [bib](publications/2025-virtualized-real-time-flow-based-idps-modbus/bibtex.bib) |
| 2025 | HyLLM-IDS: A Conceptual Hybrid LLM-Assisted Intrusion Detection Framework for Cyber-Physical Systems | TODO | TODO | [folder](publications/2025-hyllm-ids/) | [code](publications/2025-hyllm-ids/links.md) | [slides](publications/2025-hyllm-ids/slides/) | [bib](publications/2025-hyllm-ids/bibtex.bib) |
| 2025 | AI-Based Anomaly Detection for Enhanced Cybersecurity in IoT Networks | CSNet 2025 - Cyber Security in Networking Conference, Abu Dhabi | TODO | [folder](publications/2025-ai-anomaly-detection-iot-networks/) | [code](publications/2025-ai-anomaly-detection-iot-networks/links.md) | [slides](publications/2025-ai-anomaly-detection-iot-networks/slides/) | [bib](publications/2025-ai-anomaly-detection-iot-networks/bibtex.bib) |
| 2025 | AI-driven Anomaly Detection with ICS Protocols in Smart Grids | IFIP, 2025 | Published | [folder](publications/2025-ai-driven-anomaly-detection-ics-smart-grids/) | [code](publications/2025-ai-driven-anomaly-detection-ics-smart-grids/links.md) | [slides](publications/2025-ai-driven-anomaly-detection-ics-smart-grids/slides/) | [bib](publications/2025-ai-driven-anomaly-detection-ics-smart-grids/bibtex.bib) |
| 2024 | TODO: Add title (Cybersecurity strategies for smart grids / IoT / IIoT) | TODO | TODO | [folder](publications/2024-cybersecurity-strategies-smart-grids-iot-iiot/) | [code](publications/2024-cybersecurity-strategies-smart-grids-iot-iiot/links.md) | [slides](publications/2024-cybersecurity-strategies-smart-grids-iot-iiot/slides/) | [bib](publications/2024-cybersecurity-strategies-smart-grids-iot-iiot/bibtex.bib) |
| 2024 | Survey of Cybersecurity in Smart Grids: Protocols and Datasets | Procedia Computer Science, Vol | Published | [DOI](https://doi.org/10.1016/j.procs.2024.08.049) / [folder](publications/2024-survey-cybersecurity-smart-grid-protocols-datasets/) | [code](publications/2024-survey-cybersecurity-smart-grid-protocols-datasets/links.md) | [slides](publications/2024-survey-cybersecurity-smart-grid-protocols-datasets/slides/) | [bib](publications/2024-survey-cybersecurity-smart-grid-protocols-datasets/bibtex.bib) |
| 2023 | TODO: Add title (VGG-based DDoS detection in SDN) | TODO | TODO | [folder](publications/2023-vgg-ddos-sdn/) | [code](publications/2023-vgg-ddos-sdn/links.md) | [slides](publications/2023-vgg-ddos-sdn/slides/) | [bib](publications/2023-vgg-ddos-sdn/bibtex.bib) |

## Repository organization

This repository is the **academic archive and index**. It contains only text-based
artifacts: Markdown, BibTeX, links, abstracts, reproducibility notes, and folder
structure. **Substantial code should live in separate dedicated repositories**, which are
linked from each publication's `links.md` and `README.md`. By policy, PDF files are
git-ignored and are not committed to this repository.

Each publication lives under `publications/<year>-<slug>/` and contains:

- `README.md` - publication metadata and summary
- `abstract.txt` - the abstract
- `bibtex.bib` - the BibTeX entry
- `links.md` - DOI, publisher, preprint, code, dataset, slides, poster, profiles
- `reproducibility-notes.md` - environment, dependencies, how to reproduce
- `paper/`, `slides/`, `poster/`, `figures/` - subfolders with their own `README.md`

Reusable templates are in `templates/`. Shared visual assets are in `assets/`.

## Citation

Each publication folder contains a `bibtex.bib` file with the BibTeX metadata for that
work. **Please cite each paper using its own BibTeX entry** rather than citing this index
repository. A repository-level `CITATION.cff` is provided only for referencing this index
itself; it is not a substitute for the per-paper BibTeX entries.

## Legal and licensing note

Papers, slides, datasets, and code may each be covered by **different licenses**. Before
reusing any artifact, check the relevant publication folder and the publisher's terms.
Publisher PDFs are not hosted here; only legally shareable versions (author accepted
manuscripts, preprints, open-access PDFs, or links) may be added. See [LICENSE](LICENSE)
for the current (placeholder) licensing status of this repository.
