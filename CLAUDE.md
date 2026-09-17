# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

Research notes for "Italy2026" (topic so far: AI agents and econometric estimators). There is no code, build system, test suite, or linter. The only content is `notes.txt`, a plain-text outline with numbered, underlined section headings.

## Working here

- Treat `notes.txt` as the primary document. Keep its existing format: numbered section titles underlined with dashes, plain text, no Markdown.
- Do not add build tooling, package manifests, or test scaffolding unless asked.
- Remote is `origin` at `git@github.com:flyingliudi/Italy2026.git` over SSH. `main` has no upstream configured yet, so the first push needs `git push -u origin main`. On some networks port 22 to GitHub is blocked; SSH over port 443 (`ssh.github.com`) is the workaround.
