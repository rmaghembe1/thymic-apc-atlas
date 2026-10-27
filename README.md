# Human Thymic Stromal-Immune APC Atlas

This repository is the reproducibility package for:

**Single-cell and spatial transcriptomic reconstruction of human thymic stromal-immune antigen-presenting niches across early-life development**

## Scope

The project reanalyzes publicly available human thymus single-cell, CITE-seq and Visium spatial-transcriptomic data to examine epithelial, stromal and hematopoietic antigen-presenting programs.

Primary public source datasets:

- GEO GSE147520 - human thymic stromal single-cell transcriptomics.
- GEO GSE207206 - pediatric thymus CITE-seq and Visium spatial transcriptomics.

## Reproducibility boundary

The spatial results are descriptive signature co-patterning. Visium spots are multicellular; the analyses do not establish direct cell-cell contact, formal deconvolution, donor-independent statistical significance, or authenticated barcode-level cortex/medulla assignments. The B-cell/APC and MHC-II signature association is interpreted with explicit shared-marker sensitivity analysis because the original signatures share CD74 and HLA-DRA.

## Repository contents

- `scripts/` - analysis and figure-generation code retained for scientific reproducibility.
- `tables/` - processed analytical and summary tables.
- `figures/` - reproducibility figures and graphical outputs where present.
- `docs/` - project documentation retained for scientific use.
- `environment/` - portable environment information.
- `SOURCE_PROVENANCE.tsv` - source-to-public-candidate provenance mapping.
- `SHA256SUMS.txt` - SHA-256 manifest for the candidate files.

## Running the code

Run scripts from the repository root. Machine-specific absolute paths from the private working environment have been replaced by repository-relative paths in the public candidate. Review individual script inputs before execution.

## Current release status

This directory passed the final independent pre-publication audit. It is the frozen local publication-ready candidate for a bounded GitHub and Zenodo release. Environment reconstruction is documented as best-effort; exact historical environment equivalence is not claimed. Public repository and archival identifiers are intentionally absent until they are created and frozen during the release gates.

## Citation

A preliminary `CITATION.cff` is included. The final archival DOI will be added only after the public release is created.

## Third-party data

Original source datasets remain subject to the terms of their originating repositories and publications. This reproducibility package does not change third-party rights.

## Licensing

Original project code is licensed under the MIT License. Original non-software content is licensed under CC BY 4.0 to the extent rights are held by the author. Third-party source datasets and publication material are excluded from these grants. See `LICENSE.md` and `THIRD_PARTY_RIGHTS.md`.
