# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static website that displays a fullscreen image. The site is hosted on GitHub Pages at https://github.com/ahilario/marctapalla.github.io.

## Project Structure

- **index.html**: Main HTML file that displays the image fullscreen
- **Mikasa Ackerman.jpg**: The image displayed on the website (736x1308 pixels)
- **.claude/**: Claude configuration directory

## Technology Stack

- Pure HTML/CSS (no JavaScript framework)
- Hosted on GitHub Pages

## Development Commands

Since this is a static HTML site, there are no build commands. To view the site locally:
1. Open `index.html` in a web browser
2. Or use a simple HTTP server: `python -m http.server 8000` or `npx serve`

## Git Commands

- Stage all changes: `git add .`
- Commit changes: `git commit -m "commit message"`
- Push to GitHub: `git push origin main`

## GitHub Pages Deployment

The site will automatically deploy when changes are pushed to the main branch on GitHub.