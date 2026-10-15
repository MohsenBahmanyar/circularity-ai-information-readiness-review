# Final validation report

Validated against the frozen submission evidence on 2026-10-14.

## Numerical and structural checks

| Check | Expected | Observed | Status |
|---|---:|---:|---|
| Primary review: Imported occurrences | 1762 | 1762 | PASS |
| Primary review: Duplicate occurrences removed | 674 | 674 | PASS |
| Primary review: Unique records screened | 1088 | 1088 | PASS |
| Primary review: Title/abstract Include | 695 | 695 | PASS |
| Primary review: Title/abstract Maybe | 160 | 160 | PASS |
| Primary review: Title/abstract Exclude | 233 | 233 | PASS |
| Primary review: Reports sought | 855 | 855 | PASS |
| Primary review: Reports not retrieved | 123 | 123 | PASS |
| Primary review: Reports assessed | 732 | 732 | PASS |
| Primary review: Reports included | 731 | 731 | PASS |
| Primary review: Circularity-information analytical view | 726 | 726 | PASS |
| Primary review: Digital-information analytical view | 720 | 720 | PASS |
| Primary review: Full-text excluded | 1 | 1 | PASS |
| Normalized attributes | 48 | 48 | PASS |
| Source-grounded Core attributes | 19 | 19 | PASS |
| Unresolved-readiness attributes | 29 | 29 | PASS |
| LCA Data normalized name present | 1 | 1 | PASS |
| Full requirement relationships | 6248 | 6248 | PASS |
| Focused-audit attributes | 30 | 30 | PASS |
| Provenance funnel: Requirement relationships | 6248 | 6248 | PASS |
| Provenance funnel: Implemented relationships | 297 | 297 | PASS |
| Provenance funnel: Source reported | 172 | 172 | PASS |
| Provenance funnel: Timing evidenced | 57 | 57 | PASS |
| Provenance funnel: Prospectively available design relationships | 22 | 22 | PASS |
| Targeted AI imported occurrences | 4272 | 4272 | PASS |
| Targeted AI duplicates removed | 404 | 404 | PASS |
| Targeted AI unique records | 3868 | 3868 | PASS |
| High-priority queue | 300 | 300 | PASS |
| Transferable candidate queue | 1370 | 1370 | PASS |
| Gap-targeted selection | 78 | 78 | PASS |
| Empirical AI corpus | 107 | 107 | PASS |
| Targeted AI screening: Include | 1296 | 1296 | PASS |
| Targeted AI screening: Maybe | 374 | 374 | PASS |
| Targeted AI screening: Background Review | 134 | 134 | PASS |
| Targeted AI screening: Exclude | 2064 | 2064 | PASS |
| Target/Output relationships | 283 | 283 | PASS |
| Supporting-role relationships | 154 | 154 | PASS |
| AI matrix cells | 288 | 288 | PASS |
| Matrix grade A | 63 | 63 | PASS |
| Matrix grade B | 9 | 9 | PASS |
| Matrix grade C | 34 | 34 | PASS |
| Matrix grade D | 182 | 182 | PASS |
| Attributes with at least one A/B | 33 | 33 | PASS |
| Attributes without A/B | 15 | 15 | PASS |
| Readiness x AI: Source-grounded Core + AI support | 15 | 15 | PASS |
| Readiness x AI: Source-grounded Core + no verified A/B | 4 | 4 | PASS |
| Readiness x AI: Unresolved readiness + AI support | 18 | 18 | PASS |
| Readiness x AI: Unresolved readiness + no verified A/B | 11 | 11 | PASS |
| Source-grounded attributes with early-design A/B context | ['Component Identity', 'Component Relationships', 'Geometry', 'LCA Data', 'Material Quantity', 'Material Type', 'Standardization', 'Volume'] | ['Component Identity', 'Component Relationships', 'Geometry', 'LCA Data', 'Material Quantity', 'Material Type', 'Standardization', 'Volume'] | PASS |
| Formal six function names | ['Extract/Retrieve', 'Infer/Complete', 'Predict/Assess', 'Diagnose', 'Recommend', 'Generate plus Rank/Optimize'] | ['Extract/Retrieve', 'Infer/Complete', 'Predict/Assess', 'Diagnose', 'Recommend', 'Generate plus Rank/Optimize'] | PASS |
| Function coverage: Extract/Retrieve | (26, 3) | (26, 3) | PASS |
| Function coverage: Infer/Complete | (9, 2) | (9, 2) | PASS |
| Function coverage: Predict/Assess | (13, 5) | (13, 5) | PASS |
| Function coverage: Diagnose | (6, 4) | (6, 4) | PASS |
| Function coverage: Recommend | (8, 4) | (8, 4) | PASS |
| Function coverage: Generate plus Rank/Optimize | (10, 4) | (10, 4) | PASS |
| Figure S1 attributes | 48 | 48 | PASS |
| Figure S2 attributes | 48 | 48 | PASS |
| Figure S3 cells | 288 | 288 | PASS |
| Figure S3 attributes | 48 | 48 | PASS |
| Figure S3 functions | ['Diagnose', 'Extract/Retrieve', 'Generate plus Rank/Optimize', 'Infer/Complete', 'Predict/Assess', 'Recommend'] | ['Diagnose', 'Extract/Retrieve', 'Generate plus Rank/Optimize', 'Infer/Complete', 'Predict/Assess', 'Recommend'] | PASS |
| Figure 7 Band I | 8 | 8 | PASS |
| Figure 7 Band II | 7 | 7 | PASS |
| Figure 7 Band III | 4 | 4 | PASS |

Passed: 64/64. Failed: 0.

## Public-release audits

- Prohibited process-label wording in public Excel files: 0 issue(s).
- Absolute local Windows paths in public text/code: 0 issue(s).
- Stale numbered internal-task terminology in public text/data: 0 issue(s).
- Restricted or unexpected PDF/database-export files in public package: 0 issue(s).
- Supplementary document visual review: 57 pages reviewed; no clipping or broken figure placement identified.
- Supplementary figures: S1 contains 48 attributes; S2 contains 48 attributes; S3 contains 288 cells. No supplementary figure duplicates the main function-coverage figure.
- Figure 7: Roman-numeral Bands I/II/III validated at 8/7/4 attributes.

## Scientific boundaries retained

The primary and targeted AI evidence streams remain separate. Readiness and demonstrated AI capability are independently established. A/B/C/D remain evidence grades, C is not demonstrated A/B capability, and D is not technical impossibility. The targeted AI stream is purposive and cannot estimate prevalence in the broader architectural-AI literature.
