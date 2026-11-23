# imertekin.github.io

Personal site served at https://imertekin.com via GitHub Pages.

## Site structure

- Static HTML only — no build step, no framework.
- The site is English-only (`lang="en"`); there is no language toggle and no Turkish UI.
- Articles live under `writing/`.
- `yazilar/*/index.html` are redirect stubs (meta refresh + JS) that send the old Turkish article URLs to their English versions. Keep them; the Turkish texts are in git history.

## Commit rules

- Message in English, imperative mood, summary line ≤72 characters (e.g. "Add …", "Fix …", "Publish …").
- If the reason is not obvious, add a blank line and then a short "why" paragraph.
- One commit = one meaningful change. Do not mix unrelated edits.
- No meaningless messages: "update", "Add files via upload", "wip", "fix stuff", etc.
- Commits are authored by İlkay Murat Ertekin <40001929+imertekin@users.noreply.github.com> only. No `Co-Authored-By`, `Claude-Session` or "Generated with" trailers.
- Before pushing, check the message with `git log -1`.
- Never force-push to `main`.
