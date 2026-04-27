# Pantry

A web app I built to track everything in my fridge, pantry, and freezer. It saves what I have, what it cost, and what I can cook with it. The whole thing runs in a single HTML file with no backend, no accounts, and no signup. Data saves to the device it's opened on.

I built it because I kept buying duplicates of things I already had and forgetting what was about to expire.

## Features

- **Stock tracking** — three locations (fridge, pantry, freezer), with photos, quantities, calories, food groups, prices, and stores per item.
- **Price history** — every price update logs the previous one with a date, and item rows show an arrow when the price has changed since last time.
- **Recipes** — add a recipe with structured ingredients, and the app tells you what fraction of the ingredients you currently have. When you have everything, a "Cook" button appears that auto-deducts the amounts from your stock.
- **Shopping list** — automatically aggregates low-stock items and missing recipe ingredients, with one-tap copy to clipboard.
- **Receipt scanning** — takes a photo of a receipt and pulls out the line items using on-device OCR. No cloud, no API keys.

## How to run it

Open `pantry.html` in any modern browser. That's it. No install, no build step.

For phone use, host it somewhere (I used GitHub Pages) and add it to your home screen from Safari.

## Stack

React 18, Tailwind CSS, lucide icons, Tesseract.js for OCR. Everything loads from a CDN at runtime so the file stays portable.

## Credits

Built with [Claude](https://claude.ai) (Anthropic). Uses [React](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/), [lucide-react](https://lucide.dev/), [Tesseract.js](https://tesseract.projectnaptha.com/), [Babel Standalone](https://babeljs.io/docs/babel-standalone), and [esm.sh](https://esm.sh/). Font is [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans). Background photo from [Unsplash](https://unsplash.com/). Hosted on [GitHub Pages](https://pages.github.com/).
