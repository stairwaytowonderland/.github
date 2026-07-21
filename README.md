# stairwaytowonderland

[![Continuous integration](https://github.com/stairwaytowonderland/.github/actions/workflows/ci.yaml/badge.svg)](https://github.com/stairwaytowonderland/.github/actions/workflows/ci.yaml)
[![GitHub latest release](https://img.shields.io/github/v/release/stairwaytowonderland/.github?include_prereleases&logo=rocket)](https://github.com/stairwaytowonderland/.github/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/stairwaytowonderland/.github/main?logo=git)](https://github.com/stairwaytowonderland/.github/commits/main)
[![GitHub license](https://img.shields.io/github/license/stairwaytowonderland/.github?logo=opensourceinitiative)](https://github.com/stairwaytowonderland/.github/tree/main/LICENSE)
[![semantic-release: conventionalcommits](https://img.shields.io/badge/semantic--release-cc-FE5196?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?logo=pre-commit&logoColor=black)](https://github.com/pre-commit/pre-commit)

## :pushpin: Overview

Public organization info.

## :cactus: Project structure

<details>
<summary><b>Project file structure</b> <i>(click to expand) ...</i></summary><br>

> :seedling: `tree -a -F -L 3 -I '.git|.vscode' --gitignore --dirsfirst .`

```none
./
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── 01_bug_report.yml
│   │   ├── 02_feature_request.yml
│   │   ├── 03_documentation.yml
│   │   ├── 04_task.yml
│   │   └── config.yml
│   ├── workflows/
│   │   ├── ci-meta.yaml
│   │   ├── ci-package-update.yaml
│   │   ├── ci.yaml
│   │   ├── conventional-commit.yaml
│   │   ├── licensed.yaml
│   │   ├── linter-nodejs.yaml
│   │   ├── linter.yaml
│   │   ├── normalize-majorver.yaml
│   │   ├── pre-commit.yaml
│   │   ├── publish.yaml
│   │   ├── release.yaml
│   │   ├── repository-created.yaml
│   │   ├── repository-dispatched.yaml
│   │   ├── repository-stargazed.yaml
│   │   ├── stargazers.yaml
│   │   └── terraform-deploy.yaml
│   ├── CODEOWNERS
│   ├── dependabot.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── profile/
│   └── README.md
├── .editorconfig
├── .gitignore
├── .markdownlint.json
├── .pre-commit-config.yaml
├── .prettierignore
├── .prettierrc
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── SECURITY.md
```

</details>

---

## :sparkles: Contributing

### :speech_balloon: Commit Message Guidelines

- Write clear, concise commit messages that follow the
  [![conventional-commit](https://img.shields.io/badge/conventional--commit-FE5196?logo=conventionalcommits&logoColor=white)](https://www.conventionalcommits.org/)&nbsp;standard.
- The allowed _prefixes_ for this project are the following:

    ```json
    [
      "build",
      "chore",
      "ci",
      "docs",
      "feat",
      "fix",
      "perf",
      "refactor",
      "revert",
      "style",
      "test"
    ]
    ```

> [!NOTE]
>
> See [Contributing Guidelines](https://github.com/stairwaytowonderland/repository-template?tab=contributing-ov-file#contributing-guidelines)
> for more information.
