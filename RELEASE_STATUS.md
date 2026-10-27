# Release status

Status: **READY FOR BOUNDED PUBLIC RELEASE - PUBLIC IDENTIFIERS NOT YET ASSIGNED**.

## Completed gates

- Sanitized public successor constructed without modifying `repository_release_v1`.
- Environment evidence converted to a transparent best-effort reconstruction; exact historical environment equivalence is not claimed.
- MIT licensing for original software/code and CC BY 4.0 licensing for original non-software content were authorized, subject to the documented third-party rights boundary.
- Independent integrity, privacy, provenance, citation-metadata, license-scope, archive-integrity and hosting-size audit passed.
- Machine-specific paths, credential-like findings and the historical premature Zenodo DOI are absent from this candidate.

## Frozen release metadata

- Public release version: `1.0.0`.
- Persistent GitHub and Zenodo identifiers are intentionally absent until created under the separately authorized release gates.
- No exact historical environment lock is claimed; see `environment/README.md` and the environment evidence tables.

## Bounded release sequence

1. Initialize and publish the exact frozen candidate to GitHub under a separate release gate.
2. Archive the exact frozen release payload with Zenodo and obtain the live DOI under a separate release gate.
3. Freeze the live GitHub URL and Zenodo DOI only after they exist; do not invent or pre-populate identifiers.
4. Update the manuscript Data Availability and Code Availability statements with the live identifiers, then re-render and re-QA the manuscript before journal submission.

No scientific/data/code payload change is authorized by this metadata-finalization gate. The source `repository_release_v1` and all predecessor release candidates remain preserved as provenance evidence.
