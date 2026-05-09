# Font Previewer

A minimal, mobile-first web tool to preview and compare Google Fonts side-by-side.

## Motivation

Comparing typography on mobile devices often involves switching between tabs or scrolling through long lists. This tool provides a **dual-pane, swipable interface** similar to a native mobile app, allowing for immediate visual comparison of two different fonts using realistic editorial content.

Inspired by [typetester.org](https://www.typetester.org) and the [Downstyler](https://github.com/waldyrious/downstyler) project.

## Features

- **Mobile-First Design**: Uses CSS Scroll Snap for native-feeling swipe gestures between comparison panes.
- **Searchable Selectors**: Search through ~40 popular Google Fonts using a simple datalist input.
- **Dynamic Loading**: Fonts are fetched on-the-fly from the Google Fonts API (including Regular, Bold, and Italic variants).
- **Refined Typography**: Inherits fluid scaling and logarithmic heading sizes inspired by `Downstyler` for a high-quality editorial look.
- **Desktop Friendly**: Includes clickable navigation arrows and full mouse/keyboard support.

## Implementation

- **Single-File Architecture**: Entirely contained within `index.html` (HTML/CSS/JS).
- **Semantic Source**: Sample text uses semantic line breaks for better readability in the code.
- **Vanilla Tech**: No dependencies, no build steps. Just open the file in a browser.

## Usage

1. Open `index.html`.
2. Type a font name (e.g., "Merriweather" or "Roboto") into the search box at the top of either pane.
3. Swipe left/right or use the arrow buttons to compare the two panes.
