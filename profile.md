# Research Identity Profile — Hunmin Lee

**Classification cutoff:** August 14, 2026  
**Activity window for status:** August 15, 2025–August 14, 2026

## Identity summary

Hunmin Lee is a Ph.D. candidate in Computer Science and Engineering whose research identity is centered on machine learning for biomedical and neural signals, especially robust motor/gesture decoding under distribution shift. The most representative current thread combines neural/biosignal decoding with generalization, adaptation, personalization, and meta-learning. Federated learning remains an active methodological lineage, but older IoT/communications and security applications should not be weighted as strongly as the newer biomedical and rehabilitation direction.

## Classification rules

- Use the ACM Project Classification Guide together with the ACM classification reference.
- Classify the substance of a project: its main research problem, methodology, and application—not isolated keywords, dataset names, citations, or future-work mentions.
- Use the most specific ACM node clearly supported by the evidence.
- **Current/Core:** central topic in at least two substantive GitHub projects or Notion planning/research records, with substantive activity during the 12 months ending 2026-08-14.
- **Secondary/Adjacent:** genuinely connected to active research but does not meet the recurring-evidence threshold for Current/Core.
- **Historical:** clearly supported by older completed work but with no substantive GitHub/Notion activity during the 12-month window.

## Current/Core research areas

### 1. Biomedical and neural-signal pattern recognition / motor and gesture decoding
**ACM:** I.5 Pattern Recognition; I.2.6 Learning; J.3 Life and Medical Sciences

Central problem: learning robust representations and decoders from EMG/peripheral-neural and related biosignals for gesture, motor-intent, and rehabilitation-oriented tasks.

Evidence:
- `Neural_Computing_Interface_MindForce`: peripheral radial/ulnar nerve signals, hand-gesture decoding, deep learning, and robust neural decoding; substantive GitHub activity in Oct–Dec 2025.
- `Cross-motor-decoding`: upper-limb/lower-limb motor-decoding code with repeated substantive commits in Aug–Sep 2025.
- `Upper and Lower-Limb Motor Decoding for Adaptive and Generalized Neural Rehabilitation` (IEEE TNSRE): accepted May 10, 2026; Early Access May 17, 2026.
- `Bridging Biosignals and Semantics: Cross-Modal Contrastive Learning between EMG and Text`: active manuscript/revision work in June–August 2026.

### 2. Generalization, adaptation, personalization, and meta-learning under distribution shift
**ACM:** I.2.6 Learning; I.5.1 Models / I.5.2 Design Methodology

Central problem: maintaining performance across sessions, subjects, datasets, clients, and changing environments, while enabling fast or personalized adaptation.

Evidence:
- MindForce explicitly targets inter-session generalization and plans inter-subject generalization, domain adaptation, and personalization.
- Cross-motor decoding work is organized around transfer/generalization across motor settings.
- The FPAL → FedPML → TNSRE lineage repeatedly uses prototypes, meta-learning, personalization, adaptation, and generalization.
- The active EMG-text work extends semantic representation and meta-learning toward biosignal adaptation.

### 3. Federated learning and distributed personalization under heterogeneous/non-IID data
**ACM:** C.2.4 Distributed Systems; I.2.11 Distributed Artificial Intelligence; I.2.6 Learning

Central problem: learning across heterogeneous distributed clients while improving personalization/generalization.

Evidence:
- `Federated Prototype Adaptation Learning: Personalized and Generalizable Learning in Distributed Networks` (FPAL): revision and acceptance activity Oct–Nov 2025.
- `FedPML: Federated Prototype Meta-Learning for Adaptation and Generalization in Distributed Environments`: accepted-article/production activity Dec 2025–Jan 2026.

**Identity weighting note:** Federated learning is still Current/Core as a method, but generic distributed-AI, IoT, or communications alerts should not automatically receive the same weight as biomedical/neural-decoding work. Prefer alerts connecting federated learning to personalization, generalization, biosignals, adaptive interfaces, or heterogeneous learning.

## Secondary/Adjacent research areas

### Automatic modulation classification and communications-oriented ML
Connected to the federated/prototype/meta-learning line through FPAL, FedPML, and the C-AMC submission, but the application domain is less representative of the newer biomedical/rehabilitation identity. C-AMC had a Nature Communications submission receipt on May 12, 2026, so the area is not Historical.

### Semantic / cross-modal representation learning for biosignals
Strongly connected to current EMG work, but it is represented most clearly by one active manuscript (`Bridging Biosignals and Semantics`) rather than two independent recent projects, so treat the cross-modal/semantic sub-area as Secondary/Adjacent while the broader biosignal-generalization problem is Current/Core.

### Graph/GNN methods for EMG
The `EMG-based-Gesture-Classification-using-Graphs-and-GNN` repository supports a genuine EMG/GNN branch, but its latest repository activity is from 2024. The method is related to current biosignal decoding but should not by itself define the current identity.

## Historical research areas

### AI / cybersecurity and security-oriented ML
Older internal work from 2020 included AI/cybersecurity trend analysis and an AI-security report. No substantive GitHub/Notion activity in this area appears in the 12 months ending August 14, 2026, and the collaboration audit did not tie it to a verified completed joint paper. Treat security-oriented academic matches as Historical unless a newer independent project establishes otherwise.

### Mobile crowdsourcing / broad technical distributed systems proposals
A 2021 mobile-crowdsourcing proposal is documented as an older exploratory direction with no substantive activity in the cutoff window. Treat it as Historical.

### Legacy interface-control / older hand-motion classification work
Exact-title alerts for verified older papers such as the repeated `Real-time Interface Control with Motion...` campaign are strong evidence that the message is actually about Hunmin Lee, but they represent older work and should normally be labeled Adjacent or Historical rather than Current Research unless the alert itself clearly connects to the present biomedical/generalization program.

## Gmail audit decision rules

1. **Exact paper-title evidence is strongest.** If an alert names one of Hunmin Lee's verified papers, treat it as a confirmed identity match and classify by the paper/topic status above.
2. **Name-only evidence is weak.** Alerts that mention only `Hunmin Lee`, `H. Lee`, or a similar name without a verified paper title or other independent connection go to `Academic Signals/Needs Review`.
3. **Current-topic recommendations** go to `Academic Signals/Current Research` when the recommendation substantively concerns biomedical/neural signals, EMG/motor decoding, generalization/adaptation/personalization/meta-learning, or federated heterogeneous learning consistent with the Current/Core profile.
4. **Older or secondary academic matches** go to `Academic Signals/Adjacent or Historical`, including security-oriented work, communications/AMC-only matches, legacy interface-control papers, and method-specific older branches that do not represent the current core.
5. **Generic academic-platform marketing** (premium upsells, readership/view-count teasers, broad bestseller sales, generic networking promotions) goes to `Promotions/Low Value`.
6. **Security, account, login, privacy/terms-policy, and service-account messages are left untouched.**
7. When datasets, titles, or applications differ but the underlying problem is the same, classify by the underlying central research problem rather than the surface dataset/project name.
