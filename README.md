## 1. Project Overview

This project analyzes the relationship between cryptocurrency trader behavior and the broader market sentiment, as measured by the Fear & Greed Index. The primary objective is to identify patterns in trading volume, profitability (PnL), and risk-taking across different sentiment environments (from Extreme Fear to Extreme Greed). The final output is a detailed report summarizing these findings and offering strategic insights.

---


## 2. How to Run

To replicate the analysis, please follow these steps:

1.  **Environment Setup**: This project is designed to be run in a Google Colab environment. The notebook uses standard Python libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.

2.  **Open the Notebook**: Open `notebook_1.ipynb` in Google Colab.

3.  **Upload Data**:
    * Upload the two `.csv` files from the `csv_files/` directory to your Colab session's root directory.
    * Alternatively, you can modify the file paths in the notebook to point to the files if they are stored elsewhere (e.g., mounted Google Drive).

4.  **Execute Code**: Run all cells in the notebook sequentially from top to bottom.

5.  **View Outputs**: The script will:
    * Perform all data cleaning, merging, and analysis.
    * Generate and display the four analysis charts within the notebook.
    * Save copies of these charts to a newly created `outputs/` folder in the Colab environment.

---

## 3. Summary of Findings

The analysis revealed several key correlations between trader actions and market sentiment:

* **Volume & Greed**: Trading volume surges during periods of `Greed` and `Extreme Greed`, indicating that market participation is highest during optimistic times.
* **Profitability Follows Momentum**: The highest average profits are made during `Greed` phases. Conversely, `Extreme Fear` is the only sentiment category that results in an average net loss for traders.
* **Risk Peaks at Extremes**: Risk, measured by PnL volatility, is highest at both ends of the sentiment spectrum—`Extreme Greed` and `Extreme Fear`.
* **Behavior is Reactionary**: Traders tend to open more long (buy) positions during `Greed` and more short (sell) positions during `Fear`, suggesting a strong trend-following instinct.

For a complete discussion of these findings and their strategic implications, please see the `ds_report.pdf`.

