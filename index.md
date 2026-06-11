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

Quantum application development remains a complex and highly specialized task. Developers must not only understand quantum algorithms but also implement them using provider-specific SDKs, quantum programming languages, and execution environments. As the quantum ecosystem continues to diversify, maintaining and porting applications across different platforms introduces significant engineering overhead.

This tutorial introduces Qonstruct, a low-code development environment that aims to accelerate quantum application engineering by raising the level of abstraction above individual SDKs and circuit representations. Instead of manually implementing quantum programs in frameworks such as Qiskit, Braket, or other provider-specific toolchains, developers can visually model quantum applications and automatically generate executable artifacts.

Participants will learn how low-code techniques can be applied to quantum software development to improve productivity, portability, and maintainability. The tutorial demonstrates an end-to-end workflow from visual application modeling and automated artifact generation to execution across heterogeneous quantum backends through a middleware orchestration layer.

---

## Motivation

Despite significant advances in quantum hardware and software ecosystems, quantum application development remains largely code-centric. Implementing a quantum algorithm typically requires expertise in multiple layers of the stack, including quantum algorithm design, provider-specific SDKs, circuit representations, and execution workflows.

Furthermore, the growing diversity of quantum platforms has resulted in fragmented development environments. Developers often need to reimplement or adapt applications for different SDKs, intermediate representations, and execution targets, increasing development effort and reducing portability.

To address these challenges, higher-level engineering approaches are needed. Inspired by established practices in software engineering, model-driven and low-code techniques enable developers to focus on application logic rather than implementation details. Quantum algorithms can be specified as reusable, platform-independent models, which are then automatically transformed into executable artifacts such as OpenQASM 3 programs and deployment workflows.


---

## Intended Audience

This tutorial targets researchers, quantum software engineers, software architects, and practitioners who already possess a basic understanding of quantum computing and quantum algorithms.

Participants interested in improving development productivity, managing platform heterogeneity, and applying software engineering principles to quantum applications will benefit most from the tutorial. Prior experience with quantum SDKs such as Qiskit, Braket, Cirq, or similar frameworks is helpful but not required.

---

## Learning Goals

By the end of this tutorial, participants will be able to:

* Understand the challenges of developing and maintaining quantum applications across heterogeneous software ecosystems.
* Apply model-driven engineering principles to quantum software development.
* Create platform-independent quantum application models using a visual development environment.
* Automatically generate executable quantum artifacts, including OpenQASM 3 representations and workflow definitions.
* Execute quantum applications across different backends using a unified orchestration middleware.
* Evaluate how low-code and model-driven approaches can accelerate quantum software engineering workflows.

---

## Technical Requirements

Participants should bring a laptop with the following prerequisites installed:

- Docker Engine and Docker Compose
- Internet access for cloning repositories and pulling containers
- A modern web browser (Chrome, Firefox, Edge, or Safari)

---

## References

[1] Stiliadou, L., Barzen, J., Bühler, F., Georg, D., Stiliadou, S.-N.: Low-Code Quantum Algorithm Modeling and Execution for Hybrid Cloud Environments. In: Proceedings of the 16th International Conference on Cloud Computing and Services Science. SciTePress (2026).

[2] Stiliadou, L., Barzen, J., Bühler, F., Georg, D.: A Multi-Domain Quantum Low-Code Platform. In: Proceedings of the 1st International Conference on Quantum Information, Computing, Communication, and Simulation. Springer (2026).

[3] Weder, B., Barzen, J., Beisel, M., Bühler, F., Georg, D., Leymann, F., Stiliadou, L.: Qunicorn: A Middleware for the Unified Execution Across Heterogeneous Quantum Cloud Offerings. In: Proceedings of the 2025 IEEE/ACM International Workshop on Quantum Software Engineering (Q-SE), pp. 17–24. IEEE (2025).