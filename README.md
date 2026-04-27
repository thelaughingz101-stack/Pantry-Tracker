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

Open `index.html` in any modern browser. That's it. No install, no build step.

For phone use, host it somewhere (I used GitHub Pages) and add it to your home screen from Safari.

## Stack

React 18, Tailwind CSS, lucide icons, Tesseract.js for OCR. Everything loads from a CDN at runtime so the file stays portable.

## Credits

This project was developed with the assistance of [Claude](https://claude.ai) by Anthropic.

### Technologies and Services

- [React](https://react.dev/) — Frontend user interface framework  
- [Tailwind CSS](https://tailwindcss.com/) — Styling and layout system  
- [lucide-react](https://lucide.dev/) — Icon set  
- [Tesseract.js](https://tesseract.projectnaptha.com/) — On-device optical character recognition  
- [Babel Standalone](https://babeljs.io/docs/babel-standalone) — In-browser JSX compilation  
- [esm.sh](https://esm.sh/) — ES module delivery  
- [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans) — Typography  
- [Unsplash](https://unsplash.com/) — Background imagery [Photo by Bri RTP on Unsplash](https://unsplash.com/photos/white-ceramic-sink-with-stainless-steel-faucet-Kukdz3VKzNc?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)
- [GitHub Pages](https://pages.github.com/) — Deployment and hosting  
