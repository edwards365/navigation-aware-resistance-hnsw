# V7 manuscript and reproduction guide

Fixed manuscript: [artifact-manuscript-v7](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/releases/tag/artifact-manuscript-v7). Authors: Lekang Wang, Pinze Ren, Zhen Chen; all affiliated with Tsinghua University. Zhen Chen is the corresponding author. V7 is a manuscript/figure presentation and authorship update, not a new experimental release or an accepted-publication claim.

## Read and build

Download `ICDE_v7.pdf` and `ICDE_v7_Overleaf.zip`. Extract the ZIP, select `main.tex`, and build using XeLaTeX/BibTeX or Tectonic. The package includes five figure PDFs and `study_design_protocol.md`. `release-manifest.json` and `CHECKSUMS.sha256` identify the exact files. Use the release assets; GitHub's automatic repository archive is not the Overleaf package.

## Verification levels

| Level | Scope |
|---|---|
| Document build | Extracted V7 source compiled locally and compared with the delivered PDF; see verification.json for actual checks. No online Overleaf/CMT submission. |
| Saved-record reconstruction | Existing fixed releases supply declared inputs, scripts and expected results. Reconstruction is distinct from acquiring new search or timing measurements. |
| Independent algorithmic checks | P0–P11 and P12 receipts describe independently implemented checks and their stated environments, not an independent research team. |
| Original-procedure execution | Staged interfaces and data/dependency instructions are available; they do not establish a complete full-data independent rerun. |

## V7 results and fixed evidence

| V7 content | Fixed entry |
|---|---|
| Fig. 2: transfer; Fig. 4: deployment | [paper-v2 runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-paper-v2/artifact/paper/README.md) and [evidence map](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-paper-v2/artifact/EVIDENCE.md) |
| Fig. 3: summary constraints and mechanisms | [response-v1 runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-response-v1/artifact/RUNBOOK.md), [P0–P11 map](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-deepening-v2/artifact/deepening/EVIDENCE.md), [P12 map](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-deepening-v3/artifact/p12/EVIDENCE.md) |
| Fig. 5: conditional cost; Section VI answer-lookup measurements | [paper-v2 runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-paper-v2/artifact/paper/README.md) and [narrative runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-paper-v2/artifact/narrative/README.md) |
| Sections IV–V learning, qualification and construction analyses | [P0–P11 runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-deepening-v2/artifact/deepening/README.md) |
| SIFT1M boundary-tie sensitivity | [P12 runbook](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-deepening-v3/artifact/p12/README.md); P12/v3 supersedes older unresolved-status notes |
| Original execution interfaces | [delivery-v1 execution map](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-delivery-v1/artifact/original_execution/EXECUTION_MAP.md) |

The older [v5 guide](https://github.com/edwards365/when-is-cross-index-search-budget-reuse-worthwhile/blob/artifact-manuscript-v5/docs/manuscript/v5/REPRODUCIBILITY.md) retains detailed environment/command descriptions; resolve its historical Figure 6 as V7 Section VI answer-lookup evidence. V7 has five figures. The current figure PDFs replace earlier visual exports; current editable draw.io/plotting sources are not included in this release.

The V7 PDF retains its fixed v4 evidence URL. The v4 release page and repository evidence entry link forward to V7. Old tags and release assets remain unchanged. Target-informed empirical optima remain diagnostic references; the History-Max ledger does not establish costs for newly learned policies. Full provenance and verification boundaries remain in the fixed evidence maps.
