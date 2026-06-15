# Parameter-Efficient LLMs for Flow-Based Intrusion Detection

- **Authors:** Mamdouh Muhammad, Anton Wunsch, Loui Al Sardy
- **Affiliation:** Computer Networks and Communication Systems, Friedrich-Alexander-Universitat Erlangen-Nurnberg (FAU), Erlangen, Germany
- **Venue:** 41st IFIP SEC International Conference on ICT Systems Security and Privacy Protection (IFIP SEC 2026), Perth, Australia
- **Year:** 2026
- **Status:** Published
- **DOI:** 10.1007/978-3-032-27993-4_4 (https://doi.org/10.1007/978-3-032-27993-4_4)
- **Paper link:** TODO: Add paper link (see [links.md](links.md))
- **Code repository:** TODO: Add code repository URL (substantial code lives in a separate dedicated repository)
- **Dataset:** TODO: Add dataset link (see [links.md](links.md))

## Abstract

Flow-based intrusion detection systems (IDS) typically rely on statistical features extracted from network traffic. Recent fine-tuned LLMs, including instruction-tuned variants, can be adapted for security classification using lightweight, parameter-efficient methods. This paper studies binary flow-level intrusion detection (benign vs. attack) using supervised fine-tuning (SFT) and in-context learning (ICL), targeting practical deployment under limited compute. Each network flow is serialized into a compact instruction format that combines selected flow features with a concise connection log string, enabling a small decoder-only model to operate directly on realistic flow records. We adapt a 0.5B-parameter LLM via Low-Rank Adaptation (LoRA) and evaluate the accuracy-efficiency trade-off by varying LoRA rank and training data size. At inference time, we avoid free-form generation by scoring the conditional log-likelihood of the two label strings and calibrating a bias term on a validation set to control decision thresholds. Experiments on a balanced subset of a standard distributed denial-of-service (DDoS) benchmark show that LoRA-based SFT substantially improves over a zero-shot baseline, while pure ICL achieves strong performance with only a few labeled examples in the prompt. Combining LoRA adaptation with ICL yields the best results, reaching 91% accuracy and 90% macro-F1 on a 10k-flow test set. These findings indicate that small LLMs, paired with careful feature-to-text serialization and lightweight adaptation, can be viable components of flow-based IDS in resource-constrained settings.

## Keywords

Intrusion Detection System; Network Security; Large Language Models; Supervised Fine-Tuning; In-Context Learning; LoRA; DDoS Detection; Parameter-Efficient Fine-Tuning

## Main contribution

A parameter-efficient pipeline that serializes network flows into compact instruction text and adapts a 0.5B-parameter decoder-only LLM via LoRA, combining supervised fine-tuning with in-context learning and log-likelihood label scoring to reach 91% accuracy / 90% macro-F1 on a 10k-flow DDoS test set under constrained compute.

## Reproducibility status

See [reproducibility-notes.md](reproducibility-notes.md). TODO: Confirm code and dataset availability.

## Citation

Cite this work using the BibTeX entry in [bibtex.bib](bibtex.bib) (key: `muhammad2026peftllm`).
TODO: Complete any missing citation fields once the publication details are confirmed.

## Related links

See [links.md](links.md) for DOI, publisher page, preprint, code, dataset,
and profile links.
