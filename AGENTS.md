# AGENTS.md

## Scope
- This file applies to the entire repository.

## Repository State
- The repository is currently minimal and does not yet contain application source files.
- Prefer small, additive changes that establish structure without assuming frameworks or tooling that are not present.

## Working Rules
- Read the repository state before making changes.
- Preserve user changes. Do not revert or overwrite unrelated work.
- Keep edits narrowly scoped to the requested task.
- Match existing patterns when they appear. If none exist, choose the simplest maintainable approach.

## File and Tooling Conventions
- Use ASCII by default unless a file already requires another character set.
- Add comments only when they materially improve comprehension.
- Use the project's `uv` environment by default for Python work in this repository.
- Treat packages installed into the project `uv` environment as the source of truth for dependencies available during work sessions.
- When additional Python packages are needed for the task, install them into the project `uv` environment instead of using a global interpreter.
- Do not add dependencies, build tools, or frameworks unless the task requires them.

## Validation
- Run the smallest relevant verification for the change.
- If no automated checks exist, state that explicitly in the handoff.

## Handoff
- Summarize what changed.
- Note any validation performed.
- Call out follow-up work only when it is actually needed.
