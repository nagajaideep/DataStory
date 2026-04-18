# Data Stories —— AI Research Narratives

An editorial-style, dark-themed data storytelling platform built with high-fidelity visualizations and deep research narratives. This project features two primary data stories focused on the modern AI landscape.

## 🌓 Features

- **Dark Editorial Design**: Inspired by "Curio Ledger," featuring serif typography, gold accents, and glassmorphism.
- **Dynamic Interactions**: Animated bar charts, interactive search filters, and smooth entrance animations.
- **Gemma 4 Deep Dive**: A comprehensive look at Google DeepMind's latest open-weight model, including GQA, SwiGLU, and context window innovations.
- **Sentiment Benchmark**: A head-to-head comparison of top open-source emotion models (DistilRoBERTa, GoEmotions, BART) across Plutchik's framework.
- **Zero Backend**: Fully static HTML/CSS/JS application for instant performance and easy deployment.

## 📂 Project Structure

```text
datastory/
├── index.html                  # Landing page with story hub
├── index.css                   # Core design system & UI tokens
├── assets/                     # Generated visual assets and favicon
└── stories/
    ├── gemma-4/                # Gemma 4 report & benchmarks
    └── sentiment-models/       # Sentiment analysis model comparison
```

## 🚀 Getting Started

### Prerequisites
- Any modern web browser.
- (Optional) Node.js or Python to run a local server (recommended for asset handling).

### Running Locally
1. Clone the repository or download the files.
2. Open a terminal in the project root.
3. Run one of these commands:
   ```bash
   # Using Node (npx)
   npx http-server . -p 8090
   
   # Using Python
   python -m http.server 8090
   ```
4. Visit `http://localhost:8090` in your browser.

## 🛠️ Technology Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Design System)
- **Logic**: Vanilla JavaScript (ES6+)
- **Typography**: Playfair Display (Serif), Inter (Sans), JetBrains Mono (Code)

---
*Built with curiosity in 2026.*
