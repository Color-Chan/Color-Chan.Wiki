---
description: Create well-documented pull requests with comprehensive descriptions.
---

# Pull Request Skill

## Usage

```
/pr
```

## Behavior

1. Analyze commits since branching from main
2. Generate a descriptive PR title
3. Create detailed description with:
    - Summary of changes
4. Create PR via `gh pr create`

## PR Template

Title: PBI xxxxx | Short title describing change

```markdown
## Summary

Brief description of changes

## Changes

- List of specific changes made
```

## Requirements

- GitHub CLI (`gh`) installed and authenticated
- On a feature branch (not main)
