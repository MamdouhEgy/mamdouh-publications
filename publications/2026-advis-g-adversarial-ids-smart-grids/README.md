# ADVIS-G: An Adversarially Defended Intrusion Detection System for Smart Grids Using Deep Learning

- **Authors:** Ramkrishna Acharya, Loui Al Sardy, Mamdouh Muhammad, Reinhard German
- **Affiliation:** Friedrich-Alexander-Universitat Erlangen-Nurnberg (FAU), Erlangen, Germany
- **Venue:** KI - Kunstliche Intelligenz (journal)
- **Year:** 2026
- **Status:** Published
- **DOI:** 10.1007/s13218-026-00905-3 (https://doi.org/10.1007/s13218-026-00905-3)
- **Paper link:** TODO: Add paper link (see [links.md](links.md))
- **Code repository:** TODO: Add code repository URL (substantial code lives in a separate dedicated repository)
- **Slides:** TODO: Add slides link (see [slides/](slides/))
- **Poster:** TODO: Add poster link (see [poster/](poster/))
- **Dataset:** TODO: Add dataset link (see [links.md](links.md))

## Abstract

Smart Grids (SG) enhance efficiency and centralised control by enabling networked device communication, but these capabilities expose them to cyberattacks. Machine Learning (ML) and Deep Learning (DL) based Intrusion Detection Systems (IDS) have been employed to detect these threats. Yet, their adoption introduces new adversarial risks: specifically, attacks designed to fool IDS into misclassifying malicious activity as benign. In this study, we propose ADVIS-G, a novel, adversarially defended IDS framework for smart grids utilising deep learning. Our approach begins by training a high-accuracy (macro F1 >96%) classifier on session images from a DNP3-related dataset. We then assess vulnerability to adversarial examples generated using Fast Gradient Sign Method (FGSM), Basic Iterative Method (BIM), and Momentum Iterative Method (MIM) under varying perturbation rates. To counter such attacks, we introduce an adversarial blocking model based on autoencoder architectures that reconstruct input images, effectively removing adversarial perturbations. Experimental evaluation shows that while the baseline model's macro F1 drops to ~0.5 at an attack rate of 0.1, adversarial training improves robustness to 0.7. Our proposed autoencoder-based blocking further increases performance to 0.85 (lightweight) and 0.92 (heavier) at the same attack rate. Moreover, combining adversarial training with autoencoder defence achieves the highest resilience under stronger attacks. These results suggest that ADVIS-G significantly enhances IDS robustness against adversarial attacks, offering a promising direction for future smart grid security research.

## Keywords

Adversarial Attacks; Smart Grid; Cybersecurity; Intrusion Detection System; DNP3; Deep Learning; Critical Infrastructure

## Main contribution

ADVIS-G, an adversarially defended deep-learning IDS for smart grids that trains a high-accuracy classifier on DNP3 session images, evaluates robustness against FGSM/BIM/MIM adversarial attacks, and introduces an autoencoder-based blocking defence that, combined with adversarial training, restores macro-F1 to ~0.92 under attack.

## Reproducibility status

See [reproducibility-notes.md](reproducibility-notes.md). TODO: Confirm code and dataset availability.

## Citation

Cite this work using the BibTeX entry in [bibtex.bib](bibtex.bib) (key: `acharya2026advisg`).
TODO: Complete any missing citation fields once the publication details are confirmed.

## Related links

See [links.md](links.md) for DOI, publisher page, preprint, code, dataset, slides, poster,
and profile links.
