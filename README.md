# Thomas Verheul

**Data Scientist · Engineering Physics background**

Python developer with 6+ years building data-driven systems, focused on quantitative trading and machine learning. My physics training taught me to decompose complex, multi-variable problems into testable pieces and to validate results the way deterministic systems demand — reproducible, documented, and robust out of sample.

Currently building random-forest trading systems and exploring how ML models hold up under live, changing market conditions.

---

### Skills

**Languages:** Python (proficient) · TypeScript (working)
**Data Science:** Pandas · NumPy · SciPy · scikit-learn · Matplotlib · Seaborn
**Tools & Infra:** MongoDB · Git/GitHub · Linux (Ubuntu) · multiprocessing

---

### Featured Work

#### Crypto Trading Bot — *Forest Chart Algorithm* (2025–Present)
Live algorithmic trading system for Ethereum on the Hyperliquid DEX, running on 5-minute candles.

- Three-pillar architecture: hard-coded rule filters, a random forest classifier for trade decisions (HOLD / LONG / SHORT), and a weekly walk-forward calibration routine.
- Diagnosed that the rule-layer grid search was masking feature-level improvements; redesigned the test methodology to isolate the feature signal, cutting classifier overfit from **12.7% → 1.8%** and raising accuracy from **62% → 73.5%**.
- Reduced simulation-to-live profit inaccuracy from **0.216% → 0.052%** by modeling trade-entry delay and reverse-engineering Hyperliquid's execution behavior.
- Delivered weekly written reports and presentations translating methodology and results for a non-technical advisory board.

#### NFT Trading Bot (2022–2026)
Algorithmic collection-selection system placing offers on the Ethereum mainnet.

- Stayed profitable across a **90% drop** in market volume; tested forest classifiers, forest regression, gradient boosting, and a custom ML model.
- Reverse-engineered marketplace queries to scrape data no API exposed — pulling in a single request what the official API needed **100 calls** for.
- Built a keyword-based Twitter/X scraper that prevented **~60%** of potential high-risk purchases by catching collection announcements early.
- Built and led a small remote team (7 hires total, up to 3 concurrent): recruitment, sprint planning, and technical mentorship alongside core development.

---

### Background

**BASc, Engineering Physics** — The Hague University of Applied Sciences (2019–2024)
Coursework spanning statistics, signal processing, control engineering, linear algebra, and numerical methods. Thesis work included an end-to-end Laser-Induced Breakdown Spectroscopy measurement system (Spectral Industries) and a closed-loop induction-furnace control system (Tata Steel).

---

### Get in touch

- 📍 Netherlands
- 💼 [LinkedIn](https://www.linkedin.com/in/thomas-verheul)
- 📫 your-email@outlook.com
