# Collaboration Demo Project

This project is used to practice Git and GitHub collaboration workflows.

## How to contribute
1. Open an issue describing your proposed change
2. Create a branch from main
3. Make your changes
4. Submit a pull request
5. Address review comments
6. Wait for CI checks to pass
7. Get approval and merge
This project uses GitHub Actions for continuous integration.
The pipeline runs on every push and pull request.

## Setup Instructions

```bash
git clone https://github.com/YOUR-USERNAME/collaboration-demo.git
cd collaboration-demo
```

## Code Style Guidelines
- Use meaningful commit messages
- Reference issues in PR descriptions
- Keep changes focused on single issue
- Run CI checks before requesting review

## Example Workflow
1. `git checkout -b feature-name`
2. Make changes
3. `git add . && git commit -m "feat: description"`
4. `git push origin feature-name`
5. Create PR on GitHub


## Commit Message Examples
**Good:**
\`feat: add user authentication\`
\`fix: resolve login timeout issue\`

**Bad:**
\`update\` or \`fix stuff\`

## Before Requesting Review
- Ensure all CI checks pass (green ✓ in GitHub)
- Rebase your branch on latest main if needed
- Self-review your changes

