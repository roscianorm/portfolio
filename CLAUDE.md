# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static personal portfolio website for Miguel Rosciano — a frontend-focused software engineer. The entire site is a single `index.html` file with inline CSS (no build step, no framework, no dependencies).

## Development

Open `index.html` directly in a browser. There is no build process, dev server, or package manager involved.

## Structure

Everything lives in `index.html`:
- **Sections:** `#about`, `#projects` (with a `.projects-grid` of `.card` elements), and a footer
- **Styles:** Inline `<style>` blocks — a commented-out dark theme exists at the top, and project card styles below it
- **Fonts:** Inter via Google Fonts CDN

## Design Notes

- The dark theme (body background `#2b2b2b`, link color `#61dafb`) is commented out — light theme is currently active
- Project cards use a responsive CSS grid (`auto-fit, minmax(280px, 1fr)`) and pill-shaped tag badges
- No JavaScript is used anywhere in the project
