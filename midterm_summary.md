# AI Risk in 10-K Filings  
*How S&P 500 Firms Reacted to the Rise of AI*

This project explores how AI-related sentiment in annual 10-K filings influenced the stock performance of S&P 500 firms following the release of ChatGPT on November 30, 2022.

Using natural language processing techniques such as keyword matching and regular expressions, I identified themes like automation, productivity, cost-cutting, and data privacy risk. Firms were then grouped by high or low exposure to each theme, and their cumulative stock returns were compared during the event window.

---

## Key Themes Analyzed

- AI & Automation Exposure  
- AI-Driven Productivity Gains  
- AI-Based Cost Cutting  
- Data Privacy and Security Risk

---

## Methodology Overview

**Sentiment Analysis**  
Extracted AI-related mentions from 10-K filings using regex and thematic keyword sets.

**Portfolio Construction**  
Firms were divided into high and low exposure groups based on the median score for each AI-related theme.

**Return Analysis**  
Calculated cumulative returns for each firm within the event window surrounding ChatGPT’s public release.

**Statistical Modeling**  
Performed correlation analysis and regression modeling, controlling for firm characteristics such as size and profitability.

---

## Key Insights

- Firms with high automation exposure outperformed others during the event window.  
- Mentions of AI-driven productivity were strongly associated with positive abnormal returns.  
- Cost-cutting themes showed mixed effects depending on the sector.  
- High exposure to AI-related data privacy risks correlated with underperformance, likely due to regulatory concerns.

---

## Files Included

- `build_sample11.ipynb` – Main analysis notebook for sentiment extraction, portfolio sorting, and visualization  
- `sp500firms_data.csv` – S&P 500 firm data with sentiment scores  
- `event_window_returns.csv` – Daily return data for the event window

---

## Visualizations

- Scatterplots comparing returns of high vs. low sentiment firms  
- Heatmaps showing correlations between AI sentiment variables and cumulative returns  
- Bar charts and regression lines illustrating key trends across AI exposure themes

---

## Repository

Full code and data available on GitHub:  
[View the Repository](https://github.com/yourusername/your-repo-name)

---

_Last updated: May 2025_
