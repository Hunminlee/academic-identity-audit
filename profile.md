# Research Profile

**Identity:** Hunmin Lee  
**Evidence window for status decisions:** August 15, 2025–August 14, 2026  
**Prepared:** August 19, 2026

## Classification method

Research areas are named from the ACM classification reference in Google Drive and classified at the most specific level clearly supported by the substance of the project. Current/Core requires a recurring central topic across at least two substantive project or planning records plus substantive activity in the evidence window. Secondary/Adjacent is genuinely connected to the active direction but lacks that recurring recent-project evidence. Historical is supported by older completed work without substantive project activity in the evidence window.

## Current/Core

### Generalizable biosignal gesture and motor decoding for neural rehabilitation

**ACM classification:** **J.3 — Life and Medical Sciences**; **I.5.4 — Pattern Recognition: Applications**

This work develops learning systems that decode upper- and lower-limb gestures or movements from EMG and peripheral neural signals, with neural rehabilitation and reliable human–machine interaction as the central applications. The recurring problem is robust motor decoding across sessions, people, limbs, datasets, and changing signal conditions.

**Evidence**

- [Neural Computing Interface / MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — the README defines peripheral-nerve hand-gesture decoding, inter-session generalization as the current target, and later cross-subject generalization; substantive result commits continued through [December 12, 2025](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce/commit/e724186834ff25f47cf9d2fdabe7476a531ae384).
- [Cross-motor-decoding](https://github.com/Hunminlee/Cross-motor-decoding) — contains separate upper-limb and lower-limb pipelines plus shared adaptation code; substantive experiment commits continued through [September 22, 2025](https://github.com/Hunminlee/Cross-motor-decoding/commit/04196856459b1682811ec1ef74886c48c0d2f8cd).
- [GitHub-hosted publications record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — records *FedEMG* (2025), *Few-Shot Prototype Adaptation for Generalizable Electromyography Gesture Recognition* (March 2026), *Upper and Lower-Limb Motor Decoding for Adaptive and Generalized Neural Rehabilitation* (May 2026), and current peripheral-neural and EMG–text manuscripts.

### Adaptation, generalization, and personalization under distribution shift

**ACM classification:** **I.2.6 — Artificial Intelligence: Learning**

This methodological line designs models that remain useful when subjects, sessions, devices, labels, or data distributions change. Current work emphasizes adaptation and personalized or invariant representations for biomedical signals, while earlier prototype, meta-learning, and federated projects provide the methodological lineage.

**Evidence**

- [Cross-motor shared adaptation module](https://github.com/Hunminlee/Cross-motor-decoding/blob/main/Shared/Adaptation.py) and its upper-/lower-limb experiment structure show adaptation as a central method rather than an isolated keyword.
- [MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) explicitly targets inter-session robustness, cross-subject generalization, domain adaptation, and personalization; the repository also contains dedicated different-subject and self-supervised-learning experiment stages.
- [EMG graph-classification project](https://github.com/Hunminlee/EMG-based-Gesture-Classification-using-Graphs-and-GNN) establishes the earlier multi-dataset generalization and sensor-configuration line.
- [GitHub-hosted publications record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) documents continuing 2025–2026 work on FedEMG, prototype adaptation, motor decoding, and co-adaptive peripheral neural sensing.

## Secondary/Adjacent

### Federated prototype and meta-learning for heterogeneous IoT and modulation-classification systems

**ACM classification:** **I.2.11 — Distributed Artificial Intelligence**; **I.5.4 — Pattern Recognition: Applications**

This line studies personalization and generalization across non-IID distributed clients, often using automatic modulation classification as the application. Its prototype/adaptation methods remain relevant to the current generalization agenda, but the accessible project repositories do not show the same recent experimental activity as the biomedical decoding projects, so it is not treated as equally representative of the current core.

**Evidence**

- [Federated Prototype Adaptation Learning for modulation classification](https://github.com/Hunminlee/Federated-Prototype-Adaptation-Learning-for-modulation-classification) — a substantive project centered on federated prototype adaptation for communication-signal classification.
- [FedPML](https://github.com/Hunminlee/FedPML) — implements federated prototype meta-learning for adaptation and generalization.
- [GitHub-hosted publications record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) records the FPAL article in November 2025 and FedPML in January 2026, showing recent output from this line even though its project-code activity predates the evidence window.

### Peripheral-nerve neural interfaces for human–machine interaction

**ACM classification:** **H.5.2 — Information Interfaces and Presentation: User Interfaces**; **J.3 — Life and Medical Sciences**

This work uses a custom wrist-level peripheral-nerve sensing device to decode hand gestures for robust human–machine interaction. It is an active and important extension of the biosignal program, but it is supported by one recent substantive repository and therefore remains Secondary/Adjacent under the stated recurrence rule.

**Evidence**

- [Neural Computing Interface / MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — central device, decoding pipeline, gesture classes, generalization experiments, and 2025 activity.
- [GitHub-hosted publications record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — lists the current manuscript *From Muscles to Nerves: Co-adaptive Peripheral Neural Sensing for Reliable Human–Machine Interaction*.

## Historical

### Non-contact capacitive and electric-field gesture sensing

**ACM classification:** **H.5.2 — Information Interfaces and Presentation: User Interfaces**; **I.5.4 — Pattern Recognition: Applications**

This completed line used electric-field or capacitive proximity sensors for real-time hand-motion recognition and explainable interaction. The supporting works date from 2020–2024, and no substantive GitHub or independent Notion project activity for this line was found in the evidence window.

**Evidence**

- [GitHub-hosted publications record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — *Real-time Hand Motion Frame Extraction Using Electric Potential Sensors* (2020), *A BPR-CNN Based Hand Motion Classifier Using Electric Field Sensors* (2022), and *Towards Utilization of Explainable Hand Motion Recognition in 3D Capacitive Proximity Sensing* (2024).

### Machine learning for human-resource-development and organizational analytics

**ACM classification:** **J.4 — Social and Behavioral Sciences**; **I.2.6 — Artificial Intelligence: Learning**

This line applies interpretable machine learning to competency, organizational management, and HRD-environment analysis. It is supported by several completed repositories, but their substantive activity predates August 15, 2025, so it is Historical under the supplied 12-month rule.

**Evidence**

- [Deciphering HRD features in competency](https://github.com/Hunminlee/Deciphering_HRD_features_in_competency) — competency modeling, generalization tests, and SHAP analysis; last substantive commit August 9, 2025.
- [Integrating AI and human intelligence in HRD](https://github.com/Hunminlee/Integrating-AI-HI---HRD) — interpretable AI for organizational-management and HRD decisions; last activity December 2024.
- [HRD Environment Estimation](https://github.com/Hunminlee/HRD---Project2) — HCCP-based HRD-environment prediction; last activity January 2025.

## Evidence limitation

Targeted searches of the connected Notion workspace for EMG, rehabilitation, adaptation, prototype/federated learning, self-supervised learning, unlearning, and experiment or project plans returned prior audit summaries rather than independent original research/project records. Those derivative audit pages were not counted as substantive Notion planning evidence. The profile therefore relies on the independently inspectable GitHub projects, dated commits, and GitHub-hosted publication record above.
