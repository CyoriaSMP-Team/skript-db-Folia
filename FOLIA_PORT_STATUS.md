# skript-db-Folia — CyoriaSMP Folia release provenance

- Original/source project: https://github.com/btk5h/skript-db
- Original license: MIT. Upstream authorship and licensing are preserved.
- Tested target: Minecraft/Folia 1.21.11.
- Stage: **Cyoria-tested addon binary**. Pre-release only, not certified region/thread safe.
- Binary: `skript-db-2.0.0.jar` (GitHub Releases asset; no worlds/config/secrets).

## What is actually modified
The Cyoria deployed JAR advertises folia-supported. Full provenance of binary-level changes from upstream has not been reconstructed.

## Verification scope
Addon loaded with Folia and the Cyoria Skript build; concurrent SQL workloads and cross-region continuations were not fully tested.

## Limitations
Database credentials/config must never be placed in releases. No secrets are included in this artifact. Back up your data and test on a disposable world before deployment.

Source fork retains original project history. This document does not assert that a successful startup means fully Folia-compatible gameplay.
