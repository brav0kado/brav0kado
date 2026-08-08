# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

GitHub **profile README** repo (`brav0kado/brav0kado`). The single `README.md` renders on the owner's GitHub profile page. There is no application, no build system, no tests, and no dependencies — do not invent build/lint/test commands.

## Structure

- `README.md` — the entire deliverable. Everything else is git plumbing.

## Working notes

- The README was generated with **GPRM** (https://gprm.itsvg.in) — see the trailing HTML comment. Regenerating there overwrites hand edits, so prefer editing `README.md` directly.
- Content is driven by external badge/stat services rendered as images: `img.shields.io` (tech-stack badges), `github-stats-extended.vercel.app` (top-langs card), `quotes-github-readme.vercel.app` (dev quote), `visitcount.itsvg.in` (visitor counter). These render only on GitHub — a local Markdown preview won't fetch them the same way. Verify appearance by pushing and viewing the GitHub profile.
- The username `brav0kado` is hard-coded into several badge/stat URLs; keep it consistent when editing links.

## Conventions

- Owner uses Conventional Commits (imperative mood, no trailing period). Recent history is README-only.
- Do not commit or push without the owner asking.
