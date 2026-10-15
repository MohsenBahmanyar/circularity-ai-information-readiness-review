# Supplementary materials and derived public data

## Study

**Circularity information readiness and demonstrated AI capability in architectural design: A source-, stage-, and role-aware evidence synthesis**

This release contains derived research data, codebooks, figure-source data, figure-reproduction scripts, and supplementary material for the manuscript. It does not redistribute copyrighted article full texts or proprietary database exports.

## Evidence streams

The primary evidence map contains 731 included reports. Its circularity-information view includes 726 reports and its digital-information view includes 720 reports; these views overlap and are not additive. The normalized vocabulary contains 48 attributes, classified as 19 source-grounded Core attributes and 29 attributes with unresolved readiness.

The targeted supplementary AI evidence stream is purposive and gap-directed. It contains 107 page-located empirical papers and supports a 48 by 6 matrix of 288 attribute-function cells. It must not be used to estimate prevalence across the broader architectural-AI literature.

Information readiness and demonstrated AI capability are independently established evidence dimensions. Demonstrated capability under supplied data does not establish prospective design-stage availability, and source-grounded readiness does not establish AI capability.

## Repository structure

- `supplement/`: final supplementary DOCX, PDF, and tables workbook.
- `data_excel/`: eight public-facing review and evidence workbooks.
- `data_csv/`: repository-friendly mirrors of the principal flat datasets.
- `figures/`: final SVG and high-resolution PNG figures.
- `figure_code/`: relative-path Python scripts that regenerate each shared figure.
- `documentation/`: sharing, methods, freeze, and data-availability documentation.
- `checksums/`: SHA-256 checksums for the frozen public release.

## Reproducing figures

Install Python 3.11 or later with `openpyxl` and `Pillow`. From the repository root, run the relevant script in `figure_code/`. Each script reads `data_excel/07_Figure_and_Table_Source_Data.xlsx` and writes SVG and PNG outputs to `figures/`.

## Public workbooks

The eight workbooks in `data_excel/` document the primary search and PRISMA flow; attribute normalization and readiness; the prospective-provenance audit; targeted AI search and selection; Target/Output and supporting-role evidence ledgers; the complete 48 by 6 matrix and readiness alignment; source data for figures and tables; and the data dictionary/codebooks.

## Scientific boundaries

- A/B/C/D are AI evidence grades, not readiness bands.
- C is not demonstrated A/B capability.
- D means no qualifying evidence in the selected corpus, not technical impossibility.
- Supporting roles do not count as demonstrated Target/Output capability.
- Early-design AI context does not prove that every required input was prospectively available at that stage.
- Existing-building reconstruction does not establish original prospective design availability.
- The 107 empirical AI papers are not merged with the 731-report primary corpus.

## Redistribution and licensing

Copyrighted article PDFs, publisher-supplied full abstracts, proprietary database exports, credentials, and personal data are not included. Licensing for this derived public package is pending author and institutional confirmation; no public license is assigned in this release.

## Version

Package version: `v1.0-manuscript-submission`  
Created: 2026-10-14  

