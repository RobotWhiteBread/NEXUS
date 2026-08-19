# NEXUS

**Document intelligence for the 2026 UAP records release.**

NEXUS is a research instrument that treats a large government document release as a dataset. It ingests the 2026 UAP records corpus and turns unstructured pages into structured, queryable evidence: autonomous document acquisition, OCR and structured extraction into a relational schema, then spatial statistics, time-series decomposition, anomaly detection, and redaction-pattern analysis across the corpus.

The premise is simple: a hundred and sixty-plus files of scanned government paper is not a reading assignment, it is a corpus. Names, dates, places, redactions, and document structure are all measurable, and measurement scales in a way that close reading cannot.

## What the instrument does

- Acquires and versions source documents so every claim traces back to a specific page of a specific release
- Extracts text, entities, dates, and locations into a relational schema built for reproducible queries
- Runs geographic clustering, temporal decomposition, and multiple independent anomaly-detection methods over the extracted corpus
- Analyzes redaction patterns as data in their own right

## Why this repo is quiet

NEXUS is an exploratory instrument. Hypotheses stay private until they are defensible, and nothing gets asserted publicly that has not survived the same claims-audit discipline used across every Anima Audire pipeline. Write-ups will appear here if and when findings clear that bar.

## Stack

`Python` · `SQLite/Postgres` · `OCR tooling` · `pandas` · `scikit-learn` · `spatial statistics` · `Docker`

---

Aaron Price · Anima Audire, LLC · [Profile](https://github.com/RobotWhiteBread) · aaron.price.unl@gmail.com
