# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a ZIP Image Viewer - a simple web-based application that allows users to view images contained within ZIP files by dragging and dropping them into the browser.

## Architecture

The entire application is contained in a single HTML file (`index-web.html`) that includes:
- HTML structure
- CSS styling (dark theme)
- JavaScript functionality using JSZip library (loaded from CDN)

## Key Features

- Drag & drop ZIP files
- Extracts and displays images (.jpg, .jpeg, .png, .gif, .bmp, .webp)
- Keyboard navigation with arrow keys (← →)
- Shows current image name and position
- No server or installation required

## Project Guidelines

- Keep the application simple and self-contained in a single HTML file
- Ensure compatibility with modern browsers
- Handle errors gracefully (corrupted ZIP files, non-image files)
- Maintain memory efficiency when processing large ZIP files