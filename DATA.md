# Source Data

## Dataset

**Open University Learning Analytics Dataset (OULAD)**

The dataset contains anonymised data about courses, students, assessments and interactions with a Virtual Learning Environment.

It contains data for more than 30,000 students and is distributed across linked CSV files.

## Official Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset

## Direct ZIP Download

https://archive.ics.uci.edu/static/public/349/open+university+learning+analytics+dataset.zip

The ZIP is approximately 44.6 MB compressed.

## Licence

CC BY 4.0.

Teams must retain appropriate attribution to the original dataset source in their repository documentation.

## Main Files

- `courses.csv`
- `assessments.csv`
- `studentAssessment.csv`
- `studentInfo.csv`
- `studentRegistration.csv`
- `vle.csv`
- `studentVle.csv`

## Data Handling Rules

Teams should create:

```text
data/
├── README.md
├── raw/
└── processed/
```

### Raw

Original source files belong in `data/raw/`.

Do not manually edit raw files.

Because some files are large, teams may choose not to commit them to GitHub. If raw files are excluded, include download instructions and use `.gitignore`.

### Processed

Generated analytical datasets belong in `data/processed/` where appropriate.

Processed data should be reproducible from source files and code.

## Provenance

Participants may work under the project framing of the **Confidential Digital Higher Education Provider**, but the original data provenance must remain documented.

Do not claim that the public OULAD data is private data supplied by a real current Mettelo client.
