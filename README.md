# ProteinFM — Adaptive Multimodal Protein Representation Learning

## Overview

ProteinFM is an ongoing research framework for **adaptive multimodal
protein representation learning**, investigating how heterogeneous
protein foundation-model representations can be aligned and integrated
across evolutionary, sequence, and structural information.

The framework is designed to be **model-agnostic and modular**, allowing
representations from different pretrained protein models to be studied
within a shared representation-learning framework.

---

## Goal

Develop unified and generalizable protein representations by:

- Aligning heterogeneous pretrained protein representations
- Integrating complementary evolutionary, sequence, and structural
  information
- Adapting multimodal fusion to differences in biological information
  and representation quality
- Systematically evaluating the resulting representations across
  biological and representation-learning tasks

---

## Framework

ProteinFM currently explores three core components:

### PAEP — ProteinFM Adapter–Encoder–Projector

A modular interface for connecting heterogeneous pretrained protein
foundation models and mapping their representations into a shared
latent representation space.

### APF — Adaptive Protein Fusion

An adaptive fusion framework for integrating complementary
**evolutionary, sequence, and structural representations**.

### U₀–U₈ Evaluation Framework

A systematic evaluation framework for characterizing learned protein
representations across multiple biological and representational
dimensions.

---

## Research Direction

- Protein foundation-model interoperability
- Multimodal protein representation learning
- Sequence–structure–evolution integration
- Adaptive and confidence-aware representation fusion
- Representation quality and transferability
- Systematic biological probing and evaluation

---

## Models Under Investigation

ProteinFM is being developed and evaluated using pretrained protein
representation models including:

- ESM-2
- ProtT5
- SaProt
- GearNet

---

## Evaluation

The project investigates representation quality across several dimensions,
including:

- Biological representation quality
- Biological neighborhood structure
- Functional properties
- Mutation-fitness prediction
- Structural information
- Transferability
- Representation geometry
- Computational efficiency

Evaluation is designed around **controlled data splits, leakage
prevention, component-level comparisons, and multi-seed experiments**.

---

## Research Status

🚧 **Active research / under development**

The framework is currently being developed and evaluated. Research
methodology, implementation, and experimental results are evolving as
the project progresses.

---

## Note

This repository provides a **high-level overview of the ProteinFM
research direction**.

Detailed architectural specifications, implementation details,
unreleased experiments, and research results are intentionally not
publicly released while the work is ongoing.

Implementation details can be discussed upon request.