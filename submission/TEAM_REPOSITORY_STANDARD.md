# Mandatory Team Repository Standard

Each approved team must create its **own GitHub repository** for MTL-DA-002.

The team's repository is the official project submission.

## 1. Repository Name

Use:

```text
MTL-DA-002-<team-name>
```

Example:

```text
MTL-DA-002-north-star-analytics
```

Use lowercase for the team-name portion and hyphens instead of spaces.

## 2. Repository Visibility

The repository may be **private during delivery**.

If private, the Team Lead must add the designated Mettelo reviewer GitHub account as a collaborator before submission.

A GitHub organisation itself generally cannot be added as a collaborator to an externally owned private repository. Mettelo will provide the reviewer username/account to use.

Do not make the repository public unless all data, licensing and Mettelo publication requirements have been checked.

## 3. Mandatory Repository Structure

Every team repository must contain:

```text
MTL-DA-002-<team-name>/
│
├── README.md
├── CONTRIBUTIONS.md
├── requirements.txt              # if Python is used
├── .gitignore
│
├── data/
│   ├── README.md
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── 01-discovery/
│   ├── 02-data-model/
│   ├── 03-kpi-catalogue/
│   ├── 04-responsible-analytics/
│   └── 05-technical-handover/
│
├── sql/
│
├── src/
│
├── notebooks/
│
├── analysis/
│
├── dashboard/
│   └── README.md
│
├── deliverables/
│   ├── executive-briefing/
│   └── presentation/
│
└── submission/
    └── FINAL_SUBMISSION.md
```

Folders that are not technically required may contain a `README.md` explaining why they were not used. Do not simply delete required sections without explanation.

## 4. README Requirements

The repository-level `README.md` must contain:

- Project ID and title;
- team name;
- team members and roles;
- short business-problem summary;
- solution overview;
- architecture/data-flow summary;
- instructions to reproduce the work;
- links to dashboard/output;
- links to final deliverables;
- known limitations;
- source-data attribution.

A reviewer should understand the project from the README without searching through the repository.

## 5. Git Workflow

Teams should use GitHub as evidence of collaborative delivery.

Minimum expectations:

- meaningful commits;
- issues for significant work items;
- branches for substantial changes;
- pull requests for material merges where practical;
- peer review for important code/model changes;
- no single person uploading the entire final solution at the end.

Suggested branches:

```text
feature/<description>
analysis/<description>
data/<description>
docs/<description>
fix/<description>
```

## 6. File Naming

Use meaningful file names.

Good:

```text
student_engagement_model.sql
withdrawal_analysis.ipynb
kpi_catalogue.md
data_quality_report.md
executive_briefing.pdf
```

Avoid:

```text
final.ipynb
final2.ipynb
newfinal.pbix
test123.csv
document1.pdf
```

## 7. Large Files

Do not commit unnecessarily large generated files.

If a Power BI file, recording or other artefact is stored in approved shared storage, add a clear link in:

- `dashboard/README.md`; and
- `submission/FINAL_SUBMISSION.md`.

## 8. Reproducibility

The repository must allow a technically competent reviewer to understand how the solution was created.

Where relevant include:

- environment requirements;
- dependency file;
- SQL execution order;
- notebook order;
- transformation instructions;
- data download instructions;
- dashboard refresh instructions.

## 9. Contribution Evidence

`CONTRIBUTIONS.md` must record each person's actual contribution.

Mettelo may compare this record with:

- commit history;
- issues;
- pull requests;
- code reviews;
- documentation;
- presentation evidence.

The purpose is verification, not ranking by commit count.


## Mandatory Mettelo Access

Every team delivery repository **must grant Mettelo access** for review, verification and project-quality assurance.

### If the repository is owned by a team member or another organisation

The Team Lead must invite the **designated Mettelo reviewer GitHub account** as a collaborator.

### If the repository is created inside the Mettelo GitHub organisation

The required Mettelo reviewer/team access must be retained.

### Submission rule

A repository will **not be treated as a complete Mettelo submission until Mettelo access has been granted and verified**.

The Team Lead is responsible for ensuring that:

- the invitation has been sent;
- the designated Mettelo reviewer can open the repository;
- the reviewer can inspect code, documentation, issues, pull requests and contribution history;
- access remains available throughout review and verification.

Do not remove Mettelo access until the project review and verification process is complete.

