# Rocket Analyzer DI² — Public Engineering and Audit Artifacts

Grounded DI LLC’s public record for rule-governed aerospace diagnostics, failure-tree analysis, reentry phase gates, and public-safe anomaly review.

## Overview

This repository contains six dated artifacts plus this README. The collection begins with a June 12, 2025 document titled `Provisional Patent Filing — Rocket Analyzer DI²` and extends through public-source analyses prepared in May and June 2026. It preserves the project’s historical vocabulary while separating architecture descriptions, engineering analyses, and recorded evidence.

The repository is an artifact and analysis archive, not the complete Rocket Analyzer implementation. A reviewer will find a historical architecture description, an Artemis II reentry demonstration, a failure-tree graphic, an audited New Glenn geometry review, a public-safe Starship Flight 12 anomaly report, and a GitHub traffic capture.

## Why It Matters

Aerospace anomaly review must distinguish observed consequences from candidate causes. The strongest documents here use explicit phase gates, causal propagation, evidence classes, and authorization holds so that a public image or operator statement can inform an investigation without being promoted to a telemetry-backed root-cause finding.

## What the Repository Contains

| Artifact | What it records |
| --- | --- |
| `Provisional_Patent_Rocket_Analyzer_June_12_2025` | A contemporaneous architecture and filing-status description of the DLE (Deterministic Logic Engine), FPM (Failure Propagation Model), DFS failure tree, diagnostic capsule, replay recipe, DSS severity score, and HDLD-A output-denial layer. |
| `Rocket_Analyzer_DI2_Artemis_II_Artifact.pdf` | A draft Artemis II reentry explanation organized around velocity → heat → drag → stability → parachute transition → survival, with phase gates and observable proof moments. |
| `Rocket_Analyzer_Failure_Tree_Demo_Artemis_II_Reentry.jpeg` | Visual mission-critical tree with weighted gates for pre-entry configuration, entry geometry, thermal protection, plasma/comms, aerodynamic stability, parachutes, and recovery. |
| `New_Glenn_LC36_Geometry_Origin_Analysis_v2_Audited_5-29-26_Grounded_DI_LLC.pdf` | A public-source visual diagnostic for the May 28, 2026 New Glenn static-fire anomaly. It localizes the earliest brightening to a lower-aft vehicle/pad interface band with moderate camera-plane confidence; root cause remains `UNRESOLVED`. |
| `Public-Safe_Rocket_Anomaly_Output_Discipline.pdf` | An advisory-only report on SpaceX Starship Flight 12. FAA-observed facts, SpaceX-described sequence, inferred candidate states, unresolved data gaps, and export holds are kept separate; root-cause release is blocked pending telemetry and official investigation evidence. |
| `GitHub_Traffic_Grounded-DI_Rocket_Analyzer_Posts_Received_121_Clones_and_68_Unique_Cloners_in_Three_Days.pdf` | A historical GitHub analytics capture showing 121 clones and 68 unique cloners in its displayed 14-day period. This is an archive metric, not a product-adoption or performance claim. |

## What the Record Demonstrates

- The New Glenn artifact records a revised geometry finding—lower aft, slightly camera-right of centerline, near the vehicle/pad interface—and explicitly assigns zero confidence to root-cause assignment without telemetry and investigation data.
- The Starship Flight 12 report records `Authorization status: Advisory-only / causal findings export-held` and `Root-cause status: Unresolved`. It marks FAA mishap status, booster flyback involvement, public-safety outcome, and debris response as observed, while keeping propulsion, GNC, command-state, and component causes uncommitted.
- The Artemis II draft compresses a complex crewed-return sequence into phase gates and observable checks such as communications return after blackout and successful main-canopy deployment. It is a demonstration artifact, not live mission telemetry.
- The 2025 architecture document describes replayable diagnostic capsules, causal failure propagation, rule-chain integrity, severity gates, and a mismatch code for diagnostic inconsistency. Those mechanisms are documented design vocabulary in this archive; no executable implementation is included here.

