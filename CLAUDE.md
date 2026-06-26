# CLAUDE.md

Guidance for AI assistants (e.g. Claude Code) working in this repository.

## What this repository is

This is **`pratikvc18/pratikvc18`** — a GitHub **special/profile repository**.
Because the repo name matches the owner's username, GitHub renders its
`README.md` directly on the user's profile page at
`https://github.com/pratikvc18`.

There is **no application code, build system, package manager, test suite, or
CI** here. The entire deliverable is the rendered `README.md`. Treat this as a
content/documentation repo, not a software project.

## Repository structure

```
.
├── README.md      # The profile content shown on the GitHub profile page
└── CLAUDE.md      # This file — guidance for AI assistants
```

That's the whole repo. Do not assume hidden tooling exists.

## README content conventions

`README.md` follows the common profile-README format. When editing, preserve
these conventions:

- **Heading + intro**: An `## Hi, I'm Pratik 👋` heading followed by a short
  first-person intro. The user works at Welspun on yard digitalization and
  operations projects.
- **Sections** use `###` subheadings with an emoji (e.g. `### 🔧 What I'm
  working on`, `### 🛠️ Skills & tools`, `### 📊 My GitHub stats`).
- **Skill badges** use [Shields.io](https://shields.io) badge URLs in the form
  `![Name](https://img.shields.io/badge/Name-HEXCOLOR?style=flat&logo=LOGO&logoColor=white)`.
  Match the existing `style=flat` and per-technology brand colors/logos when
  adding badges.
- **Stats card** uses the
  `github-readme-stats.vercel.app/api?username=pratikvc18` service. Keep the
  `username=pratikvc18` query parameter correct if this block is changed.
- Tone is friendly, concise, and first-person ("I'm building…"). Keep it
  beginner-friendly — the user describes themselves as building development
  skills one project at a time.

## How to verify changes

There is nothing to compile or test. To verify edits:

1. Confirm the file is **valid GitHub-Flavored Markdown** and renders cleanly.
2. Check that every badge / external image URL is well-formed (Shields.io and
   github-readme-stats both fail silently to a broken-image icon if the URL is
   malformed).
3. Confirm `username=pratikvc18` is used consistently in any service URLs.

Markdown can be previewed in any editor; no local server is required.

## Git & contribution workflow

- The default branch is `main`.
- Development for AI-assisted tasks happens on a dedicated feature branch
  (currently `claude/claude-md-docs-grx8p5`) — do **not** commit directly to
  `main` unless explicitly told to.
- Use clear, descriptive commit messages.
- Push with `git push -u origin <branch-name>`.
- **Do not open a pull request unless the user explicitly asks for one.**

## Things to keep in mind

- Keep changes minimal and focused — this is a personal profile page, so
  factual accuracy about the user (employer, role, skills) matters more than
  volume of content.
- Don't introduce build configs, workflows, or dependencies unless the user
  asks to turn this into something more than a profile README.
- External badge/stat images depend on third-party services
  (img.shields.io, github-readme-stats.vercel.app); broken renders are usually
  a URL or service issue, not a repo problem.
