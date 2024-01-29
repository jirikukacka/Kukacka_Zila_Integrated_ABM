# Wealth, cost, and misperception: Empirical estimation of three interaction channels in a financial-macroeconomic agent-based model

This repository contains the data for "Wealth, cost, and misperception: Empirical estimation of three interaction channels in a financial-macroeconomic agent-based model", [ssrn.com/abstract=4709540](https://ssrn.com/abstract=4709540), by [Jiri Kukacka](mailto:jiri.kukacka@fsv.cuni.cz) and [Eric Zila](mailto:zila.eric@gmail.com).

## Requirements

To download the content of the repository and move to the root directory, run:
```
git clone git@github.com:jirikukacka/Zila_Kukacka_Moment_Selection.git
cd Zila_Kukacka_Moment_Selection/
```
Alternatively, for a convenient download of the data, click "Code" (green button) and "Download ZIP".

## Data

Empirical data used for empirical estimation are located in the `data/` folder. The data are available in both `CSV` (human-readable) and `JLD` (encoded) formats.

Daily financial data track the performance of the S&P 500 index between 31/12/1953 and 23/11/2022.

Quarterly macroeconomic data for the United States cover the period from 1954:Q3 until 2022:Q2. To calculate the output gap, the one-sided Hodrick-Prescott filter is used with $\lambda = 1,600$ (`Data_US_all_272`), $\lambda = 18,736$ (`Data_US_all_272_DT_18736`), and $\lambda = 12,016$ (`Data_US_all_272_ST_12016`).
