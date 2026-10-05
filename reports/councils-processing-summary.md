# SME Legal — Stage 05 Councils Processing

Date: 2026-10-05

## Scope
- CACS-FUNDEB: 305 documents
- CAE: 184 documents
- Fórum Municipal de Educação: 15 documents
- Total: 504/504 processed
- Historical WordPress corpus remains immutable at 256 resources.

## Processing states
- ANALISADO_TEXTO: 260
- ANALISADO_VISUAL: 22
- ANALISADO_EQUIVALENTE_HISTORICO: 2
- INDEXADO_VISUAL: 218
- ANALISADO_ANOMALIA_FONTE: 1
- ANALISADO_DUPLICATA_EXATA: 1

## Drive QA
- 504/504 expected individual files present.
- 0 missing and 0 duplicate filenames.
- 502/504 match manifest size exactly.
- Documents 1070 and 1071 preserve the canonical PDF bytes as an exact prefix and contain a 24,880-byte PDF incremental update in the Drive copy. Canonical exact bytes remain preserved in the GitHub artifact and ZIP packages.

## Key findings
- Lei Municipal 6.089/2018 in council documents 209/210 is the same legal act as historical DOC-0059, although the physical files differ from the historical corpus copy.
- CACS document 258 is miscataloged as Lei 10.880/2008; the PDF itself is Lei 10.880, de 9 de junho de 2004.
- CACS document 2517 is cataloged under Decretos but is a 2026 council-composition table.
- FME documents 2488 and 2734 are Resoluções SME 04/2025 and 05/2025 even though the portal section is Decretos; their period wording is internally inconsistent (2025-2027 vs 2025-2028).
- CACS document 1743 is a source attachment/label defect: its bytes and content are the CAE pauta 1652.
- Parecer CACS 002/2026 records a 4% FUNDEB reserve in a specific investment account for Educação em Tempo Integral.
- FME document 2494 is the monitoring/evaluation report for PME 2015-2024 and is a key evidence source for the transition to the next PME cycle.
