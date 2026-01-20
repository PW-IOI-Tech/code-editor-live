# Project Name

A short description of what this project does and why it exists.

This project is maintained under **PW Institute of Innovation – Open Source** and follows real-world open-source development practices.

---

## Getting Started

### Prerequisites

- Git
- Required language/runtime (Node.js / Python / Java, etc.)

### Installation

```bash
git clone https://github.com/ORG_NAME/REPO_NAME.git
```

```bash
cd REPO_NAME
install dependencies here
run the project here
```

---

## Project Structure

```text
src/
docs/
tests/
.github/
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

- **Original Author(s):** Name(s) / Github handle(s)
- **Maintainers:** See repository contributors

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

---

## Code of Conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

---

## License

Add your license information here.
