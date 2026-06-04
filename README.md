# Global Economics - Hypothesis Testing Dashboard

## Project Overview
This interactive dashboard is designed to fulfill the requirements for the C8 and C9 criteria of the Term 3 Global Economics Assessment. It provides visual, real-time calculation models for standard Z-tests under both manual configurations and automated dataset imports.

## How to test CSV Mode (C9):
1. Launch the deployed URL or open the `index.html` file in any standard web browser.
2. Click on the tab labeled **"Automated CSV Data Import (C9)"** at the top of the interface.
3. Make sure you have downloaded the two mandatory example files from this repository:
   * `G11_T3_L4_C8C9_example_mean_data.csv`
   * `G11_T3_L4_C8C9_example_proportion_data.csv`
4. Click the **"Upload CSV Dataset"** button on the interface.
5. Select either of the two downloaded files to see the calculations run automatically:
   * Loading the `mean_data` file will automatically compute sample size ($n$), sample means ($\bar{x}$), and sample standard deviations ($s$) for each region.
   * Loading the `proportion_data` file will automatically identify binary success structures ($0$ and $1$) and run a standard two-sample proportion comparison test.
6. Observe how the probability distribution curve and contextual conclusions change dynamically upon loading.