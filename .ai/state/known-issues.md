# Known issues and open decisions · 2026-09-26

## Evidence from the inspected examples repository

- `mmap/benchmark.py` generates distinct random offsets for `read` and `mmap`, has no fixed seed, and benchmarks sequentially on one file; cache state and ordering can confound comparison. CLI accepts zero values that may cause errors.
- `strace/trace_process.sh` uses `grep -P`, an unstated GNU grep dependency; no-match grep pipelines can exit under `set -euo pipefail`.
- The examples README declares MIT but the inspected tree had no `LICENSE` file. Confirm the intended license with the owner before adding legal text.
- No automated tests or CI appeared in the inspected examples tree. This is an observation, not proof about any private checks.

## Decisions needed

- Canonical PL/EN drafting and localization relationship.
- Editorial approver and publishing procedure.
- Whether “production-oriented” is retained with a verification gate or narrowed as a claim.
- Scope of approved sources, taxonomy, SEO rules and article update cycle.

Recheck the current repositories before acting; entries may have been fixed after this snapshot.
