# Raw Data

Place the original downloaded OULAD source files in this folder.

## Expected Files

- `courses.csv`
- `assessments.csv`
- `studentAssessment.csv`
- `studentInfo.csv`
- `studentRegistration.csv`
- `vle.csv`
- `studentVle.zip` — compressed source for the very large `studentVle.csv`

## Large File Handling

`studentVle.csv` is approximately 454 MB uncompressed, so it must **not** be committed to normal GitHub storage.

For this project, keep the compressed `studentVle.zip` in this folder using **Git LFS**.

The repository-level `.gitattributes` file marks `data/raw/*.zip` for Git LFS.

### Uploading studentVle.zip

From a local clone of this repository:

```bash
git lfs install
git pull
cp /path/to/studentVle.zip data/raw/studentVle.zip
git add .gitattributes data/raw/studentVle.zip
git commit -m "Add raw student VLE dataset"
git push origin main
```

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
