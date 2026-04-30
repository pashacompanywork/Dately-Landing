# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Landing page for **Dately** — an iOS dating tracker app. Static single-page site with no build system, no dependencies, no framework.

## Architecture

- `index.html` — entire site in one file (HTML + inline CSS + inline JS)
- `images/` — app screenshots and icons used on the page
- No package.json, no bundler, no CSS preprocessor

## Development

Open `index.html` directly in a browser. No build step or dev server required.

## Key Details

- Brand color: `#C17B50` (warm copper/terracotta)
- Dark sections use `#1A1A1A` background
- App Store link: `https://apps.apple.com/us/app/dately-dating-journal-diary/id6761208917`
- Legal docs hosted externally at `pashacompanywork.github.io/Legal_Docs/`
- All styles are inline in `<style>` block; all JS is inline in `<script>` block at bottom
- Responsive breakpoint at 768px
- Carousel has 3 slides with autoplay (4s interval) and touch swipe support
