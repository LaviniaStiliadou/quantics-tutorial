---
title: About
layout: default

navigation_weight: 1
---

# Quantics 2026 Tutorial: Low-Code Quantum Application Development — From Visual Modeling to Quantum Execution

## About

This website hosts the official material for the tutorial **Low-Code Quantum Application Development: From Visual Modeling to Quantum Execution**, which will be held in Porto (Portugal) during the 2026 edition of the International Conference on Quantum Information, Computing, Communications and Simulation (Quantics).

---

## Abstract

Quantum applications are inherently hybrid systems, requiring tight integration between classical control software and quantum processing units. However, current quantum software engineering practices are often constrained by low-level, circuit-centric development paradigms, which limit accessibility and scalability.

This tutorial introduces **Qonstruct**, a low-code, model-driven development environment for quantum applications. Qonstruct decouples quantum application logic from hardware-specific circuit representations by enabling visual specification of quantum algorithms and automatic compilation into executable quantum circuits.

Participants will explore how model-driven engineering principles, visual programming abstractions, and automated transformation pipelines can be applied to quantum software development. The toolchain supports end-to-end workflows including model specification, transformation into OpenQASM3, validation, and execution across heterogeneous quantum backends via a middleware orchestration layer.

---

## Motivation

Quantum computing offers computational advantages for specific problem classes by leveraging quantum mechanical phenomena such as superposition and entanglement. However, practical deployment remains challenging due to the requirement of low-level circuit design and backend-specific implementation details.

To address these limitations, a shift toward higher-level abstraction mechanisms is emerging in quantum software engineering. Low-code and model-driven approaches enable domain experts to specify quantum algorithms using visual building blocks such as state preparation, oracle definitions, and diffusion operators, rather than explicit gate-level programming.

This tutorial demonstrates how such abstractions can be systematically mapped to executable quantum artifacts through automated compilation and orchestration. The result is a unified workflow that spans from visual modeling to execution on quantum hardware or simulators.

---

## Intended Audience

This tutorial is designed for software engineers, researchers, and system architects interested in quantum software development. No deep background in quantum physics or quantum circuit design is required.

Participants will benefit from basic familiarity with software engineering concepts, distributed systems, or model-driven development approaches.

---

## Technical Requirements

Participants should bring a laptop with the following prerequisites installed:

- Docker Engine and Docker Compose
- Internet access for cloning repositories and pulling containers
- A modern web browser (Chrome, Firefox, Edge, or Safari)

---

## Learning Goals

By the end of this tutorial, participants will be able to:

1. Understand the principles of model-driven and low-code quantum software engineering.
2. Construct quantum application models using a visual development environment.
3. Transform high-level models into executable OpenQASM3 representations.
4. Execute quantum workflows via a middleware-based orchestration layer across heterogeneous backends.

---

## References

[1] Stiliadou, L., Barzen, J., Bühler, F., Georg, D., Stiliadou, S.-N.: Low-Code Quantum Algorithm Modeling and Execution for Hybrid Cloud Environments. In: Proceedings of the 16th International Conference on Cloud Computing and Services Science. SciTePress (2026).

[2] Stiliadou, L., Barzen, J., Bühler, F., Georg, D.: A Multi-Domain Quantum Low-Code Platform. In: Proceedings of the 1st International Conference on Quantum Information, Computing, Communication, and Simulation. Springer (2026).

[3] Weder, B., Barzen, J., Beisel, M., Bühler, F., Georg, D., Leymann, F., Stiliadou, L.: Qunicorn: A Middleware for the Unified Execution Across Heterogeneous Quantum Cloud Offerings. In: Proceedings of the 2025 IEEE/ACM International Workshop on Quantum Software Engineering (Q-SE), pp. 17–24. IEEE (2025).