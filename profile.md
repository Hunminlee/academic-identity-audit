# Research Identity Profile

**Researcher:** Hunmin Lee  
**Affiliation:** PhD Candidate, Department of Computer Science and Engineering, University of Minnesota  
**Status cutoff used for this audit:** August 14, 2026  
**Activity window:** August 15, 2025–August 14, 2026

## Classification rules used

This profile separates *research-area classification* from *research-status classification*. ACM areas are assigned from the substance and central contribution of each project, using the most specific clearly supported ACM node. Current/Core, Secondary/Adjacent, and Historical status are then assigned independently using the activity rules supplied for this audit.

- **Current/Core:** central in at least two GitHub projects or Notion planning/research records, with at least one qualifying record active during the 12-month activity window.
- **Secondary/Adjacent:** genuinely connected to the active program but does not meet the recurring-evidence threshold for Current/Core.
- **Historical:** clearly supported by older completed work, with no GitHub or Notion activity found during the activity window.
- Publication-only topics without corroborating project evidence are not promoted into the active profile merely because a similarly named author appears on an academic platform.

## Current/Core

### 1. Neural and biosignal motor decoding for gesture recognition and rehabilitation

**Description.** Machine-learning systems that decode human motor intent from biosignals and peripheral neural signals, especially upper- and lower-limb gesture/movement decoding. The active emphasis is robust decoding across sessions and people, with rehabilitation and deployable neural-interface use as the main application setting.

**ACM classification:**
- **I.5.4 — Pattern Recognition: Applications**
- **J.3 — Life and Medical Sciences**

