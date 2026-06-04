# 🐛 DefinitelyNotJira

A fake Jira ticket generator for weddings, bachelor parties, and other critical production incidents.

**[→ Open it](https://kmb5.github.io/fakejira/)**

## What it does

Generates a realistic-looking Jira bug ticket you can fill in and export as a PNG. Useful for printing, slideshows, or handing to a groom as his final task before getting married.

## Usage

1. Edit any field by clicking on it
2. Adjust priority from the toolbar
3. Switch language with the **EN / HU** toggle (URL updates to `?lang=hu` — shareable)
4. Hit **⬇ Export PNG** — always exports a clean desktop-sized image even on mobile

## Stack

Single `index.html` — no build step, no dependencies, no excuses.  
Export powered by [html-to-image](https://github.com/bubkoo/html-to-image) (SVG foreignObject renderer, avoids html2canvas font spacing bugs).

Deployed on GitHub Pages.
