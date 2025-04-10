# Consumer Insight Mining via Unstructured Web Data

This project explores how publicly available consumer conversations on automotive forums can be mined and analyzed to support brand strategy and competitive positioning. Using Python, NLP, and statistical modeling, we extract brand-level insights and visualize brand relationships through co-occurrence analysis and dimensionality reduction techniques.

---

## Project Objectives

- Identify and extract consumer language around car brands and models from automotive forum posts.
- Uncover patterns in how consumers mention and associate brands in organic discussions.
- Map the competitive landscape based on co-occurrence and clustering of brand mentions.
- Provide interpretable insights to inform marketing and positioning strategy.

---

## Key Insights

### 1. Zipf’s Law & Word Usage Patterns
Analysis of term frequency revealed that a small number of words dominate consumer conversation. This is consistent with Zipf’s Law and highlights:
- Core topics of interest (e.g., performance, price, reliability).
- Differences in vocabulary density across brand communities.

**Implication**: Messaging and content strategies should align with high-frequency vocabulary within brand-specific discussions to better resonate with target audiences.

### 2. Brand-Model Mapping
By matching mentions of specific models to brands, we created a clean brand-model frequency map. This enabled:
- Recognition of flagship models driving brand reputation.
- Identification of niche or underrepresented products.

**Implication**: Marketing resources could be aligned with the most-discussed models to maximize brand relevance and reach.

### 3. Co-Occurrence & Lift Analysis
Lift ratios for brand pairs were calculated to assess how often two brands were mentioned together relative to chance. Key observations include:
- Strong positive lift between certain competing brands (e.g., Honda–Toyota, BMW–Audi).
- Negative or neutral lift between brands targeting different market segments.

**Implication**: Co-mentioned brands represent competitive sets in the minds of consumers. Marketers can monitor these pairings for cross-targeting opportunities or differentiation efforts.

### 4. Multi-Dimensional Scaling (MDS)
Using the lift-based brand similarity matrix, we applied MDS to create a 2D map of brand relationships. Results show:
- Clusters of brands perceived similarly by consumers.
- Clear separation between economy and luxury brands.

**Implication**: The spatial representation offers a strategic tool for identifying market gaps, adjacent competitors, and potential repositioning opportunities.

---

## Methodology Overview

- **Web Scraping**: Collected user comments from automotive forums using Selenium.
- **NLP Processing**: Tokenization, frequency analysis, stopword removal with NLTK.
- **Statistical Analysis**: Zipf's law validation, lift computation with contingency tables.
- **Visualization**: Used scikit-learn's MDS and matplotlib to plot brand clusters.

---

## Tools Used

- Python
- Selenium (web scraping)
- NLTK (natural language processing)
- Statsmodels and Scikit-learn (analysis and modeling)
- Matplotlib (visualization)

---

## Potential Applications

- Competitive brand monitoring based on real consumer perception.
- Content optimization by aligning with naturally occurring discussion themes.
- Strategic marketing based on brand clusters and adjacency analysis.
- Early detection of brand or product associations forming in public discourse.

---

## About the Project

This project was developed as part of a course on unstructured data analysis. It demonstrates how forum conversations—an often-overlooked data source—can be transformed into structured intelligence for strategic decision-making in marketing.


