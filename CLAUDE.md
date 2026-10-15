# imertekin.github.io

Personal site served at https://imertekin.com via GitHub Pages.

## Site structure

- Static HTML only — no build step, no framework.
- Every page carries both languages side by side as `class="ui" lang="tr|en"` pairs; the language toggle shows one and hides the other.
- When you add or change visible text, add/update **both** the TR and the EN element. Never leave a string in only one language.
- Turkish articles live under `yazilar/`, their English counterparts under `writing/`.

## Commit rules

- Message in English, imperative mood, summary line ≤72 characters (e.g. "Add …", "Fix …", "Publish …").
- If the reason is not obvious, add a blank line and then a short "why" paragraph.
- One commit = one meaningful change. Do not mix unrelated edits.
- No meaningless messages: "update", "Add files via upload", "wip", "fix stuff", etc.
- Commits are authored by İlkay Murat Ertekin <40001929+imertekin@users.noreply.github.com> only. No `Co-Authored-By`, `Claude-Session` or "Generated with" trailers.
- Before pushing, check the message with `git log -1`.
- Never force-push to `main`.
