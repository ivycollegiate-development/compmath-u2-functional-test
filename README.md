# Unit 2 Functional Test — Campus Network Threat Data

## Test Overview

50-minute live coding test on the VPS. You will:

1. **Load & Clean** `threats_raw.csv` with an audit trail (`clean_threats.py`)
2. **Chart 1**: Daily timeline of phishing reports + failed logins (`project_charts.py`)
3. **Chart 2**: Weekday vs weekend average phishing reports (same file)
4. **Analysis**: Three-paragraph `analysis.md` (audience, key number, limitation each)

## Setup

```bash
cd ~
git clone https://github.com/ivycollegiate-development/compmath-u2-functional-test.git functional-test
cd functional-test
ls
```

You should see `threats_raw.csv` in this directory. **Do not modify the raw CSV.**

## Files in this repo

- `threats_raw.csv` — the raw dataset (8 comment lines, 61 data rows, intentional defects)
- `README.md` — this file

## Submission

Write your scripts in this directory, commit, and push to your own repo:

```bash
git init
git add .
git commit -m "Unit 2 functional test submission"
git remote add origin https://github.com/ivycollegiate-development/compmath-u2-functional-test-$(whoami)_student.git
git push -u origin main
```

Then open a PR on GitHub and submit the PR link to Classroom.

**Password prompt = Personal Access Token, not your GitHub password.**
