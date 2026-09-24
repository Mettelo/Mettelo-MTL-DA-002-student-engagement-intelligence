# Raw Data

Place the original downloaded OULAD source files in this folder.

## Expected Files

- `courses.csv`
- `assessments.csv`
- `studentAssessment.csv`
- `studentInfo.csv`
- `studentRegistration.csv`
- `vle.csv`
- `studentVle.zip` — compressed source containing `studentVle.csv`

## Large File Handling

`studentVle.csv` is approximately 454 MB uncompressed, so it must not be committed directly to normal GitHub storage.

The compressed `studentVle.zip` is approximately 44 MB and can be stored directly in this private repository.

Do not extract `studentVle.csv` and commit the extracted file.

## Raw Data Rules

- Do not manually edit source files.
- Preserve original filenames where practical.
- Do not place processed or cleaned datasets in this folder.
- Derived datasets belong in the team's own `data/processed/` folder.
- Keep the original dataset attribution and provenance documented.

## Original Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset
