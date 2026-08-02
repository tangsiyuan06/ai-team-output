# Everything-in-AI Interview Demo

An independent static introduction site for [Everything-in-AI](https://github.com/tangsiyuan06/Everything-in-ai), built for the ROOT AI Native full-stack exercise.

## What it demonstrates

- Select either an AI product company or an indie game studio.
- Edit the team name, objective, three role responsibilities, and collaboration rule.
- Run a transparent, deterministic local collaboration replay and inspect three output cards.
- Persist the selected template and team configuration using browser `localStorage`.

The replay is intentionally local and deterministic. It is not a live LLM or a replacement for the source project's multi-agent engine.

## Technical choices

- One dependency-free `index.html` with inline CSS and JavaScript.
- Versioned local storage with invalid-data fallback to the default template.
- No API keys, backend, build tool, or external database required.

## Scope and next steps

This demo focuses on the "define -> run -> output" loop. It does not reproduce real agent scheduling, SSE, authentication, or collaboration. A next iteration would connect the replay panel to the original project's observable agent events while retaining the current safe local fallback.
