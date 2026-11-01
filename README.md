# Xanadu

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Xanadu is a Canadian photonic quantum computing company building room-temperature, fault-tolerant, scalable quantum computers based on photonic continuous-variable (CV) and Gaussian boson sampling architectures. Xanadu maintains a large open-source software stack — most notably PennyLane (the cross-platform framework for quantum differentiable programming, quantum chemistry, and quantum machine learning), Catalyst (a JIT/MLIR compiler for hybrid quantum-classical programs), the PennyLane Lightning family of high-performance state-vector and tensor-network simulators, the PennyLane Plugin ecosystem (Qiskit/IBM, AWS Braket, Cirq, Rigetti, IonQ, AQT, Quantinuum, Qulacs, ProjectQ, and Xanadu's own Strawberry Fields), MrMustard, Jet, FlamingPy, The Walrus, Blackbird (the CV quantum assembly language), XIR, and the Xanadu Quantum Codebook. Xanadu hardware milestones include the X8 photonic chip, Borealis (quantum advantage demonstration on a 216-mode programmable Gaussian boson sampler), and Aurora (the first modular, networked photonic quantum computer combining server racks and kilometres of optical fibre). The Xanadu Cloud — the original photonic-hardware-as-a-service offering with REST/Python/CLI access to Borealis and X8 — has been retired (the `xanadu-cloud-client` and Strawberry Fields repos are archived), and Xanadu's developer-facing surface today centres on the PennyLane Python ecosystem and hardware execution via PennyLane plugins against partner cloud platforms.

**Areas:** Quantum Computing · Photonic Quantum · Quantum Machine Learning · Quantum Chemistry · Differentiable Programming · PennyLane · Open Source · Compilers · Simulator · Continuous Variable · Gaussian Boson Sampling · Fault Tolerance

## Xanadu on APIs.io

Everything profiled for Xanadu is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/xanadu-ai/](https://apis.io/providers/xanadu-ai/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [PennyLane](https://apis.io/apis/xanadu-ai/pennylane/) — PennyLane is the flagship open-source Python framework for quantum differentiable programming — train and optimize variational quantum circuits with the…
- [PennyLane Catalyst](https://apis.io/apis/xanadu-ai/pennylane-catalyst/) — Catalyst is a JIT compiler for hybrid quantum programs written in PennyLane. The `@qjit` decorator compiles entire quantum-classical workflows — including…
- [PennyLane Lightning](https://apis.io/apis/xanadu-ai/pennylane-lightning/) — The Lightning plugin family — `lightning.qubit` (C++ CPU), `lightning.gpu` (cuQuantum), and `lightning.kokkos` (multi-architecture HPC) — provides Xanadu's…
- [PennyLane Plugins](https://apis.io/apis/xanadu-ai/pennylane-plugins/) — The PennyLane plugin layer exposes a uniform `qml.device` interface across third-party quantum SDKs and QPU clouds — IBM Qiskit / IBM Quantum, AWS Braket,…
- [PennyLane Quantum Chemistry (qchem)](https://apis.io/apis/xanadu-ai/pennylane-qchem/) — `qml.qchem` is PennyLane's quantum chemistry submodule for constructing molecular Hamiltonians, differentiable Hartree-Fock, VQE workflows, and resource…
- [PennyLane Datasets](https://apis.io/apis/xanadu-ai/pennylane-datasets/) — A curated catalogue of pre-computed quantum datasets — molecular Hamiltonians, spin systems, QML benchmarks — accessible via `qml.data.load(...)` for…
- [Strawberry Fields](https://apis.io/apis/xanadu-ai/strawberry-fields/) — Strawberry Fields is Xanadu's full-stack Python library for designing, simulating, and optimizing continuous-variable (CV) photonic quantum circuits.…
- [MrMustard](https://apis.io/apis/xanadu-ai/mrmustard/) — MrMustard is a differentiable simulator that acts as a bridge between phase-space and Fock-space representations of bosonic / CV quantum systems. Built for…
- [The Walrus](https://apis.io/apis/xanadu-ai/thewalrus/) — The Walrus is a high-performance C++/Python library for computing hafnians, loop hafnians, Hermite polynomials, and Gaussian boson sampling probabilities —…
- [Jet](https://apis.io/apis/xanadu-ai/jet/) — Jet is a cross-platform C++ library for simulating quantum circuits via tensor-network contractions, with task-based parallelism for HPC-scale workloads.
- [FlamingPy](https://apis.io/apis/xanadu-ai/flamingpy/) — FlamingPy is a Python library with multiple backends for efficient simulation of error correction in fault-tolerant photonic quantum architectures,…
- [Blackbird Language](https://apis.io/apis/xanadu-ai/blackbird/) — Blackbird is Xanadu's quantum assembly language for continuous-variable photonic quantum computation. Programs target Strawberry Fields simulators and were…
- [XIR](https://apis.io/apis/xanadu-ai/xir/) — XIR is an intermediate representation language for quantum circuits, designed to ferry circuits between front-end frameworks (Strawberry Fields, PennyLane)…
- [Xanadu Quantum Codebook](https://apis.io/apis/xanadu-ai/xanadu-quantum-codebook/) — An interactive, free, browser-based quantum computing course built on PennyLane. Covers introductory quantum computing, single- and multi-qubit systems,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Xanadu Ai Domain Security](https://apis.io/security/xanadu-ai/xanadu-ai-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.pennylane.ai/)
- [Documentation](https://docs.pennylane.ai/en/stable/)
- [Getting started](https://docs.pennylane.ai/en/stable/introduction/pennylane.html)
- [Support](https://discuss.pennylane.ai)
- [Changelog](https://docs.pennylane.ai/en/stable/development/release_notes.html)
- [Blog](https://www.xanadu.ai/blog)
- [Terms of service](https://www.xanadu.ai/terms)
- [Privacy policy](https://www.xanadu.ai/privacy)
- [GitHub](https://github.com/XanaduAI)

## API Evangelist rating

**Kin Score 30.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 6.5 |
| Contract governance | 0.0 |
| Operational transparency | 21.1 |
| Developer ergonomics | 61.9 |
| Access clarity | 21.1 |

**Agent readiness 1.3** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 13.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/xanadu-ai/](https://apis.io/providers/xanadu-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Xanadu: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/xanadu-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
