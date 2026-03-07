# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is the `conorluddy/conorluddy` GitHub profile README repo. The single `README.md` file renders on Conor's GitHub profile page. The goal is to maintain an active, up-to-date bio featuring:

- Personal intro and social links
- Recent blog posts from conor.fyi
- Active GitHub projects and their status
- Products currently in development (Afterset, Grapla, etc.)

## Structure

- `README.md` — the only file that matters. This renders directly on the GitHub profile.

## Conventions

- Content is written in GitHub-flavoured markdown
- Links use inline format: `[text](url)`
- Sections use backtick-styled labels for visual consistency (e.g. `` `Photography` [`Instagram`](url) ``)
- Keep it concise — this is a profile card, not a blog post

## Key URLs

- Website: https://www.conor.fyi/
- Afterset (iOS app): https://apps.apple.com/us/app/afterset/id6756236020
- Grapla (BJJ app): https://www.grapla.app/
- LinkedIn: https://linkedin.com/in/cluddy
- Code style guide: https://www.conor.fyi/writing/codestyle

## Workflow

- No build step, linter, or tests — this is a pure markdown repo
- Use `gh` CLI for PR-based changes (never push directly to main)
- To preview changes, render the markdown locally with `glow README.md` or check the GitHub preview after pushing to a branch
