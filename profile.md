# Research Identity Profile

This profile is intended to guide academic-signal triage as of **August 14, 2026**. Research-area status and ACM classification are separate judgments: status is based on substantive project/research activity, while ACM codes describe the subject of the work at the most specific level clearly supported by the evidence.

**Status rules used here**
- **Current/Core:** central in at least two substantive GitHub projects or Notion planning records and supported by substantive activity during August 15, 2025–August 14, 2026.
- **Secondary/Adjacent:** genuinely connected to active research but does not warrant equal weight in the current research identity.
- **Historical:** clearly supported by older completed work but without substantive GitHub/Notion project activity in the 12-month window above.

**Notion evidence note:** targeted Notion searches surfaced prior audit/synthesis pages rather than original research-planning records. Those derivative pages were used as navigation/context but were not counted as independent substantive project records for the thresholds above.

## Current/Core

### 1. Generalizable and personalized biosignal and neural decoding
**ACM:** `I.5.4` — Pattern Recognition: Applications

The central application line is robust decoding of human motor intent from EMG and peripheral neural signals, especially gesture and upper-/lower-limb motor decoding. The work increasingly emphasizes biomedical and rehabilitation settings, with robustness across sessions and people rather than classification accuracy in a single fixed setting.

**Evidence**
- [EMG-based Gesture Classification using Graphs and GNN](https://github.com/Hunminlee/EMG-based-Gesture-Classification-using-Graphs-and-GNN) — multi-dataset EMG gesture recognition with explicit generalizability, interpretability, sensor configuration, and rehabilitation motivation.
- [Neural Computing Interface — MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — peripheral radial/ulnar nerve gesture decoding with inter-session generalization as the current target and inter-subject generalization as a planned extension.
- [Cross-motor-decoding](https://github.com/Hunminlee/Cross-motor-decoding) — upper- and lower-limb motor-decoding project with substantive activity in September 2025.
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — includes 2026 work on adaptive/generalized neural rehabilitation and few-shot generalizable EMG gesture recognition.

### 2. Adaptation, generalization, and personalization under heterogeneity
**ACM:** `I.2.6` — Artificial Intelligence: Learning

A recurring methodological direction is learning models that remain useful when subjects, sessions, devices, sites, or data distributions differ. Prototype learning, few-shot adaptation, personalization, meta-learning, and federated learning are treated here as related methods serving that broader adaptation/generalization problem rather than as separate research identities.

**Evidence**
- [Neural Computing Interface — MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — explicitly targets inter-session robustness, later inter-subject generalization, domain adaptation, and personalization.
- [FedPML](https://github.com/Hunminlee/FedPML) — federated prototype meta-learning for adaptation and generalization in distributed environments.
- [Federated Prototype Adaptation Learning for Modulation Classification](https://github.com/Hunminlee/Federated-Prototype-Adaptation-Learning-for-modulation-classification) — personalized/generalizable prototype adaptation in a distributed setting.
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — records recent work on FedPML, federated prototype adaptation, few-shot prototype adaptation for EMG, and adaptive/generalized neural rehabilitation.

## Secondary/Adjacent

### 3. Graph-based and interpretable learning for biomedical signals
**ACM:** `I.5.1` — Pattern Recognition: Models

Graph representations and structured models are an important supporting methodology, including spatiotemporal modeling of multichannel EMG and other biomedical data. This is strongly connected to the current biosignal program but is narrower and less recurrent in recent project activity than the broader generalization/adaptation direction.

**Evidence**
- [EMG-based Gesture Classification using Graphs and GNN](https://github.com/Hunminlee/EMG-based-Gesture-Classification-using-Graphs-and-GNN)
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — includes spatiotemporal GNN EMG decoding and graph/topology-oriented biomedical studies.

### 4. Distributed IoT and automatic modulation classification
**ACM:** `I.2.11` — Artificial Intelligence: Distributed Artificial Intelligence

Distributed IoT and modulation-classification projects are genuine parts of the research record and helped develop the federated/prototype learning line. They remain methodologically adjacent to the active adaptation work, but the application domain is less representative of the current biomedical/rehabilitation-centered identity.

**Evidence**
- [FedPML](https://github.com/Hunminlee/FedPML)
- [Federated Prototype Adaptation Learning for Modulation Classification](https://github.com/Hunminlee/Federated-Prototype-Adaptation-Learning-for-modulation-classification)
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — includes recent distributed-IoT federated/prototype work.

### 5. Other biomedical machine-learning applications
**ACM:** `I.5.4` — Pattern Recognition: Applications

The publication record also includes biomedical machine learning outside motor decoding, such as brain-tumor segmentation and heterogeneous graph modeling for drug response. These projects are genuinely biomedical and methodologically related, but they are episodic rather than the recurring center of the current research program.

**Evidence**
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html)

## Historical

### 6. Capacitive/electric-field gesture sensing and interface control
**ACM:** `H.1.2` — Information Systems: User/Machine Systems

Earlier work developed non-contact capacitive/electric-field sensing and hand-motion interfaces, including BPR-CNN and explainable capacitive gesture recognition. It is a genuine research lineage, but it has no substantive GitHub/Notion project activity in the August 15, 2025–August 14, 2026 window and should not be treated as the current core identity merely because citation platforms continue to surface it.

**Evidence**
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html) — records the capacitive/electric-field gesture publications in the older portion of the publication history.

### 7. AI-driven HRD and organizational analytics
**ACM:** `I.2.1` — Artificial Intelligence: Applications and Expert Systems

AI/ML for HRD, competency analysis, and organizational analytics is a genuine collaborative research direction, but its substantive repository activity falls outside the defined 12-month current window. It is therefore retained as historical rather than allowed to dilute the present biosignal/neural-decoding identity.

**Evidence**
- [Deciphering HRD Features in Competency](https://github.com/Hunminlee/Deciphering_HRD_features_in_competency)
- [Integrating AI-HI — HRD](https://github.com/Hunminlee/Integrating-AI-HI---HRD)
- [GitHub publication record](https://github.com/Hunminlee/Hunminlee.github.io/blob/main/publications.html)

---

## Audit interpretation rule
For promotional academic alerts, an exact title of a verified paper is strong evidence that the signal concerns this research record. A bare name match such as **Hunmin Lee**, **H. Lee**, or a similar variant is not sufficient. Ambiguous name-only alerts should remain in **Academic Signals/Needs Review** unless the email itself supplies enough title/author/venue/context evidence to establish the match.