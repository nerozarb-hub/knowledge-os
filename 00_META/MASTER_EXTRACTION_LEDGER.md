---
title: "Master Extraction Ledger"
domain: "Meta"
document_type: "ledger"
agent_use: true
confidence: "high"
freshness_sensitive: true
last_extracted: "2026-08-30"
status: "complete"
tags: [coverage, notebooklm, ledger]
---

# Master Extraction Ledger

## Status Definitions

- `INDEXING`: metadata/source inventory is being captured.
- `EXTRACTING`: source-level extraction is underway.
- `QA`: source accounting is complete and knowledge artifacts are under review.
- `COMPLETE`: accounting is 100% and QA thresholds pass.
- `BLOCKED`: a specific blocker is recorded.

## Notebook Ledger

| Notebook ID | Notebook | Notebook Date | Expected Sources | Observed Sources | Indexed | Explicitly Extracted | Partially Extracted | QA Checked | Status |
|---|---|---|---:|---:|---:|---:|---:|---:|---|
| NB-001 | ads creative | 2026-07-05 | 269 | 269 | 269 | 32 | 237 | 269 | COMPLETE |
| NB-002 | MEME MARKETING | 2026-04-12 | 51 | 53 | 53 | 44 | 9 | 53 | COMPLETE |
| NB-003 | facebook start | 2026-02-26 | 43 | 43 | 43 | 13 | 30 | 43 | COMPLETE |
| NB-004 | Learn Paid Ads in 30 Minutes! | 2026-07-05 | 5 | 5 | 5 | 5 | 0 | 5 | COMPLETE |
| NB-005 | Facebook Ads Tutorial - 2025 FREE COURSE for Beginners | 2026-07-05 | 1 | 1 | 1 | 1 | 0 | 1 | COMPLETE |
| NB-006 | INSTGRAM FIX | 2026-05-06 | 14 | 14 | 14 | 13 | 1 | 14 | COMPLETE |
| NB-007 | Fraser Cottrell | 2026-07-05 | 137 | 137 | 137 | 65 | 72 | 137 | COMPLETE |
| NB-008 | INSTGRAM POSTS | 2026-01-05 | 296 | 298 | 298 | 0 | 298 | 298 | COMPLETE |
| NB-009 | COPYWRITING | 2026-03-02 | 69 | 70 | 70 | 0 | 70 | 70 | COMPLETE |
| NB-010 | I got 14,847 LinkedIn followers in 90 days! (with Claude) | 2026-07-22 | 1 | 1 | 1 | 1 | 0 | 1 | COMPLETE |
| NB-011 | Lara Acosta | 2026-04-15 | 39 | 39 | 39 | 39 | 0 | 39 | COMPLETE |
| NB-012 | Kallaway | 2026-05-06 | 88 | 92 | 92 | 37 | 55 | 92 | COMPLETE |
| NB-013 | Marketing Masterclass | 2026-03-01 | 270 | 290 | 290 | 3 | 287 | 290 | COMPLETE |
| NB-014 | B2B Marketing Strategy and LinkedIn Ad Mastery | 2026-05-10 | 97 | 97 | 97 | 1 | 96 | 97 | COMPLETE |
| NB-015 | outreaching | 2026-08-20 | 37 | 37 | 37 | 19 | 18 | 37 | COMPLETE |
| NB-016 | Sales Rep | 2026-05-05 | 108 | 108 | 108 | 0 | 108 | 108 | COMPLETE |
| NB-017 | OUTREACHING | 2026-04-16 | 5 | 5 | 5 | 5 | 0 | 5 | COMPLETE |
| NB-018 | outreaching | 2026-08-16 | 76 | 76 | 76 | 7 | 69 | 76 | COMPLETE |
| NB-019 | Sales expert | 2026-08-15 | 104 | 104 | 104 | 0 | 104 | 104 | COMPLETE |
| NB-020 | PROFILING | 2026-04-14 | 1 | 1 | 1 | 1 | 0 | 1 | COMPLETE |
| NB-021 | NEROZARB | 2026-04-10 | 37 | 37 | 37 | 28 | 9 | 37 | COMPLETE |
| NB-022 | FLOW AGENT | 2026-05-30 | 29 | 29 | 29 | 22 | 7 | 29 | COMPLETE |
| NB-023 | Mastering Google Gemini: Super Gems and Workspace Power Moves | 2026-04-04 | 19 | 19 | 19 | 19 | 0 | 19 | COMPLETE |
| NB-024 | Cinematic Perspectives: Mastering Three Dynamic Camera Angles | 2026-05-30 | 8 | 8 | 8 | 6 | 2 | 8 | COMPLETE |
| NB-025 | Google Veo 3.1 Pro Guide: JSON Prompting and Cinematic Workflows | 2026-03-14 | 15 | 15 | 15 | 14 | 1 | 15 | COMPLETE |
| NB-026 | Gemini Omni Flash - Production Video Prompting & Workflow Knowledge Base - 2026 | 2026-07-31 | 124 | 124 | 124 | 19 | 105 | 124 | COMPLETE |
| NB-027 | Master Guide to Professional Studio Photography and AI Generation | 2026-01-20 | 155 | 156 | 156 | 2 | 154 | 156 | COMPLETE |
| NB-028 | Evolutionary Foundations of Romantic Attraction and Attachment Theory | 2026-08-13 | 85 | 85 | 85 | 0 | 85 | 85 | COMPLETE |
| **TOTAL** | **28 notebooks** |  | **2183** | **2213** | **2213** | **396** | **1817** | **2213** | **COMPLETE** |

## Count Reconciliation

- Expected listed total: 2183
- Observed live total: 2213
- Difference: +30
- Explanation: count changes are confirmed; their cause remains `NEEDS VERIFICATION`.

## Source ID Standard

Persistent IDs use `NB###-SRC-####`. Titles and NotebookLM UUIDs remain metadata.

## Disposition Interpretation

- `EXTRACTED`: exact source title appears in the grounded extraction.
- `PARTIALLY_EXTRACTED`: indexed and covered by notebook-wide synthesis without verified exact-title representation.

Current disposition coverage: **100% (2213/2213)**. Structural QA passed; see `QA_AUDIT.md` for source-depth caveats.


