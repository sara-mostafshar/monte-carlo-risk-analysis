# Monte Carlo Risk Analysis – Is our contingency enough?

**▶ Use it free:** https://sara-mostafshar.github.io/monte-carlo-risk-analysis/ · **🎥 Video (3 min):** https://youtu.be/S6XUDV6LFCs

**📥 Sample Excel file:** [MC_Input_Template.xlsx](https://github.com/sara-mostafshar/monte-carlo-risk-analysis/raw/main/MC_Input_Template.xlsx) – a complete example project (fictional data) in the exact layout the tool expects. Open it to see what to fill in, then replace the values with your own.

A free, transparent Monte Carlo cost and schedule risk tool for project controllers and project managers. Upload your cost estimate and risk register and get, in seconds:

- P50 / P80 / P90 cost and finish dates
- Probability of staying within budget (BAC) and finishing on time
- Contingency needed to reach P80 vs contingency held
- Traffic lights, the top risk drivers with suggested actions, and a management summary
- Which estimate lines to firm up, and how much of the cost uncertainty comes from the estimate vs from risk events
- Export of all results to Excel

## How to use
1. Open the link and click **Try with sample project**, or download the Excel template (it contains the sample project). The page also explains the file layout under *What should my Excel file look like?*
2. Fill in three sheets: `Project`, `Cost_Estimate`, `Risk_Register`.
3. Upload the file and click **Run**.

## Method
Triangular distributions for estimate lines and risk impacts, one occurrence draw per open risk shared by cost and schedule, working-day schedule offsets, Spearman rank correlation for drivers (risks and estimate lines), and each input's share of the cost variance. Optional: estimate correlation (one shared factor, Gaussian copula) and a time-related cost per working day of delay. With both options at 0, results are identical to earlier versions. The full method and thresholds are written on the page.

🔒 Runs entirely in your browser – your file is not uploaded anywhere. The sample project is fictional.

## Use the online version
Please use the online version for the latest tested release: https://sara-mostafshar.github.io/monte-carlo-risk-analysis/ – downloaded copies do not receive fixes and updates.

## License
Free to use, share and adapt under the [MIT License](LICENSE). Please keep the credit to Sara Mostafshar.

Built by [Sara Mostafshar](https://sara-mostafshar.github.io) · AI agents and free tools for project controllers and project managers
