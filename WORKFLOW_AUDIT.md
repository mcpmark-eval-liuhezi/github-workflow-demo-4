# Workflow Audit

This page documents how the four pillars of a tidy GitHub workflow fit
together: **branch**, **pull request**, **issue**, and **close-out**.

## Branch

Every change starts on a dedicated feature branch off the default branch
(e.g. `main`).

- `feature/audit-notes` — a working branch for the workflow audit documentation.
- Naming convention before a number, e.g. `feature/<short-description>`.

## Pull Request

A branch is never merged directly. It is proposed as a pull request,
whichtlists the diff between the branch and the default branch.

- Branch `feature/audit-notes` → PR `Add workflow audit notes` merges into `main`.
- Leaving the PR open during review keeps the history explicit and auditable.

## Issue

Work items live in issues so that requirements, questions, and small
follow-ups are tracked separately from code changes.

- `Demo: workflow checklist` — tracks the workflow checklist itself.
- A follow-up issue is attached as a sub-issue for granular progress tracking.

## Close-Out

Tracking and closing are the final step of the loop.

- Checklist issue: comment "Checklist complete, closing this out".
- Checklist issue: closed as **completed**; follow-up issue left open.

## Owner

- **Login:** HeziLiu
- **Name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
- **Profile:** https://github.com/HeziLiu
