# IMC Prosperity 2023 & 2024

This repository contains my work (code, analysis, and write-ups) for the IMC Prosperity algorithmic trading challenges in 2023 and 2024.

---

## Overview of IMC Prosperity

IMC Prosperity is a global, fantasy-themed trading challenge hosted by IMC Trading. Over a multi-day simulation, teams compete to “bring the most prosperity to their virtual island” by trading various fictional assets (e.g., amethysts, starfruit, coconuts) in a continuously evolving market. Each edition consists of five rounds, combining both algorithmic trading (using code and quantitative models) and manual trading (solving probability/math problems under timed conditions). Prosperity attracts thousands of university-level teams worldwide, testing participants on market-making, arbitrage, statistical prediction, and strategic decision-making under realistic market constraints .

- **Duration:**  
  - 2023 edition (15-day simulation)  
  - 2024 edition (15-day simulation)  
- **Structure (per round):**  
  1. **Algorithmic trading:** Implement a program that interacts with IMC’s simulated order books, ingesting live data feeds, computing fair values, and submitting buy/sell orders to maximize island “seashell” profits.  
  2. **Manual trading:** Solve short-duration probability or optimization problems (e.g., bidding in an auction model) under time pressure.

---

## Team & Personal Role

I participated as part of a **five-person team** in both editions. All team members were in Bachelor/Master programs at the time, balancing this competition alongside thesis and coursework commitments.

- **2023 Edition:**  
  - Fully engaged throughout the 15 days.  
  - My responsibilities:   
    - Implementing the market-making logic in Python (order-book ingestion, strategy backtesting).
    - Designing the core fair-value model for new assets (e.g., using volume-weighted midprices to filter noise).
    - Leading the analysis of new historical data to develop predictive signals / strategies for new products .
    - Collaborating on manual-trading solutions, focusing on probability-based auctions.  
  - **Results:**  
    - 1st place in France (100+ teams)  
    - 51st globally (10,000+ teams)

- **2024 Edition:**  
  - Due to thesis deadlines, team involvement was more limited, yet we remained consistent contributors.  
  - My responsibilities:  
    - Refining and modularizing our existing code base for faster backtesting of strategies.  
    - Leading the analysis of Round 2 historical data to improve our predictive signals.  
  - **Results:**  
    - Top 500 worldwide (14,000+ teams)

---

## Repository Structure

```
IMC-Prosperity-2023-2024/
├── 2023/
│   ├── algorithmic/     ← Python scripts, notebooks, and backtests for 2023
│   └── manual/          ← LaTeX write-ups or Jupyter notebooks for manual rounds (probability/optimization)
├── 2024/
│   ├── algorithmic/     ← Refactored code base for 2024, with modular strategy files
│   └── manual/          ← Solution write-ups to 2024 manual rounds
├── plots/               ← Performance charts (PnL over time, PnL distribution, etc.)
├── README.md            ← This file
└── .gitignore           ← Ignored files/folders (e.g., data dumps, pycache)
```


- **`2023/algorithmic/`** 

- **`2023/manual/`**  

- **`2024/algorithmic/`**  

- **`2024/manual/`**  

- **`plots/`**  


---

## Contact & Feedback

If you have questions about any of my implementations or want to discuss the strategies in more detail, feel free to open an Issue or reach out to me at raphael.dangelo@edhec.com.


