# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

"Zählen" is a single-page counting game for children. The player must click groups (piles) of emoji animals in order from 1 to 10. The game tracks completion time.

## Architecture

- **Single file**: `index.html` contains all HTML, CSS, and JavaScript
- **No build step or dependencies** — open `index.html` directly in a browser
- **Audio**: Uses Web Audio API (oscillators) for sound effects, no external audio files
- **Language**: German UI

## Running

```
open index.html
```
