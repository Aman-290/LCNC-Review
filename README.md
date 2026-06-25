# LCNC Review Evidence Repository

This repository contains the supporting evidence and extraction artifacts for a conference-style literature review on low-code/no-code (LCNC), no-code, zero-code, and AI-assisted software development.

The repository is intended to document the evidence base behind the review, including the selected research papers, extraction workbook, screening records, paper-level JSON files, and generated manuscript assets.

## Authors

- Aman J Sonal
- Deepak Naik

MCA Students, MIT Manipal

## Repository Purpose

This repository is not a software library. It is an evidence package for a literature review. Its main goal is to make the review process transparent by preserving:

- the original PDF corpus used for extraction,
- the 170-record screening and selection workbook,
- the completed 50-paper extraction workbook,
- per-paper structured JSON extraction files,
- PDF manifest files,
- extraction report and synthesis outputs,
- generated review-paper draft assets.

All extracted claims should be checked against the original PDFs before final publication or camera-ready submission.

## Evidence Summary

The review workflow used a 170-record corpus and selected 50 full-text papers for detailed extraction.

| Item | Value |
|---|---:|
| Records supplied by authors | 125 |
| Additional records identified during expansion | 45 |
| Total records before screening | 170 |
| Records screened after duplicate/low-fit flags | 161 |
| Final selected papers | 50 |
| PDFs processed successfully | 50 |
| Failed or unparseable PDFs | 0 |
| Per-paper JSON files | 50 |
| Evidence quote rows | 200 |

## Main Files and Folders

| Path | Description |
|---|---|
| `research paper/` | Folder containing the 50 PDF research papers used for extraction. |
| `lcnc_expanded_170_and_final_top_50.xlsx` | Screening workbook containing the expanded 170-record corpus and final top-50 selection. |
| `completed_review_extraction.xlsx` | Completed extraction workbook used as the main evidence source for synthesis. |
| `backup_before_extraction.xlsx` | Backup of the original workbook before extraction changes. |
| `extraction_outputs/` | Structured per-paper JSON extraction files, `P001.json` through `P050.json`. |
| `pdf_manifest.csv` | CSV manifest of all processed PDFs. |
| `pdf_manifest.json` | JSON manifest of all processed PDFs. |
| `EXTRACTION_REPORT.md` | Extraction run summary, assumptions, caveats, and human-review notes. |
| `paper_outputs/` | Generated review-paper draft, figures, and paper data summary. |
| `scripts/` | Scripts used to build extraction and paper outputs. |

## Extraction Workbook

The completed workbook is `completed_review_extraction.xlsx`. It includes the following sheets:

- `Master_Extraction`
- `Evidence_Quotes`
- `Quality_Appraisal`
- `Theme_Codebook`
- `Synthesis_Matrix`
- `Method_Taxonomy`
- `Agent_Prompt`
- `Dashboard`

The extraction followed a conservative evidence rule:

- If information was not explicitly found in the PDF, it was marked `Not reported`.
- If information was ambiguous, it was marked `Unclear` with a short explanation where possible.
- Major claims, methods, findings, limitations, and theme assignments were supported with evidence quotes where available.

## Quality Appraisal Summary

The 50 selected papers were appraised using a 12-item rubric with a maximum score of 24.

| Quality rating | Count |
|---|---:|
| Strong | 43 |
| Moderate | 7 |
| Weak | 0 |

Average quality score: **21.38 / 24**

## Dominant Research Methods

| Method | Count |
|---|---:|
| Prototype Evaluation | 8 |
| Survey | 8 |
| Case Study | 6 |
| Systematic Review | 5 |
| Document Analysis | 3 |
| Interview | 3 |
| Experiment | 3 |
| Benchmarking | 2 |
| Literature Review | 1 |
| Focus Group | 1 |
| Not reported | 10 |

## Dominant Themes

| Theme code | Count |
|---|---:|
| `PLATFORM_COMPARISON` | 40 |
| `AI_AUTOMATION` | 34 |
| `EDUCATION` | 18 |
| `ENTERPRISE_ADOPTION` | 15 |
| `USABILITY_UX` | 13 |
| `INTEGRATION` | 12 |
| `MDE_VISUAL_PROGRAMMING` | 11 |
| `CITIZEN_DEV` | 10 |
| `GOVERNANCE` | 7 |
| `QUALITY_TESTING` | 6 |
| `SCALABILITY` | 6 |

## Generated Review Paper Draft

The generated draft and figures are stored in `paper_outputs/`.

Current main draft:

```text
paper_outputs/LCNC_IEEE_Conference_Review_Paper_Aman_Deepal.docx
```

The draft uses the completed extraction workbook and the 170-to-50 screening workbook as its evidence base. Before submission, the manuscript should be manually reviewed for formatting, venue-specific IEEE requirements, exact citation style, and quote/page-number verification.

## Reproducibility Notes

The extraction process created intermediate structured JSON files before writing to the final workbook. This was done to keep the workbook consolidation step controlled and auditable.

Recommended verification steps:

1. Open `pdf_manifest.csv` or `pdf_manifest.json` to confirm all 50 PDFs were discovered.
2. Inspect `extraction_outputs/P001.json` through `extraction_outputs/P050.json`.
3. Review `completed_review_extraction.xlsx`, especially `Evidence_Quotes`, `Quality_Appraisal`, and `Synthesis_Matrix`.
4. Check `EXTRACTION_REPORT.md` for assumptions, unavailable fields, and items needing human review.
5. Verify important claims against the original PDFs before using them in a final submission.

## Important Caveats

- This repository is an academic evidence archive for a student literature review.
- Some PDFs may be copyrighted by their publishers or authors. They should be used only for legitimate academic review, citation checking, and evidence verification.
- Automated extraction can miss layout-dependent information, especially tables, figures, footnotes, and scanned text.
- Fields marked `Not reported` or `Unclear` should not be treated as negative findings; they mean the information was not explicit or was ambiguous in the parsed source.
- The quality appraisal is a structured first-pass assessment and should be manually reviewed before final publication.

## Citation and Use

If this repository is used as supporting material, cite the final review paper or conference submission associated with this evidence package. When citing individual findings, cite the original research paper rather than this repository.

## Institution

Department of Computer Applications  
MIT Manipal  
Manipal Academy of Higher Education, India
