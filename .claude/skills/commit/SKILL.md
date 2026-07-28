---
description: Create well-formatted git commits following conventional commit standards.
---

# Git Commit Skill

## Usage

```
/commit
```

## Behavior

1. Analyze staged changes with `git diff --staged`
2. Generate a conventional commit message
3. Create the commit with proper formatting
4. Never include yourself as a co-author

## Commit Format

```
<type>: <description>

[optional body]

[optional footer]
```

## Types

- feat: New feature
- fix: Bug fix
- docs: Documentation changes
- style: Code style changes
- refactor: Code refactoring
- test: Adding or modifying tests
- chore: Maintenance tasks

## Example Output

```
feat: add password reset functionality

- Add forgot password form
- Implement email verification flow
- Add password reset endpoint
```
