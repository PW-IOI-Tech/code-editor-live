# Code Editor Live

A lightweight, browser-based live code editor that allows users to write and preview HTML, CSS, and JavaScript in real time.
This project exists to help learners and developers instantly see the output of their code without setting up a local environment.

This project is maintained under **PW Institute of Innovation – Open Source** and follows real-world open-source development practices.

---

## Getting Started

### Prerequisites

- Git
- A modern web browser (Chrome, Edge, Firefox, Safari)
- No additional runtime or backend required

### Installation

```bash
git clone git@github.com:PW-IOI-Tech/code-editor-live.git
```

```bash
cd code-editor-live
open index.html
```

---

## Project Structure

```text
code-editor-live/
├── src/
│   ├── index.html
│   ├── styles.css
│   └── script.js
├── docs/
│   ├── screenshots/
│   └── README.md
├── tests/
│   └── editor.test.md
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml        # Template for reporting bugs
│   │   ├── chore.yml             # Template for maintenance tasks
│   │   ├── config.yml            # Issue template configuration
│   │   ├── documentation.yml     # Template for documentation updates
│   │   └── feature_request.yml   # Template for feature requests
│   └── pull_request_template.md
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md

```

---

## Git Flow

This project follows Git Flow:

| Branch     | Use case           |
| ---------- | ------------------ |
| main       | Production-ready   |
| develop    | Active development |
| feature/\* | New features       |
| bugfix/\*  | Bug fixes          |
| hotfix/\*  | Critical fixes     |

### Development Rules

- All work branches must be created from `develop`
- Pull Requests must target `develop`
- Direct commits to `main` are **not allowed**

### Hotfixes

- `hotfix/*` branches are created from `main`
- Hotfix PRs must be merged into both `main` and `develop`

### Releases

- Releases are prepared from `develop`
- Final merges go into `main`
- Releases are tagged using semantic versioning
  (`v1.0.0`, `v1.1.0`, etc.)

---

## Issues & Features

Use the provided Issue Templates:

- Bug Report
- Feature Request
- Documentation
- Chore

Blank issues are disabled.

## Label System

We use a consistent labeling system across all repositories.

| Issue Types     | Difficulty         | Status         | Priority           |
| --------------- | ------------------ | -------------- | ------------------ |
| `bug`           | `good first issue` | `help wanted`  | `priority: high`   |
| `feature`       | `easy`             | `in progress`  | `priority: medium` |
| `enhancement`   | `medium`           | `blocked`      | `priority: low`    |
| `documentation` | `hard`             | `needs review` |
| `refactor`      |                    |                |
| `chore`         |                    |                |
| `discussion`    |                    |                |

Please use:

- **One Issue Type**
- **One Difficulty**
- **One Priority (optional)**
- **One Status (maintainers only)**

This helps us triage and respond faster.

---

## Pull Requests

- Follow the PR template
- Link issues using Fixes #<issue-number>
- Ensure all checks pass before review

---

## Credits

- **Original Author(s):** [Zahid Shaikh](https://github.com/iamshkzahid)
- **Maintainers:** See repository contributors

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## Code of Conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

---

## License

Add your license information here.
