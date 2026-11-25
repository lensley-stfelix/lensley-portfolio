# Study Notebook

An offline Python desktop application built to organize computer science coursework in a single local study workspace.

## Problem and solution

Course materials often span text notes, diagrams, screenshots, and videos. Study Notebook keeps these resources together in individual lessons, with offline HTML previews and portable Markdown exports.

## Features

- Import existing text and Markdown lessons in numerical course order.
- Paste notes and clipboard images, and attach local images or video files.
- Preview lessons with embedded media in a browser.
- Reorder lessons manually or restore course order from original files.
- Delete and recover lessons without losing their attached media.
- Persist notes, lesson ordering, and attachments locally.

## Technologies

Python, Tkinter, Pillow, JSON, HTML, and Markdown. The companion transcript exporter uses Beautiful Soup and Playwright.

## Engineering focus

File-based persistence, backward-compatible updates, local media handling, recoverable deletion, and automated tests for storage and ordering.

Source code upload is pending. Personal study notes and media are intentionally excluded from this public repository.
