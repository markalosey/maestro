# Git Workflow Command

## Usage

/git-workflow

## Purpose

Execute complete git workflow for file changes in MAESTRO project

## Behavior

1. `pwd` (verify location)
2. `git status` (check state)
3. `git add .` (stage changes)
4. `git commit -m "descriptive message"` (commit)
5. `git push origin main` (push)

## When to Use

- After creating new files
- After modifying existing files
- Before ending a session
- When user requests file changes
- After implementing MAESTRO features

## MAESTRO-Specific Commit Messages

Use descriptive commit messages that reference MAESTRO components:

- `feat(backend): add new API endpoint for document processing`
- `fix(frontend): resolve UI issue in mission tracking`
- `docs: update installation guide for Docker setup`
- `refactor(ai): improve agent coordination logic`
- `test: add unit tests for RAG pipeline`

## Examples

```bash
# After adding a new API endpoint
git commit -m "feat(backend): add document search API endpoint"

# After fixing a frontend component
git commit -m "fix(frontend): resolve mission status display issue"

# After updating documentation
git commit -m "docs: update quickstart guide with new setup steps"
```
