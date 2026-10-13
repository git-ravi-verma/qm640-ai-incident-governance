# qm640-ai-incident-governance
Reproducible data audit, NLP-assisted risk classification, and AI governance control mapping for a QM640 capstone study.
# NLP-Assisted Risk Classification and AI Governance Control Mapping

## Overview

This repository supports a QM640 Data Analytics Capstone study examining whether a reproducible analytics workflow can organise public generative AI and agentic AI security-event records into a human-reviewed risk taxonomy and map those themes to practical AI governance review questions.

Financial services is the application lens. The dataset is not assumed to consist exclusively of banking incidents, and results will not be interpreted as estimates of incident prevalence across banks.

## Research questions

1. What are the composition, evidence streams, metadata completeness, and data-quality characteristics of the frozen dataset?
2. What risk-theme taxonomy can be developed and applied consistently to a human-reviewed sample of records?
3. If the adjudicated labels provide sufficient class support, how well does TF-IDF with logistic regression classify risk themes compared with a majority-class baseline?
4. How can the resulting risk themes be mapped transparently to AI governance review questions?

## Data source

The study uses the GenAI & Agentic AI Security Incidents dataset, version 2.0.0, hosted on Zenodo:

https://zenodo.org/records/20248676

Consult the source record for its license and reuse conditions before redistributing any source data. See `data/README.md` for provenance, access instructions, and the project's data-handling decisions.

## Planned methods

- Dataset validation and descriptive statistics
- Human-reviewed risk-theme coding with explicit uncertainty handling
- TF-IDF text features and logistic regression, subject to adequate label support
- Majority-class baseline comparison
- Macro-F1, per-class precision and recall, confusion matrix, and error analysis
- Traceable mapping of risk themes to governance review questions

## Repository status

Analyses and results will be marked as completed only after they have been executed and checked. Proposed methods and hypotheses are not reported as findings.

## Limitations

Public incident records are subject to selection and reporting bias, inconsistent evidence, missing metadata, and uneven date precision. The dataset is not a representative sample of banking incidents. Classification performance depends on label quality and class support. Governance mappings are analytical aids, not proof of compliance or evidence that a control caused an outcome.

## Reproducibility

Reproducibility instructions, environment requirements, data dictionary, coding guide, analysis notebooks, and evaluation outputs will be documented in this repository as they become available.

## Academic context

Prepared for QM640: Data Analytics Capstone, Walsh College. See the accompanying synopsis for the full research design and references.
