# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

Marketing site for Enchiridion Labs (enchiridionlabs.online) — infrastructure for AI agents. Single static HTML file with all CSS and JS inline. No build step, no dependencies, no framework.

## Deployment

Hosted on GitHub Pages from the `main` branch. Push to `main` and it's live.

- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — prevents Jekyll processing

## Architecture

Everything lives in `index.html`: markup, styles (in a `<style>` block), and behavior (in a `<script>` block). Design tokens are CSS custom properties in `:root`. The site uses Google Fonts loaded via `<link>` (Fraunces, Crimson Pro, JetBrains Mono).

## Development

Open `index.html` in a browser. No server needed. To preview changes, refresh the browser.
