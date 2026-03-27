# Vertical-AI-Companies

Static tracker page for Vertical AI companies, styled in a polished black-and-white direction inspired by Harvey.ai.

## Overview

This repository contains a single static page at `index.html`.

The page is intentionally:

- data first
- monochrome
- lightweight
- easy to expand as more companies are added

The initial tracker includes:

- OpenEvidence
- Abridge
- Harvey

## References

This project takes structural inspiration from:

- [hsmahon/ai-dev-tool-startups](https://github.com/hsmahon/ai-dev-tool-startups)
- [hsmahon/inference-companies](https://github.com/hsmahon/inference-companies)

## Tracked Fields

Each company row includes:

- `Company`
- `Headcount`
- `Funding Round`
- `Amount Raised`
- `Careers Page`
- `Sources`

## Updating The Tracker

To add another company:

1. Open `index.html`.
2. Find the `<tbody>` inside the main table.
3. Copy an existing `<tr>` block.
4. Update the company name, metrics, careers link, and source links.

## Design Notes

The current design keeps the interface close to the reference trackers while applying a more polished monochrome presentation:

- almost-black background
- subtle grid texture
- crisp borders and row dividers
- compact heading block above the table

No build step is required. Open `index.html` directly in a browser.
