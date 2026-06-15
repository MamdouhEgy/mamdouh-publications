# AI-Based Anomaly Detection for Enhanced Cybersecurity in IoT Networks

- **Authors:** Mamdouh Muhammad, Sushmetha Arumugam, Loui Al Sardy
- **Affiliation:** Computer Networks and Communication Systems (Informatik 7), Department of Computer Science, Friedrich-Alexander-Universitat Erlangen-Nurnberg (FAU), Erlangen, Germany
- **Venue:** 2025 9th Cyber Security in Networking Conference (CSNet 2025), Abu Dhabi, UAE
- **Year:** 2025
- **Status:** Published
- **DOI:** 10.1109/CSNet67572.2025.11288241 (https://doi.org/10.1109/CSNet67572.2025.11288241)
- **Paper link:** TODO: Add paper link (see [links.md](links.md))
- **Code repository:** TODO: Add code repository URL (substantial code lives in a separate dedicated repository)
- **Slides:** TODO: Add slides link (see [slides/](slides/))
- **Poster:** TODO: Add poster link (see [poster/](poster/))
- **Dataset:** TODO: Add dataset link (see [links.md](links.md))

## Abstract

Intrusion Detection Systems (IDSs) play a crucial role in securing Internet of Things (IoT) networks, which are increasingly exposed to sophisticated cyber threats. This paper presents an adaptive, reconstruction-based IDS leveraging multiple class-specific Long Short-Term Memory Autoencoders (LSTM-AEs), each trained on a single traffic class (Normal, DDoS-HTTP, DDoS-TCP, DDoS-ICMP). Unlike conventional anomaly detection that models only normal traffic, our approach performs multi-class classification by comparing reconstruction errors across all class-specific models. Evaluated on the Edge-IIoTset dataset, the method achieved a macro-averaged F1-score of 0.9963, underscoring the suitability of LSTM-AE architectures for fine-grained, threat-specific detection in realistic IoT environments.

## Keywords

IoT Security; Anomaly detection; Optuna; Deep Learning; LSTM Autoencoder; Edge-IIoTset

## Main contribution

An adaptive reconstruction-based IDS using multiple class-specific LSTM autoencoders (one per traffic class) that performs multi-class classification by comparing reconstruction errors across models, achieving a 0.9963 macro-F1 on the Edge-IIoTset dataset.

## Reproducibility status

See [reproducibility-notes.md](reproducibility-notes.md). TODO: Confirm code and dataset availability.

## Citation

Cite this work using the BibTeX entry in [bibtex.bib](bibtex.bib) (key: `muhammad2025iotanomaly`).
TODO: Complete any missing citation fields once the publication details are confirmed.

## Related links

See [links.md](links.md) for DOI, publisher page, preprint, code, dataset, slides, poster,
and profile links.