## Architecture in the Public Artifacts

The public-safe anomaly report and New Glenn audit show the repository’s clearest control pattern:

```text
public facts, images, and event timeline
        → phase / failure-tree organization
        → observed, inferred, and unresolved evidence classes
        → candidate causal-state and propagation review
        → authorization / replay sufficiency gate
        → advisory artifact or held root-cause output
```

The June 2025 filing text uses the names DLE, FPM, DFS, DSS, HDLD-A, Diagnostic Capsule, and Replay Recipe. These names are retained as contemporaneous project terminology; each source file remains the authority for its own definitions.

## Technical Significance

The notable technical feature of this record is controlled non-commitment. Public-source geometry can support a camera-plane location; official statements can support an observed mishap; and a candidate propagation path can be documented. The release gate still blocks a component or root-cause conclusion when telemetry, synchronized imagery, damage mapping, replay inputs, or official findings are missing.

## How to Review

1. Read `Public-Safe_Rocket_Anomaly_Output_Discipline.pdf` for the observed / inferred / unresolved evidence model and authorization matrix.
2. Read `New_Glenn_LC36_Geometry_Origin_Analysis_v2_Audited_5-29-26_Grounded_DI_LLC.pdf` for a concrete visual-geometry audit and its explicit root-cause boundary.
3. Read `Rocket_Analyzer_DI2_Artemis_II_Artifact.pdf` and the JPEG for the phase-gate and failure-tree examples.
4. Read `Provisional_Patent_Rocket_Analyzer_June_12_2025` for the earliest public architecture description.
5. Treat the traffic PDF as historical repository analytics only.

## Validation and Testing

No source tree, package manifest, executable analyzer, telemetry feed, or repository test suite is included. There is therefore no current test command to run. The statuses quoted above are the statuses recorded in the artifacts: `Observed`, `Inferred`, `Unresolved`, `Advisory-only`, `Blocked`, and `UNRESOLVED`.

The artifacts provide analysis and evidence discipline for specific public cases. They do not establish a general aerospace forecasting score, independent flight certification, or a telemetry-backed root-cause result.

## Patent and Intellectual Property Record

The archive includes a file titled `Provisional_Patent_Rocket_Analyzer_June_12_2025`, dated June 12, 2025, and labeled `Patent Pending` in the document. The public-safe report also references U.S. Application No. `19/706,930` as a framework source. These are public artifact references, not an assertion that a patent has issued; this repository does not include a USPTO receipt or issued-patent record for those references.

No open-source license is currently provided in this repository. Copyright and other rights remain with Grounded DI LLC and applicable authors except where expressly stated otherwise.

## Commercial and Integration Context

Organizations evaluating evidence-governed anomaly review, aerospace failure trees, public-source diagnostic workflows, or replay and authorization controls can use these artifacts as a discussion and proof-of-concept starting point. A production integration would require access to mission data, synchronized telemetry, engineering review, and an agreed validation and safety process.

Evaluation, licensing, integration, and research inquiries can be opened through the [Grounded DI GitHub organization](https://github.com/Grounded-DI).

## Authorship and Provenance

The files identify Grounded DI LLC and preserve dates, artifact names, source lists, evidence registers, and report versions. The June 2025 filing text is retained as historical development language; later reports preserve their own preparation dates and evidence cutoffs. File hashes, where supplied inside an artifact, identify the recorded bytes and do not independently establish the substantive truth of every statement.

## Repository Scope and Status

This is a public documentary and engineering-analysis record. It is not the complete private Rocket Analyzer runtime, SDK, telemetry integration, regulatory submission, or investigation dossier. Public-source conclusions are intentionally scoped: the New Glenn root cause and the Starship Flight 12 root cause remain unresolved in the included records.

## Contact

Use the [Grounded DI GitHub organization](https://github.com/Grounded-DI) for collaboration, evaluation, licensing, or integration inquiries.
