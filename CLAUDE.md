# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **GitHub profile README repository** (`jc-discdev/jc-discdev`). It contains a single `README.md` that GitHub renders as the public profile page for the user `jc-discdev`. There is no application code, build system, or test suite.

## Structure

| File | Purpose |
|---|---|
| `README.md` | The GitHub profile page, rendered at github.com/jc-discdev |
| `LICENSE` | MIT License (2021, JC) |

## README Widgets

The `README.md` uses three externally-hosted widgets that render dynamically:

- **Ko-fi button** — `https://ko-fi.com/F1F359ANJ` — donation/support link
- **Lanyard Discord Presence** — `https://lanyard-profile-readme.vercel.app/api/354178131680165888` — shows live Discord activity for user ID `354178131680165888`
- **GitHub Stats card** — `github-readme-stats.vercel.app` — displays contribution stats for `jc-discdev` with `theme=dark`

These are standard `[![alt](image-url)](link-url)` Markdown image-link patterns. The widgets are rendered by third-party services at request time; no local assets exist.

## Development

Editing this repository means editing `README.md` directly. Changes take effect on the GitHub profile as soon as they are merged to `main`. There are no commands to run locally.

To preview locally, use any Markdown renderer (e.g. VS Code's built-in preview with `Ctrl+Shift+V`), keeping in mind that the dynamic badge images will only render correctly if you have an internet connection.
