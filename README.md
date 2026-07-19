<div align="center">
  <h1>lailai0916 · GitHub defaults</h1>
  <p>English | <a href="README.zh-Hans.md">简体中文</a></p>
  <p>
    <img src="https://img.shields.io/github/last-commit/lailai0916/.github?style=flat-square" alt="last commit" />
    <img src="https://img.shields.io/github/license/lailai0916/.github?style=flat-square" alt="license" />
  </p>
</div>

## Project Introduction

Shared community health defaults for repositories owned by `lailai0916`. Repositories
without local overrides inherit the issue templates, pull-request checklist, contribution
guide, and security policy from this single source.

## Project Features

📮 **Issue intake** — bilingual bug and feature templates ask for reproducible,
actionable reports.

🔀 **Review baseline** — one pull-request checklist keeps scope, validation, documentation,
and Agent guidance visible during review.

🧭 **Contribution guide** — shared workflow and commit expectations apply wherever a
repository does not provide project-specific instructions.

🔒 **Security policy** — vulnerability reports use GitHub's private reporting channel
instead of public issues.

## Getting Started

GitHub applies these files automatically to repositories that do not contain a local file of
the same type. A repository can override a default by adding its own file. Any file under a
repository's `.github/ISSUE_TEMPLATE/` directory overrides the entire inherited issue-template
directory.

`lailai-template` intentionally retains one portable copy of the templates for repositories
created outside this account. Other repositories should keep only project-specific overrides.

## Project Structure

```bash
.github/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md           # shared bug report
│   │   ├── config.yml              # issue creation settings
│   │   └── feature_request.md      # shared feature request
│   ├── CONTRIBUTING.md             # contribution workflow
│   ├── PULL_REQUEST_TEMPLATE.md    # pull-request checklist
│   └── SECURITY.md                 # private vulnerability reporting
├── .gitignore                      # ignored local files
├── LICENSE                         # code license
├── README.md                       # English documentation
└── README.zh-Hans.md               # Simplified Chinese documentation
```

## License

This project's code is licensed under [MIT License](LICENSE).
