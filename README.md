# COMPASS

COMPASS is a lightweight AI research discovery platform that helps researchers, students, and engineers stay up to date with the latest developments in Artificial Intelligence. It aggregates research papers from OpenAlex/arXiv sources, ranks them using BM25-based relevance scoring, identifies emerging trends.

## Live 

https://alvi-uiu.github.io/COMPASS/

---

## Features

* Research Search — Search AI papers with relevance-based ranking.
* Research Feed — Discover the latest papers across AI, Machine Learning, NLP, Computer Vision, Robotics, and related fields.
* Trending Research — Identify emerging papers using recency and citation signals.
* Saved Papers & Collections — Bookmark and organize papers into custom collections.
* AI News Feed — Track AI-related discussions & news.
* Learning Hub — Explore educational content on core AI concepts such as Transformers and Attention.

---

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* OpenAlex API
* Hacker News Algolia API

---

## Core Capabilities

### Intelligent Ranking

COMPASS combines multiple signals to rank papers:

```text
Score =
(BM25 Relevance)
+ Citation Impact
+ Recency
+ Exact Match Boost
```

### Research Analysis

Generate structured research briefs including:

* Major themes
* Frequent keywords
* Leading authors
* Emerging topics
* Suggested reading order

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/COMPASS.git
cd COMPASS
```

Run locally:

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

---

## Project Structure

```text
COMPASS
├── OpenAlex Integration
├── BM25 Ranking Engine
├── Trend Analysis
├── News Aggregator
├── Collections Manager
└── UI & Rendering Layer
```

---

## License

MIT License

