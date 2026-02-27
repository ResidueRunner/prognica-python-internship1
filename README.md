# PubMed Article Extractor

## Objective
Fetch 50 PubMed articles using NCBI E-utilities API for the keyword "oncology biomarkers".

## Implementation
- Used esearch to retrieve PMIDs
- Used efetch to retrieve XML metadata
- Extracted:
  - PMID
  - Title
  - Authors
  - Abstract
  - Publication Date
  - Journal
- Cleaned whitespace and handled missing values

## Output
`pubmed_articles.json` contains an array of 50 formatted article objects.
