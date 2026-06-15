# Virtualized Real-Time Flow-based IDPS for Modbus/TCP Traffic

- **Authors:** Mamdouh Muhammad, Debanjali Banerjee, Loui Al Sardy
- **Affiliation:** Computer Networks and Communication Systems, Friedrich-Alexander-Universitat Erlangen-Nurnberg (FAU), Erlangen, Germany
- **Venue:** International Conference on Cybertechnology and Future Networks (ICCFN), Smart Village, Cairo, Egypt
- **Year:** 2025
- **Status:** Accepted (not yet published)
- **DOI:** TODO: Add DOI
- **Paper link:** TODO: Add paper link (see [links.md](links.md))
- **Code repository:** TODO: Add code repository URL (substantial code lives in a separate dedicated repository)
- **Slides:** TODO: Add slides link (see [slides/](slides/))
- **Poster:** TODO: Add poster link (see [poster/](poster/))
- **Dataset:** TODO: Add dataset link (see [links.md](links.md))

## Abstract

Industrial Internet of Things (IIoT) networks that use Modbus/TCP remain vulnerable due to the lack of authentication and encryption. Many Industrial Control Systems (ICS) still communicate using plaintext Modbus/TCP, exposing them to attack vectors such as capture-and-retransmission (replay), resource-exhaustion/flooding (Denial of Service), and command tampering/injection (protocol manipulation). This paper presents a real-time Intrusion Detection and Prevention System (IDPS) for Modbus/TCP evaluated in a virtualized testbed using Linux namespaces. The system mirrors traffic, extracts compact flow features, and applies an unsupervised Isolation Forest algorithm with protocol-aware rules and adaptive thresholds. It detects SYN floods, replay attempts, and malformed Application Data Units (ADU), and can automatically block offending IPs. Experiments on the CIC Modbus 2023 dataset and live attack simulations demonstrate high detection accuracy.

## Keywords

Industrial Control Systems; Operational Technology; Modbus/TCP; Intrusion Detection System; Cybersecurity

## Main contribution

A real-time flow-based IDPS for Modbus/TCP running in a virtualized Linux-namespace testbed, combining an unsupervised Isolation Forest with protocol-aware rules and adaptive thresholds to detect SYN floods, replay, and malformed ADUs and to automatically block offending IPs, evaluated on the CIC Modbus 2023 dataset and live attack simulations.

## Reproducibility status

See [reproducibility-notes.md](reproducibility-notes.md). TODO: Confirm code and dataset availability.

## Citation

Cite this work using the BibTeX entry in [bibtex.bib](bibtex.bib) (key: `muhammad2025modbusidps`).
TODO: Complete any missing citation fields once the publication details are confirmed.

## Related links

See [links.md](links.md) for DOI, publisher page, preprint, code, dataset, slides, poster,
and profile links.
