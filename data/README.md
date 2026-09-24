# Data Workspace

This folder contains the source-data guidance for **MTL-DA-002 — Student Engagement, Retention & Academic Performance Intelligence**.

## Folder Structure

```text
data/
├── README.md
├── raw/
├── reference/
└── metadata/
```

## raw/

Use `data/raw/` for the original OULAD source files.

Expected files:

- `courses.csv`
- `assessments.csv`
- `studentAssessment.csv`
- `studentInfo.csv`
- `studentRegistration.csv`
- `vle.csv`
- `studentVle.csv`

Do not manually edit these files.

## reference/

Use `data/reference/` for supporting reference material such as:

- source documentation;
- field descriptions;
- licence notes;
- external reference mappings;
- approved contextual lookup files.

## metadata/

Use `data/metadata/` for Mettelo-maintained metadata such as:

- provenance notes;
- source links;
- extraction/download notes;
- data inventory;
- schema documentation.

## Official Dataset Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset

Direct ZIP:

https://archive.ics.uci.edu/static/public/349/open+university+learning+analytics+dataset.zip

## Licence

CC BY 4.0.

The source dataset must remain attributed in project documentation.

## Important

This master repository may contain either:

- the actual raw files, where practical; or
- download/source instructions if file-size or storage considerations make direct storage unsuitable.

The team repositories should follow the separate repository standard in `/submission/TEAM_REPOSITORY_STANDARD.md`.
