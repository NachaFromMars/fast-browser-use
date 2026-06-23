# fast-browser-use — Rust-powered browser automation at native speed

> A Rust-based browser automation engine driving Chrome directly via CDP — up to 10x faster than Puppeteer. Built for speed, stealth, and high-volume automation.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
fast-browser-use controls Chrome through the Chrome DevTools Protocol using a compiled Rust binary, eliminating the Node.js overhead that slows down Puppeteer. Built-in recipes handle bot-detection bypass (mouse jitter + random delays), form filling, and data scraping. A strong fit for high-volume tasks where both latency and detection resistance matter.

## Features
- **~10x faster than Puppeteer** — Rust binary, direct CDP, no Node overhead
- **Bot-detection bypass** — mouse jitter and randomized delays
- **Form filling** — automated input recipes
- **Scraping** — structured data extraction workflows
- **Cross-platform** — macOS and Linux

## Usage / Quick Start
```bash
# Install
brew install rknoche6/tap/fast-browser-use
# or
cargo install fast-browser-use

# Required env
export CHROME_PATH="/path/to/chrome"
```

## Trigger Keywords (OpenClaw)
fast browser, Rust browser automation, CDP browser, fast-browser-use

## Related Skills
- [browser-use](https://github.com/NachaFromMars/browser-use) — full-featured Python browser automation
- [agent-browser](https://github.com/NachaFromMars/agent-browser) — snapshot-driven browser CLI

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
