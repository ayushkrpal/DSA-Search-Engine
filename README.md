# AlgoLens

A semantic DSA problem discovery engine that helps users search coding problems across competitive programming platforms using TF-IDF ranking and cosine similarity.

## Features
- Search coding problems instantly
- TF-IDF ranking system
- Cosine similarity matching
- Problem scraping using Puppeteer
- Responsive frontend UI
- Fast Express.js backend

## Tech Stack
- Node.js
- Express.js
- Puppeteer
- Natural.js
- HTML/CSS/JavaScript

## Architecture
1. Scrape problems from coding platforms
2. Merge and preprocess datasets
3. Generate TF-IDF vectors
4. Rank results using cosine similarity
5. Return top relevant matches

## Installation

```bash
npm install
```

## Run Scraper

```bash
npm run scrape
```

## Merge Datasets

```bash
npm run merge
```

## Start Development Server

```bash
npm run dev
```

## Future Improvements
- Semantic vector search
- Redis caching
- Difficulty filters
- Personalized recommendations
- Typo-tolerant search