**Evidence:**
- GitHub: [Neural_Computing_Interface_MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — explicitly targets neural hand-gesture decoding, inter-session generalization, and later inter-subject generalization; qualifying commits continue through December 2025.
- GitHub: [Cross-motor-decoding](https://github.com/Hunminlee/Cross-motor-decoding) — contains upper-limb and lower-limb decoding work, with qualifying gesture/gait experiments and adaptation commits in August–September 2025.
- Notion: **Professor Daehee Seo Collaboration Audit (2020–2026)** — identifies the 2026 TNSRE motor-decoding work as the application shift into EMG/biosignal decoding and neural rehabilitation while preserving the generalization/adaptation problem.
- Publication evidence: **“Upper and Lower-Limb Motor Decoding for Adaptive and Generalized Neural Rehabilitation”** (IEEE TNSRE, 2026) and **“Few-Shot Prototype Adaptation for Generalizable Electromyography Gesture Recognition”** (2026), both present in the Google Scholar snapshot.

### 2. Adaptation, personalization, and generalization for neural/biosignal learning

**Description.** Learning under subject, session, task, and dataset shift using few-shot learning, prototype learning, meta-learning, domain adaptation, and personalization. This is treated as a separate core methodological area because it is not incidental to the biosignal application: adaptation/generalization is an explicit target across multiple active decoding projects.

**ACM classification:**
- **I.2.6 — Artificial Intelligence: Learning**
- **I.5.4 — Pattern Recognition: Applications**
- **J.3 — Life and Medical Sciences**

**Evidence:**
- GitHub: [Neural_Computing_Interface_MindForce](https://github.com/Hunminlee/Neural_Computing_Interface_MindForce) — names inter-session generalization as the current target and explicitly proposes domain adaptation and personalization.
- GitHub: [Cross-motor-decoding](https://github.com/Hunminlee/Cross-motor-decoding) — qualifying 2025 commits include few-shot adaptation alongside upper-/lower-limb gesture and gait decoding.
- Notion: **Professor Daehee Seo Collaboration Audit (2020–2026)** — describes prototype/meta-learning for adaptation under distribution shift as the durable bridge from earlier distributed-learning work to current EMG rehabilitation.
- Publication evidence: **“Few-Shot Prototype Adaptation for Generalizable Electromyography Gesture Recognition”** (2026) and **“Upper and Lower-Limb Motor Decoding for Adaptive and Generalized Neural Rehabilitation”** (2026).

## Secondary/Adjacent

### 3. Federated prototype and meta-learning for distributed personalization/generalization

**Description.** Federated learning under non-IID heterogeneity, especially prototype-based personalization, adaptation, and meta-learning. This remains methodologically close to the current decoding program, but the dedicated FedPML/FPAL GitHub repositories do not show qualifying activity inside the status window, so it does not meet the Current/Core activity threshold.

**ACM classification:**
- **I.2.11 — Artificial Intelligence: Distributed Artificial Intelligence**
- **I.2.6 — Artificial Intelligence: Learning**

**Evidence:**
- GitHub: [FedPML](https://github.com/Hunminlee/FedPML) and [Federated-Prototype-Adaptation-Learning-for-modulation-classification](https://github.com/Hunminlee/Federated-Prototype-Adaptation-Learning-for-modulation-classification).
- Notion: **Professor Daehee Seo Collaboration Audit (2020–2026)** — documents the CLSM-FL → FPAL → FedPML lineage and its methodological continuity with current adaptation/generalization work.
- Publication evidence: **“FedPML: Federated Prototype Meta-Learning for Adaptation and Generalization in Distributed Environments”** (2026), **“Federated Prototype Adaptation Learning: Personalized and Generalizable Learning in Distributed Networks”** (2025), and earlier federated-learning publications in the Google Scholar snapshot.

### 4. Graph-based representation learning for EMG gesture recognition

**Description.** Modeling spatial/temporal relationships among EMG channels with graph neural networks for accurate, generalizable, interpretable gesture recognition. It is directly related to the current biosignal program but is substantively concentrated in one older project rather than recurring across multiple qualifying active records.

**ACM classification:**
- **I.5.1 — Pattern Recognition: Models**
- **J.3 — Life and Medical Sciences**

**Evidence:**
- GitHub: [EMG-based-Gesture-Classification-using-Graphs-and-GNN](https://github.com/Hunminlee/EMG-based-Gesture-Classification-using-Graphs-and-GNN).
- Publication evidence: **“Decoding Gestures in Electromyography: Spatiotemporal Graph Neural Networks for Generalizable and Interpretable Classification”** (2024), listed in the Google Scholar snapshot.

### 5. Semantic and cross-modal biosignal representation

**Description.** Aligning biosignal classes with semantic/text representations and learning cross-modal prototypes. Evidence inside the cutoff shows a substantive active manuscript, but this direction appears in only one current research branch, so it remains adjacent rather than core.

**ACM classification:**
- **I.2.6 — Artificial Intelligence: Learning**

**Evidence:**
- Notion: **Professor Daehee Seo Collaboration Audit (2020–2026)** — records active work on **“Bridging Biosignals and Semantics: Cross-Modal Contrastive Learning between EMG and Text”**, including a June 4, 2026 reject/resubmit decision and describes Sentence-BERT semantic prototypes, contrastive alignment, and Reptile-style meta-learning.
- Later Notion context (not counted toward status because it was updated after the cutoff): **Language-Guided Biosignal Representation**.

## Historical

### 6. Wireless/IoT automatic modulation classification as a federated-learning application

**Description.** Earlier work applied federated learning, prototype adaptation, robustness, and meta-learning to non-IID IoT/distributed networks and automatic modulation classification. The methods remain relevant, but the application domain has shifted toward biosignal/neural rehabilitation.

**ACM classification:**
- **I.2.11 — Artificial Intelligence: Distributed Artificial Intelligence**
- **I.2.6 — Artificial Intelligence: Learning**

**Evidence:**
- GitHub: [Federated-Prototype-Adaptation-Learning-for-modulation-classification](https://github.com/Hunminlee/Federated-Prototype-Adaptation-Learning-for-modulation-classification) — latest activity found in 2024.
- GitHub: [FedPML](https://github.com/Hunminlee/FedPML) — latest activity found in July 2025, before the activity window.
- Notion: **Professor Daehee Seo Collaboration Audit (2020–2026)** explicitly identifies the application-domain shift from non-IID IoT/automatic modulation classification to biosignal decoding and rehabilitation.
- Publication evidence: CLSM-FL, FPAL, FedPML, FedVaccine, and related modulation/distributed-learning papers in the Google Scholar snapshot.

### 7. AI/ML analytics for Human Resource Development and social/behavioral research

**Description.** Applying machine learning and explainability to HRD competency and related social/behavioral questions. Multiple repositories establish that this was a genuine research direction, but no GitHub or Notion activity was found during the status window; the most recent HRD repository activity found was August 9, 2025, just before the window began.

**ACM classification:**
- **I.2.6 — Artificial Intelligence: Learning**
- **J.4 — Social and Behavioral Sciences**

**Evidence:**
- GitHub: [Deciphering_HRD_features_in_competency](https://github.com/Hunminlee/Deciphering_HRD_features_in_competency), [Integrating-AI-HI---HRD](https://github.com/Hunminlee/Integrating-AI-HI---HRD), and [HRD---Project2](https://github.com/Hunminlee/HRD---Project2).
- Publication evidence: **“Using Machine Learning in Human Resource Development Research: A Comprehensive Review and Future Directions”** (2026), listed in the Google Scholar snapshot. The publication date does not override the project-activity rule used for status.

### 8. Anomaly detection in smart manufacturing

**Description.** Pattern-recognition/anomaly-detection work for smart-manufacturing settings. The repository is clearly project-specific and has no activity during the status window.

**ACM classification:**
- **I.5.4 — Pattern Recognition: Applications**
- **J.6 — Computer-Aided Engineering**

**Evidence:**
- GitHub: [AD-in-Smart-Manufacturing](https://github.com/Hunminlee/AD-in-Smart-Manufacturing) — latest activity found in September 2024.

### 9. Capacitive/electric-field motion and gesture sensing

**Description.** Earlier hand-motion/gesture recognition and real-time interface-control work using non-contact capacitive or electric-potential sensing. These are verified older publications but no qualifying GitHub or Notion activity was found in the status window.

**ACM classification:**
- **I.5.4 — Pattern Recognition: Applications**

**Evidence:**
- Publication evidence in the Google Scholar snapshot includes **“Real-time Interface Control with Motion Gesture Recognition Based on Non-contact Capacitive Sensing”** (2022), **“A BPRCNN Based Hand Motion Classifier Using Electric Field Sensors”** (2022), **“Explainable Hand Motion Recognition in 3-D Capacitive Proximity Sensing”** (2024), and **“Real-Time Hand Motion Frame Extraction Using Electric Potential Sensors”** (2020).

## Evidence sources used

- Google Drive: **Hunmin_Lee_Google_Scholar_Profile_2026-08-27.pdf** — publication/profile snapshot.
- Google Drive: **ACM Classification Inventory in GitHub repositories and Notion research-planning pages** — project-to-ACM mappings.
- Google Drive: **ACM Project Classification Guide** — rules for selecting ACM level and avoiding keyword-only classification.
- Google Drive: **ACM Classification Codes** reference — hierarchy and code names used above.
- GitHub: repository contents and commit activity through the August 14, 2026 status cutoff.
- Notion: research/audit records available on or before the cutoff; post-cutoff August 19 future-planning pages are used only as contextual evidence and do not determine Current/Core status.

## Audit interpretation note

For academic-alert triage, an exact match to a verified publication title is stronger identity evidence than a name-only match to “Hunmin Lee” or “H. Lee.” Name-only matches should remain **Academic Signals/Needs Review** unless another source ties the alert to this profile. This is especially important for pharmacy, materials/sensing, medical-imaging, and social-science results, where similarly named researchers may create plausible but incorrect matches.