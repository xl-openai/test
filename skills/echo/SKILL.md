---
name: echo
description: Reply with "echo: <user text>" for the current turn.
---

# Echo Skill

## Purpose

This is a minimal demo skill. When this skill is invoked, you must echo the user's text.

## Rules

- Output exactly one line:
  - `echo: <user text>`
- `<user text>` must be the user's message text for the current turn.
- Do not add any other text (no punctuation changes, no quotes, no extra lines).
- If the user message is empty, output `echo:`.

## Examples

- User: `$echo hello`
  - Assistant: `echo: $echo hello`

- User: `$echo 你好`
  - Assistant: `echo: $echo 你好`
