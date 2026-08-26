# Ateeq Janam Dev

Software engineer building **trustworthy, reproducible, and inspectable systems**.

I focus on the engineering boundary between AI capability and operational trust: evidence, provenance, deterministic evaluation, privacy-aware debugging, and failure-resistant developer tools.

## Flagship project

[FaultPack](https://github.com/ateeqdesktop-dot/faultpack) is my primary open-source project: a local-first, privacy-preserving evidence interchange for reproducible software failures and AI-agent/tool runs. The `v1.4.0` release adds a verified, dependency-free offline HTML evidence viewer alongside digest-first event timelines, offline semantic evidence diff, producer-neutral contracts, signed artifacts, replay, reduction, SARIF/JUnit reports, and a reusable GitHub Action.

> Capture once. Share safely. Verify independently. Replay anywhere.

## Supporting projects

| Project | What it demonstrates | Status |
|---|---|---|
| [TraceVeil](https://github.com/ateeqdesktop-dot/traceveil) | Local-first privacy policy compilation for OpenTelemetry GenAI telemetry, with deterministic sanitization, verifiable decision evidence, optional Ed25519 signatures, offline verification, SARIF/JUnit output, and a composite GitHub Action | [v0.1.0](https://github.com/ateeqdesktop-dot/traceveil/releases/tag/v0.1.0) |
| [DiffProof](https://github.com/ateeqdesktop-dot/diffproof) | Portable, privacy-safe, verifiable change evidence capsules for pull requests with impact findings, deterministic integrity, offline verification, SARIF/JUnit-ready CI output, and a composite GitHub Action | [v0.1.0](https://github.com/ateeqdesktop-dot/diffproof) |
| [FaultPack](https://github.com/ateeqdesktop-dot/faultpack) | Portable, privacy-first, verifiable failure evidence with safe capture, redaction, integrity checks, replay, reduction, differential comparison, Ed25519 signatures, CI reports, and a composite GitHub Action | [v1.0.0 Release](https://github.com/ateeqdesktop-dot/faultpack/releases/tag/v1.0.0) |

TraceVeil extends this work to the export boundary: it turns a reviewed privacy policy into a portable decision record before rich GenAI telemetry is handed to an observability system.

FaultPack is the clearest expression of my engineering approach: **small stable contracts, fail-closed behavior, deterministic evidence, and explicit security boundaries**. It is local-first and does not require a hosted account, model call, or implicit upload. The v1.0.0 release includes a tested wheel, source distribution, and architecture documentation.

## Engineering snapshot

| Signal | Current focus |
|---|---|
| Reliability | Reproducible failure evidence, regression fixtures, and deterministic replay |
| Trust | Provenance, signatures, privacy boundaries, and explainable verification |
| Developer experience | CLI-first workflows, GitHub Actions, SARIF/JUnit reports, and maintainable contracts |

## Selected work

| Project | What it demonstrates |
|---|---|
| [CorpusSeal](https://github.com/ateeqdesktop-dot/corpus-seal) | Evidence-first benchmark contamination and dataset integrity auditing with deterministic exact/near matching, SARIF, HTML, and GitHub Actions |
| [BidiFence](https://github.com/ateeqdesktop-dot/bidifence) | Deterministic RTL/i18n conformance checks for Playwright with SARIF, baselines, and Arabic fixtures |
| [TraceSift](https://github.com/ateeqdesktop-dot/tracesift) | Offline causal diagnosis and privacy-safe regression fixtures for AI-agent traces |
| [VeriTrace](https://github.com/ateeqdesktop-dot/veritrace) | Deterministic conformance and replay testing for agent governance |
| [ML ProofLedger](https://github.com/ateeqdesktop-dot/ml-proofledger) | Portable, verifiable evidence manifests for machine-learning runs |
| [Mizan](https://github.com/ateeqdesktop-dot/mizan-claim-verifier) | Evidence-backed Arabic claim verification with abstention and reproducible evaluation |

## Engineering interests

AI reliability and observability, benchmark and dataset integrity, OpenTelemetry-compatible trace contracts, reproducible ML evaluation, privacy-preserving artifacts, policy-as-code, Python tooling, API design, test architecture, and open-source maintenance.

## Technical stack

Python · TypeScript · FastAPI · pytest · GitHub Actions · OpenTelemetry · Docker · PostgreSQL · React

## Open-source principles

I prefer small stable contracts over opaque integrations, fail-closed behavior over optimistic guesses, local-first workflows where sensitive data is involved, and documentation that states limitations as clearly as capabilities.

## Contact

The best way to collaborate is through GitHub Issues and Discussions on the relevant project.
