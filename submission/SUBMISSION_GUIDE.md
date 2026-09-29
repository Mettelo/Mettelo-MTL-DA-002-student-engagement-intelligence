# Team Submission Guide

## Overview

For MTL-DA-002, teams submit a **GitHub repository**, not a folder inside the Mettelo master repository and not an email attachment.

The team's repository should represent the complete evidence trail of the project.

## Step 1 — Agree Your Team Name

Choose a unique team name.

Example:

`North Star Analytics`

Repository-safe version:

`north-star-analytics`

## Step 2 — Create the Team Repository

Create:

```text
MTL-DA-002-north-star-analytics
```

One repository per team.

Do not create a separate repository for each team member.

## Step 3 — Add Team Members

The Team Lead should add all team members as collaborators with appropriate access.

Each participant should use their own GitHub account so contribution history remains attributable.

Do not share one GitHub login across the team.

## Step 4 — Invite Mettelo to Your Repository — Mandatory

Before your project can be submitted, your team must give Mettelo access to the delivery repository.

### GitHub username to invite

```text
OlaoluwajohnsonT
```

### Step-by-step

1. Open your team project repository on GitHub.
2. Click **Settings**.
3. Select **Collaborators** or **Collaborators and teams**.
4. Click **Add people**.
5. Search for **OlaoluwajohnsonT**.
6. Select the matching GitHub user.
7. Send the invitation.
8. Confirm the invitation appears as sent/pending or accepted.
9. Keep the access active until Mettelo completes review and verification.

### Important

Your submission is **not complete until Mettelo can access the repository**.

Mettelo must be able to inspect:

- project files;
- commit history;
- branches;
- issues;
- pull requests;
- contribution records;
- final deliverables.

If the repository is already inside the Mettelo GitHub organisation, retain the existing Mettelo access.

## Step 5 — Build the Required Structure

Follow [TEAM_REPOSITORY_STANDARD.md](TEAM_REPOSITORY_STANDARD.md).

Your repository must contain the required folders and files before final submission.

## Step 6 — Work Through GitHub

During the project:

- create issues for meaningful tasks;
- assign owners;
- use branches for substantial work;
- make descriptive commits;
- use pull requests for major merges;
- document important decisions;
- maintain the contribution record.

Do not wait until Week 6 and upload everything in one commit.

## Step 7 — Complete FINAL_SUBMISSION.md

Create:

```text
submission/FINAL_SUBMISSION.md
```

It must contain:

### Submission details
- Project ID
- team name
- Team Lead
- team members
- submission date

### Repository
- repository URL
- default/final branch
- release/tag if used

### Deliverables
Links to each required deliverable D1–D10.

### Dashboard
Link/file location and access instructions.

### Key findings
Concise summary of major findings.

### Recommendations
Concise management recommendations.

### Known limitations
Important analytical, data and implementation limitations.

### Contribution evidence
Link to `CONTRIBUTIONS.md`.

### Declaration
Confirmation that the work is the team's own, sources are acknowledged, and the simulated client has not been represented as a real external Mettelo customer.

## Step 8 — Perform Your Own Final QA

Before submission verify:

- [ ] repository name follows the standard;
- [ ] GitHub user `OlaoluwajohnsonT` has been invited and access verified;
- [ ] README is complete;
- [ ] required structure exists;
- [ ] data-download instructions work;
- [ ] code is reproducible;
- [ ] dashboard link works;
- [ ] D1–D10 are present;
- [ ] CONTRIBUTIONS.md is complete;
- [ ] FINAL_SUBMISSION.md is complete;
- [ ] no secrets, passwords or API keys are committed;
- [ ] no prohibited personal information is included;
- [ ] source dataset is attributed;
- [ ] all external links are accessible.

## Step 9 — Submit the Repository URL

The final submission is the URL of the team's GitHub repository.

Example:

```text
https://github.com/<owner>/MTL-DA-002-north-star-analytics
```

Mettelo will later specify the central form or platform field into which the URL should be submitted.

**Do not send the project files by email.**

## Step 10 — Freeze the Reviewed Version

At the submission deadline, create a release or Git tag:

```text
mettelo-final-submission
```

or:

```text
v1.0-mettelo-submission
```

This provides a stable reference to the exact version submitted for review.

Teams may continue developing afterwards, but Mettelo will assess the tagged submission unless otherwise agreed.
