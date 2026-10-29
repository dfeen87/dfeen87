
<div align="center">

  <h1>👋 Hello, I'm Don.</h1>

  <h3>
    I build with curiosity, care, and scientific rigor.
  </h3>

  <p>
    <strong>
      Design Top-Down. Verify Bottom-Up. Iterate Across.
    </strong>
  </p>

  <p>
    <img
      src="Cinematic Billiards Under Blue Glass.png"
      width="420"
      alt="Cinematic Billiards Under Blue Glass"
    />
  </p>

  <p>
    <em>
      Independent research, guided by a love of building.
    </em>
  </p>

</div>

---

I build systems where **AI, software, and the physical world** meet.

**I develop and maintain open-source software released under the MIT License.**

What drives me is a simple question:

**How can we make powerful technology understandable, dependable, and worthy of trust?**

I work toward that by setting clear boundaries, making decisions traceable, preparing for failure, and letting evidence speak for the work.

---

### My Engineering Philosophy

I begin with a vision of what a system should accomplish, then work downward through its architecture, features, and user experience.

I believe the user experience should inform the design from the beginning, not simply emerge after the underlying logic is implemented.

As development progresses, I move continuously between interface design, application logic, and data architecture. Each layer challenges and informs the others, revealing constraints, opportunities, and sometimes entirely new ideas.

I verify from the foundations upward, allowing evidence and discovered invariants to challenge my original assumptions.

**Design establishes the vision. Verification establishes what is true. Iteration connects the two.**

---

## **Research Program**

The projects take different paths, but the engineering commitments behind them are shared:

- **Governance and context** — trust membranes, attributable context transfer, policy constraints, and bounded behavior for agentic systems.
- **Runtime and verification** — deterministic pipelines, distributed and verifiable computation, reproducible evaluation, and explicit failure handling.
- **Physical and embedded systems** — computer vision, smart glasses, EV and battery systems, biosignals, and other interfaces where computational decisions meet the physical world.
- **Mathematical and scientific foundations** — nonlinear dynamics, phase memory, invariant-driven modeling, simulation, and falsifiable reference implementations.
- **Interoperability** — practical bridges between legacy and modern compute without hiding system state or weakening governance boundaries.

Different projects, one recurring challenge: **how can we make complex systems useful without losing the ability to understand, test, and recover them?**

### Engineering Architecture

<p align="center">
  <img src="5 Stage.png" width="620" alt="5 Stage">
</p>

Governance defines permitted action and establishes the boundaries of the system; context supplies attributable state; runtimes execute within those boundaries; verification continuously informs and refines governance; and physical systems provide the ultimate real-world test of whether the architecture behaves as intended.

<p align="center">
  <img src="5 updown.jpeg" width="620" alt="5 Stage">
</p>

This engineering philosophy establishes a continuous relationship between architectural design, implementation, and verification. Top-down design begins with the intended outcome, defining system responsibilities, interfaces, and invariants before implementation. Bottom-up verification validates individual components, their contracts, and their integration into the complete system. Iteration across connects these processes through incremental, end-to-end feature development, allowing the architecture to evolve as deeper requirements and invariants emerge. The objective is not simply to produce functional code, but to build systems that remain understandable, testable, maintainable, and adaptable as complexity grows.

---

## **Noteworthy and favorite Repositories**

These repositories in this GitHub are my independent research workshop, spanning software, hardware, mathematics, music, animation, and scientific tools. I enjoy following difficult questions across disciplines, then doing the careful work to make each idea testable, reproducible, and useful to others.

**Where to start:** Follow what sparks your curiosity. **AILEE Trust Layer**, **Context Broker**, **Ambient AI + VCP System**, and **U.F.O.** explore how intelligent systems can remain trustworthy, understandable, and accountable. **AeroCam** and **DS-EV** bring computation closer to physical engineering, while **ISLA** and **ZORG Animation Engine** explore what engineering can express through sound, motion, and mathematics. Each project stands on its own, inviting exploration from a different perspective.

