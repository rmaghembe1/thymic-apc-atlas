# Environment reconstruction

This directory documents the software-environment evidence available for the Thymic APC Atlas reproducibility release.

## Important boundary

An exact historical environment lock **could not be reconstructed defensibly**. The private historical requirements file contained 86 machine-local build references. P11_D3 recovered non-conflicting exact version evidence for 84 of those entries from active Python/Conda metadata, but 2 entries had conflicting Python and Conda version metadata. In addition, among 51 package versions that were explicitly pinned in the historical freeze, 49 matched the inspected active environment and 2 did not.

Therefore the files here are **reconstruction evidence, not a claim of exact historical environment equivalence**.

## Files

- `requirements_reconstructed_best_effort.txt` - install-style best-effort package specification. It preserves all explicit historical pins and adds only non-conflicting recovered local-build versions. Conflicted local-build packages are omitted.
- `requirements_historical_explicit.txt` - only the package/version pins explicitly recorded in the private historical freeze.
- `local_build_version_recovery.tsv` - package-by-package Python/Conda recovery evidence for the 86 local-build entries.
- `explicit_pin_concordance.tsv` - comparison of historical explicit pins with the inspected active environment.
- `environment_conflicts.tsv` - the 2 local-build packages for which Python and Conda metadata disagreed.

Users should treat these files as provenance-supported reconstruction aids. They may need to resolve the listed conflicts and adapt package versions to their platform before rerunning the workflow.
