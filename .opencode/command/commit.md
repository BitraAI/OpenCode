
---
description: Generate a Conventional Commit message from staged changes and commit
---

Inspect the staged changes using `git diff --cached` and `git status`.

Generate a concise Conventional Commit message in this format:

`<type>(<scope>): <description>`

Use one of: feat, fix, refactor, docs, test, chore, perf.

Requirements:
1. Base the message only on the staged changes.
2. If nothing is staged, stop and tell me to stage changes first.
3. Do not stage additional files automatically.
4. Do not push to the remote.
5. Show the proposed commit message before committing.
6. Commit only after I approve the message.
