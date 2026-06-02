# PlayLAdev label taxonomy

This taxonomy is the current default for `linear-issue-labeler` in this repository.

Because the Linear workspace is not directly accessible from this repository context, these labels are grounded in the repository's existing triage labels and should be updated if the team uses different Linear label names.

Taxonomy version: `2026-06-02`

## Required label families

### Type (required: exactly one)

- `bug` — broken behavior, defects, or regressions
- `enhancement` — feature work or improvements
- `documentation` — docs-only updates or documentation debt
- `question` — clarification requests that need an answer before implementation

If issue evidence supports more than one type label, do not auto-add and create a repair proposal instead.

## Optional triage labels (human-managed, no auto-add)

- `duplicate`
- `invalid`
- `wontfix`
- `good first issue`
- `help wanted`

These labels require explicit human triage judgment and should only be suggested in repair proposals.

## Deprecated labels

No deprecated labels are currently defined for this repository.

When the team deprecates labels, list them here so the daemon never applies them.
