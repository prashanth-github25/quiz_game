# Quiz Mania – Git Fundamentals and Branching Strategy

## Project Overview
Quiz Mania is a simple Python-based quiz application. This project demonstrates Git fundamentals, version control, branching strategies, commits, merging and merge conflict resolution.

## Team Structure
The project is developed by a team of three developers.

- Developer 1: Main branch management and integration.
- Developer 2: Quiz functionality development.
- Developer 3: Testing, validation and bug fixes.

## Branching Strategy

We follow a Feature Branch Workflow.

| Branch | Purpose |
|---|---|
| `main` | Contains stable and tested code. |
| `feature/*` | Used to develop new features. |
| `fix/*` | Used to fix bugs and errors. |

### Development Workflow

1. Developers clone the project repository.
2. New features are developed in separate feature branches.
3. Meaningful commits are created for every change.
4. Changes are tested before integration.
5. Feature branches are merged into `main` after review.
6. Merge conflicts are resolved before completing the merge.

## Feature Development

**Feature branch:** `feature/quiz-improvements`

The following improvements were developed:

- Improved welcome interface.
- Added input validation.
- Added quiz performance statistics.
- Added replay functionality.

## Merge Conflict Resolution

A merge conflict occurs when different branches modify the same part of a file.

For demonstration, conflicting changes are introduced in the `main` and feature branches. The conflict is resolved manually by selecting the appropriate final code, followed by a successful merge.

## Git Commands Used

```bash
git init
git branch
git switch -c feature/quiz-improvements
git add .
git commit -m "Meaningful commit message"
git switch main
git merge feature/quiz-improvements
git log --oneline --graph --all --decorate
```

## Conclusion

This project demonstrates the practical implementation of Git version control, feature branching, meaningful commits, merging, merge conflict resolution and commit history visualization.