| **Repository** | **What it explores** |
|---|---|
| **[AILEE Trust Layer](https://github.com/dfeen87/AILEE-Trust-Layer)** | An adaptive trust and governance middleware architecture that evaluates AI-generated decisions before they become system actions. Integrates deterministic trust scoring, confidence thresholds, contextual mediation (GRACE), distributed consensus, auditable decision pathways, and stability-preserving fallback mechanisms across multiple computational and industrial domains. |
| **[Ambient AI + VCP System](https://github.com/dfeen87/Ambient-AI-VCP-System)** | A distributed, verifiable computing architecture coordinating heterogeneous devices, AI workloads, and decentralized processing resources through a unified orchestration framework. Combines node-health intelligence, trust-based task scheduling, cryptographic verification with zero-knowledge proofs, and resilient offline-first operating capabilities. |
| **[AeroCam](https://github.com/dfeen87/AeroCam)** | A multidisciplinary C++ engineering framework exploring real-time motion intelligence, embedded control systems, inertial sensor fusion, and computational camera stabilization. Integrates ARM Cortex-M firmware, Extended Kalman Filtering, OpenFX video-processing tools, and experimental motion-aware computer vision applications for aerospace, filmmaking, and augmented reality. |
| **[ISLA](https://github.com/dfeen87/ISLA)** | An experimental digital audio signal-processing platform investigating phase-aware note smoothing, harmonic blending, and perceptually connected musical transitions. Combines offline WAV processing, real-time macOS system-audio monitoring, and interactive terminal and desktop interfaces with Velvet, Legato, Melt, and transparent Bypass listening modes. |
| **[U.F.O.](https://github.com/dfeen87/UFO)** | A governed, compute-aware AI architecture modeling adaptive behavior and computational constraints through a deformable radial membrane and dynamically routed V-Channels. Integrates bounded reasoning, geometric stability control, behavioral governance, trust memory, adaptive recurrence, and auditable simulation to investigate computationally responsible AI personalization. |
| **[Context Broker](https://github.com/dfeen87/Context-Broker)** | A vendor-neutral context-interoperability framework supporting controlled information exchange between AI systems, software applications, and connected devices. Uses explicitly authorized, time-bounded, attributable context packets with deterministic expiration, provenance tracking, and ALCOA-oriented auditability to reduce uncontrolled persistence and cross-system ambiguity. |
| **[DS-EV](https://github.com/dfeen87/DS-EV)** | A research-stage electric-vehicle battery intelligence and energy-governance architecture investigating dual-state battery modeling, degradation estimation, regenerative-energy management, and battery-aware power control. Combines C++/Python simulation, safety-boundary enforcement, energy-continuity accounting, and auditable BMS middleware, with physical vehicle validation remaining outside its established capabilities. |
| **[ZORG-Animation-Engine](https://github.com/dfeen87/ZORG-Animation-Engine)** | Exploring the intersection of mathematics, motion, and visual expression through procedural geometry, governed numerical dynamics, and reproducible simulation. Transforming mathematical fields and computational principles into expressive visual forms, advancing new possibilities in animation and creative computing. |

---

## **Engineering Principles**

**Reproducibility is a foundation of my engineering, not simply an objective I hope to achieve.** I build with documented methods, repeatable processes, rigorous testing, and evidence that others can examine, reproduce, and challenge. I take pride in this foundation while recognizing there is always more to learn, question, and improve.

Whatever I'm building, these are the qualities I work toward:

- **Interpretable** — important state and decision boundaries are visible.
- **Deterministic where it matters** — identical inputs and conditions support reproducible evaluation.
- **Auditable** — actions, transitions, and provenance leave inspectable records.
- **Falsifiable** — research claims can be tested against simulations, benchmarks, or explicit invariants.
- **Fail-safe** — unsafe transitions are constrained and fallback paths remain available.
- **Composable** — governance, context, runtime, and verification can evolve without collapsing their boundaries.

The work is research-stage unless a repository states otherwise. I use terms such as *reference implementation*, *simulation*, and *validated benchmark* deliberately so that exploratory results are not mistaken for production claims.

---

## **Background**

My perspective is shaped by hands-on manufacturing, quality work, technical writing, and independent research. They've taught me that good engineering involves not just getting something to work, but making it clear, dependable, and considerate of the people who rely on it.

- **Quality, Manufacturing & Validation** — Technical Writing, Assembly, Logistics
- **Systems & Research Writing** — Grants, Business Development
- **Independent Research** — agentic-AI, biosignal modeling, deterministic systems, reproducible scientific infrastructure

---

## College Education

- **Pennsylvania State University** — B.S. Business, Marketing and Management

Currently pursuing graduate school, my decision to pursue Applied Science in Computer Science with a focus in Cybersecurity is rooted in a desire to strengthen the foundations behind the systems I've already built. Through independent research, software development, and experimentation with artificial intelligence, I've learned that some of the most valuable opportunities for improvement come from understanding the fundamentals I may have overlooked. As I pursue advanced study, I intend to apply what I learn directly to my existing repositories, gradually improving their architecture, reliability, security, and performance. My goal isn't to replace my previous work, but to build upon it — allowing my portfolio to evolve alongside my education.

---

## **Nonprofit Work**

- **World Food Programme** — Financial Donor
- **American Red Cross** — Platelet Donor

---

## Member of Information Physics Institute

An international research organization exploring the fundamental role of information in physics, computing, and the universe. I'm proud to be part of a community that brings together curious minds, encourages scientific inquiry, and explores questions that cross traditional disciplines. 

https://www.informationphysicsinstitute.org/

---

## Publications & Research

**[A Proof-of-Concept Deterministic Phase-Memory Operator for Respiratory Instability Detection Using Chest-Mounted Smartphone IMU Signals](https://doi.org/10.47852/bonviewSWT62029484)**

<details>
<summary><strong>Details</strong></summary>

**Research Area:** Respiratory Instability Detection

**Status:** Published · Peer-Reviewed

**Journal:** *Smart Wearable Technology*

**Publication Date:** May 13, 2026

**DOI:** [10.47852/bonviewSWT62029484](https://doi.org/10.47852/bonviewSWT62029484)

### Research Overview

Co-authored with Marcel Krüger, this peer-reviewed research introduces a deterministic phase-memory framework for identifying changes in respiratory patterns using chest-mounted smartphone motion sensors.

Rather than relying on opaque machine-learning models, the proposed method measures deviations between instantaneous respiratory phase velocity and its short-term history, enabling transparent, reproducible, threshold-based detection.

The framework was evaluated using five publicly available respiratory recordings with controlled breathing irregularities, including frequency drift, intermittent pauses, and burst-like disturbances. Experimental results demonstrated reproducible responses to these perturbations, while the reference Python implementation processed 60-second respiratory signals in approximately 2.37 milliseconds.

### My Contributions

My contributions included software engineering, computational validation, methodology, and reproducibility infrastructure.

### Scientific Significance

The study establishes a foundation for further investigation of lightweight, interpretable wearable sensing, while explicitly distinguishing proof-of-concept feasibility from clinical validation.

### Research Resources

**Source Code:** [Smartphone-Based Chest Monitoring](https://github.com/dfeen87/Smartphone-Based-Chest-Monitoring)

</details>

**[Information-Theoretic Modeling of Neural Coherence via Triadic Spiral-Time Dynamics: A Framework for Neurodynamic Collapse](https://doi.org/10.47852/bonviewMEDIN62029043)**

<details>
<summary><strong>Details</strong></summary>

**Research Area:** Neural Coherence & Spiral-Time Dynamics

**Status:** Published · Peer-Reviewed

**Journal:** *Medinformatics*

**Publication Date:** April 3, 2026

**DOI:** [10.47852/bonviewMEDIN62029043](https://doi.org/10.47852/bonviewMEDIN62029043)

### Research Overview

Co-authored with Marcel Krüger and Marcel Theodor Wende, this peer-reviewed theoretical research introduces a unified information-theoretic and geometric framework for investigating neural coherence, cognitive organization, and transitions between stable and unstable neurodynamic states.

The study integrates the Helix–Light–Vortex (HLV) triadic spiral-time operator, the DLHR multi-layer psychological architecture, and proposed neurophotonic coupling mechanisms into a common mathematical formulation.

By examining relationships between temporal dynamics, emotional regulation, memory, identity, and phase coherence, the framework establishes testable hypotheses for future computational and experimental investigation.

Potential validation pathways include electroencephalography (EEG), magnetoencephalography (MEG), heart-rate variability, and advanced quantum-sensing methods. The accompanying EEG analysis offers an exploratory illustration of selected model quantities rather than definitive validation of the full theoretical framework.

### My Contributions

My credited contributions included conceptualization and scientific manuscript review and editing.

### Scientific Significance

The research proposes a theoretical foundation for investigating relationships between information dynamics, temporal organization, and neural coherence.

Its scientific value lies in establishing mathematical representations and hypotheses that can be examined through future computational and experimental studies. The complete framework remains subject to further empirical validation.

### Research Resources

**Research Code:** [NeuroDynamics Collapse Validation](https://github.com/nwycomp/NeuroDynamics-Collapse-Validation-/blob/main/eeg-part-four.ipynb)

**Archived Research Data:** [Zenodo — 10.5281/zenodo.17990696](https://doi.org/10.5281/zenodo.17990696)

</details>

**Deterministic Spiral-Time Governance for Safe Execution Filtering under Hallucinations in LLM-Controlled Climbing and Walking Robots**

<details>
<summary><strong>Details</strong></summary>

**Research Area:** Deterministic Governance for Embodied AI

**Status:** Accepted for Publication

**Journal:** *Journal of Climbing and Walking Robots*

**DOI:** Forthcoming

### Research Overview

Co-authored with Marcel Krüger, this research introduces a deterministic Spiral-Time Governor designed to improve execution safety in climbing and walking robots controlled by Large Language Models (LLMs).

Rather than modifying the underlying language model, the framework introduces an external supervisory layer that evaluates proposed actions and environmental claims against verifiable system information.

A deterministic instability function combines structural, informational, and contextual coherence deviations with temporal changes to regulate three operating modes: **EXECUTE, VERIFY, and SAFE**.

The research establishes a formal supervisory architecture, a discrete Lyapunov-based boundedness argument under defined assumptions, and a reproducible experimental framework.

Evaluation includes controlled synthetic simulations involving climbing, stair navigation, and gap traversal, followed by physics-grounded validation using a MuJoCo quadruped environment.

In the MuJoCo proof of concept, the governor reduced average safety violations from **11.4 to 4.7 per episode**, representing approximately a **59% reduction**, without changing the simulated hallucination rate.

These results demonstrate the potential value of deterministic execution filtering while distinguishing simulation-based validation from proven safety on physical robotic hardware.

### My Contributions

My contributions included implementation of the simulation testbed, experimental execution, data generation, statistical evaluation, computational validation, and technical feedback during manuscript refinement.

### Scientific Significance

The study investigates how deterministic governance can provide an auditable safety layer between probabilistic language-model outputs and robotic execution.

Its central contribution is an interpretable, model-agnostic supervisory architecture that applies explicit constraints and verification procedures before proposed actions are executed.

The simulated results suggest that execution-level safety filtering can reduce unsafe actions without requiring changes to the underlying language model.

Further validation on physical robotic hardware remains necessary to establish real-world safety and reliability.

### Research Resources

**Research Manuscript:** [PAPER.md](https://github.com/dfeen87/STG-Embodied-POC/blob/main/PAPER.md)

**Source Code:** [STG Embodied Proof of Concept](https://github.com/dfeen87/STG-Embodied-POC)

</details>

**Detection of Solar Plasma Instabilities Using Multi-Channel GOES Observations: Toward Early Solar Flare Forecasting**

<details>
<summary><strong>Details</strong></summary>

**Research Area:** Solar-Flare Analysis & Scientific Verification

**Status:** Under Peer Review

**Journal:** *Archives of Advanced Engineering Science*

### Research Overview

Co-authored with Marcel Krüger, this ongoing research investigates solar X-ray variability and its relationship to solar-flare activity using observations from the Geostationary Operational Environmental Satellites (GOES).

The study explores computational methods for characterizing changes in solar activity while examining the scientific and methodological challenges involved in interpreting observational patterns as potential forecasting indicators.

The research incorporates computational signal analysis, mathematical evaluation, and reproducibility-focused verification to investigate relationships between solar variability, historical flare activity, and the interpretation of observational evidence.

Particular attention is given to distinguishing retrospective associations from genuine predictive information, evaluating methodological limitations, and ensuring that scientific conclusions remain consistent with the evidence available.

### My Contributions

My contributions include computational implementation, data processing, software validation, reproducibility infrastructure, methodological investigation, and technical analysis supporting the peer-review revision.

I have contributed to examining experimental assumptions, reconstructing computational procedures, verifying historical results, and developing reproducible approaches to evaluating the research findings.

### Scientific Significance

The research examines the methodological challenges involved in evaluating computational indicators of solar-flare activity and their potential relevance to forecasting.

An important objective is to distinguish reproducible numerical results from the scientific interpretations those results can legitimately support.

The ongoing revision emphasizes transparent reporting, careful treatment of experimental uncertainty, and the scientific value of both negative and inconclusive findings.

Rather than treating predictive performance as an assumed outcome, the study prioritizes evidence-based interpretation and the identification of methodological questions that can guide future controlled investigations.

### Research Status

The manuscript is undergoing peer-review revision, with its scientific objectives and interpretations being refined in response to editorial and reviewer feedback.

Final conclusions, manuscript details, and publication information remain subject to completion of the review process.

</details>

---

<div align="center">

  <h3>Thank you for reading my GitHub README.</h3>

  <p>
    <img
      src="Brulemon.gif"
      width="160"
      alt="Brulemon"
    />
  </p>

  <p>
    <img
      src="Autumn Lakeside Flag Under Blue Skies.png"
      width="420"
      alt="American flag overlooking Lake Galena beneath blue skies"
    />
  </p>

  <p>
    <em>
      A photograph I took at Lake Galena,
      a beautiful park in historic Bucks County, Pennsylvania.
    </em>
  </p>

</div>
