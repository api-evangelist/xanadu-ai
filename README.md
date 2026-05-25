# Xanadu (xanadu-ai)
Xanadu is a Canadian photonic quantum computing company building room-temperature, fault-tolerant, scalable quantum computers based on photonic continuous-variable (CV) and Gaussian boson sampling architectures. Xanadu maintains a large open-source software stack — most notably PennyLane (the cross-platform framework for quantum differentiable programming, quantum chemistry, and quantum machine learning), Catalyst (a JIT/MLIR compiler for hybrid quantum-classical programs), the PennyLane Lightning family of high-performance state-vector and tensor-network simulators, the PennyLane Plugin ecosystem (Qiskit/IBM, AWS Braket, Cirq, Rigetti, IonQ, AQT, Quantinuum, Qulacs, ProjectQ, and Xanadu's own Strawberry Fields), MrMustard, Jet, FlamingPy, The Walrus, Blackbird (the CV quantum assembly language), XIR, and the Xanadu Quantum Codebook. Xanadu hardware milestones include the X8 photonic chip, Borealis (quantum advantage demonstration on a 216-mode programmable Gaussian boson sampler), and Aurora (the first modular, networked photonic quantum computer combining server racks and kilometres of optical fibre). The Xanadu Cloud — the original photonic-hardware-as-a-service offering with REST/Python/CLI access to Borealis and X8 — has been retired (the `xanadu-cloud-client` and Strawberry Fields repos are archived), and Xanadu's developer-facing surface today centres on the PennyLane Python ecosystem and hardware execution via PennyLane plugins against partner cloud platforms.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/xanadu-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Quantum Computing, Photonic Quantum, Quantum Machine Learning, Quantum Chemistry, Differentiable Programming, PennyLane, Open Source, Compilers, Simulators, Continuous Variable, Gaussian Boson Sampling, Fault Tolerance

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### PennyLane
PennyLane is the flagship open-source Python framework for quantum differentiable programming — train and optimize variational quantum circuits with the same automatic differentiation engines used in classical machine learning. PennyLane unifies quantum machine learning, quantum chemistry, and hybrid quantum-classical workflows behind a single device-abstraction API, interoperates with NumPy, PyTorch, JAX, and TensorFlow/Keras, and runs against 40+ simulators and hardware backends through its plugin ecosystem. Apache 2.0 licensed. 3,200+ GitHub stars.

**Human URL:** [https://pennylane.ai](https://pennylane.ai)

- [Documentation](https://docs.pennylane.ai/en/stable/)
- [API Reference](https://docs.pennylane.ai/en/stable/code/qml.html)
- [GitHub Repository](https://github.com/PennyLaneAI/pennylane)
- [PyPI](https://pypi.org/project/PennyLane/)
- [Tutorials](https://pennylane.ai/qml/demonstrations)
- [Code Examples — Demos](https://github.com/PennyLaneAI/demos)

### PennyLane Catalyst
Catalyst is a JIT compiler for hybrid quantum programs written in PennyLane. The `@qjit` decorator compiles entire quantum-classical workflows — including conditionals, loops, and gradients — to a custom MLIR quantum dialect, then lowers to LLVM and QIR for execution against Lightning, AWS Braket, and an expanding set of QPUs. Apache 2.0.

**Human URL:** [https://docs.pennylane.ai/projects/catalyst](https://docs.pennylane.ai/projects/catalyst)

- [Documentation](https://docs.pennylane.ai/projects/catalyst/en/stable/)
- [GitHub Repository](https://github.com/PennyLaneAI/catalyst)
- [PyPI](https://pypi.org/project/PennyLane-Catalyst/)

### PennyLane Lightning
The Lightning plugin family — `lightning.qubit` (C++ CPU), `lightning.gpu` (cuQuantum), and `lightning.kokkos` (multi-architecture HPC) — provides Xanadu's fast state-vector and tensor-network simulators for PennyLane. Designed for 20+ qubit research workflows and HPC integration.

**Human URL:** [https://docs.pennylane.ai/projects/lightning](https://docs.pennylane.ai/projects/lightning)

- [Documentation](https://docs.pennylane.ai/projects/lightning/en/stable/)
- [GitHub Repository](https://github.com/PennyLaneAI/pennylane-lightning)
- [PyPI](https://pypi.org/project/PennyLane-Lightning/)

### PennyLane Plugins
The PennyLane plugin layer exposes a uniform `qml.device` interface across third-party quantum SDKs and QPU clouds — IBM Qiskit / IBM Quantum, AWS Braket, Google Cirq, Rigetti Forest, IonQ, AQT, Quantinuum (Honeywell), Microsoft QDK / Q#, Qulacs, ProjectQ, Zapata Orquestra, and Xanadu Strawberry Fields. Each plugin is a separate pip-installable Python package.

**Human URL:** [https://pennylane.ai/plugins](https://pennylane.ai/plugins)

- [Documentation](https://pennylane.ai/plugins)
- [GitHub — pennylane-qiskit](https://github.com/PennyLaneAI/pennylane-qiskit)
- [GitHub — pennylane-cirq](https://github.com/PennyLaneAI/pennylane-cirq)
- [GitHub — pennylane-rigetti](https://github.com/PennyLaneAI/pennylane-rigetti)
- [GitHub — PennyLane-IonQ](https://github.com/PennyLaneAI/PennyLane-IonQ)
- [GitHub — pennylane-aqt](https://github.com/PennyLaneAI/pennylane-aqt)
- [GitHub — pennylane-honeywell](https://github.com/PennyLaneAI/pennylane-honeywell)
- [GitHub — pennylane-qulacs](https://github.com/PennyLaneAI/pennylane-qulacs)
- [GitHub — pennylane-pq](https://github.com/PennyLaneAI/pennylane-pq)
- [GitHub — PennyLane-qsharp](https://github.com/PennyLaneAI/PennyLane-qsharp)
- [GitHub — pennylane-orquestra](https://github.com/PennyLaneAI/pennylane-orquestra)
- [GitHub — pennylane-sf](https://github.com/PennyLaneAI/pennylane-sf)

### PennyLane Quantum Chemistry (qchem)
`qml.qchem` is PennyLane's quantum chemistry submodule for constructing molecular Hamiltonians, differentiable Hartree-Fock, VQE workflows, and resource estimation against fault-tolerant algorithms, integrated with PennyLane's autodiff stack.

**Human URL:** [https://docs.pennylane.ai/en/stable/code/qml_qchem.html](https://docs.pennylane.ai/en/stable/code/qml_qchem.html)

- [Documentation](https://docs.pennylane.ai/en/stable/code/qml_qchem.html)
- [Tutorials](https://pennylane.ai/qml/whatisqchem)

### PennyLane Datasets
A curated catalogue of pre-computed quantum datasets — molecular Hamiltonians, spin systems, QML benchmarks — accessible via `qml.data.load(...)` for reproducible experiments and education.

**Human URL:** [https://pennylane.ai/datasets](https://pennylane.ai/datasets)

- [Documentation](https://pennylane.ai/datasets)
- [API Reference](https://docs.pennylane.ai/en/stable/code/qml_data.html)
- [GitHub Repository](https://github.com/PennyLaneAI/DatasetsSource)

### Strawberry Fields
Strawberry Fields is Xanadu's full-stack Python library for designing, simulating, and optimizing continuous-variable (CV) photonic quantum circuits. Historically the bridge from Python to Xanadu's X8 and Borealis hardware via the Xanadu Cloud. The repository is now archived following the Xanadu Cloud retirement; remains useful as an educational/simulator stack for CV quantum optics.

**Human URL:** [https://strawberryfields.ai](https://strawberryfields.ai)

- [Documentation](https://strawberryfields.ai/photonics/)
- [GitHub Repository](https://github.com/XanaduAI/strawberryfields)
- [PyPI](https://pypi.org/project/StrawberryFields/)

### MrMustard
MrMustard is a differentiable simulator that acts as a bridge between phase-space and Fock-space representations of bosonic / CV quantum systems. Built for design and optimization of photonic circuits with gradient-based methods.

**Human URL:** [https://mrmustard.readthedocs.io](https://mrmustard.readthedocs.io)

- [Documentation](https://mrmustard.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/MrMustard)
- [PyPI](https://pypi.org/project/mrmustard/)

### The Walrus
The Walrus is a high-performance C++/Python library for computing hafnians, loop hafnians, Hermite polynomials, and Gaussian boson sampling probabilities — the numerical backbone underpinning Xanadu's photonic simulations.

**Human URL:** [https://the-walrus.readthedocs.io](https://the-walrus.readthedocs.io)

- [Documentation](https://the-walrus.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/thewalrus)
- [PyPI](https://pypi.org/project/thewalrus/)

### Jet
Jet is a cross-platform C++ library for simulating quantum circuits via tensor-network contractions, with task-based parallelism for HPC-scale workloads.

**Human URL:** [https://quantum-jet.readthedocs.io](https://quantum-jet.readthedocs.io)

- [Documentation](https://quantum-jet.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/jet)

### FlamingPy
FlamingPy is a Python library with multiple backends for efficient simulation of error correction in fault-tolerant photonic quantum architectures, including GKP-encoded qubit cluster states. Archived.

**Human URL:** [https://flamingpy.readthedocs.io](https://flamingpy.readthedocs.io)

- [Documentation](https://flamingpy.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/flamingpy)

### Blackbird Language
Blackbird is Xanadu's quantum assembly language for continuous-variable photonic quantum computation. Programs target Strawberry Fields simulators and were historically deployed against the X8 / Borealis hardware via Xanadu Cloud.

**Human URL:** [https://strawberryfields.ai/photonics/blackbird/](https://strawberryfields.ai/photonics/blackbird/)

- [Documentation](https://quantum-blackbird.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/blackbird)

### XIR
XIR is an intermediate representation language for quantum circuits, designed to ferry circuits between front-end frameworks (Strawberry Fields, PennyLane) and backend hardware/simulators.

**Human URL:** [https://xir.readthedocs.io](https://xir.readthedocs.io)

- [Documentation](https://xir.readthedocs.io/en/latest/)
- [GitHub Repository](https://github.com/XanaduAI/xir)

### Xanadu Quantum Codebook
An interactive, free, browser-based quantum computing course built on PennyLane. Covers introductory quantum computing, single- and multi-qubit systems, quantum algorithms, and quantum chemistry with executable code cells.

**Human URL:** [https://pennylane.ai/codebook](https://pennylane.ai/codebook)

- [Documentation](https://pennylane.ai/codebook)
- [GitHub Repository](https://github.com/XanaduAI/Xanadu-Quantum-Codebook)

## Common Properties

- [Portal — Xanadu Homepage](https://www.xanadu.ai)
- [Portal — PennyLane](https://pennylane.ai)
- [Documentation — PennyLane Docs](https://docs.pennylane.ai/en/stable/)
- [GettingStarted](https://docs.pennylane.ai/en/stable/introduction/pennylane.html)
- [GitHubOrganization — XanaduAI](https://github.com/XanaduAI)
- [GitHubOrganization — PennyLaneAI](https://github.com/PennyLaneAI)
- [SDK — PennyLane on PyPI](https://pypi.org/project/PennyLane/)
- [Tutorials — PennyLane Demonstrations](https://pennylane.ai/qml/demonstrations)
- [Courses — Xanadu Quantum Codebook](https://pennylane.ai/codebook)
- [Resources — PennyLane Datasets](https://pennylane.ai/datasets)
- [Integrations — PennyLane Plugins Directory](https://pennylane.ai/plugins)
- [Integrations — PennyLane Devices](https://pennylane.ai/devices)
- [Support — PennyLane Discussion Forum](https://discuss.pennylane.ai)
- [Blog — Xanadu](https://www.xanadu.ai/blog)
- [Blog — PennyLane](https://pennylane.ai/blog)
- [YouTube — Xanadu](https://www.youtube.com/c/XanaduAI)
- [LinkedIn — Xanadu](https://www.linkedin.com/company/xanaduai)
- [X — XanaduAI](https://twitter.com/XanaduAI)
- [Resources — Careers](https://www.xanadu.ai/careers)
- [Events — QHack](https://www.xanadu.ai/qhack)
- [ReleaseNotes — PennyLane](https://docs.pennylane.ai/en/stable/development/release_notes.html)
- [ChangeLog — PennyLane](https://docs.pennylane.ai/en/stable/development/release_notes.html)
- [Legal — Apache 2.0 License (PennyLane)](https://github.com/PennyLaneAI/pennylane/blob/master/LICENSE)
- [PrivacyPolicy](https://www.xanadu.ai/privacy)
- [TermsOfService](https://www.xanadu.ai/terms)

## Features

| Name | Description |
|------|-------------|
| Open-source quantum differentiable programming | Train variational quantum circuits with PyTorch / JAX / TensorFlow / NumPy autodiff through PennyLane. |
| Hardware-agnostic device API | Swap between 40+ simulators and QPU backends behind a single `qml.device(...)` interface. |
| JIT compilation of hybrid programs | Catalyst compiles quantum + classical control flow to MLIR / LLVM / QIR for fast, gradient-aware execution. |
| High-performance simulators | Lightning (CPU/C++), Lightning-GPU (cuQuantum), Lightning-Kokkos (HPC), and Jet (tensor-network) scale to research-grade workloads. |
| Quantum chemistry built in | `qml.qchem` provides differentiable Hartree-Fock, VQE, and Hamiltonian construction. |
| Curated datasets and codebook | PennyLane Datasets and the Xanadu Quantum Codebook deliver standardized benchmarks and an interactive learning curriculum. |
| Photonic continuous-variable tooling | Strawberry Fields, MrMustard, The Walrus, Blackbird, and FlamingPy form a complete CV photonic stack — simulation, optimization, fault-tolerant codes. |
| Hardware milestones | X8 (8-mode squeezed-light chip), Borealis (216-mode programmable Gaussian boson sampler; Nature 2022 quantum advantage), Aurora (modular networked photonic computer, 2025). |

## Use Cases

| Name | Description |
|------|-------------|
| Quantum Machine Learning | Variational classifiers, quantum kernels, generative quantum models, hybrid quantum-classical neural networks. |
| Quantum Chemistry | Molecular ground-state energies via VQE, differentiable Hartree-Fock, resource estimation for fault-tolerant electronic-structure algorithms. |
| Quantum Algorithm Research | Rapid prototyping of QAOA, amplitude estimation, quantum signal processing, and error-correction protocols. |
| Hybrid HPC Workloads | Catalyst + Lightning-GPU / Lightning-Kokkos for scaling hybrid quantum-classical workloads on HPC clusters. |
| Quantum Education | PennyLane Codebook, demos, and datasets for university courses and self-directed learners. |
| Hardware Benchmarking | Cross-vendor execution and benchmarking via the plugin ecosystem (IBM, IonQ, Rigetti, AWS Braket, AQT, Quantinuum). |

## Integrations

| Name | Description |
|------|-------------|
| IBM Quantum / Qiskit | `pennylane-qiskit` plugin — run circuits on IBM Quantum hardware and Qiskit simulators. |
| AWS Braket | Amazon Braket plugin — execute on Rigetti, IonQ, OQC, Quera, and the SV1/DM1/TN1 managed simulators. |
| Google Cirq | `pennylane-cirq` plugin for Cirq simulators and Google Quantum AI workflows. |
| Rigetti Forest | `pennylane-rigetti` plugin for Rigetti QPUs, QVM, and wavefunction simulator. |
| IonQ | `PennyLane-IonQ` plugin for IonQ simulators and trapped-ion hardware. |
| AQT (Alpine Quantum Technologies) | `pennylane-aqt` plugin for AQT ion-trap hardware. |
| Quantinuum (Honeywell) | `pennylane-honeywell` plugin for Quantinuum / Honeywell ion-trap hardware. |
| Microsoft Q# / QDK | `PennyLane-qsharp` plugin for the Microsoft Quantum Development Kit full state simulator. |
| Qulacs | `pennylane-qulacs` plugin — high-performance C++ simulator. |
| ProjectQ | `pennylane-pq` plugin — IBM, simulator, and classical-simulator devices via ProjectQ. |
| Strawberry Fields | `pennylane-sf` plugin — drive Xanadu's continuous-variable photonic simulators. |
| PyTorch | PennyLane's `torch` interface for gradient-based optimization with PyTorch tensors. |
| JAX | PennyLane's `jax` interface and Catalyst JAX support. |
| TensorFlow / Keras | PennyLane's `tf` interface for seamless integration with TensorFlow models. |
| NumPy / Autograd | Default PennyLane interface for classical autodiff with NumPy. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
