---
title: "Quantum Materials Hands-On Training at the NSF QC4MC Summer School at Arizona State University"
date: 2026-06-18
EventDate: "Jun 18, 2026"
ShortSummary: "Hanna Terletska led a talk and hands-on session on modeling quantum materials for students and researchers at the 2026 NSF CyberTraining QC4MC Summer School at Arizona State University."
images:
    - /images/outreach/asu-qc4mc-2026/room.jpg
hide_gallery: true
---
![Summer school participants at ASU (left) during the online session with Hanna Terletska (right).](/images/outreach/asu-qc4mc-2026/room.jpg)

*Summer school participants at ASU (left) during the online session with Hanna Terletska (right).*

On June 18, 2026, TN-QuMat lead Hanna Terletska, Professor of Physics and Director of the QRISE Center at Middle Tennessee State University (MTSU), gave an invited talk and hands-on training on modeling quantum materials at the 2026 NSF CyberTraining Quantum Computing for Materials Science and Chemistry (QC4MC) Summer School at Arizona State University (ASU).

The four-day school, held June 16–19 on ASU's Tempe campus, was led by David Liu of Purdue University and Houlong Zhuang of ASU and supported by the National Science Foundation (award 2417293). It brought together upper-level undergraduates, graduate students, researchers, and faculty from Arizona universities and colleges to build quantum computing skills for research in materials science and chemistry. Terletska joined the program online.

## Why Quantum Materials Are Hard to Model

In her session, “Modeling and Tuning Quantum Materials Properties Across Phase Transitions: from Complexity to Control,” Terletska explained why quantum materials are central to new technologies and why they are challenging to study. She showed how computational modeling connects simple models to observed phenomena, and how properties can be tuned across phase transitions.

![Title slide of the presentation](/images/outreach/asu-qc4mc-2026/title.jpg)

![Quantum materials can be tuned: changing temperature or doping drives transitions between new phases, including superconductivity.](/images/outreach/asu-qc4mc-2026/tuning.jpg)

*Quantum materials can be tuned: changing temperature or doping drives transitions between new phases, including superconductivity.*

![The modeling approach: start with the simplest model, then add disorder or interactions to capture new physics.](/images/outreach/asu-qc4mc-2026/hamiltonians.jpg)

*The modeling approach: start with the simplest model, then add disorder or interactions to capture new physics.*

## Learning by Doing

Participants then worked through the ideas themselves using Google Colab notebooks. The notebooks grew out of the hands-on training developed for the TN-QuMat Workshop in 2025.

- **Part 1: non-interacting electrons.** Participants followed one recipe: build a Hamiltonian, diagonalize it, find the allowed energies, and compute the density of states to decide whether a system is a metal or an insulator. They applied it to three models of rising complexity: a tight-binding chain, a dimerized (SSH) chain, and a chain with random disorder.
- **Part 2: interacting electrons.** Adding electron-electron interactions makes exact calculations impractical beyond about 16 to 20 sites. Participants used the ALPS software package and dynamical mean-field theory (DMFT) to simulate the Mott metal-insulator transition in the Hubbard model.

![The three models participants explored, from a uniform chain to random disorder.](/images/outreach/asu-qc4mc-2026/models.jpg)

*The three models participants explored, from a uniform chain to random disorder.*

![Results from the hands-on session: the density of states shows whether each model is a metal or an insulator.](/images/outreach/asu-qc4mc-2026/dos.jpg)

*Results from the hands-on session: the density of states shows whether each model is a metal or an insulator.*

![The Mott transition in the Hubbard model: as the interaction U increases, a metal becomes a Mott insulator.](/images/outreach/asu-qc4mc-2026/mott.jpg)

*The Mott transition in the Hubbard model: as the interaction U increases, a metal becomes a Mott insulator.*

Sharing this training beyond Tennessee is part of TN-QuMat's commitment to expanding access to hands-on quantum science education and building connections with programs across the country. TN-QuMat thanks David Liu and Houlong Zhuang for the invitation.

Learn more about the summer school on the [program website](https://sites.google.com/asu.edu/qc4mc/home) and in [ASU's article about the program](https://semte.engineering.asu.edu/?p=3337).

## Acknowledgment

TN-QuMat is supported by the U.S. Department of Energy RENEW program under award DE-SC0025748. For more about TN-QuMat, visit https://tn-qumat.org.
