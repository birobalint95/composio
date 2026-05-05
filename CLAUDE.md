# CLAUDE.md

## Starting a Task

When assigned an issue (e.g. "Work on issue: ALI-5"), always fetch the issue details before touching any files:

```bash
gh issue view 5 --repo birobalint95/composio
```

Extract the numeric part from the issue ID (ALI-5 → 5) and read the full title and description. If the issue cannot be fetched, run `ao report needs-input` and ask for clarification rather than guessing.
