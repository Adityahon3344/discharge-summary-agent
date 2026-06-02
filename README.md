
# Discharge Summary Agent

## Overview
This project reads clinical source-note PDFs and generates a discharge summary draft.

## Features
- OCR-based PDF ingestion
- Diagnosis extraction
- Pending result detection
- No-fabrication guardrail
- Clinician review flags
- Agent trace generation

## Agent Workflow
1. Read PDF
2. Extract facts
3. Detect missing information
4. Detect pending results
5. Generate discharge summary
6. Generate trace log

## Safety
The system never invents facts. Missing information is flagged for clinician review.

## Limitations
- OCR errors may affect extraction quality.
- Medication reconciliation is not fully automated.
- Conflict detection is rule-based.

## Future Improvements
- LLM-based extraction
- Better medication reconciliation
- Multi-patient support
- Learning from clinician edits
