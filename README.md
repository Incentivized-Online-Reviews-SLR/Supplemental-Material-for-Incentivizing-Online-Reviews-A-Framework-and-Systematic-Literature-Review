# Supplemental Material for *Incentivizing Online Reviews: A Framework and Systematic Literature Review of Strategies and Effects*

This repository contains the supplemental materials accompanying the manuscript *Incentivizing Online Reviews: A Framework and Systematic Literature Review*. The repository provides the complete study sample, coding scheme, coding results for psychological and behavioral outcome, and publication outlet information.

## Repository Contents

### [`systematic_review_complete_sample.csv`](./systematic_review_complete_sample.csv)

Contains the complete sample of publications (N=148) included in the systematic literature review. For each publication, the dataset reports the search strategy through which the study was identified, bibliographic information (title, authors, publication year), study characteristics (empirical/theoretical), as well as the investigated incentives.

This file represents the final study sample used in the review.

---

### [`coding_scheme.csv`](./coding_scheme.csv)

Contains the complete coding scheme applied during the systematic literature review. The file documents all coding categories, constructs, and operational definitions that guided the coding process.

This coding scheme served as the basis for coding every study contained in [`systematic_review_complete_sample.csv`](./systematic_review_complete_sample.csv).

---

### [`coding_psychological_outcome.csv`](./coding_psychological_outcome.csv)

Contains the coding framework for psychological outcomes identified in the reviewed literature. The file includes all psychological constructs together with their operational definitions.

---

### [`coding_behavioral_outcome.csv`](./coding_behavioral_outcome.csv)

Contains the coding framework for behavioral outcomes identified in the reviewed literature. The file documents all behavioral constructs together with their operational definitions.

---

### [`outlets_journals.csv`](./outlets_journals.csv)

Lists all journals represented in the final study sample together with their corresponding journal rankings.

---

### [`outlets_conferences.csv`](./outlets_conferences.csv)

Lists all conferences represented in the final study sample together with their corresponding conference rankings.

## Repository Structure

```text
systematic_review_complete_sample.csv
                  │
                  ▼
          coding_scheme.csv
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
coding_psychological_   coding_behavioral_
      outcome.csv             outcome.csv

Additional publication information:
├── outlets_journals.csv
└── outlets_conferences.csv
```

## Workflow

The files are intended to be used together:

1. The complete study sample is provided in [`systematic_review_complete_sample.csv`](./systematic_review_complete_sample.csv).
2. The coding framework applied to all included studies is documented in [`coding_scheme.csv`](./coding_scheme.csv).
3. Detailed coding definitions for psychological and behavioral outcomes are provided in [`coding_psychological_outcome.csv`](./coding_psychological_outcome.csv) and [`coding_behavioral_outcome.csv`](./coding_behavioral_outcome.csv), respectively.
4. Information on the publication venues represented in the final sample is available in [`outlets_journals.csv`](./outlets_journals.csv) and [`outlets_conferences.csv`](./outlets_conferences.csv).

Together, these materials provide transparent documentation of the study selection and coding procedures and facilitate transparency and reuse of the systematic literature review.
