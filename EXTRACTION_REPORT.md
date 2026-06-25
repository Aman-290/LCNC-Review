# Extraction Report

Generated: 2026-06-12

## Run Summary

- PDFs found: 50
- PDFs processed successfully: 50
- Failed or unparseable PDFs: 0
- Per-paper JSON files: extraction_outputs/P001.json through extraction_outputs/P050.json
- PDF manifest files: pdf_manifest.csv and pdf_manifest.json
- Final workbook: completed_review_extraction.xlsx

## Failed or Unparseable PDFs

- None

## Assumptions Made

- Paper IDs are assigned by numeric filename order.
- No external bibliographic sources were used; extraction is based on parsed PDF text and file metadata.
- Quality appraisal is an automated rubric application from parsed text and should be treated as first-pass scoring.

## Fields Commonly Unavailable or Unclear

- Human_Reviewer: 50 paper(s)
- Country_or_Region: 50 paper(s)
- Discipline_Field: 50 paper(s)
- Location_Context: 50 paper(s)
- Most_Important_Table_Figure: 50 paper(s)
- Theoretical_Implications: 50 paper(s)
- Contrasts_With_Papers: 50 paper(s)
- Citation_BibTeX: 50 paper(s)
- Domain_Code: 46 paper(s)
- Time_Period: 41 paper(s)
- Sample_Size: 31 paper(s)
- DOI: 24 paper(s)
- Source_URL: 24 paper(s)
- Research_Questions_or_Hypotheses: 22 paper(s)
- Definition_of_No_Code: 20 paper(s)

## Items Needing Human Review

- Verify automated title, author, venue, method, sample size, limitations, and theme coding for all papers.
- Verify exact quotes and page numbers against the original PDF layout before manuscript use.
- Review fields marked Not reported or Unclear; many PDFs do not explicitly state all workbook fields.

## Verification Notes

- Workbook sheet order was preserved: START_HERE, Master_Extraction, Evidence_Quotes, Quality_Appraisal, Theme_Codebook, Synthesis_Matrix, Method_Taxonomy, Controlled_Vocab, Agent_Prompt, Dashboard.
- Formula columns were preserved rather than overwritten in Master_Extraction, Quality_Appraisal, Synthesis_Matrix, Method_Taxonomy, and Dashboard.
- No formula-error strings were found by the artifact-tool scan.
- Rendered sheet previews were created under extraction_outputs/workbook_previews for visual QA.

## Caveats

This is a conservative automated extraction from parsed PDF text. Fields marked "Not reported" were not found explicitly in the parsed PDF text. Fields marked "Unclear" need human review because the parsed evidence was ambiguous or the title/discipline/method could not be reliably resolved.
